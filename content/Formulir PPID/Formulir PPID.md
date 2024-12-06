---
author: sekret.bppkb
title: "Formulir PPID"
date: 2024-08-06 07:48:58
---

<script>
    const items = [
        {
            title: "Formulir Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1UFrfGOp735QUO-K9a1utrazM35wfC0jW/preview",
            file: ""
        },
        {
            title: "Formulir Pengajuan Keberatan Atas Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1QB1usppYoQOMcIMMmsyBKBGnrBHno-EB/preview",
            file: ""
        },
        {
            title: "Formulir Pemberitahuan Tertulis Atas Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1RDV8G0Shspw--hty8hl1i-1ORpUdPJZh/preview",
            file: ""
        },
        {
            title: "Formulir Pemberitahuan Kurangnya Kelengkapan Atas Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1orwYG_anp9VxTmN0Hqo2WbA2I6StSq5Q/preview",
            file: ""
        },
        {
            title: "Formulir Tanda Terima Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1iyLzSawGkANjbEnURWTBZOk8NvihsmRr/preview",
            file: ""
        },
        {
            title: "Formulir Tanda Terima Keberatan Atas Permohonan Informasi",
            category: "",
            link: "https://drive.google.com/file/d/1_OSe3-eq5sPJykTVM1Un9bMMSqk9lzF6/preview",
            file: ""
        }
    ];
</script>

<div class="flex justify-between items-center mb-4">
    <div class="flex items-center border-2 border-green-500 rounded-lg p-2 ml-auto" style="flex-shrink: 0;">
        <i class="fas fa-search text-green-500 text-xl"></i>
        <input type="text" placeholder="Cari" class="ml-2 text-green-500 text-xl outline-none" style="background: transparent; border: none; width: 150px;" id="searchInput">
        <div class="border-l-2 border-green-500 h-6 mx-4"></div>
        <div class="flex items-center cursor-pointer" id="categoryDropdownToggle">
            <i class="fas fa-filter text-green-500 text-xl"></i>
            <span id="selectedFilter" class="ml-2 text-green-500 text-xl truncate" style="max-width: 100px; width: 100px;"></span>
        </div>
    </div>
    <div class="relative">
        <div id="categoryDropdown" class="absolute right-0 mt-6 w-48 bg-white border border-gray-300 rounded-lg shadow-lg hidden" style="max-height: 200px; overflow-y: auto;">
            <div id="categoryList" class="list-none p-0 m-0"></div>
        </div>
    </div>
</div>

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<div class="flex justify-center mt-4" id="pagination"></div>
<style>
@media (max-width: 768px) {
    #information-list {
        justify-content: space-around;
    }
}
.pagination-button {
    margin: 0 5px;
    padding: 8px 12px;
    border: 1px solid #2F855A;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
    color: #2F855A;
}
.pagination-button:hover {
    background-color: #2F855A;
    color: white;
}
.pagination-button.active {
    background-color: #2F855A;
    color: white;
}
.pagination-ellipsis {
    margin: 0 5px;
    padding: 8px 12px;
    color: #2F855A;
}
</style>

<script>
    const container = document.getElementById('information-list');
    const paginationContainer = document.getElementById('pagination');
    const categorySet = new Set();
    const itemsPerPage = 12;
    let currentPage = 1;
    let selectedCategory = 'All';

    function renderItems(filteredItems) {
        container.innerHTML = '';
        const start = (currentPage - 1) * itemsPerPage;
        const end = start + itemsPerPage;
        const paginatedItems = filteredItems.slice(start, end);

        if (paginatedItems.length === 0) {
            const noResultsDiv = document.createElement('div');
            noResultsDiv.className = 'w-full text-center text-gray-500';
            noResultsDiv.textContent = 'Tidak ada hasil yang cocok';
            container.appendChild(noResultsDiv);
        } else {
            paginatedItems.forEach(item => {
                const div = document.createElement('div');
                div.className = 'w-64 bg-white border border-gray-300 rounded-lg overflow-hidden shadow-lg m-2 flex flex-col';
                div.innerHTML = `
                    <div class="flex items-center justify-center w-full h-48 bg-gray-200">
                        ${item.file ? `<i class="fas fa-image fa-5x text-red-600"></i>` : `<i class="fas fa-file-pdf fa-5x text-red-600"></i>`}
                    </div>
                    <div class="p-4 bg-green-600 text-white flex-grow flex flex-col justify-between">
                        <p class="text-base font-semibold">${item.title}</p>
                        <div class="flex items-center mt-auto">
                            <i class="fas fa-file-alt mr-2"></i>
                            <span class="text-xs">${item.category}</span>
                        </div>
                    </div>
                    <button class="block p-4 bg-green-700 text-white text-center hover:bg-green-800 mt-auto no-underline" onclick="${item.file ? `openImgModal('${item.file}')` : `openPdfModal('${item.link}')`}">
                        <span class="text-sm font-semibold text-white">
                            Lihat Selengkapnya
                            <i class="fas fa-arrow-right"></i>
                        </span>
                    </button>
                `;
                container.appendChild(div);
            });
        }
        renderPagination(filteredItems.length);
    }

    function renderPagination(totalItems) {
        paginationContainer.innerHTML = '';
        const totalPages = Math.ceil(totalItems / itemsPerPage);
        const maxPagesToShow = 6;
        const halfMaxPagesToShow = Math.floor(maxPagesToShow / 2);

        let startPage = Math.max(1, currentPage - halfMaxPagesToShow);
        let endPage = Math.min(totalPages, currentPage + halfMaxPagesToShow);

        if (currentPage <= halfMaxPagesToShow) {
            endPage = Math.min(totalPages, maxPagesToShow);
        } else if (currentPage + halfMaxPagesToShow >= totalPages) {
            startPage = Math.max(1, totalPages - maxPagesToShow + 1);
        }

        if (startPage > 1) {
            paginationContainer.appendChild(createPaginationButton(1));
            if (startPage > 2) {
                paginationContainer.appendChild(createEllipsis());
            }
        }

        for (let i = startPage; i <= endPage; i++) {
            paginationContainer.appendChild(createPaginationButton(i));
        }

        if (endPage < totalPages) {
            if (endPage < totalPages - 1) {
                paginationContainer.appendChild(createEllipsis());
            }
            paginationContainer.appendChild(createPaginationButton(totalPages));
        }
    }

    function createPaginationButton(page) {
        const button = document.createElement('button');
        button.className = `pagination-button ${page === currentPage ? 'active' : ''}`;
        button.textContent = page;
        button.addEventListener('click', () => {
            currentPage = page;
            renderItems(items);
            window.scrollTo(0, 0);
        });
        return button;
    }

    function createEllipsis() {
        const ellipsis = document.createElement('span');
        ellipsis.className = 'pagination-ellipsis';
        ellipsis.textContent = '...';
        return ellipsis;
    }

    items.forEach(item => {
        categorySet.add(item.category);
    });

    const categoryList = document.getElementById('categoryList');
    const selectedFilter = document.getElementById('selectedFilter');

    const allDiv = document.createElement('div');
    allDiv.className = 'pl-4 p-1 pt-2 hover:bg-gray-100 cursor-pointer text-sm';
    allDiv.textContent = 'All';
    allDiv.addEventListener('click', () => {
        currentPage = 1;
        selectedCategory = 'All';
        selectedFilter.textContent = selectedCategory;
        renderItems(items);
        document.getElementById('categoryDropdown').classList.add('hidden');
        document.getElementById('categoryDropdownToggle').classList.remove('text-green-700');
    });
    categoryList.appendChild(allDiv);

    categorySet.forEach(category => {
        const div = document.createElement('div');
        div.className = 'pl-4 p-1 hover:bg-gray-100 cursor-pointer text-sm';
        div.style.overflow = 'hidden';
        div.textContent = category;
        div.addEventListener('click', () => {
            currentPage = 1;
            selectedCategory = category;
            selectedFilter.textContent = selectedCategory;
            const filteredItems = items.filter(item => item.category === category);
            renderItems(filteredItems);
            document.getElementById('categoryDropdown').classList.add('hidden');
            document.getElementById('categoryDropdownToggle').classList.remove('text-green-700');
        });
        categoryList.appendChild(div);
    });

    document.getElementById('categoryDropdownToggle').addEventListener('click', function(event) {
        const dropdown = document.getElementById('categoryDropdown');
        dropdown.classList.toggle('hidden');
        this.classList.toggle('text-green-700');
        event.stopPropagation();
    });

    document.addEventListener('click', function(event) {
        const dropdown = document.getElementById('categoryDropdown');
        const toggle = document.getElementById('categoryDropdownToggle');
        if (!dropdown.classList.contains('hidden') && !dropdown.contains(event.target) && !toggle.contains(event.target)) {
            dropdown.classList.add('hidden');
            toggle.classList.remove('text-green-700');
        }
    });

    document.getElementById('searchInput').addEventListener('input', function() {
        currentPage = 1;
        const searchTerm = this.value.toLowerCase();
        const filteredItems = items.filter(item => item.title.toLowerCase().includes(searchTerm));
        renderItems(filteredItems);
    });
    selectedFilter.textContent = selectedCategory;
    renderItems(items);
</script>

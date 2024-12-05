---
author: sekret.bppkb
title: "Aparatur"
date: 2024-08-01 03:35:13
---

<script>
    const items = [
        {
            title: "",
            category: "Jumlah Pegawai",
            link: ""
        },
        {
            title: "",
            category: "Grafik Pegawai",
            link: ""
        },
        {
            title: "",
            category: "Daftar Urut Kepangkatan",
            link: ""
        },
        {
            title: "",
            category: "Kenaikan Pangkat",
            link: ""
        },
        {
            title: "",
            category: "Kenaikan Berkala",
            link: ""
        },
        {
            title: "",
            category: "Batas Usia Pensiun",
            link: ""
        },
        {
            title: "",
            category: "LHKPN / LHKASN",
            link: ""
        },
        {
            title: "",
            category: "Peta Jabatan",
            link: ""
        }
    ];
</script>

<div class="flex justify-between items-center mb-4">
    <div class="flex items-center border-2 border-green-500 rounded-lg p-2 ml-auto">
        <i class="fas fa-search text-green-500 text-xl"></i>
        <input type="text" placeholder="Cari" class="ml-2 text-green-500 text-xl outline-none" style="background: transparent; border: none;" id="searchInput">
        <div class="border-l-2 border-green-500 h-6 mx-4"></div>
        <i class="fas fa-filter text-green-500 text-xl cursor-pointer" id="categoryDropdownToggle"></i>
    </div>
    <div class="relative">
        <div id="categoryDropdown" class="absolute right-0 mt-2 w-48 bg-white border border-gray-300 rounded-lg shadow-lg hidden">
            <div id="categoryList" class="list-none p-0 m-0"></div>
        </div>
    </div>
</div>

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<style>
@media (max-width: 768px) {
    #information-list {
        justify-content: space-around;
    }
}
</style>

<script>
    const container = document.getElementById('information-list');
    const categorySet = new Set();

    function renderItems(filteredItems) {
        container.innerHTML = '';
        if (filteredItems.length === 0) {
            const noResultsDiv = document.createElement('div');
            noResultsDiv.className = 'w-full text-center text-gray-500';
            noResultsDiv.textContent = 'Tidak ada hasil yang cocok';
            container.appendChild(noResultsDiv);
        } else {
            filteredItems.forEach(item => {
                const div = document.createElement('div');
                div.className = 'w-64 bg-white border border-gray-300 rounded-lg overflow-hidden shadow-lg m-2 flex flex-col';
                div.innerHTML = `
                    <div class="flex items-center justify-center w-full h-48 bg-gray-200">
                        <i class="fas fa-file-pdf fa-5x text-red-600"></i>
                    </div>
                    <div class="p-4 bg-green-600 text-white flex-grow flex flex-col justify-between">
                        <p class="text-base font-semibold">${item.title}</p>
                        <div class="flex items-center mt-auto">
                            <i class="fas fa-file-alt mr-2"></i>
                            <span class="text-xs">${item.category}</span>
                        </div>
                    </div>
                    <a class="block p-4 bg-green-700 text-white text-center ${item.link ? 'hover:bg-green-800' : 'cursor-not-allowed'} mt-auto no-underline" href="${item.link}" target="_blank" style="text-decoration: none;" ${item.link ? '' : 'onclick="return false;"'}>
                        <span class="text-sm font-semibold text-white">
                            Lihat Selengkapnya
                            <i class="fas fa-arrow-right"></i>
                        </span>
                    </a>
                `;
                container.appendChild(div);
            });
        }
    }

    items.forEach(item => {
        categorySet.add(item.category);
    });

    const categoryList = document.getElementById('categoryList');

    const allDiv = document.createElement('div');
    allDiv.className = 'pl-4 p-1 pt-2 hover:bg-gray-100 cursor-pointer text-sm';
    allDiv.textContent = 'All';
    allDiv.addEventListener('click', () => {
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
        const searchTerm = this.value.toLowerCase();
        const filteredItems = items.filter(item => item.title.toLowerCase().includes(searchTerm));
        renderItems(filteredItems);
    });

    renderItems(items);
</script>

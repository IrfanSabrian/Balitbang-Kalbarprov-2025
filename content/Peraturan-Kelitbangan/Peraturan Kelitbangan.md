---
author: sekret.bppkb
title: "Peraturan Kelitbangan"
date: 2024-08-01 03:53:04
---

<script>
    const items = [
        {
            title: "UU No. 8 Tahun 2002 Sistem Nasional Penelitian dan Pengembangan dan Penerapan Ilmu Pengetahuan dan Teknologi",
            category: "Undang-Undang",
            link: "https://drive.google.com/file/d/1ZFZTPlMvLGP-zwso-msHSE1hBCxPKmrk/preview",
            file: ""
        },
        {
            title: "UU No. 11 Tahun 2019 Sistem Nasional Ilmu Pengetahuan dan Teknologi",
            category: "Undang-Undang",
            link: "https://drive.google.com/file/d/1tSYO2Whx9nJBR5B4b_F8Z5q7cDXHNCbT/preview",
            file: ""
        },
        {
            title: "Peraturan Presiden Nomor 78 Tahun 2021 tentang BRIN",
            category: "Peraturan Presiden",
            link: "https://drive.google.com/file/d/1m7NvTrLzGLtsDh4Is1C7fKbdsjYiSKd0/preview",
            file: ""
        },
        {
            title: "Permendagri No 17 Tahun 2016 tentang Pedoman Penelitian dan Pengembangan di Kementerian Dalam Negeri dan Pemerintah Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1mwE3RJO7I0GMqHDiDMrndlcQ96t8wL7W/preview",
            file: ""
        },
        {
            title: "Peraturan Pemerintah No 38 Tahun 2017 ttg Inovai Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1d3tvDTuh0XZkbD87kQGpbbEgt8cVZwjO/preview",
            file: ""
        },
        {
            title: "Permendagri No 104 Tahun 2018 tentang Penilaian dan Pemberian Penghargaan Inovasi Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1NvyGkkmXDYCcCK5c8pM5Yi4c-6yVtJIT/preview",
            file: ""
        },
        {
            title: "Permenpan RB Nomor 1 Tahun 2020 tentang Pedoman Analisis Jabatan dan Analisis Beban Kerja",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1zQeb0TbfLqiDK7CdE78wK9qeua9IQgtJ/preview",
            file: ""
        },
        {
            title: "Permendagri No. 19 Tahun 2020 ttg Indeks Pengelolaan Keuangan Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/11VCEDx5RH8YNko6AeJTJRQ5pP1JVlr8V/preview",
            file: ""
        },
        {
            title: "Peraturan Daerah No. 8 Tahun 2016 tentang Pembentukan dan Susunan Perangkat Daerah Provinsi Kalbar",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/1XrLDZyXvktWjy4xf1aoWiXwKnnzTWnx8/preview",
            file: ""
        },
        {
            title: "Peraturan Daerah No. 11 Tahun 2019 tentang Perubahan Atas Perda No 8 Tahun 2016",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/1DpVFti7A6ANMpg4_5Zp3woFMyqaLmbI0/preview",
            file: ""
        },
        {
            title: "Perda No 5 Tahun 2021 tentang Perubahan Kedua Atas Perda No. 8 tahun 2016 tentang Pembentukan dan Susunan Perangkat Daerah Provinsi Kalimantan Barat",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/11LOnd1XZnI0kseIaqaPhpbPV-zHeBkzf/preview",
            file: ""
        },
        {
            title: "Peraturan Gubernur Kalbar Nomor 125 Tahun 2016 tentang Kedudukan, Susunan Organisasi, Tugas dan Fungsi serta Tata Kerja Balitbang Provinsi Kalbar",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1AmKiMnOy4X2tkZKKjpEUZVrtBLygt6Wr/preview",
            file: ""
        },
        {
            title: "Pergub No. 48 Tahun 2019 Perubahan Pergub No. 11 Tahun 2019 tentang Pendelegasian Kewenangan",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1GNWpR9O-VSBEmIZ2Uh-CEF1YTm4SNmtl/preview",
            file: ""
        },
        {
            title: "Peraturan Gubernur Kalbar Nomor 38 Tahun 2019 tentang Pedoman Penelitian dan Pengembangan",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1ohlBugoNzZ0PPtqAtfKbKpkgvmaLTqkm/preview",
            file: ""
        },
        {
            title: "Pergub No. 102 Tahun 2020 tentang Kode Etik Pelayanan Publik",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/16F_UOGUVp55gc25SJkw4lm48KGMHcugW/preview",
            file: ""
        },
        {
            title: "Peraturan Gubernur Nomor 138 Tahun 2021 tentang Kedudukan, Susunan organisasi, Tugas dan Fungsi serta Tata Kerja Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1csfQQ5eSjxrTgMMbA3rrXe6ak9Eo7PiG/preview",
            file: ""
        },
        {
            title: "Peraturan Gubernur Kalbar No. 211 Tahun 2021 tentang Penyelenggaraan Inovasi Daerah",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1hRSbewQquGvLnUffhkzeaP-K4Pogv2Q7/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang Periode 2019-2021",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1UiOAuMmdDUYutVvJW_H-NzG-iHs_pptJ/preview",
            file: ""
        },
        {
            title: "Keputusan Pembentukan HIMPENINDO Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/18oM5T7IDUV9T4vf8j-xhIL0yPmSdfCbb/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang 2023",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1186I_UZfYhjQx5KWiWowPn23ddlAOXYN/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur tentang Simpul Jaringan Inovasi Provinsi Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1ZymNddtRbsEoHQx87cWMYJFg2Ik4a1Rb/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur No. 224/BAPPEDA/2023 tentang Forum Satu Data Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1iSt61sTOBqLc2uktFB_-bqYXexntKGGO/preview",
            file: ""
        },
        {
            title: "Keputusan Sekda Pembentukan Tim Admin Satu Data Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1OeRkZ5tGmk3xCTpSOPbKSIVlntEjV3jZ/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang 2024",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1pt1G9OOlREwLBeCAytVnEezaMw8qLIe5/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur Kalimantan Barat tentang Pembentukan HIMPENINDO Kalimantan Barat",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/18oM5T7IDUV9T4vf8j-xhIL0yPmSdfCbb/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur Kalbar tentang Pembentukan Majelis Pertimbangan Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat Tahun 2019 sd 2021",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1UiOAuMmdDUYutVvJW_H-NzG-iHs_pptJ/preview",
            file: ""
        },
        {
            title: "Keputusan Gubernur Kalbar tentang Pembentukan Majelis Pertimbangan Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat Tahun 2023",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1186I_UZfYhjQx5KWiWowPn23ddlAOXYN/preview",
            file: ""
        },
        {
            title: "Surat Pengumuman Peringatan Evakuasi Dini 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1dYHdkrGXdxxPUd5jNIt_8zskeD3zYk_O/preview",
            file: ""
        },
        {
            title: "Keputusan Kaban ttg Penetapan Maklumat, Motto, Tim Pelayanan Publik 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1s3saJX21QceFg92HHmmGf5lfGZGl3Pbr/preview",
            file: ""
        },
        {
            title: "Keputusan Kaban ttg Pengelolaan Pengaduan Pelayanan Publik 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1Hsv8DK_qL8bLIZFHz48inVpwqlxluTTz/preview",
            file: ""
        },
        {
            title: "Keputusan Kaban ttg Pembentukan Arsip Dinamis 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1NXslh4uz-r6AHbqqQOJ-BnQtHpUVxeOp/preview",
            file: ""
        },
        {
            title: "",
            category: "Peraturan Pemerintah",
            link: ""
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

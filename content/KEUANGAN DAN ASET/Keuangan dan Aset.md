---
author: sekret.bppkb
title: "Keuangan dan Aset"
date: 2024-08-13 00:59:55
---

<script>
    const items = [
        {
            title: "Laporan LRA Tahun 2023",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/1Emsczi_-IqZyLl2ew4i5U-iimvVdNzTe/view?usp=sharing"
        },
        {
            title: "Laporan CALK Tahun 2023",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/14tTCrbMkxUQmlZJV4Tqfx_W_-FLrxGNz/view?usp=sharing"
        },
        {
            title: "Laporan Neraca Tahun 2023",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/1VBiryQOg1U1fZvDGAKo1g70mTxBOJo-8/view?usp=sharing"
        },
        {
            title: "Laporan Keuangan Balitbang Tahun 2023",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/1sRiVKjD1CjmrKboKbE7jyYB9SuR04jgG/view?usp=sharing"
        },
        {
            title: "Laporan Keuangan Balitbang Tahun 2022",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/144qsd-2fAvmsNtUuRf2XZWpNiB44dQG0/view?usp=sharing"
        },
        {
            title: "Laporan Keuangan Balitbang Tahun 2021",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/1Dg4hAnIoo_Xon_44c4Mw2qa7g2RbsrpD/view?usp=sharing"
        },
        {
            title: "Laporan Keuangan Balitbang Tahun 2020",
            category: "Laporan Keuangan",
            link: "https://drive.google.com/file/d/1gYMXvKYlm_xr9zN81e0Kn8JnU6TfYf4h/view?usp=sharing"
        },
        {
            title: "Laporan Aset Balitbang Tahun 2023",
            category: "Laporan Aset",
            link: "https://drive.google.com/file/d/11KE6FO4fKl-ICYJcnNWnU8P4NvsqGu1w/view?usp=sharing"
        },
        {
            title: "Laporan Aset Balitbang Tahun 2022",
            category: "Laporan Aset",
            link: "https://drive.google.com/file/d/1UMMvZv0aOKZMG-QwF5nDIKgiews_-SDq/view?usp=sharing"
        },
        {
            title: "Laporan Aset Balitbang Tahun 2021",
            category: "Laporan Aset",
            link: "https://drive.google.com/file/d/1tBhXgc9sy2ZQ1bH29inUvr4cx8s1Ii0d/view?usp=sharing"
        },
        {
            title: "Laporan Aset Balitbang Tahun 2020",
            category: "Laporan Aset",
            link: "https://drive.google.com/file/d/1OlX15WVDquXXIer2PYhEpGVz8DMBbp_2/view?usp=sharing"
        },
        {
            title: "RKA Balitbang Tahun 2024",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1NBl6m4wHRvvBWhPBajgYppZoZD1VuL9M/view?usp=sharing"
        },
        {
            title: "DPA Balitbang Tahun 2024",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1gdiOqefqnoHm22kn3WBEDR4-zMmIE5GM/view?usp=sharing"
        },
        {
            title: "RKA Balitbang Tahun 2023",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1m8ZZfIyFeO0ErqX3FTlf3UDkTqJ7K6HW/view?usp=sharing"
        },
        {
            title: "DPA Balitbang Tahun 2023",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1pWMzCoxQTWd8YI2l0rGKIlqJgnfYGRLk/view?usp=sharing"
        },
        {
            title: "RKA dan DPA Balitbang Tahun 2022",
            category: "RKA dan DPA",
            link: ""
        },
        {
            title: "DPA Balitbang Tahun 2022",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1x8fz__U2sPy0YumqcQAqdAoPiBNUDrbB/view?usp=sharing"
        },
        {
            title: "RKA dan DPA Balitbang Tahun 2021",
            category: "RKA dan DPA",
            link: ""
        },
        {
            title: "DPA Balitbang Tahun 2021",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1hfChBoF83fHCAWjwbYlbo-Ze5EUi_tIV/view?usp=sharing"
        },
        {
            title: "RKA dan DPA Balitbang Tahun 2020",
            category: "RKA dan DPA",
            link: ""
        },
        {
            title: "DPA Balitbang Tahun 2020",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1kGbidHoNzILBu4QMApWBLRejpktOJQZI/view?usp=sharing"
        },
        {
            title: "RKA dan DPA Balitbang Tahun 2019",
            category: "RKA dan DPA",
            link: ""
        },
        {
            title: "DPA Balitbang Tahun 2019",
            category: "RKA dan DPA",
            link: "https://drive.google.com/file/d/1L-td5YK51Ua-t1g8BDfktUt1eqrzC9Xh/view?usp=sharing"
        },
        {
            title: "RKBMD dan RKPBMD 2023",
            category: "RKBMD dan RKPBMD",
            link: "https://drive.google.com/file/d/1UMMvZv0aOKZMG-QwF5nDIKgiews_-SDq/view?usp=sharing"
        },
        {
            title: "RKBMD dan RKPBMD 2024",
            category: "RKBMD dan RKPBMD",
            link: "https://drive.google.com/file/d/1T7u8z7Z4hp-JNE39u94Eg4I6JRHQodCX/view?usp=sharing"
        },
        {
            title: "Realisasi Keuangan Balitbang Tahun 2023",
            category: "Realisasi Keuangan",
            link: "https://drive.google.com/file/d/1EXx6Aby9zh3ZkpgNE20c2i0yI7HCpChK/view?usp=sharing"
        },
        {
            title: "Realisasi Keuangan Balitbang Tahun 2024",
            category: "Realisasi Keuangan",
            link: "https://drive.google.com/file/d/1ffvN5MFvzEJsTMU2P65Lfc-5MMhJJ5gv/view?usp=sharing"
        },
        {
            title: "KAK Kegiatan Arsip Dinamis",
            category: "KAK Kegiatan",
            link: ""
        },
        {
            title: "KAK Kegiatan Pendidikan dan Pelatihan Pegawai",
            category: "KAK Kegiatan",
            link: "https://drive.google.com/file/d/1gKLFR49DT5UcnusmaBvjAalsksGcCp9u/view?usp=sharing"
        },
        {
            title: "KAK Kegiatan Koordinasi dan Pelaksanaan Akuntansi SKPD",
            category: "KAK Kegiatan",
            link: "https://drive.google.com/file/d/1pBvwzJC-FeyZsOVdoSMQsCP4lDK2fAQA/view?usp=sharing"
        },
        {
            title: "KAK Kegiatan Penyediaan Barang Cetakan dan Penggandaan",
            category: "KAK Kegiatan",
            link: "https://drive.google.com/file/d/1nfxZ_dRk0zmb2CjNXpP6wguI-8hajYJU/view?usp=sharing"
        },
        {
            title: "KAK Penyediaan Peralatan dan Perlengkapan Kantor",
            category: "KAK Kegiatan",
            link: "https://drive.google.com/file/d/1Eirdq6rR-EtGQBbFA91Z0_SWu8CqdfOt/view?usp=sharing"
        },
        {
            title: "KAK Penyediaan Peralatan Rumah Tangga",
            category: "KAK Kegiatan",
            link: "https://drive.google.com/file/d/1CxyjVzL4p7qXqB69EZES-TRcTJgwD7vx/view?usp=sharing"
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

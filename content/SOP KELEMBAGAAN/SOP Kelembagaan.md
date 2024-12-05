---
author: sekret.bppkb
title: "SOP Kelembagaan"
date: 2024-10-15 01:45:19
---

<script>
    const items = [
        {
            title: "SOP Pengelolaan Adm Surat Masuk",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1FrmehyCFNM_Pv9ya7KFlrqsT1rZSsC7f/view?usp=sharing"
        },
        {
            title: "SOP Pengelolaan Adm Surat Keluar",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1dp8KJApNU60Poaq2Gc4wWbEwKUUQT8ZD/view?usp=sharing"
        },
        {
            title: "SOP Pedoman Penyusunan DUK",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1pSatuCxcVRhS3MqxMwkAljjBxZfkYqUJ/view?usp=sharing"
        },
        {
            title: "SOP Pedoman Usulan Formasi PNS",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/10LWss0cwZt5FDU6uJIsSuO8FQLdbcHgD/view?usp=sharing"
        },
        {
            title: "SOP Usulan Kenaikan Pangkat",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1Lt23ioe5bND4xyQdyQO5GBGVUEN7ldgp/view?usp=sharing"
        },
        {
            title: "SOP Usulan Kenaikan Gaji Berkala",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/18UofkAb2rgKXpwXbpKR9PQLAo6J-2xqy/view?usp=sharing"
        },
        {
            title: "SOP Pedoman Pelaksanaan Cuti ASN",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/11p4fH-HmzecrqRtmevW3RIdrOGq7_O7d/view?usp=sharing"
        },
        {
            title: "SOP Pedoman Persyaratan mengikuti Diklat, Beasiswa dan Tugas Belajar",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1iqHJmqlQVl9i3CXeUv81cnPHLp-DkBIU/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan Renja",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1eorAxl9sLn6mKQym5S9rN4-30CnmeamG/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan Renstra",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/19maRCU8NpI8Qx5iN2o1UUGTLCtazb730/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan RKA",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1JG9sU_sUlWJcn4JSfwSzwIo52bmYHfhy/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan DPA",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1bkwI5KTkwM1jEBa8YCmmU7tMkIoCtYsc/view?usp=sharing"
        },
        {
            title: "SOP Pelaks dan Pelaporan Monev",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1mOAicWRxA4Y0BGCa8juetxjFmw9daAbw/view?usp=sharing"
        },
        {
            title: "SOP Manajemen Resiko",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1fe0WyIGB2rq_Qd1Eq4m5vzgSGG130TUS/view?usp=sharing"
        },
        {
            title: "SOP Penatausahaan Keuangan",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1X7F4WTedYGr558GJyxIFFuCNjGiF7Yiq/view?usp=sharing"
        },
        {
            title: "SOP Pengelolaan Barang",
            category: "SOP Sekretariat",
            link: "https://drive.google.com/file/d/1eIZppDfwCl6bD9s3DbY4r2qUnvOrS2QC/view?usp=sharing"
        },
        {
            title: "SOP Pelaksanaan Riset Swakelola Tipe I",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/108jDnIW2X78V2669gjAiZgDH-ugxTWII/view?usp=sharing"
        },
        {
            title: "SOP Pelaksanaan Riset Swakelola Tipe II",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/1lR7hJStu1RtjBSZk018JpqpIC3Hez5Ym/view?usp=sharing"
        },
        {
            title: "SOP Pelaksanaan Riset Swakelola Tipe III",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/10FZoFi6lj1JSBIW_FPuZYtmjNcggZRqz/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan Pergub Pertek Izin Penelitian",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/1OKSJFbFTfGeB_4Fox5S5H70DJqr2YbI0/view?usp=sharing"
        },
        {
            title: "SOP Penginputan IPKD Provinsi",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/15wKVv3M1Y8BnqvFOOFbOVCC6T8PRaMMy/view?usp=sharing"
        },
        {
            title: "SOP Pengukuran IPKD Kabupaten Kota",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/1JH-aL4uXRtQ3lDULM6KA0reqtqY2osk3/view?usp=sharing"
        },
        {
            title: "SOP Permohonan Penerbitan Pertek Izin Penelitian/Pendataan",
            category: "SOP Bidang Sosial dan Pemerintahan",
            link: "https://drive.google.com/file/d/1FyD2dfsMk0-TUkPkZ0seUUATjhVWlKUG/view?usp=sharing"
        },
        {
            title: "SOP Pelaks Swakelola Peneltian Ekbang",
            category: "SOP Bidang Ekonomi dan Pembangunan",
            link: "https://drive.google.com/file/d/108jDnIW2X78V2669gjAiZgDH-ugxTWII/view?usp=sharing"
        },
        {
            title: "SOP Pelaks Swakelola Penelitian Inovtek",
            category: "SOP Bidang Inovasi dan Teknologi",
            link: "https://drive.google.com/file/d/1bt2bYUrd1y2-lePYijzw50TyXxZLlwCI/view?usp=sharing"
        },
        {
            title: "SOP Pengelolaan Jurnal",
            category: "SOP Bidang Inovasi dan Teknologi",
            link: "https://drive.google.com/file/d/1DpKC7fTQ9fDI8mdh0N37sSWgz6kf07wZ/view?usp=sharing"
        },
        {
            title: "SOP Penerbitan Jurnal",
            category: "SOP Bidang Inovasi dan Teknologi",
            link: "https://drive.google.com/file/d/1n3GmaPmi4ZCN4A--xKHrqzTFu9T2nGFi/view?usp=sharing"
        },
        {
            title: "SOP Fasilitasi HKI",
            category: "SOP Bidang Inovasi dan Teknologi",
            link: "https://drive.google.com/file/d/1ekNiSWMIRuGoRUM2e6WLoFjn6Awt6dG4/view?usp=sharing"
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

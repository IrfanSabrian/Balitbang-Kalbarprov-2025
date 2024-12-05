---
author: sekret.bppkb
title: "Renja Monev"
date: 2024-08-06 07:57:19
---

<script>
    const items = [
        {
            title: "Renja Balitbang 2017",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1JIZxr0p_d54wKe-g4PGVNC1ZIeDylbPW/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2018",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1DgjhxiXCk7sXgRwHAOK0w1KScLHHbmtv/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2019",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1I1z_Qbi709ot39wWJZjTn0_n5vzEXT_t/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2020",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1jm1YCZgXVfEQa9vOo1IBOa5QvZvYIW0d/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2021",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1euVFUuRztLzbTtGKjn7wZdcmqMrOkqaf/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2022",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1WLeJ2mqCKDh69caNy-OMpm_nUmNikB0Z/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2023",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/1-NGAOG7VUaoqb5Q0gQBZ_7e6QWcMva8D/view?usp=sharing"
        },
        {
            title: "Renja Balitbang 2024",
            category: "Rencana Kerja",
            link: "https://drive.google.com/file/d/15rhnZCQRUOMPbpX8wJt_FRQRI4YhrLSz/view?usp=sharing"
        },
        {
            title: "Renstra Balitbang 2018 - 2023",
            category: "Rencana Strategis",
            link: "https://drive.google.com/file/d/1EXIryhQX_1CIDzHwcuzqi3lSPnQhlSXt/view?usp=sharing"
        },
        {
            title: "Renstra Balitbang 2019 - 2023",
            category: "Rencana Strategis",
            link: "https://drive.google.com/file/d/1MhX75w-L4KVkLX-VoCMlY8hKkz1_kqU6/view?usp=sharing"
        },
        {
            title: "Renstra Balitbang 2024 - 2026",
            category: "Rencana Strategis",
            link: "https://drive.google.com/file/d/10PNCAmF58Dco4zpKl80DbWp5PTAcJ9h8/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2018",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/1MJhbWVh3gJ6_9K5s0NfPLxWJASiH7swI/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2019",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/1p_ZzxQX6NJtFqzTzgM-_EEeTPWodJZCi/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2020",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/1A_qLCRmJYYkOJNjsmP6aSdJLjAU0lWg5/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2021",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/1jVq2iZH7uhjwLb_34xekgCFhjS1NeHnG/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2022",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/16z6PUNZOdMTGW4IZZb-U60JigOxTG2ck/view?usp=sharing"
        },
        {
            title: "Laporan Kinerja Balitbang 2023",
            category: "Laporan Kinerja",
            link: "https://drive.google.com/file/d/1EOpODRqzRHzWNjrJl0gKLKZmBOyu2rs2/view?usp=sharing"
        },
        {
            title: "LPPD Balitbang 2019",
            category: "LPPD",
            link: "https://drive.google.com/file/d/11uF_hl9ewDQK8IgzhM2RtHlFtJtX9wp0/view?usp=sharing"
        },
        {
            title: "LPPD Balitbang 2020",
            category: "LPPD",
            link: "https://drive.google.com/file/d/1G5KU6KRrhyuSF4EymL2ZBhIipaeNDewJ/view?usp=sharing"
        },
        {
            title: "LPPD Balitbang 2021",
            category: "LPPD",
            link: "https://drive.google.com/file/d/1Fe-c2Tgn8s1u2adhvC-XIRLdCq3d3HUk/view?usp=sharing"
        },
        {
            title: "LPPD Balitbang 2022",
            category: "LPPD",
            link: "https://drive.google.com/file/d/1eFmTzUURu1QVxMTs69LohNaM-k559HnC/view?usp=sharing"
        },
        {
            title: "LPPD Balitbang 2023",
            category: "LPPD",
            link: "https://drive.google.com/file/d/1NbOTlxjdhvXNJGspMUa323LOAStZV0su/view?usp=sharing"
        },
        {
            title: "LKPJ Balitbang 2019",
            category: "LKPJ",
            link: "https://drive.google.com/file/d/1NQqTRRaEvvJRKDaSFC8sDl4cTeoq7_EA/view?usp=sharing"
        },
        {
            title: "LKPJ Balitbang 2020",
            category: "LKPJ",
            link: "https://drive.google.com/file/d/1SE37-bulUgVDXxckyMHNwVBL7MflnfMm/view?usp=sharing"
        },
        {
            title: "LKPJ Balitbang 2022",
            category: "LKPJ",
            link: "https://drive.google.com/file/d/1-98iHE0GmyXzfPJqrNU5IhUcaIP4RHYg/view?usp=sharing"
        },
        {
            title: "LKPJ Balitbang 2023",
            category: "LKPJ",
            link: "https://drive.google.com/file/d/1MTzcBK1JpMTGMWrai9THfNfKXXYLvbjw/view?usp=sharing"
        },
        {
            title: "IKU Balitbang Tahun 2019",
            category: "Indikator Kinerja Utama",
            link: "https://drive.google.com/file/d/1WHoBAXvfKMVEti1Y6MiIb0s5SskA1TdW/view?usp=sharing"
        },
        {
            title: "IKU Balitbang Tahun 2020",
            category: "Indikator Kinerja Utama",
            link: "https://drive.google.com/file/d/1nqkB-nkLw3QUlFr8kf8dAYN4FHLmBpiU/view?usp=sharing"
        },
        {
            title: "IKU Balitbang Tahun 2024",
            category: "Indikator Kinerja Utama",
            link: "https://drive.google.com/file/d/1UOi-BbUvcV90dT1WxO2NaL0Le3NONPup/view?usp=drive_link"
        },
        {
            title: "Rumus IKU Balitbang",
            category: "Indikator Kinerja Utama",
            link: "https://drive.google.com/file/d/1iNjaOH30f2ckeeRQ-LRtuCb5IKvuq7xv/view?usp=sharing"
        },
        {
            title: "Perjankin Balitbang Tahun 2023",
            category: "Perjankin",
            link: "https://drive.google.com/file/d/1qWquSRZgHUOrJu3xOyfbQ1WzRWISNZeE/view?usp=sharing"
        },
        {
            title: "Perjankin Kepala Balitbang Tahun 2024",
            category: "Perjankin",
            link: "https://drive.google.com/file/d/1OXKWYXPulen4bJNxFbPzWNNZCnOxiEAB/view?usp=sharing"
        },
        {
            title: "Perjankin Eselon III sd Pelaksana Tahun 2024",
            category: "Perjankin",
            link: "https://drive.google.com/file/d/1b6TqPFvlntlfzvY9Pl0AUjkJHDSfJiCe/view?usp=sharing"
        },
        {
            title: "Perjankin Peneliti dan Perekayasa Tahun 2024",
            category: "Perjankin",
            link: "https://drive.google.com/file/d/1b6TqPFvlntlfzvY9Pl0AUjkJHDSfJiCe/view?usp=sharing"
        },
        {
            title: "Proses Peta Bisnis Balitbang 2024",
            category: "Proses Bisnis",
            link: "https://drive.google.com/file/d/1_3YWHWH0OsW-F0uWxazkz5UaI7-OaaVz/view?usp=sharing"
        },
        {
            title: "Rencana Aksi Balitbang Provinsi Kalbar Tahun 2023",
            category: "Rencana Aksi",
            link: "https://drive.google.com/file/d/1lR88rGP78bKCGYvRLe0xxV8BTzwrGa4T/view?usp=sharing"
        },
        {
            title: "Rencana Aksi Balitbang Provinsi Kalbar Tahun 2024",
            category: "Rencana Aksi",
            link: "https://drive.google.com/file/d/12YnMrSdpl9Fq8qcbfUTSkygvuczSmwzM/view?usp=sharing"
        },
        {
            title: "Cascading Balitbang Tahun 2022",
            category: "Berjenjang",
            link: "https://drive.google.com/file/d/1xVNIX7EMqWiGn-qme5uAkl1QmjwnivPx/view?usp=sharing"
        },
        {
            title: "Cascading Balitbang Tahun 2023",
            category: "Berjenjang",
            link: "https://drive.google.com/file/d/11L94Eyvad7xPRjuegliSZ3U69Bu1gTJO/view?usp=sharing"
        },
        {
            title: "Cascading Balitbang Tahun 2024",
            category: "Berjenjang",
            link: "https://drive.google.com/file/d/174oDcv2oZW4x-AGPgakMDqDIwo6-o3pb/view?usp=sharing"
        },
        {
            title: "Pohon Kinerja Balitbang 2024",
            category: "Pohon Kinerja",
            link: "https://drive.google.com/file/d/10lt-jFGCX5FQDL4_7g_2Ghct6ubTc9o4/view?usp=sharing"
        },
        {
            title: "Laporan Hasil Evaluasi",
            category: "Laporan Hasil Evaluasi",
            link: "https://drive.google.com/file/d/1sYwl0gsn2Dah9R1CUBEgeJPgk11YVNWK/view?usp=sharing"
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

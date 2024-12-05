---
author: sekret.bppkb
title: "Template"
date: 2024-11-08 06:30:02
---

<script>
    const items = [
    {
        title: "Leaflet Profil Balitbang Provinsi Kalbar 2022",
        category: "Templat Tahun 2022",
        link: "https://drive.google.com/file/d/12DVCMqBXMOhXvUukGryi74e_e7MP06ik/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas PPID Balitbang 2022",
        category: "Templat Tahun 2022",
        link: "https://drive.google.com/file/d/1p7sgK23j47ahHZ61jfSH56_83td3EMLJ/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas Pelayanan Balitbang 2022",
        category: "Templat Tahun 2022",
        link: "https://drive.google.com/file/d/1-NSJym-rFKng8L9UqZNQB_iP4Oz1u8yP/view?usp=sharing"
    },
    {
        title: "Leaflet Mekanisme Pertek Rekomendasi Penelitian 2022",
        category: "Templat Tahun 2022",
        link: "https://drive.google.com/file/d/1ZpEWAXMaSCbrdBOZ8SApepTDsv9JL6IL/view?usp=sharing"
    },
    {
        title: "Leaflet Profil Balitbang Provinsi Kalbar 2023",
        category: "Templat Tahun 2023",
        link: "https://drive.google.com/file/d/1GFtqqVmWPgVdVsOYYM-GfZ4p10RnSlwc/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas PPID Balitbang 2023",
        category: "Templat Tahun 2023",
        link: "https://drive.google.com/file/d/1sPwRhD5FwOAK0bvJcpGTFLh6MgsRxBn1/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas Pelayanan Balitbang 2023",
        category: "Templat Tahun 2023",
        link: "https://drive.google.com/file/d/1zRWSozf7K-feoVKmalkml-9p1iAep3v-/view?usp=sharing"
    },
    {
        title: "Profil Badan Publik 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1hGx0g7w1eOE2dhKxTyhlvgPS07kfO0JF/view?usp=sharing"
    },
    {
        title: "Poster Call For Papers Jurnal Borneo Akcaya 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1bpo8tkxhktYu0XRQb9hJWeiDXWMWTJpq/view?usp=sharing"
    },
    {
        title: "Poster Syarat Pengajuan Hak Cipta 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1FUZsOkHc2Ini5Cu-0rYZxUGUrVS2-Hoe/view?usp=sharing"
    },
    {
        title: "Poster Syarat Pengajuan Hak Merk 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1xx5v_yPyyDmmp3a6x_Aj57Wrj-3L2ycZ/view?usp=sharing"
    },
    {
        title: "Leaflet Profil Balitbang Provinsi Kalbar 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1_Pr4-TShjeTxC5G0p_8xm2MgeeWrfCDk/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas PPID Balitbang 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1F2giH6rcU_EQaxm-XKNe09FgiexWQc4g/view?usp=sharing"
    },
    {
        title: "Leaflet Sekilas Pelayanan Balitbang 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1F2giH6rcU_EQaxm-XKNe09FgiexWQc4g/view?usp=sharing"
    },
    {
        title: "Poster Denah Jalur Evakuasi Dini 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1kE9x98yBcWVx1ldqWNzpbTHjJqdjI_zK/view?usp=sharing"
    },
    {
        title: "Poster Barcode SKM Balitbang 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1CEZQ6bC8GkjGURdBFKtvtSnZrjvJQGt8/view?usp=sharing"
    },
    {
        title: "Poster Barcode Layanan Balitbang 2024",
        category: "Templat Tahun 2024",
        link: "https://drive.google.com/file/d/1q2utMOoJREXpnJ7-xQVpVSocBt6kN49w/view?usp=sharing"
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
            <div id="categoryList" class="list-none p-0 m-0"></div> <!-- Hilangkan list bullets -->
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
                <div class="p-4 bg-green-600 text-white flex-grow">
                    <p class="text-lg font-semibold">${item.title}</p>
                    <div class="flex items-center mt-2">
                        <i class="fas fa-file-alt mr-2"></i>
                        <span class="text-xs">${item.category}</span>
                    </div>
                </div>
                <a class="block p-4 bg-green-700 text-white text-center hover:bg-green-800 mt-auto no-underline" href="${item.link}" target="_blank" style="text-decoration: none;">
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

// Tambahkan opsi "All" untuk menampilkan semua item
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
    div.className = 'pl-4 p-1 hover:bg-gray-100 cursor-pointer text-sm'; // Perkecil ukuran list category dan beri jarak di kiri
    div.style.overflow = 'hidden'; // Tambahkan overflow hidden
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
    this.classList.toggle('text-green-700'); // Change color when active
    event.stopPropagation(); // Prevent click from propagating to document
});

document.addEventListener('click', function(event) {
    const dropdown = document.getElementById('categoryDropdown');
    const toggle = document.getElementById('categoryDropdownToggle');
    if (!dropdown.classList.contains('hidden') && !dropdown.contains(event.target) && !toggle.contains(event.target)) {
        dropdown.classList.add('hidden');
        toggle.classList.remove('text-green-700'); // Reset color when inactive
    }
});

document.getElementById('searchInput').addEventListener('input', function() {
    const searchTerm = this.value.toLowerCase();
    const filteredItems = items.filter(item => item.title.toLowerCase().includes(searchTerm));
    renderItems(filteredItems);
});

// Render all items initially
renderItems(items);
</script>
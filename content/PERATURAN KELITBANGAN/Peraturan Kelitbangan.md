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
            link: "https://drive.google.com/file/d/1ZFZTPlMvLGP-zwso-msHSE1hBCxPKmrk/view?usp=sharing"
        },
        {
            title: "UU No. 11 Tahun 2019 Sistem Nasional Ilmu Pengetahuan dan Teknologi",
            category: "Undang-Undang",
            link: "https://drive.google.com/file/d/1tSYO2Whx9nJBR5B4b_F8Z5q7cDXHNCbT/view?usp=sharing"
        },
        {
            title: "",
            category: "Peraturan Pemerintah",
            link: ""
        },
        {
            title: "Peraturan Presiden Nomor 78 Tahun 2021 tentang BRIN",
            category: "Peraturan Presiden",
            link: "https://drive.google.com/file/d/1m7NvTrLzGLtsDh4Is1C7fKbdsjYiSKd0/view?usp=sharing"
        },
        {
            title: "Permendagri No 17 Tahun 2016 tentang Pedoman Penelitian dan Pengembangan di Kementerian Dalam Negeri dan Pemerintah Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1mwE3RJO7I0GMqHDiDMrndlcQ96t8wL7W/view?usp=sharing"
        },
        {
            title: "Peraturan Pemerintah No 38 Tahun 2017 ttg Inovai Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1d3tvDTuh0XZkbD87kQGpbbEgt8cVZwjO/view?usp=sharing"
        },
        {
            title: "Permendagri No 104 Tahun 2018 tentang Penilaian dan Pemberian Penghargaan Inovasi Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1NvyGkkmXDYCcCK5c8pM5Yi4c-6yVtJIT/view?usp=sharing"
        },
        {
            title: "Permenpan RB Nomor 1 Tahun 2020 tentang Pedoman Analisis Jabatan dan Analisis Beban Kerja",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/1zQeb0TbfLqiDK7CdE78wK9qeua9IQgtJ/view?usp=sharing"
        },
        {
            title: "Permendagri No. 19 Tahun 2020 ttg Indeks Pengelolaan Keuangan Daerah",
            category: "Peraturan Menteri",
            link: "https://drive.google.com/file/d/11VCEDx5RH8YNko6AeJTJRQ5pP1JVlr8V/view?usp=sharing"
        },
        {
            title: "Peraturan Daerah No. 8 Tahun 2016 tentang Pembentukan dan Susunan Perangkat Daerah Provinsi Kalbar",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/1XrLDZyXvktWjy4xf1aoWiXwKnnzTWnx8/view?usp=sharing"
        },
        {
            title: "Peraturan Daerah No. 11 Tahun 2019 tentang Perubahan Atas Perda No 8 Tahun 2016",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/1DpVFti7A6ANMpg4_5Zp3woFMyqaLmbI0/view?usp=sharing"
        },
        {
            title: "Perda No 5 Tahun 2021 tentang Perubahan Kedua Atas Perda No. 8 tahun 2016 tentang Pembentukan dan Susunan Perangkat Daerah Provinsi Kalimantan Barat",
            category: "Peraturan Daerah",
            link: "https://drive.google.com/file/d/11LOnd1XZnI0kseIaqaPhpbPV-zHeBkzf/view?usp=sharing"
        },
        {
            title: "Peraturan Gubernur Kalbar Nomor 125 Tahun 2016 tentang Kedudukan, Susunan Organisasi, Tugas dan Fungsi serta Tata Kerja Balitbang Provinsi Kalbar",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1AmKiMnOy4X2tkZKKjpEUZVrtBLygt6Wr/view?usp=sharing"
        },
        {
            title: "Pergub No. 48 Tahun 2019 Perubahan Pergub No. 11 Tahun 2019 tentang Pendelegasian Kewenangan",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1GNWpR9O-VSBEmIZ2Uh-CEF1YTm4SNmtl/view?usp=sharing"
        },
        {
            title: "Peraturan Gubernur Kalbar Nomor 38 Tahun 2019 tentang Pedoman Penelitian dan Pengembangan",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1ohlBugoNzZ0PPtqAtfKbKpkgvmaLTqkm/view?usp=sharing"
        },
        {
            title: "Pergub No. 102 Tahun 2020 tentang Kode Etik Pelayanan Publik",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/16F_UOGUVp55gc25SJkw4lm48KGMHcugW/view?usp=sharing"
        },
        {
            title: "Peraturan Gubernur Nomor 138 Tahun 2021 tentang Kedudukan, Susunan organisasi, Tugas dan Fungsi serta Tata Kerja Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1csfQQ5eSjxrTgMMbA3rrXe6ak9Eo7PiG/view?usp=sharing"
        },
        {
            title: "Peraturan Gubernur Kalbar No. 211 Tahun 2021 tentang Penyelenggaraan Inovasi Daerah",
            category: "Peraturan Gubernur",
            link: "https://drive.google.com/file/d/1hRSbewQquGvLnUffhkzeaP-K4Pogv2Q7/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang Periode 2019-2021",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1UiOAuMmdDUYutVvJW_H-NzG-iHs_pptJ/view?usp=sharing"
        },
        {
            title: "Keputusan Pembentukan HIMPENINDO Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/18oM5T7IDUV9T4vf8j-xhIL0yPmSdfCbb/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang 2023",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1186I_UZfYhjQx5KWiWowPn23ddlAOXYN/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur tentang Simpul Jaringan Inovasi Provinsi Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1ZymNddtRbsEoHQx87cWMYJFg2Ik4a1Rb/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur No. 224/BAPPEDA/2023 tentang Forum Satu Data Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1iSt61sTOBqLc2uktFB_-bqYXexntKGGO/view?usp=sharing"
        },
        {
            title: "Keputusan Sekda Pembentukan Tim Admin Satu Data Kalimantan Barat",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1OeRkZ5tGmk3xCTpSOPbKSIVlntEjV3jZ/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur tantang Pembentukan Majelis Pertimbangan Balitbang 2024",
            category: "Keputusan Gubernur",
            link: "https://drive.google.com/file/d/1pt1G9OOlREwLBeCAytVnEezaMw8qLIe5/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur Kalimantan Barat tentang Pembentukan HIMPENINDO Kalimantan Barat",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/18oM5T7IDUV9T4vf8j-xhIL0yPmSdfCbb/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur Kalbar tentang Pembentukan Majelis Pertimbangan Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat Tahun 2019 sd 2021",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1UiOAuMmdDUYutVvJW_H-NzG-iHs_pptJ/view?usp=sharing"
        },
        {
            title: "Keputusan Gubernur Kalbar tentang Pembentukan Majelis Pertimbangan Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat Tahun 2023",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1186I_UZfYhjQx5KWiWowPn23ddlAOXYN/view?usp=sharing"
        },
        {
            title: "Surat Pengumuman Peringatan Evakuasi Dini 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1dYHdkrGXdxxPUd5jNIt_8zskeD3zYk_O/view?usp=sharing"
        },
        {
            title: "Keputusan Kaban ttg Penetapan Maklumat, Motto, Tim Pelayanan Publik 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1s3saJX21QceFg92HHmmGf5lfGZGl3Pbr/view?usp=sharing"
        },
        {
            title: "Keputusan Kaban ttg Pengelolaan Pengaduan Pelayanan Publik 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1Hsv8DK_qL8bLIZFHz48inVpwqlxluTTz/view?usp=sharing"
        },
        {
            title: "Keputusan Kaban ttg Pembentukan Arsip Dinamis 2024",
            category: "Keputusan Kepala Badan",
            link: "https://drive.google.com/file/d/1NXslh4uz-r6AHbqqQOJ-BnQtHpUVxeOp/view?usp=sharing"
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

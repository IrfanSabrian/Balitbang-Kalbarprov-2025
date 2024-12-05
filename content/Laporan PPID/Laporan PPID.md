---
author: sekret.bppkb
title: "Laporan PPID"
date: 2024-08-01 05:39:22
---

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<script>
    const items = [
        {
            title: "Laporan PPID Pelaksana Balitbang Tahun 2019",
            link: "https://drive.google.com/file/d/1vR6u0jaLN2HT-pZDZnOw4EzQnXSedE0N/view?usp=sharing"
        },
        {
            title: "Laporan PPID Pelaksana Balitbang Tahun 2020",
            link: "https://drive.google.com/file/d/1nBrVN1gUBXEfet6SyTeLZlrIm2TPENnh/view?usp=sharing"
        },
        {
            title: "Laporan PPID Pelaksana Balitbang Tahun 2021",
            link: "https://drive.google.com/file/d/1qD5rJJFHmfvEiDo5dgQmsom8BkF4SFBq/view?usp=sharing"
        },
        {
            title: "Laporan PPID Pelaksana Balitbang Tahun 2022",
            link: "https://drive.google.com/file/d/1ClCuOJzLymTT-5zWXKO1z68Cyi2tkIJb/view?usp=sharing"
        },
        {
            title: "Laporan PPID Pelaksana Balitbang Tahun 2023",
            link: "https://drive.google.com/file/d/1XWp8HehoSH5TrBVtGvq99Sh9VBsSX32e/view?usp=sharing"
        },
        {
            title: "Tanda Terima Penyampaian Laporan PPID 2023",
            link: "https://drive.google.com/file/d/1FF7wtnYzo08AsPXKXORHEF6K_9SE1w5E/view?usp=sharing"
        }
    ];

    const container = document.getElementById('information-list');

    items.forEach(item => {
        const div = document.createElement('div');
        div.className = 'w-64 bg-white border border-gray-300 rounded-lg overflow-hidden shadow-lg m-2 flex flex-col';
        div.innerHTML = `
            <div class="flex items-center justify-center w-full h-48 bg-gray-200">
                <i class="fas fa-file-pdf fa-5x text-red-600"></i>
            </div>
            <div class="p-4 bg-green-600 text-white flex-grow">
                <p class="text-lg font-semibold">${item.title}</p>
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
</script>

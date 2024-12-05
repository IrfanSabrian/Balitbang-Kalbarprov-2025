---
author: sekret.bppkb
title: "Standar Pelayanan"
date: 2024-08-01 02:22:19
items:
---

<div class="flex flex-wrap justify-start gap-12" id="service-standards"></div>

<script>
    const items = [
        {
            title: "Standar Pelayanan Penerbitan Pertek Izin Penelitian",
            link: "https://drive.google.com/file/d/1sueEHlPhBf5-nhXuFJIy-XbxiG_vz8si/view?usp=sharing"
        },
        {
            title: "Standar Pelayanan Penerbitan Jurnal",
            link: "https://drive.google.com/file/d/1tVAHmIk1DTV053xpX1kXSAD2NzWItP6H/view?usp=sharing"
        },
        {
            title: "Standar Pelayanan Pengusulan Fasilitasi HKI",
            link: "https://drive.google.com/file/d/1UsrDlZS51Hd4dMbdK2wFblI6TIVKEZL-/view?usp=sharing"
        }
    ];

    const container = document.getElementById('service-standards');

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

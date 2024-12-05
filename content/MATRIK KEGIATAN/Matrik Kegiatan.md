---
author: sekret.bppkb
title: "Matrik Kegiatan"
date: 2024-08-01 01:27:18
---

<div class="flex flex-wrap justify-start gap-12" id="activity-matrix"></div>

<script>
    const items = [
        {
            title: "Matrik w45",
            link: "https://drive.google.com/file/d/1tLK3qge2JzL9rGt2wW40tPaFE1DzL8Oz/view?usp=sharing"
        },
        {
            title: "Matrik Kegiatan Bidang Sospem",
            link: "https://drive.google.com/file/d/1fPuDpibyPwpIpFO9QdpdmOECvBFOvuDS/view?usp=sharing"
        },
        {
            title: "Matrik Kegiatan Bidang Ekbang",
            link: "https://drive.google.com/file/d/1mTFT3jq2Ja4tnglIr1SpajDwvElj05Dy/view?usp=sharing"
        },
        {
            title: "Matrik Kegiatan Bidang Inovteak",
            link: "https://drive.google.com/file/d/1fp9emYJk0WHunxWOQ7idyuGwQaGbS6WP/view?usp=sharing"
        }
    ];

    const container = document.getElementById('activity-matrix');

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

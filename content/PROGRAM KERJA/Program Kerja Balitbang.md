---
author: sekret.bppkb
title: "Program Kerja Balitbang"
date: 2024-08-08 06:19:19
---

<div class="flex flex-wrap justify-start gap-12" id="program-kerja"></div>

<script>
    const items = [
        {
            title: "Program Kerja 2022",
            link: "https://drive.google.com/file/d/1OxqLQZzbw772FUpr3H04phdLpvSSCLTH/view?usp=sharing"
        },
        {
            title: "Program Kerja 2023",
            link: "https://drive.google.com/file/d/1tFTFiSA5ovUKSkVukR-bMSzTKqRu_bfg/view?usp=sharing"
        },
        {
            title: "Program Kerja 2024",
            link: "https://drive.google.com/file/d/17eiHUaN5GdTyKtbg-N7d0eBq_8IaxFXe/view?usp=sharing"
        }
    ];

    const container = document.getElementById('program-kerja');

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

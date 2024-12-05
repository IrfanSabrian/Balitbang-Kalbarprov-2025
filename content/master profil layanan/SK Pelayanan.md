---
author: sekret.bppkb
title: "SK Pelayanan"
date: 2024-03-07 00:57:06
---

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<script>
    const items = [
        {
            title: "SK Standar Pelayanan Balitbang",
            link: "https://drive.google.com/file/d/1y7cvl0_oBomUdOBuVljUFhZ9tFwmSORE/view?usp=sharing"
        },
        {
            title: "SK Tim Pelayanan Publik Balitbang Tahun 2024",
            link: "https://drive.google.com/file/d/1u0Zq9oz48BsY-SmLN5eR49ztBZXn6eJE/view?usp=sharing"
        },
        {
            title: "SK Pengelola Pengaduan Balitbang Tahun 2024",
            link: "https://drive.google.com/file/d/1UbXbFKznnjB3oHFFM-M6u7jRFXJZ6mjQ/view?usp=sharing"
        },
        {
            title: "SK Tim Pelayanan Publik Balitbang Tahun 2023",
            link: "https://drive.google.com/file/d/1SmG4ihqsgNlNNjYEJCTGYbUuhO5DHMC4/view?usp=sharing"
        },
        {
            title: "SK Pengelola Pengaduan Balitbang Tahun 2023",
            link: "https://drive.google.com/file/d/1bLxQdD2ZxdKUQTCgJBVTiikrWbJryvK_/view?usp=sharing"
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

---
author: sekret.bppkb
title: "Pengumuman"
date: 2024-08-01 01:52:36
---

<script>
    const items = [
        {
            title: "Barcode Layanan",
            thumbnail: "/images/nz9zJ7nG9CYWmE2yjXWk.png",
            date: "1 Agustus 2024"
        },
        {
            title: "Call For Papers Journal",
            thumbnail: "/images/nz9zJ7nG9CYWmE2yjXWk.png",
            date: "1 Agustus 2024"
        },
        {
            title: "Layanan HKI",
            thumbnail: "/images/nz9zJ7nG9CYWmE2yjXWk.png",
            date: "1 Agustus 2024"
        },
        {
            title: "Layanan Pertek Izin Penelitian/Pendataan",
            thumbnail: "/images/nz9zJ7nG9CYWmE2yjXWk.png",
            date: "1 Agustus 2024"
        }
    ];
</script>

<div class="container p-6 mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4 lg:gap-8" id="announcement-list"></div>

<script>
    const announcementContainer = document.getElementById('announcement-list');

    items.forEach(item => {
        const div = document.createElement('div');
        div.className = 'group relative overflow-hidden rounded-lg shadow-md transition duration-500 ease-in-out cursor-pointer';
        div.style.width = 'auto';
        div.style.height = '55vh';
        div.innerHTML = `
            <img src="${item.thumbnail}" alt="${item.title}" class="rounded-lg shadow-sm w-full h-full object-cover transform group-hover:scale-105 transition duration-500 ease-in-out" />
            <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition duration-500 ease-in-out flex flex-col justify-center items-center text-white">
                <div class="text-base font-semibold mb-2 p-8 text-center">${item.title}</div>
                <div class="text-sm">${item.date}</div>
            </div>
        `;
        announcementContainer.appendChild(div);
    });
</script>
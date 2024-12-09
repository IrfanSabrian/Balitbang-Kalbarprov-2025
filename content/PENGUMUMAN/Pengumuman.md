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
            date: "1 Agustus 2024",
            images: ["/images/nz9zJ7nG9CYWmE2yjXWk.png"]
        },
        {
            title: "Call For Papers Journal",
            thumbnail: "/images/bbL4WEPMa74zvzHrq84o.png",
            date: "1 Agustus 2024",
            images: ["/images/bbL4WEPMa74zvzHrq84o.png"]
        },
        {
            title: "Layanan HKI",
            thumbnail: "/images/ZqcLt0fNwvdMV8QCyy4M.png",
            date: "1 Agustus 2024",
            images: ["/images/ZqcLt0fNwvdMV8QCyy4M.png", "/images/tj2W5fLx0zJhJQtv8gfh.png"]
        },
        {
            title: "Layanan Pertek Izin Penelitian/Pendataan",
            thumbnail: "/images/WCSs5BzX3HTd2QaD3po7.png",
            date: "1 Agustus 2024",
            images: ["/images/WCSs5BzX3HTd2QaD3po7.png"]
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
        div.style.padding = '0'; 
        div.style.margin = '0';  
        div.innerHTML = `
            <img src="${item.thumbnail}" alt="${item.title}" 
                class="rounded-lg shadow-sm object-cover transform group-hover:scale-105 transition duration-500 ease-in-out h-full" 
                style="width: 100%; height: 100%; margin: 0; padding: 0;"/>
            <div class="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition duration-500 ease-in-out flex flex-col justify-center items-center text-white">
                <div class="text-base font-semibold mb-2 p-8 text-center">${item.title}</div>
                <div class="text-sm">${item.date}</div>
            </div>
        `;
        div.addEventListener('click', () => {
            Fancybox.show(
                item.images.map((src) => ({
                    src: src,
                    type: 'image',
                    options: {
                        Toolbar: {
                            display: ["slideshow", "fullscreen", "close"],
                        },
                        Image: {
                            zoom: false,
                        },
                        transitionEffect: "fade",
                    }
                }))
            );
        });
        announcementContainer.appendChild(div);
    });
</script>
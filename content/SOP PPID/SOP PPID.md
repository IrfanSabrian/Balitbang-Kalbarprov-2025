---
author: sekret.bppkb
title: "SOP PPID"
date: 2024-09-06 02:30:59
---

<div class="flex flex-wrap justify-start gap-12" id="sop-ppid"></div>

<script>
    const items = [
        {
            title: "SOP Pengumuman Informasi",
            link: "https://drive.google.com/file/d/17xI5gBkDBRYWsL_JepnNeiQTjRSlJI1V/view?usp=sharing"
        },
        {
            title: "SOP Permohonan Informasi",
            link: "https://drive.google.com/file/d/1e6BPJlabNScc46UDpz74EeCNZCcV3Ul8/view?usp=sharing"
        },
        {
            title: "SOP Penanganan Keberatan Informasi",
            link: "https://drive.google.com/file/d/1IN4giZ1BIqeE6u4May8yNyYixfos7XpK/view?usp=sharing"
        },
        {
            title: "SOP Penyusunan Daftar Informasi dan Dokumentasi",
            link: "https://drive.google.com/file/d/1ZHaGbZb4l3swNt7xmBHAdMkWhom7n_BO/view?usp=sharing"
        },
        {
            title: "SOP Pendokumentasian Informasi",
            link: "https://drive.google.com/file/d/1pwT6WWom8oSTwLH_fygo_tziQqukx4FQ/view?usp=sharing"
        },
        {
            title: "SOP Pendokumentasian Informasi kecualikan",
            link: "https://drive.google.com/file/d/1l_1J6AXZDceyhU-JlFu6uY0xIcBhv9sE/view?usp=sharing"
        },
        {
            title: "SOP Uji Lanjutan",
            link: "https://drive.google.com/file/d/1F5XmIwkPeAe2Hlit8SUyCkwKpahsB6T3/view?usp=sharing"
        },
        {
            title: "SOP Fasilitasi Sengketa Informasi",
            link: "https://drive.google.com/file/d/1UkGV7zlbj3XTqjEWXogW0h0zGvbSmBqp/view?usp=sharing"
        }
    ];

    const container = document.getElementById('sop-ppid');

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

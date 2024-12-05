---
author: sekret.bppkb
title: "Formulir PPID"
date: 2024-08-06 07:48:58
---

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<script>
    const items = [
        {
            title: "Formulir Permohonan Informasi",
            link: "https://drive.google.com/file/d/1UFrfGOp735QUO-K9a1utrazM35wfC0jW/view?usp=sharing"
        },
        {
            title: "Formulir Pengajuan Keberatan Atas Permohonan Informasi",
            link: "https://drive.google.com/file/d/1QB1usppYoQOMcIMMmsyBKBGnrBHno-EB/view?usp=sharing"
        },
        {
            title: "Formulir Pemberitahuan Tertulis Atas Permohonan Informasi",
            link: "https://drive.google.com/file/d/1RDV8G0Shspw--hty8hl1i-1ORpUdPJZh/view?usp=sharing"
        },
        {
            title: "Formulir Pemberitahuan Kurangnya Kelengkapan Atas Permohonan Informasi",
            link: "https://drive.google.com/file/d/1orwYG_anp9VxTmN0Hqo2WbA2I6StSq5Q/view?usp=sharing"
        },
        {
            title: "Formulir Tanda Terima Permohonan Informasi",
            link: "https://drive.google.com/file/d/1iyLzSawGkANjbEnURWTBZOk8NvihsmRr/view?usp=sharing"
        },
        {
            title: "Formulir Tanda Terima Keberatan Atas Permohonan Informasi",
            link: "https://drive.google.com/file/d/1_OSe3-eq5sPJykTVM1Un9bMMSqk9lzF6/view?usp=sharing"
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

---
author: sekret.bppkb
title: "Daftar Informasi"
date: 2024-09-10 06:51:03
---

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<script>
    const items = [
        {
            title: "Penetapan Daftar Informasi Publik 2024",
            link: "https://drive.google.com/file/d/1lqzPKDKLyVy_0yxU8AJ6iVVdP4P4v7xw/view?usp=sharing"
        },
        {
            title: "Daftar Informasi Publik PPID Utama",
            link: "https://sikedip.kalbarprov.go.id/opd/badan-penelitian-dan-pengembangan-prov-kalbar"
        },
        {
            title: "Daftar Informasi Publik",
            link: "https://drive.google.com/file/d/1UWh5ro8RGsWzF7ETk9jP8GxJJXe3OiIo/view?usp=sharing"
        },
        {
            title: "Daftar Informasi Secara Berkala",
            link: "https://drive.google.com/file/d/1bjWlNK8AqrZtvu-UYKcNxW92xY30nPcK/view?usp=sharing"
        },
        {
            title: "Daftar Informasi Serta Merta",
            link: "https://drive.google.com/file/d/1NqhNKB17TmM8jL19fLXvZBj94CFZbzPg/view?usp=sharing"
        },
        {
            title: "Daftar Informasi Setiap Saat",
            link: "https://drive.google.com/file/d/1iwYX-t5tF-lPI8kcKZuB9a7v45X5HFRE/view?usp=sharing"
        },
        {
            title: "Daftar Informasi Dikecualikan",
            link: "https://drive.google.com/file/d/18O1lGXs-8GuljPXw_lIpyFqNYP1GF-3q/view?usp=sharing"
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

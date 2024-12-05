---
author: sekret.bppkb
title: "Jurnal Borneo Akcaya"
date: 2024-08-01 03:53:49
---

<div class="flex flex-wrap justify-start gap-12" id="information-list"></div>

<script>
const items = [
    {
        title: "Jil. 5 No. 1",
        category: "Jurnal Borneo Akcaya Tahun 2019",
        link: "https://drive.google.com/file/d/1DMNE0ODUjM5nYJX1T-ZK1V08SvvwJEO_/view?usp=sharing"
    },
    {
        title: "Jil. 5 No. 2",
        category: "Jurnal Borneo Akcaya Tahun 2019",
        link: "https://drive.google.com/file/d/1LKseL0hu8Nqi9HGevqmt05GEiPFbmE4g/view?usp=sharing"
    },
    {
        title: "Jil. 6 No. 2",
        category: "Jurnal Borneo Akcaya Tahun 2020",
        link: "https://drive.google.com/file/d/1MQrE28gLsJU3nVn3wZ5PkkTwBKpp63Br/view?usp=sharing"
    },
    {
        title: "Jil. 7 No. 1",
        category: "Jurnal Borneo Akcaya Tahun 2021",
        link: "https://drive.google.com/file/d/1VzCm6h0bc06BUhFsoeB8bkZNmwAYKsOg/view?usp=sharing"
    },
    {
        title: "Jil. 7 No. 2",
        category: "Jurnal Borneo Akcaya Tahun 2021",
        link: "https://drive.google.com/file/d/1GOq2pr5eBnkG2X_pDay8JgNRKudzq613/view?usp=sharing"
    },
    {
        title: "Jil. 8 No. 1",
        category: "Jurnal Borneo Akcaya Tahun 2022",
        link: "https://drive.google.com/file/d/1KanOwed1OBe-pAIU4T7E4A4xvnl2wfxf/view?usp=sharing"
    },
    {
        title: "Jil. 8 No. 2",
        category: "Jurnal Borneo Akcaya Tahun 2022",
        link: "https://drive.google.com/file/d/1qfZypsP04nJH9wCuhzA7Ec7df8ZCTFEb/view?usp=sharing"
    },
    {
        title: "Jil. 9 No. 2",
        category: "Jurnal Borneo Akcaya Tahun 2023",
        link: "https://drive.google.com/file/d/1pxQh-OWsvh--VA-kNIf_-jAXjfn1JbSS/view?usp=sharing"
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
            <div class="flex items-center mt-2">
                <i class="fas fa-file-alt mr-2"></i>
                <span class="text-xs">${item.category}</span>
            </div>
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

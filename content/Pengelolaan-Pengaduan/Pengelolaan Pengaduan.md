---
author: sekret.bppkb
title: "Pengelolaan Pengaduan"
date: 2024-08-07 07:00:19
---
<div style="display: flex; flex-wrap: wrap; gap: 30px; width: 100%; margin-top: 40px;">

  <div style="flex: 1 1 calc(50% - 30px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-sitemap text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Alur Mekanisme Pengaduan</span>
    <button onclick="openPdfModal('https://drive.google.com/file/d/1LXX3ZJHwHT8OH_O9gRThb9f_CYE6t_Ia/preview')" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 30px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-user-tie text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Pejabat Pengelola Pengaduan</span>
    <button onclick="window.location.href='/master-pengelolaan-pengaduan/pejabat-pengelola-pengaduan'" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 30px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-edit text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Pengaduan Online</span>
    <button onclick="window.location.href='https://docs.google.com/forms/d/1fa-wNkLbkmdtC-VUa23765_Ra68I8OZZe-i0B2sKkm0/'" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 30px); box-sizing: border-box; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;" class="border-customGreen bg-customGreen rounded-2xl dark:bg-gray-700 dark:text-white">
      <i class="fas fa-chart-bar text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif;" class="text-white">Rekap Pengaduan</span>
    <button onclick="window.location.href='/master-pengelolaan-pengaduan/rekapitulasi-pengaduan'" class="px-2.5 py-1.5 bg-transparent text-white border border-white rounded-xl text-base cursor-pointer transition-colors duration-300 hover:bg-white hover:text-customGreen dark:hover:text-gray-700">Lihat Detail <i class="fas fa-arrow-right ml-1.5"></i></button>
  </div>

<style>
@media (max-width: 1024px) { 
  div[style*="display: flex; flex-wrap: wrap;"] > div {
    flex: 1 1 100%; 
    margin-bottom: 20px;
  }
}

@media (max-width: 768px) { 
  div[style*="display: flex; flex-wrap: wrap;"] {
    flex-direction: column; 
    align-items: center; 
  }

  div[style*="display: flex; flex-wrap: wrap;"] > div {
    flex: none; 
    width: calc(70% - 30px); 
    height: 150px; 
    max-width: calc(70% - 30px);
    margin-bottom: 20px;
  }
}
</style>

</div>
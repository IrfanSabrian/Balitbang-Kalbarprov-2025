---
author: sekret.bppkb
title: "Pengelolaan Pengaduan"
date: 2024-08-07 07:00:19
---
<div style="display: flex; flex-wrap: wrap; gap: 30px; width: 100%; margin-top: 40px;">

  <div style="flex: 1 1 calc(50% - 20px); box-sizing: border-box; padding: 10px; border: 1px solid #2f855a; background-color: #2f855a; border-radius: 15px; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;">
      <i class="fas fa-sitemap text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif; color: #fff;">Alur Mekanisme Pengaduan</span>
    <button onclick="window.open('https://drive.google.com/file/d/1LXX3ZJHwHT8OH_O9gRThb9f_CYE6t_Ia/view?usp=sharing', '_blank')" style="margin-top: 10px; padding: 5px 10px; background-color: transparent; color: #fff; border: 1px solid #fff; border-radius: 15px; font-size: 10pt; cursor: pointer;" onmouseover="this.style.backgroundColor='#fff'; this.style.color='#2f855a';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#fff';">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 20px); box-sizing: border-box; padding: 10px; border: 1px solid #2f855a; background-color: #2f855a; border-radius: 15px; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;">
      <i class="fas fa-user-tie text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif; color: #fff;">Pejabat Pengelola Pengaduan</span>
    <button onclick="window.location.href='/master-pengelolaan-pengaduan/pejabat-pengelola-pengaduan'" style="margin-top: 10px; padding: 5px 10px; background-color: transparent; color: #fff; border: 1px solid #fff; border-radius: 15px; font-size: 10pt; cursor: pointer;" onmouseover="this.style.backgroundColor='#fff'; this.style.color='#2f855a';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#fff';">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 20px); box-sizing: border-box; padding: 10px; border: 1px solid #2f855a; background-color: #2f855a; border-radius: 15px; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;">
      <i class="fas fa-edit text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif; color: #fff;">Pengaduan Online</span>
    <button onclick="window.location.href='https://docs.google.com/forms/d/1fa-wNkLbkmdtC-VUa23765_Ra68I8OZZe-i0B2sKkm0/'" style="margin-top: 10px; padding: 5px 10px; background-color: transparent; color: #fff; border: 1px solid #fff; border-radius: 15px; font-size: 10pt; cursor: pointer;" onmouseover="this.style.backgroundColor='#fff'; this.style.color='#2f855a';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#fff';">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
  </div>

  <div style="flex: 1 1 calc(50% - 20px); box-sizing: border-box; padding: 10px; border: 1px solid #2f855a; background-color: #2f855a; border-radius: 15px; height: 150px; margin-bottom: 20px; display: flex; flex-direction: column; align-items: center; justify-content: center;">
      <i class="fas fa-chart-bar text-white" style="margin-bottom: 5px; font-size: 40px;"></i>
      <span style="font-size: 12pt; font-family: 'Poppins', sans-serif; color: #fff;">Rekap Pengaduan</span>
    <button onclick="window.location.href='/master-pengelolaan-pengaduan/rekapitulasi-pengaduan'" style="margin-top: 10px; padding: 5px 10px; background-color: transparent; color: #fff; border: 1px solid #fff; border-radius: 15px; font-size: 10pt; cursor: pointer;" onmouseover="this.style.backgroundColor='#fff'; this.style.color='#2f855a';" onmouseout="this.style.backgroundColor='transparent'; this.style.color='#fff';">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
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
---
author: sekret.bppkb
title: "Google Scholar Lityasa"
date: 2024-08-01 01:41:35
---

<style>
    .profile-container {
    background-color: #03A055;
    border-radius: 0.5rem;
    padding: 0.5rem 0.5rem; /* Mengurangi lebar padding */
    margin: 0.5rem 0.25rem; /* Mengurangi margin atas dan bawah */
    text-align: center;
    height: auto;
    }

  .profile-content {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .profile-pic {
    border-radius: 50%;
    width: 100px;
    height: 100px;
    object-fit: cover;
  }
  .profile-name {
    font-family: arial, helvetica, sans-serif;
    font-size: 14pt;
    color: white;
    margin-bottom: 0.5rem;
  }
  .profile-link {
    text-decoration: none;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 0.5rem;
    border: 2px solid white; /* Memperbesar garis tepi */
    padding: 0.5rem;
    border-radius: 0.5rem;
    width: 100%;
    transition: background-color 0.3s, color 0.3s;
  }
  .profile-link:hover {
    background-color: white;
    color: #03A055;
  }
  .profile-detail {
    color: white;
    font-family: arial, helvetica, sans-serif;
    font-size: 10pt;
  }
  .profile-icon {
    color: white;
    margin-left: 0.5rem;
  }
  .profile-button {
    margin-top: 10px;
    padding: 5px 10px;
    background-color: transparent;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 15px;
    font-size: 10pt;
    cursor: pointer;
  }
  .profile-button:hover {
    background-color: #fff;
    color: #2f855a;
  }
</style>

<div class="flex flex-wrap justify-around gap-12">
  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-1" alt="Pramushinta Arum Pynanjung" class="profile-pic">
      <span class="profile-name">Pramushinta Arum Pynanjung</span>
      <button id="profile-link-1" onclick="window.location.href='https://scholar.google.co.id/citations?user=FQ9H5oAAAAAJ&amp;hl=id'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>

  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-2" alt="Giska Hediyanti" class="profile-pic">
      <span class="profile-name">Giska Hediyanti</span>
      <button id="profile-link-2" onclick="window.location.href='https://scholar.google.com/citations?user=FJ-SNbIAAAAJ&amp;hl=id'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>

  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-3" alt="Dwi Septiyarini" class="profile-pic">
      <span class="profile-name">Dwi Septiyarini</span>
      <button id="profile-link-3" onclick="window.location.href='https://scholar.google.co.id/citations?user=bUr4FcUAAAAJ&amp;hl=id'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>
</div>

<div class="flex flex-wrap justify-around gap-12">
  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-4" alt="Edy Agustinus" class="profile-pic">
      <span class="profile-name">Edy Agustinus</span>
      <button id="profile-link-4" onclick="window.location.href='https://scholar.google.com/citations?user=G04TTjYAAAAJ&amp;hl=en'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>

  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-5" alt="Reny Rianti" class="profile-pic">
      <span class="profile-name">Reny Rianti</span>
      <button id="profile-link-5" onclick="window.location.href='https://scholar.google.co.id/citations?user=lAwacPkAAAAJ&amp;hl=en'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>

  <div class="w-full sm:w-1/4 p-1 profile-container"> <!-- Mengurangi lebar padding -->
    <div class="profile-content">
      <img id="profile-pic-6" alt="Resky Nanda Pranaka" class="profile-pic">
      <span class="profile-name">Resky Nanda Pranaka</span>
      <button id="profile-link-6" onclick="window.location.href='https://scholar.google.com/citations?user=yvASHTcAAAAJ&amp;hl=en'" class="profile-button">Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i></button>
    </div>
  </div>
</div>

<p class="MsoNormal" style="margin-bottom: 0cm; line-height: 1.1;">
  <span style="font-family: arial, helvetica, sans-serif; font-size: 10pt;">&nbsp;</span>
</p>

<script>
  function setProfilePicture(linkId, imgId) {
    const link = document.getElementById(linkId).getAttribute('onclick').split("'")[1];
    const userId = new URL(link).searchParams.get("user");
    const imgSrc = `https://scholar.google.com/citations?view_op=medium_photo&user=${userId}`;
    document.getElementById(imgId).src = imgSrc;
  }

  setProfilePicture("profile-link-1", "profile-pic-1");
  setProfilePicture("profile-link-2", "profile-pic-2");
  setProfilePicture("profile-link-3", "profile-pic-3");
  setProfilePicture("profile-link-4", "profile-pic-4");
  setProfilePicture("profile-link-5", "profile-pic-5");
  setProfilePicture("profile-link-6", "profile-pic-6");
</script>

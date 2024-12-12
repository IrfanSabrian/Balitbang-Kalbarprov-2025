---
author: sekret.bppkb
title: "Google Scholar Lityasa"
date: 2024-08-01 01:41:35
---

<script>
    // Data nama dan link profil
  const profiles = [
    {
      name: "Pramushinta Arum Pynanjung",
      link: "https://scholar.google.co.id/citations?user=FQ9H5oAAAAAJ&hl=id"
    },
    {
      name: "Giska Hediyanti",
      link: "https://scholar.google.com/citations?user=FJ-SNbIAAAAJ&hl=id"
    },
    {
      name: "Dwi Septiyarini",
      link: "https://scholar.google.co.id/citations?user=bUr4FcUAAAAJ&hl=id"
    },
    {
      name: "Edy Agustinus",
      link: "https://scholar.google.com/citations?user=G04TTjYAAAAJ&hl=en"
    },
    {
      name: "Reny Rianti",
      link: "https://scholar.google.co.id/citations?user=lAwacPkAAAAJ&hl=en"
    },
    {
      name: "Resky Nanda Pranaka",
      link: "https://scholar.google.com/citations?user=yvASHTcAAAAJ&hl=en"
    }
  ];
</script>

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

<div class="flex flex-wrap justify-around gap-12" id="profile-container"></div>

<script>
  // Generate elemen HTML secara dinamis
  const profileContainer = document.getElementById('profile-container');

  profiles.forEach((profile, index) => {
    const userId = new URL(profile.link).searchParams.get("user");
    const profileHtml = `
      <div class="w-full sm:w-1/4 p-1 profile-container">
        <div class="profile-content">
          <img src="https://scholar.google.com/citations?view_op=medium_photo&user=${userId}" alt="${profile.name}" class="profile-pic">
          <span class="profile-name">${profile.name}</span>
          <button onclick="window.location.href='${profile.link}'" target="_blank" class="profile-button">
            Lihat Detail <i class="fas fa-arrow-right" style="margin-left: 5px;"></i>
          </button>
        </div>
      </div>`;
    profileContainer.innerHTML += profileHtml;
  });
</script>

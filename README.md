# Balitbang Kalbarprov 2025

Repository ini berisi source code website resmi Badan Penelitian dan Pengembangan Provinsi Kalimantan Barat.

Website produksi: https://litbang.kalbarprov.go.id/

## Ringkasan

Website ini dibangun sebagai static site berbasis Hugo. Struktur kontennya disusun dari file Markdown di folder `content`, sedangkan gambar, dokumen, slider, thumbnail, dan aset publik lain disimpan di folder `static`.

Bagian utama yang sudah tersedia di dalam konten antara lain:

- Profil Badan, Unit Kerja, Profil Pegawai, Program Kerja, dan kontak.
- Riset, Program Riset, Hasil Kelitbangan, Litbangjirap, dan Kerjasama Kelitbangan.
- Berita, Artikel, Flyers, Gallery Kegiatan, Video, Jurnal, Template, dan Pengumuman.
- PPID, Daftar Informasi, Formulir PPID, Laporan PPID, SOP PPID, dan Permohonan Online.
- Aplikasi Balitbang, Aplikasi SPBE, Aplikasi Data Kalbar, serta Link Terkait.

## Teknologi

- Hugo static site generator.
- Theme `blist`.
- Tailwind CSS, PostCSS, Autoprefixer, dan plugin Typography untuk proses styling.
- Markdown dengan front matter untuk mengelola halaman dan posting.
- Aset statis di `static`.

## Struktur Folder

```text
.
|-- archetypes/      # Template awal konten Hugo
|-- content/         # Halaman, berita, artikel, galeri, PPID, dan konten website
|-- layouts/         # Override layout Hugo jika dibutuhkan
|-- static/          # Gambar, dokumen, thumbnail, slider, dan aset publik
|-- themes/blist/    # Theme Hugo yang digunakan
|-- config.toml      # Konfigurasi website, menu, parameter, dan metadata
|-- package.json     # Script dan dependency frontend/theme
`-- package-lock.json
```

## Menjalankan di Lokal

Pastikan sudah memasang:

- Hugo Extended.
- Node.js dan npm.

Install dependency:

```bash
npm install
```

Jalankan mode development:

```bash
npm run start
```

Perintah tersebut menjalankan:

```bash
hugo server --disableFastRender
```

Setelah server aktif, buka alamat lokal yang ditampilkan Hugo, biasanya:

```text
http://localhost:1313
```

## Build Produksi

Untuk membuat output static production:

```bash
npm run build
```

Script tersebut menjalankan:

```bash
NODE_ENV=production hugo --gc
```

Hasil build akan dibuat di folder `public`.

## Mengelola Konten

1. Tambahkan atau ubah file Markdown di folder `content/<nama-section>`.
2. Gunakan front matter seperti `title`, `date`, `author`, `thumbnail`, dan field tambahan lain yang sudah dipakai pada konten sejenis.
3. Simpan gambar atau dokumen pendukung di folder yang sesuai di `static`.
4. Pastikan path aset di Markdown diawali dari root website, misalnya `/Berita/thumbnails/nama-file.jpg`.
5. Jalankan `npm run start` untuk mengecek tampilan sebelum build.

Contoh front matter:

```yaml
---
author: sekret.bppkb
title: "Judul Konten"
date: 2025-01-01
thumbnail: /Berita/thumbnails/contoh.jpg
---
```

## Catatan Konfigurasi

- Menu utama dan submenu website diatur melalui `config.toml`.
- Domain produksi yang dicatat di konfigurasi adalah `litbang.kalbarprov.go.id`.
- Parameter halaman depan seperti `frontBundle`, `frontBundle2`, dan seterusnya menentukan section konten yang ditampilkan di beranda.
- Jika deploy ke domain produksi, pastikan nilai `baseurl`/`baseURL` di `config.toml` sesuai kebutuhan server.

## Deployment

Website ini dapat dideploy sebagai static site. Setelah menjalankan build, folder `public` dapat dipublikasikan ke server hosting atau pipeline deployment yang digunakan untuk domain resmi.

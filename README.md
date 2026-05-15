# Nisrina Fatinawati — GitHub Pages Ready

Folder ini sudah disiapkan supaya bisa langsung di-upload ke repository GitHub dan dipublish via GitHub Pages.

## Struktur

```bash
nisrina-github-pages/
├── index.html
├── .nojekyll
├── README.md
└── karya/
    ├── ketika-sunyi-lebih-jujur.html
    ├── di-meja-tempat-hujan.html
    └── teddy-bear-di-jendela.html
```

## Langkah upload ke GitHub Pages

1. Buat repository baru di GitHub, misalnya: `nisrina-fatinawati`.
2. Upload semua isi folder ini ke root repository.
3. Pastikan file utama bernama `index.html`.
4. Buka repository di GitHub.
5. Masuk ke **Settings**.
6. Klik **Pages** di sidebar.
7. Pada **Build and deployment**, pilih:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
8. Klik **Save**.
9. Tunggu beberapa menit sampai GitHub selesai deploy.
10. Website akan live di URL seperti:
    `https://username.github.io/nisrina-fatinawati/`

## Kenapa ada file .nojekyll?

File `.nojekyll` dipakai supaya GitHub Pages tidak mencoba memproses situs ini dengan Jekyll. Ini aman dan cocok untuk static HTML biasa.

## Kalau nanti mau custom domain

Bisa ditambahkan setelah website live lewat menu:
**Settings → Pages → Custom domain**

## Catatan penting

- File homepage harus tetap bernama `index.html`.
- Semua link internal di website ini sudah disusun agar cocok untuk GitHub Pages versi project site.
- Kalau nanti mau tambah artikel baru, cukup duplikasi file HTML di folder `karya/`, lalu tambahkan link-nya di `index.html`.

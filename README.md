# Sulapa Falak

Arah • Waktu • Falak

Prototype UI/UX Sulapa Falak yang siap dipublikasikan menggunakan GitHub Pages.

## Struktur

- `index.html` — halaman utama
- `assets/logo.png` — logo Sulapa Falak
- `.nojekyll` — memastikan GitHub Pages menyajikan file statis tanpa pemrosesan Jekyll

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `sulapa-falak`.
2. Upload seluruh isi folder ini ke repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
5. Simpan.
6. GitHub akan memberikan alamat seperti:
   `https://USERNAME.github.io/sulapa-falak/`

Catatan: paket ini adalah versi web/prototype. Fitur yang membutuhkan sensor perangkat, GPS, AR, notifikasi Azan, dan perhitungan astronomi real-time masih perlu implementasi Web API/Android native agar benar-benar berfungsi penuh.

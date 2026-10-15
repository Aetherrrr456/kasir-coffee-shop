# Nice Coffe POS – Aplikasi Kasir

## Isi folder
- `index.html` – aplikasi POS
- `manifest.json`, `sw.js` – agar bisa dipasang sebagai aplikasi & jalan offline
- `icon-*.png`, `apple-touch-icon.png` – ikon aplikasi

## Langkah 1 – Unggah ke GitHub Pages (gratis)
1. Daftar/masuk di https://github.com
2. Klik **New repository**, beri nama `nice-coffe-pos`, pilih **Public**, klik **Create repository**.
3. Klik **uploading an existing file**, tarik SEMUA file di folder ini (bukan zip-nya), lalu **Commit changes**.
4. Buka **Settings → Pages**. Di *Build and deployment* pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu **Save**.
5. Tunggu 1–3 menit. Alamat aplikasi: `https://USERNAME.github.io/nice-coffe-pos/`

## Langkah 2 – Pasang di perangkat
- **Android / Chrome**: buka alamat di atas → menu ⋮ → **Install app** (atau tombol **Pasang** di sidebar aplikasi).
- **iPhone / Safari**: tombol **Share** → **Add to Home Screen**.
- **Windows / Mac (Chrome/Edge)**: ikon install di ujung kolom alamat.

Setelah terpasang, aplikasi punya ikon sendiri, tampil layar penuh, dan tetap bisa dibuka tanpa internet.

## Memindahkan data lama
Data tersimpan di browser per alamat web, jadi tidak ikut pindah otomatis.
1. Di versi lama: **Laporan → Backup data** → salin teksnya.
2. Di aplikasi baru: **Laporan → Pulihkan data** → tempel → Pulihkan.

## Update aplikasi
Ganti `index.html` di GitHub, lalu naikkan angka `VERSI` di `sw.js` (mis. `nicecoffe-v2`) agar perangkat memuat versi baru.

## Catatan
- Data tetap tersimpan lokal di tiap perangkat (tidak sinkron antar perangkat).
- Jangan hapus data situs/cache browser; lakukan backup berkala.
- Mode Pelanggan bekerja di perangkat/browser yang sama dengan kasir.

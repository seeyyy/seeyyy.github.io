PCPM 41 — Rencana Belajar
==========================

Cara pakai:
1. Upload folder ini (atau cukup file index.html) ke hosting statis pilihanmu,
   misalnya Netlify, Vercel, GitHub Pages, atau Cloudflare Pages.
2. Atau buka langsung index.html di browser (double click) — semua fitur tetap
   jalan secara lokal, tidak butuh server/backend apa pun.

Penyimpanan data:
- File ini otomatis mendeteksi lingkungannya. Saat dibuka di luar Claude.ai
  (di-deploy sendiri seperti ini), progres centangan/kalender/pomodoro disimpan
  via localStorage di browser yang dipakai membuka halaman ini.
- localStorage bersifat per-browser & per-perangkat — artinya progres di HP dan
  laptop TIDAK otomatis sinkron satu sama lain kalau di-deploy mandiri seperti ini
  (beda dengan saat dibuka sebagai Artifact di Claude.ai, yang tersimpan ke akun).
- Jangan clear cache/data browser untuk domain tempat file ini di-hosting, karena
  itu akan menghapus progres yang tersimpan.

Tidak ada dependensi build (tidak perlu npm install dsb) — murni HTML/CSS/JS
satu file, font dimuat dari Google Fonts via koneksi internet biasa.

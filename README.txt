# Misi Harian PWA

Paket ini sudah siap dijadikan Progressive Web App (PWA).

File:
- index.html — aplikasi
- manifest.webmanifest — identitas aplikasi
- sw.js — offline cache

Penting:
PWA harus dibuka dari HTTPS (atau localhost saat development). File lokal `file://` tidak cukup untuk menampilkan opsi Install/Tambahkan ke layar utama.

Setelah di-host di HTTPS:
1. Buka URL aplikasi di Chrome Android.
2. Buka menu ⋮.
3. Pilih "Install app" / "Tambahkan ke layar utama" (nama bisa berbeda).

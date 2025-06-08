# ilham-razk.github.io

Website personal interaktif berisi ucapan romantis lengkap dengan musik latar dan rundown acara.

## Deskripsi

Website ini dibuat sebagai hadiah khusus untuk Melisa Jane, dengan fitur:

- Halaman login sederhana untuk akses ke halaman utama.
- Halaman utama menampilkan foto, pesan romantis yang muncul satu per satu dengan efek fade-in.
- Musik latar yang dapat diputar otomatis setelah login.
- Rundown acara yang bisa dilihat melalui popup modal tanpa menghentikan musik.
- Fitur logout dan proteksi akses halaman utama agar tidak bisa dibuka langsung tanpa login.
- Auto logout otomatis setelah 5 menit tidak ada aktivitas user (idle).
- Desain warna romantis dan responsif.

## Struktur Folder / File

- `index.html` — Halaman login
- `home.html` — Halaman utama dengan pesan, musik, dan modal rundown
- `apt-bruno-mars.mp3` — File musik latar
- `icanme.jpeg` — Foto di halaman utama
- `README.md` — Dokumentasi ini

## Cara Menggunakan

1. Buka `index.html`.
2. Login dengan username dan password yang sudah di-set (atau sesuai implementasi).
3. Setelah login berhasil, otomatis diarahkan ke `home.html`.
4. Musik latar otomatis berjalan.
5. Klik tombol **Lihat Rundown** untuk membuka popup rundown acara.
6. Klik tombol **Logout** untuk keluar dan kembali ke halaman login.
7. Jika tidak ada aktivitas selama 5 menit, user akan otomatis logout.

## Catatan

- Autoplay musik mungkin dibatasi oleh browser jika tidak ada interaksi user.
- Pastikan file musik dan gambar tersedia di direktori yang sama dengan HTML.
- Penggunaan `localStorage` untuk menyimpan status login dan pengaturan musik.

## Lisensi

Proyek ini dibuat untuk keperluan pribadi dan pembelajaran.

---

*Created with ❤️ by Ilham Razk*

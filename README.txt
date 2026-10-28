LINKTREE AUSTIN

Isi zip:
- index.html  : halaman utama
- admin.html  : halaman admin (buka /admin.html)
- data.json   : isi halaman (nama, tombol, sosmed), diedit lewat admin
- assets/     : taruh foto/logo di sini sebagai avatar.png

Cara pasang:
1. Upload semua isi zip ke root repo GitHub.
2. Deploy lewat hosting yang otomatis update dari GitHub (GitHub Pages, Vercel, Netlify, Cloudflare Pages).
3. Foto/logo: taruh di assets/avatar.png atau unggah lewat admin.

Cara pakai admin:
1. Buka /admin.html
2. Isi repo (user/nama-repo), branch, file data (data.json), dan token GitHub.
   Pakai fine-grained token khusus repo ini, izin Contents: Read and write.
3. Klik Muat data, edit, lalu klik Simpan ke GitHub.
   Situs ikut berubah setelah deploy selesai.

Catatan: data.json sudah berisi profil dan link sosmed terbaru.
Foto di data.json mengarah ke assets/avatar.webp, jadi pastikan file
foto itu ada di folder assets/ (atau unggah lewat admin).

Musik latar: isi kolom "music" di data.json (contoh assets/music.mp3) atau
unggah mp3 lewat admin. Musik mulai saat pengunjung pertama kali menyentuh
halaman (browser memblokir autoplay bersuara), dan ada tombol putar/jeda
di pojok kanan bawah. Kosongkan "music" untuk mematikan fitur ini.

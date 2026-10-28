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

Catatan: link WhatsApp, TikTok, Instagram, Facebook, dan Telegram di data.json
masih placeholder. Ganti lewat admin.

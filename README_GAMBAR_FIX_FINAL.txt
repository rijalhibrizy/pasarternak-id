PERBAIKAN GAMBAR PRODUK PASARTERNAK.ID

Paket ini memakai gambar yang disimpan di folder public/images/products, sehingga tidak bergantung pada internet atau layanan foto eksternal.

CARA PASANG (PENTING):
1. Ekstrak ZIP ini. Di dalamnya langsung terlihat folder src, public, file package.json, dan file lainnya.
2. Salin SEMUA isi hasil ekstrak tersebut ke folder proyek yang berisi package.json milik PasarTernak.id. Jangan menyalin folder ZIP ke dalam folder proyek sebagai subfolder baru.
3. Jika Windows bertanya, pilih Replace/Timpa file yang sama. Pastikan folder public/images/products ikut disalin, karena di sanalah gambar lokal berada.
4. Hentikan server di terminal dengan Ctrl+C, lalu jalankan: npm run dev -- --host 127.0.0.1
5. Buka atau refresh http://127.0.0.1:5173/ (Ctrl+F5 untuk hard refresh).

Pencarian produk dan pengaturan tombol WhatsApp dari paket sebelumnya tetap disertakan.

CATATAN: Gambar lokal pada paket ini adalah ilustrasi SVG, bukan foto hewan asli. Tujuannya agar kartu produk tidak lagi menampilkan ikon gambar rusak.

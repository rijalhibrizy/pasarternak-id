PERBAIKAN GAMBAR PRODUK PASARTERNAK.ID

Yang diperbaiki:
- Foto eksternal tetap dicoba terlebih dahulu.
- Jika foto eksternal gagal dimuat, kartu produk dan halaman detail otomatis memakai file lokal agar tidak menampilkan ikon gambar rusak.
- Galeri gambar pada halaman detail juga memiliki fallback lokal.
- Search bar dan tombol WhatsApp dari ZIP sebelumnya tetap dipertahankan.

Catatan penting:
- Foto utama masih menggunakan layanan foto eksternal. Jika layanan itu berhasil diakses, foto akan tampil.
- File lokal fallback adalah ilustrasi SVG yang sudah ada di proyek, bukan foto hewan asli. Fallback ini hanya mencegah area gambar kosong saat sumber foto eksternal gagal. Untuk memastikan seluruh 80 produk menggunakan foto hewan asli secara lokal, diperlukan kumpulan foto berlisensi/diizinkan untuk digunakan dan disertakan ke proyek.

Cara memasang:
1. Ekstrak ZIP.
2. Salin file/folder hasil ekstrak ke folder proyek PasarTernak.id dan pilih Replace/Timpa jika diminta.
3. Jika terminal Vite sedang berjalan, refresh browser. Jika belum, jalankan: npm run dev -- --host 127.0.0.1
4. Buka http://127.0.0.1:5173/

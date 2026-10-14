PASARTERNAK.ID - UPDATE MARKETPLACE

Perubahan pada versi ini:
1. Tombol + pada bottom navigation sudah dirapikan.
2. Katalog berisi 80 produk: 10 Sapi, 10 Kambing, 10 Ayam, 10 Bebek, 10 Ikan, 10 Daging, 10 Telur, 10 Susu.
3. Setiap kategori hanya menampilkan produk yang sesuai.
4. Setiap kartu produk dapat diklik menuju halaman detail /produk/:id.
5. Halaman detail menampilkan foto, harga, lokasi, rating, stok, terjual, spesifikasi, deskripsi, dan informasi penjual.
6. Dashboard dan halaman lain yang sudah ada tetap dipertahankan.

CARA MENGGUNAKAN:
- Ekstrak file ZIP ini ke folder D:\\, sehingga menjadi D:\\Pasarternak.id.
- Jika Windows meminta konfirmasi replace/merge file, pilih Replace/Replace the files in the destination.
- Buka D:\\Pasarternak.id di VS Code.
- Jika folder node_modules tidak ada, buka Terminal VS Code dan jalankan:
  npm install
- Jalankan preview development:
  npm run dev -- --host 127.0.0.1
- Buka http://127.0.0.1:5173/

Catatan: node_modules sengaja tidak dimasukkan ke ZIP karena ukurannya besar dan bergantung pada sistem operasi. npm install akan membuatnya kembali.

UPDATE 14 OKTOBER 2026
- 240 gambar ilustrasi SVG lokal (3 variasi untuk masing-masing dari 80 produk), ukuran file kecil dan tidak memerlukan koneksi ke layanan gambar eksternal.
- Gambar bersifat ilustrasi vektor kategori, bukan foto dokumentasi penjual/produk nyata.
- Bagian manfaat di beranda menjelaskan penjual terverifikasi, asal produk transparan, dan hubungi penjual.
- Halaman detail menampilkan tiga variasi gambar produk.

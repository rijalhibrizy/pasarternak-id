PEMBARUAN PASARTERNAK.ID

1. Pencarian produk berfungsi di halaman utama, kolom pencarian navigasi, dan halaman Cari Produk.
2. Pencarian mencocokkan nama produk, kategori, lokasi, nama penjual, deskripsi, kondisi, dan spesifikasi. Hasil serta jumlah produk diperbarui berdasarkan kata kunci.
3. Tombol “Hubungi Penjual via WhatsApp” di halaman detail produk membuka WhatsApp dengan pesan produk yang sudah disiapkan.

PENTING TENTANG NOMOR WHATSAPP
Data produk saat ini belum memiliki nomor WhatsApp asli untuk setiap penjual. Karena itu, tombol membuka WhatsApp dengan pesan yang sudah terisi agar pengguna bisa memilih chat tujuan. Jika Anda memiliki satu nomor WhatsApp admin PasarTernak.id, buka src/config/contact.js dan isi WHATSAPP_NUMBER dengan nomor format internasional tanpa tanda +, spasi, atau tanda hubung (contoh format: 6281234567890). Setelah nomor diisi, tombol akan langsung menuju nomor tersebut. Untuk kontak penjual berbeda-beda, tambahkan properti whatsapp atau phone pada data masing-masing produk. Jangan gunakan nomor contoh sebagai nomor nyata.

CARA MEMASANG
- Ekstrak ZIP ke folder proyek Anda dan timpa file yang diminta jika muncul konfirmasi.
- Jalankan PowerShell di folder proyek.
- Jika node_modules belum ada, jalankan: npm install
- Jalankan: npm run dev -- --host 127.0.0.1
- Buka alamat yang ditampilkan Vite, biasanya http://127.0.0.1:5173/

LOPPOMART KEUANGAN VERSI 2.0

Fitur:
- Catatan keuangan harian dan laporan bulanan.
- Daftar barang kosong: nama barang, jumlah, harga satuan, jadwal/sales.
- Subtotal per barang dan total estimasi semua barang yang belum dibeli.
- Tandai barang sudah dibeli; barang selesai tidak dihitung dalam total yang masih harus dibelanjakan.
- Daftar belanja tersimpan otomatis di browser HP melalui localStorage.
- Backup/pulihkan mencakup catatan harian dan daftar belanja.

PENTING:
Penyimpanan lokal hanya ada di browser/perangkat yang digunakan. Belum ada sinkronisasi cloud otomatis. Unduh backup berkala dan jangan hapus data browser sebelum backup.
Website harus di-host di HTTPS agar PWA/service worker offline berfungsi.

CARA UPDATE GITHUB:
Unggah dan timpa file index.html, styles.css, app.js, sw.js, manifest.webmanifest, icon.svg, README.txt dari folder ini ke root repository. Commit changes. Setelah deployment selesai, buka website dan refresh. Jika aplikasi masih menampilkan versi lama, tutup aplikasi lalu buka ulang Chrome; service worker cache versi baru akan mengganti cache lama.

Perhitungan daftar belanja:
Subtotal = jumlah × harga satuan.
Total estimasi = jumlah seluruh subtotal dari barang yang belum ditandai sudah dibeli.

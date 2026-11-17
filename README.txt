LOPPOMART KEUANGAN — PANDUAN

Paket ini berisi aplikasi web sederhana untuk catatan harian, laporan bulanan, dan backup/pulihkan data.

PENTING TENTANG OFFLINE/ONLINE:
- Data transaksi tersimpan di localStorage browser pada HP ini.
- Aplikasi dapat dibuka melalui internet setelah di-host pada alamat HTTPS.
- Service worker menyimpan file aplikasi agar dapat dibuka offline setelah pertama kali dibuka saat online.
- Belum ada sinkronisasi cloud otomatis atau akses lintas perangkat. Simpan backup JSON secara berkala melalui menu Backup.

CARA MENJALANKAN DARI HP ANDROID:
1. Ekstrak ZIP di aplikasi Files / My Files.
2. Untuk uji tampilan, buka index.html dengan Chrome. Beberapa fitur PWA/offline memerlukan hosting HTTPS.
3. Agar dapat dipasang sebagai aplikasi, unggah seluruh isi folder ke hosting statis HTTPS. Dari HP, lakukan lewat Chrome dengan opsi Situs desktop jika diperlukan.
4. Buka URL HTTPS hasil hosting, lalu menu Chrome > Tambahkan ke layar utama atau Instal aplikasi.
5. Buka sekali saat online agar file tersimpan untuk penggunaan offline.

CARA MENGISI:
- Omzet: total penjualan hari itu.
- HPP: modal barang yang terjual hari itu (untuk estimasi laba).
- Belanja stok: pembelian stok yang benar-benar dibayar hari itu.
- Bayar tagihan sales: pembayaran utang stok pembelian sebelumnya.
- Gaji, operasional, pribadi, cicilan: uang kas keluar menurut kategori.

Rumus saldo kas akhir = saldo awal + omzet - belanja stok - pembayaran tagihan sales - gaji - operasional - pribadi - cicilan.
Estimasi laba operasional = omzet - HPP - gaji - operasional. Ini estimasi sederhana, bukan laporan akuntansi resmi. Belum mencakup biaya yang belum dimasukkan.
Catatan tanggal yang sama akan diperbarui jika disimpan lagi.

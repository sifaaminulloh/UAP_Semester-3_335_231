# UAP_Semester-3_335_231

Fast Food Dashboard
Deskripsi

Fast Food Dashboard adalah aplikasi berbasis Java Swing yang dirancang untuk mempermudah pengelolaan transaksi pada restoran cepat saji. Aplikasi ini memungkinkan pelanggan memilih makanan dan minuman, menghitung total harga, serta menyediakan metode pembayaran yang mudah. Selain itu, aplikasi ini juga memiliki fitur login admin untuk menambah stok barang dan melihat riwayat transaksi.
Fitur Utama

    Antarmuka Pengguna Interaktif:
        Pilihan kategori makanan dan minuman.
        Tampilan stok barang yang tersisa.
        Penyesuaian jumlah pesanan menggunakan spinner.

    Fitur Pembayaran:
        Tiga metode pembayaran: Tunai, Transfer Bank, dan QRIS.
        Cetak struk pembayaran untuk pelanggan.

    Login Admin:
        Tambah stok makanan dan minuman.
        Lihat riwayat transaksi yang telah dilakukan.

    Peringatan Stok:
        Sistem memperbarui stok secara otomatis setelah transaksi.

    Riwayat Transaksi:
        Admin dapat melihat seluruh transaksi yang tercatat.

Struktur Kode

    Main Class: FastFoodDashboard
        Berfungsi sebagai titik masuk utama aplikasi.
        Mengelola GUI, logika transaksi, dan antarmuka admin.
    Panel Makanan & Minuman:
        Menampilkan daftar item berdasarkan kategori.
        Setiap item memiliki gambar, harga, stok, dan spinner jumlah pesanan.
    Fungsi Utama:
        initializeStockAndPrices: Inisialisasi data stok dan harga barang.
        updateOrderSummary: Memperbarui ringkasan pesanan pelanggan.
        showPaymentOptions: Menampilkan opsi pembayaran.
        processOrder: Memproses transaksi dan memperbarui stok.
        showAdminMenu: Menampilkan menu admin.

Cara Menggunakan

    Jalankan Program:
        Kompilasi dan jalankan file Java menggunakan perintah:

        javac FastFoodDashboard.java
        java FastFoodDashboard

    Untuk Pelanggan:
        Pilih kategori (Makanan/Minuman).
        Tambahkan jumlah pesanan dengan spinner.
        Klik "Lanjutkan Pembayaran" dan pilih metode pembayaran.
        Terima struk setelah transaksi berhasil.
    Untuk Admin:
        Klik "Login Admin" di sidebar.
        Masukkan username: admin dan password: password.
        Pilih untuk menambah stok atau melihat riwayat transaksi.

Persyaratan Sistem

    Java: JDK 8 atau versi lebih baru.
    Platform: Kompatibel dengan Windows, macOS, dan Linux.
    Library Tambahan: Tidak diperlukan.

Catatan Penting

    Gambar Barang:
        Simpan gambar barang di folder images dengan nama sesuai item (contoh: burger.png).
        Ukuran gambar yang disarankan: 100x100 piksel.
    Stok Awal:
        Default stok untuk semua barang adalah 50.
    Metode Pembayaran:
        Pastikan metode QRIS dan Transfer Bank terhubung ke sistem pembayaran Anda jika digunakan secara nyata.

Pengembangan Selanjutnya

    Fitur Tambahan:
        Tambahkan fitur laporan penjualan harian.
        Penambahan diskon untuk pesanan tertentu.
    Peningkatan Antarmuka:
        Desain responsif dengan tampilan modern.
    Validasi Tambahan:
        Cegah pelanggan memilih item dengan stok habis.
    Keamanan Login Admin:
        Implementasi enkripsi untuk password.

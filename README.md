NAMA : AURELIO DECA SETYAWAN
NIM : 24090122
EMAIL : deka19@gmail.com
LINK GITHUB REPOSITORY :
LINK GITHUB PAGES : 
DESKRIPSI :
    LOGIN, Halaman Login berfungsi untuk memvalidasi email dan password pengguna sebelum masuk ke sistem. Jika kedua input terisi, pengguna diarahkan ke halaman Dashboard. Jika ada yang kosong, sistem menampilkan pesan error.
    Fungsi initLoginPage(): 
     - Mengambil form login
     - Cek apakah email & password kosong
     - Jika terisi → tampilkan alert “Login berhasil!” dan pindah ke dashboard
    Fokusnya hanya validasi sederhana dan redirect.

    DASHBOARD, Halaman Dashboard berfungsi untuk menampilkan ringkasan data sistem, yaitu total produk, total penjualan, dan total pendapatan. Data ditampilkan dalam bentuk card dan diambil dari script JavaScript. Dashboard juga menyediakan tombol untuk menuju halaman daftar produk.
    Fungsi initDashboardPage():
     - Mengambil elemen yang menampilkan total produk, penjualan, dan pendapatan
     - Mengisi angkanya menggunakan objek summary
    Tujuannya menampilkan statistik ringkas.

    PRODUCT, Halaman Products berfungsi untuk menampilkan daftar produk dalam bentuk tabel. Data produk diambil dari array JavaScript, lalu ditampilkan secara dinamis. Pada setiap baris terdapat tombol Edit dan Delete; Edit menampilkan alert nama produk, sedangkan Delete menghapus baris produk dari tabel setelah konfirmasi.
    Fungsi initProductsPage():
     - Mengisi tabel produk secara dinamis
     - Menampilkan nomor, nama produk, harga, dan stok
     - Pada setiap baris ada tombol Edit dan Delete
     - Edit → tampilkan alert
     - Delete → hapus baris setelah konfirmasi
    Ini inti dari halaman product untuk menampilkan daftar barang.
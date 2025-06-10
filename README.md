# Kostify
**Kostify** adalah aplikasi desktop berbasis Java yang dikembangkan menggunakan NetBeans IDE untuk membantu pemilik kost dalam mengelola kamar, penghuni, dan transaksi pembayaran secara efisien.

Dibuat Oleh Kelompok 4: PTI 2024 A
##  Anggota Kelompok
####  Abidah Ardelia F. N. C. [24050974030]
####  Ria Agustina [24050974019]
---

## Tujuan Aplikasi
Aplikasi **Kostify** dibuat untuk membantu pemilik kost dalam mengelola data kamar, penghuni, dan pembayaran secara digital. Aplikasi ini mempermudah proses pencatatan dan pelaporan informasi seputar penghuni kost secara efisien, cepat, dan akurat.


## Teknologi yang Digunakan
- Java (NetBeans IDE)
- MySQL Database
- JDBC (mysql-connector-j-9.3.0.jar)


## Fungsi dan Fitur Aplikasi 

| Fitur/Fungsi           | Deskripsi                                                                 |
|------------------------|--------------------------------------------------------------------------|
|    Login               | Form login dengan username dan password admin                            |
|    Dashboard/Home      | Halaman utama aplikasi setelah login yang akan menampilkan 5 fitur utama (Kamar, Penghuni, Keuangan, Pengaturan dan Akun |
|    Manajemen Kamar     | Melihat daftar kamar, status, harga, dan informasi penyewa               |
|    Data Penghuni       | Menampilkan dan mengelola informasi penghuni kost                        |
|    Riwayat Pembayaran  | Melihat detail pembayaran berdasarkan nama penyewa dan nomor kamar       |
|    Data Pemilik Kost   | Informasi lengkap tentang pemilik kost dan properti                   |
|   Pengaturan Aplikasi  | Edit akun dan konfigurasi tambahan                                       |
|    Koneksi Database    | Menghubungkan aplikasi dengan database `kostify` melalui JDBC            |

---

##  Struktur Akses 
- `Login.java` – Form login awal
- `Home.java` – Halaman dashboard utama
- `Kamar.java` – Modul untuk mengelola kamar
- `Penghuni.java` – Modul untuk data penghuni
- `DetailPembayaran.java` – Modul untuk data transaksi pembayaran
- `PemilikKost.java` – Modul pemilik kost
- `MainKoneksi.java` – File untuk menghubungkan ke database
- `kostify.sql` – Struktur dan data awal database MySQL

---


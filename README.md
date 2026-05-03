# Pengembangan Aplikasi CampEats Berbasis Android dengan Peningkatan UI/UX dan Fitur Manajemen Pesanan

### - Nama: Muhamad Nikmal Wahid
### - Kelas: I241C
### - Nim: 312410372
### - Mata Kuliah: Pemrograman Mobile 2
### - Dosen Pengampu: Donny Maulana, S.Kom., M.M.S.I.,

### LInk Clickup:  https://sharing.clickup.com/90181799294/l/h/4-90187327418-1/979bc9884f335c5

# 1. Pendahuluan 

## 1.1 Latar Belakang

Pada semester sebelumnya telah dikembangkan aplikasi CampEats versi awal dengan fitur dasar pemesanan makanan. Namun, berdasarkan evaluasi sistem, masih diperlukan peningkatan pada aspek antarmuka pengguna, pengalaman pengguna, serta penambahan fitur manajemen pesanan dan dashboard admin. Oleh karena itu, pada pengembangan lanjutan ini dilakukan redesign UI/UX dan penambahan fitur baru.

## 1.2 Rumusan Masalah 

Permasalahan yang diangkat dalam pengembangan aplikasi ini antara lain:
1. Bagaimana merancang aplikasi pemesanan makanan berbasis Android yang mudah digunakan?
2. Bagaimana menerapkan sistem poin sebagai bentuk reward pengguna?

# 1.3 Tujuan Penelitian 
Tujuan dari pengembangan aplikasi CampEats adalah:
- Merancang dan membangun aplikasi pemesanan makanan berbasis Android.
- Meningkatkan pengalaman pengguna melalui antarmuka yang sederhana dan modern.

# 1.4 Manfaat Penelitian 
- Bagi Mahasiswa: Mempermudah proses pemesanan makanan di lingkungan kampus.
- Bagi Pengembang: Sebagai media pembelajaran penerapan Android Development dengan Java.
- Bagi Akademik: Sebagai Studi Kasus Implementasi aplikasi mobile untuk lingkungan kampus.

# 2. Landasan Teori 
## 2.1 Aplikasi Mobile 

Aplikasi mobile merupakan perangkat lunak yang dirancang untuk berjalan pada perangkat bergerak seperti smartphone. Android adalah sistem operasi berbasis Linux yang banyak digunakan karena bersifat open-source dan memiliki ekosistem pengembangan yang luas.

## 2.2 Android SDK dan Java 

Android SDK menyediakan berbagai library dan tools untuk membangun aplikasi Android. Bahasa pemrograman Java digunakan karena stabil, terstruktur, dan didukung penuh oleh Android Studio.

## 2.3 Material Design 

Android SDK menyediakan berbagai library dan tools untuk membangun aplikasi Android. Bahasa pemrograman Java digunakan karena stabil, terstruktur, dan didukung penuh oleh Android Studio.

# 3. Analisis dan Perancangan Sistem 
## 3.1 Analisis Kebutuhan Fungsional 
Aplikasi CampEats memiliki kebutuhan fungsional sebagai berikut:
- Autentikasi pengguna (login dan registrasi)
- Menampilkan daftar menu makanan
- Pencarian menu makanan
- Manajemen keranjang pesanan
- Proses checkout dan perhitungan total harga
- Riwayat transaksi pemesanan
- Sistem poin/reward
- Manajemen profil pengguna dan logout
  
## 3.2 Alur Sistem 

1. Pengguna melakukan login atau registrasi akun.
2. Pengguna mengakses halaman beranda dan melihat daftar menu.
3. Pengguna memilih menu dan menambahkannya ke keranjang.
4. Pengguna melakukan checkout dan memilih metode pembayaran.
5. Sistem menyimpan transaksi dan menambahkan poin reward.

## 3.3 Perancangan Antarmuka 
Antarmuka dirancang menggunakan XML dengan pendekatan:
- Tampilan sederhana dan modern
- Navigasi menggunakan Bottom Navigation
- Konsistensi warna dan komponen Material Design

## 3.4 Evaluasi Sistem Sebelumnya 
Berdasarkan implementasi versi sebelumnya, ditemukan beberapa kekurangan:
- Tampilan antarmuka masih sederhana
- Belum tersedia tracking status pesanan
- Belum tersedia sistem pembayaran yang lebih terstruktur
- Dashboard admin masih terbatas
- Fitur CRUD menu belum optimal

# 4. Implementasi Sistem 
## 4.1 Teknologi Yang Digunakan 

- Bahasa Pemrograman: Java
- Platform: Android
- UI Design: XML + Material Design
- IDE: Android Studio

## 4.2 Implementasi Fitur Utama 

- RecyclerView digunakan untuk menampilkan daftar menu makanan.
- SharedPreferences digunakan untuk menyimpan data sesi pengguna.
- Bottom Navigation digunakan untuk mempermudah navigasi antar halaman.

## 4.3 Cuplikan Tampilan Aplikasi 

## Cuplikan Tampilan Aplikasi User (Design Figma) 

| Halaman | Preview | Halaman | Preview |
|--------|---------|--------|---------|
| Splash Screen | <img src="UIDesign/Splash.png" width="220"/> | Pilih Bahasa | <img src="UIDesign/Bahasa.png" width="220"/> |
| Welcome | <img src="UIDesign/Welcome.png" width="220"/> | Login | <img src="UIDesign/SIgnIn.png" width="220"/> |
| Register | <img src="UIDesign/CreateAccount.png" width="220"/> | Home | <img src="UIDesign/Home(Update).png" width="220"/> |
| Search | <img src="UIDesign/SearchUI(Update).png" width="220"/> | Cart | <img src="UIDesign/Cart(Update).png" width="220"/> |
| Profile | <img src="UIDesign/Profile(Update).png" width="220"/> | Detail Produk | <img src="UIDesign/Detail(Update).png" width="220"/> |
| Keranjang Update | <img src="UIDesign/Cart2(Update).png" width="220"/> | Tracking Order | <img src="UIDesign/OrderTracking(Update).png" width="220"/> |
| Final Order | <img src="UIDesign/FinalizeOrder(Update).png" width="220"/> | Success Order | <img src="UIDesign/Success(Update).png" width="220"/> |/> |

## Cuplikan Tampilan Aplikasi Admin (Design Figma) 

| Halaman | Preview | Halaman | Preview |
|--------|---------|--------|---------|
| Dashboard Admin 1 | <img src="AdminUI/DashboardAdmin.png" width="220"/> | Dashboard Admin 2 | <img src="AdminUI/DashboardAdmin2.png" width="220"/> |
| Dashboard Admin 3 | <img src="AdminUI/DashboardAdmin3.png" width="220"/> | Dashboard Admin 4 | <img src="AdminUI/DashboardAdmin4.png" width="220"/> |
| Dashboard Admin 5 | <img src="AdminUI/DashboardAdmin5.png" width="220"/> |  |  |

## 4.4 Pengembangan Fitur Lanjutan
Pada semester ini dilakukan beberapa pengembangan utama, yaitu:

1. Redesign tampilan aplikasi dengan konsep modern minimalis.
2. Penambahan halaman tracking pesanan.
3. Penambahan metode pembayaran digital.
4. Pengembangan dashboard admin.
5. Penambahan fitur CRUD menu makanan.
6. Optimalisasi navigasi pengguna.
7. Penyempurnaan alur checkout.

# 5. Pengujian dan Evaluasi 
Pengujian dilakukan secara fungsional dengan memastikan setiap fitur berjalan sesuai dengan kebutuhan sistem. Berdasarkan hasil pengujian:
- Aplikasi dapat berjalan dengan baik tanpa error utama.
- Seluruh fitur utama dapat digunakan sesuai rancangan.
- Penyimpanan data lokal berjalan dengan stabil.

# 6. Kesimpulan 
Hasil pengembangan lanjutan menunjukkan bahwa aplikasi CampEats mengalami peningkatan signifikan dari sisi tampilan, fitur, dan pengalaman pengguna dibanding versi sebelumnya.












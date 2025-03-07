# Dokumentasi Proyek Flutter - Shrine App

## 1. Pendahuluan
Proyek ini merupakan implementasi aplikasi berbasis Flutter yang menampilkan UI e-commerce sederhana dengan beberapa fitur seperti login, navigasi kategori, tampilan produk, dan animasi backdrop.

## 2. Struktur Proyek

Berikut adalah struktur utama dari proyek:

- **main.dart** - Titik masuk utama aplikasi.
- **app.dart** - Konfigurasi dan pengaturan rute aplikasi.
- **login.dart** - Halaman login dengan UI responsif.
- **home.dart** - Halaman utama yang menampilkan daftar produk berdasarkan kategori.
- **backdrop.dart** - Widget backdrop untuk menampilkan menu navigasi dan produk.
- **category_menu_page.dart** - Halaman untuk memilih kategori produk.
- **colors.dart** - Definisi warna yang digunakan dalam aplikasi.
- **product.dart** - Model data untuk produk.
- **products_repository.dart** - Repositori berisi daftar produk.
- **asymmetric_view.dart** - Tata letak tampilan produk yang tidak simetris.
- **product_card.dart** - Widget kartu produk yang menampilkan informasi produk.
- **product_columns.dart** - Tata letak untuk menampilkan daftar produk dalam bentuk kolom.
- **cut_corners_border.dart** - Kustomisasi border input field dengan efek potongan sudut.

## 3. Penjelasan File Utama

### 3.1 main.dart
File ini berisi fungsi utama `main()` yang menjalankan aplikasi dengan memanggil `ShrineApp()`.

### 3.2 app.dart
- Mengatur tema aplikasi dengan `ThemeData`.
- Menentukan rute utama dan halaman login.
- Menggunakan `Backdrop` sebagai layout utama.

### 3.3 login.dart
- Menyediakan UI login dengan `TextField` untuk username dan password.
- Menggunakan tombol `CANCEL` untuk menghapus input dan `NEXT` untuk navigasi berikutnya.

### 3.4 home.dart
- Menggunakan `AsymmetricView` untuk menampilkan daftar produk berdasarkan kategori yang dipilih.

### 3.5 backdrop.dart
- Mengatur tampilan menu backdrop dengan animasi transisi antara menu kategori dan daftar produk.
- Mengontrol visibilitas tampilan depan (produk) dan belakang (menu kategori).

### 3.6 category_menu_page.dart
- Menampilkan daftar kategori yang tersedia.
- Memungkinkan pengguna untuk memilih kategori dan memperbarui tampilan produk berdasarkan kategori yang dipilih.

### 3.7 colors.dart
- Mendefinisikan skema warna aplikasi.

### 3.8 product.dart
- Model produk yang berisi informasi seperti ID, nama, harga, kategori, dan status unggulan.

### 3.9 products_repository.dart
- Berisi daftar produk yang dikategorikan.
- Metode `loadProducts(Category category)` digunakan untuk memfilter produk berdasarkan kategori tertentu.

### 3.10 asymmetric_view.dart
- Menggunakan tata letak asimetris untuk menampilkan produk.
- Produk ditampilkan dalam kolom dengan kombinasi kartu produk tunggal dan ganda.

### 3.11 product_card.dart
- Widget untuk menampilkan informasi produk seperti gambar, nama, dan harga.

### 3.12 product_columns.dart
- Menata tampilan produk dalam bentuk kolom.
- Menggunakan kombinasi `OneProductCardColumn` dan `TwoProductCardColumn` untuk tampilan asimetris.

### 3.13 cut_corners_border.dart
- Kustomisasi `OutlineInputBorder` dengan sudut yang terpotong untuk elemen input seperti `TextField`.

## 4. Cara Menjalankan Aplikasi

### 4.1 Prasyarat
- Flutter SDK terinstal.
- Emulator atau perangkat fisik terhubung.

### 4.2 Langkah-Langkah
1. Buka terminal dan arahkan ke direktori proyek.
2. Jalankan perintah berikut:
   ```sh
   flutter pub get
   flutter run
   ```

Aplikasi akan berjalan pada perangkat yang dikonfigurasi.

## 5. Kesimpulan
Aplikasi ini menggunakan Flutter untuk membangun UI yang menarik dan responsif dengan fitur seperti login, navigasi kategori, dan tampilan produk yang unik. Dengan pendekatan modular, aplikasi ini mudah diperluas dan dikembangkan lebih lanjut.

## 6. Dokumentasi
![image](https://github.com/user-attachments/assets/a53e613d-7dc1-4c01-8f02-421e1ef19dc9)
![image](https://github.com/user-attachments/assets/684ad119-af8a-4eff-9bae-7c4e66ff0694)
![image](https://github.com/user-attachments/assets/2fb02d8d-6c00-4836-9ab5-3370786ad3ce)





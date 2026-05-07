# Lab7Web.

## Nama               : Nadhia Shafira_ 312410498

## Kelas              : I241E

## Matkul             : Pemograman Web

## Dosen Pengampu     : Agung Nugroho, S.Kom., M.Kom. 

___


# 📚 Laporan Praktikum Pemrograman Web 2 DARI PRAKTIKUM 1 SAMPAI 4

## 🛠️ Praktikum 1: Persiapan & Instalasi Framework CodeIgniter 4

Pada tahap awal ini, saya melakukan instalasi dan konfigurasi dasar untuk memastikan lingkungan kerja siap digunakan. 🏠✨

**Penjelasan Lengkap:**

* **Instalasi:** Mengunduh dan memasang framework CodeIgniter 4 sehingga muncul halaman "Welcome" sebagai tanda sistem berjalan. 📥
  
* **Konfigurasi Environment:** Mengubah pengaturan pada file `.env` dari mode `production` menjadi `development` agar mempermudah proses debugging. ⚙️
  
* **Routing Dasar:** Belajar mengatur alamat URL (routing) untuk mengarahkan user ke halaman tertentu, seperti halaman 'About'. 🗺️
  
* **View & Layouting:** Membuat tampilan sederhana menggunakan file View dan mulai menerapkan basic layouting agar tampilan konsisten. 🎨

**Dokumentasi Langkah-langkah:**

1. **Konfigurasi Welcome Page:** Berhasil menjalankan server dan memunculkan halaman utama CI4. 🌟
   ![01_Instalasi_Sukses_Welcome](https://github.com/NadhiaShafira/Lab7Web./blob/a40cbfe1c01c464100a05965c0a19a00622c2979/ssweb1/01_Instalasi_Sukses_Welcome_.png)

2. **Setup Environment:** Mengaktifkan mode development pada file konfigurasi `.env`. 🛠️
   ![02_Konfigurasi_Environment_Development](https://github.com/NadhiaShafira/Lab7Web./blob/047801405e2c9d5774f046013968014f4752469a/ssweb1/02_Konfigurasi_Environment_Development.png)

3. **Uji Coba Routing:** Berhasil membuat route baru untuk halaman About. 📍
   ![03_Routing_About_Berhasil](https://github.com/NadhiaShafira/Lab7Web./blob/a7bdcc74bcca7527cef75a94df76637ce5d27759/ssweb1/03_Routing_About_Berhasil.png)

4. **Tampilan View:** Membuat konten halaman About melalui file View. 🖼️
   ![04_Tampilan_View_About](https://github.com/NadhiaShafira/Lab7Web./blob/8b8c70724563fbd5deb4df1deafd95a1b6e345f6/ssweb1/04_Tampilan_View_About.png)

5. **Hasil Layouting:** Menerapkan struktur layouting dasar pada halaman About. 🏛️
   ![05_Hasil_Layouting_Halaman_About](https://github.com/NadhiaShafira/Lab7Web./blob/f4770c26cb6203cffbadab7045fadcdbdf6365a8/ssweb1/05_Hasil_Layouting_Halaman_About.png)

6. **Final Styling:** Hasil akhir tampilan dengan kustomisasi style agar lebih rapi. 💎
   ![06_Final_Result_Lab11_Custom_Style](https://github.com/NadhiaShafira/Lab7Web./blob/fafc0def69100047e114a6b7d619d4c999bd2ccb/ssweb1/06_Final_Result_Lab11_Custom_Style.png)

---

## 📝 Praktikum 2: Framework Dasar (CRUD Artikel)

Pada praktikum ini, saya mulai masuk ke bagian inti yaitu membangun fitur CRUD (Create, Read, Update, Delete) untuk manajemen data artikel secara dinamis. 🌊✨

**Penjelasan Lengkap:**

* **Koneksi Database:** Melakukan konfigurasi pada file `.env` agar aplikasi CodeIgniter 4 terhubung dengan database MySQL. 🔗⚙️
  
* **Pembuatan Tabel:** Membuat struktur tabel `artikel` di phpMyAdmin untuk menyimpan data seperti judul, isi, dan status artikel. 🗃️
  
* **Query Data:** Belajar melakukan manipulasi data (Insert) langsung melalui database untuk pengujian awal. 📥
  
* **Logika Admin:** Membangun halaman admin khusus untuk mengelola artikel, lengkap dengan form tambah dan edit yang fungsional. 🧩✨

**Dokumentasi Langkah-langkah:**

1. **Konfigurasi Database:** Mengatur nama database, username, dan password pada file `.env`. 🛠️
   ![01_Konfigurasi_Database_env](https://github.com/NadhiaShafira/Lab7Web./blob/42454ba8048f7d867e14addb2bcda37055706bff/ssweb2/01_Konfigurasi_Database_env.png)

2. **Struktur Tabel Artikel:** Penampakan tabel `artikel` yang sudah dibuat di phpMyAdmin. 📋
   ![02_Struktur_Tabel_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/40542ff11153092bd8f0e156231c96a195b17559/ssweb2/02_Struktur_Tabel_Artikel.png)

3. **Tampilan Awal:** Kondisi halaman daftar artikel yang masih kosong sebelum diisi data. 📄
   ![03_Tampilan_Awal_Kosong](https://github.com/NadhiaShafira/Lab7Web./blob/ccecae8e4760068f8578075ca2ef0d6df89b296d/ssweb2/03_Tampilan_Awal_Kosong.png)

4. **Insert Data:** Melakukan pengisian data awal menggunakan query SQL. 💾
   ![04_Query_Insert_Data](https://github.com/NadhiaShafira/Lab7Web./blob/67f66acdeb52cb034da0a546734810bf42f1ce25/ssweb2/04_Query_Insert_Data.png)

5. **Daftar Artikel:** Halaman depan yang menampilkan daftar artikel hasil dari database. 📰
   ![05_Tampilan_Daftar_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/8b8f3fce70b528747e5131c2b03d1c1eb9884a3e/ssweb2/05_Tampilan_Daftar_Artikel.png)

6. **Admin Index:** Halaman manajemen artikel khusus untuk admin. 👮‍♀️
   ![06_Tampilan_Admin_Index](https://github.com/NadhiaShafira/Lab7Web./blob/6ed42113a5362e1aac0454d96c7ba8a5a4812e5b/ssweb2/06_Tampilan_Admin_Index.png)

7. **Form Tambah:** Formulir untuk memasukkan artikel baru ke sistem. ➕
   ![07_Form_Tambah_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/362bdeafcebb8937d20f3c224eb7bbed8663932d/ssweb2/07_Form_Tambah_Artikel.png)

8. **Hasil Tambah:** Bukti artikel baru berhasil tersimpan dan muncul di daftar. ✅
   ![08_Hasil_Tambah_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/b146151e748475ec1d0d775b72e74a5e8abb530e/ssweb2/08_Hasil_Tambah_Artikel.png)

9. **Form Ubah:** Formulir untuk mengedit artikel yang sudah ada. ✏️
   ![09_Form_Ubah_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/c8451446a545285e57d2465f3e54508baf74a4fa/ssweb2/09_Form_Ubah_Artikel.png)

10. **Hasil Ubah:** Tampilan artikel setelah berhasil diperbarui. 🌟
    ![10_Hasil_Ubah_Artikel](https://github.com/NadhiaShafira/Lab7Web./blob/05e7e6851c7c3c9f5a101f6f9e32784ccd5757df/ssweb2/10_Hasil_Ubah_Artikel.png)

    ---

 ## 🎨 Praktikum 3: Layouting & View Cell
 
Pada praktikum ini, saya belajar teknik "Layouting" untuk membuat kerangka website yang konsisten dan menggunakan "View Cell" agar komponen web bisa digunakan berulang kali secara efisien. 🧱✨

**Penjelasan Lengkap:**

* **Layout Utama:** Membuat file induk (template) yang berisi bagian Header, Navigasi, dan Footer yang sama untuk semua halaman. Jadi, saya tidak perlu menulis kode yang sama berulang-ulang di setiap file. 🏛️
  
* **Modularisasi:** Menggunakan fungsi `renderSection` untuk menentukan bagian mana dari layout yang isinya akan berubah-ubah (dinamis) sesuai halaman yang dibuka. 🧩
  
* **View Cell (Widget):** Membuat komponen kecil yang berdiri sendiri untuk menampilkan daftar "Artikel Terkini". Komponen ini sangat praktis karena bisa dipanggil di halaman mana pun hanya dengan satu baris kode. 📱🔗

**Dokumentasi Langkah-langkah:**

1. **Implementasi View Layout:** Hasil penerapan template utama pada halaman website sehingga tampilannya lebih rapi dan terstruktur. 🖼️
   ![1_Implementasi_View_Layout](https://github.com/NadhiaShafira/Lab7Web./blob/2d035a6bcdfa526a024cd8908e6a75a0fb0d3cd5/ssweb3/1_Implementasi_View_Layout.png)

2. **Implementasi View Cell Artikel Terkini:** Penampakan widget "Artikel Terkini" di bagian sidebar yang datanya diambil secara otomatis dari sistem. 🔗✨
   ![2_Implementasi_View_Cell_Artikel_Terkini](https://github.com/NadhiaShafira/Lab7Web./blob/2c65255e69b274c0825584e8788f6f7fa74860c8/ssweb3/2_Implementasi%20View%20Cell%20Artikel%20Terkini.png)

---

## 🔐 Praktikum 4: Framework Lanjutan (Sistem Login & Auth Filter)

Pada praktikum terakhir ini, saya membangun sistem keamanan autentikasi untuk membatasi hak akses halaman admin agar tidak bisa diakses oleh sembarang orang. 👮‍♀️🛡️

**Penjelasan Lengkap:**

* **Manajemen User:** Membuat tabel `user` di database untuk menyimpan data kredensial admin seperti username, email, dan password. 👤
  
* **Autentikasi Session:** Membangun logika login yang memeriksa kecocokan data input dengan database. Jika cocok, sistem akan menyimpan data login dalam "Session". 🔍
  
* **Auth Filter (Satpam Otomatis):** Mengimplementasikan fitur Filter dari CodeIgniter 4 yang bertugas sebagai pencegat. Jika user yang belum login mencoba mengakses halaman admin, sistem akan otomatis menolak dan mengarahkan kembali ke halaman login. 🚫
  
* **UI Refinement:** Mempercantik tampilan formulir login menggunakan **Bootstrap** agar terlihat lebih modern, bersih, dan profesional. 💎🎨

**Dokumentasi Langkah-langkah:**

1. **Struktur Tabel User:** Membuat tabel `user` lengkap dengan kolom username dan password. 📋
   ![01_Struktur_Tabel_User](01_Struktur_Tabel_User.png)

2. **Data User Testing:** Memasukkan data admin contoh ke dalam database untuk keperluan uji coba login. 🔑
   ![02_Data_User_Testing](02_Data_User_Testing.png)

3. **Tampilan Login Baru:** Hasil desain halaman login yang sudah dipercantik dan terlihat lebih estetik. 🎨
   ![03_Tampilan_Login_Baru](03_Tampilan_Login_Baru.png)

4. **Login Berhasil Admin:** Tampilan dashboard admin yang berhasil terbuka setelah memasukkan akun yang benar. ✅
   ![04_Login_Berhasil_Admin](04_Login_Berhasil_Admin.png)

5. **Uji Coba Filter Auth:** Dokumentasi saat sistem berhasil memblokir akses ilegal dan memberikan peringatan keamanan. 🔒
   ![05_Uji_Coba_Filter_Auth](05_Uji_Coba_Filter_Auth.png)

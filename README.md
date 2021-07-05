# Nama :Dollar Rahmat Hasibuan 
# NIM :311910026
# Kelas : TI.19.B2

# Praktikum 13
# 1.Buat Table user
![gambar](https://user-images.githubusercontent.com/81583408/123116337-06774100-d46b-11eb-8242-38b1b141db8f.png)
# 2. membuat Model untuk memproses data Login. Buat file baru pada direktori app/Models dengan nama UserModel.php
![image](https://user-images.githubusercontent.com/81579730/123547852-9b8c7980-d78c-11eb-8b8d-52520d96b3fa.png)
# 3. Membuat Controller User Buat Controller baru dengan nama User.php pada direktori app/Controllers.Kemudian tambahkan method index() untuk menampilkan daftar user, dan method login() untuk proses login.
![image](https://user-images.githubusercontent.com/81579730/123547896-cc6cae80-d78c-11eb-9583-34a8854bc9be.png)
![image](https://user-images.githubusercontent.com/81579730/123547909-d8587080-d78c-11eb-8d07-cab1e01a61fc.png)
# 4. Membuat View Login Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file baru dengan nama login.php.
![image](https://user-images.githubusercontent.com/81579730/123547957-0d64c300-d78d-11eb-8168-1eefb80ba137.png)
![image](https://user-images.githubusercontent.com/81579730/123547976-1e153900-d78d-11eb-9f20-338c064f4723.png)
# 5. Membuat Database Seeder Database seeder digunakan untuk membuat data dummy. Untuk keperluan ujicoba modul login, kita perlu memasukkan data user dan password kedaalam database. Untuk itu buat database seeder untuk tabel user. Buka CLI, kemudian tulis perintah berikut:
![image](https://user-images.githubusercontent.com/81579730/123548054-6fbdc380-d78d-11eb-925d-f731d5431962.png)
# Selanjutnya, buka file UserSeeder.php yang berada di lokasi direktori /app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut:
![image](https://user-images.githubusercontent.com/81579730/123548089-8ebc5580-d78d-11eb-8ca7-522cdd957cce.png)
![image](https://user-images.githubusercontent.com/81579730/123548110-a562ac80-d78d-11eb-83fb-12628ee83628.png)
# 6. Menambahkan Auth Filter Selanjutnya membuat filer untuk halaman admin. Buat file baru dengan nama Auth.php pada direktori app/Filters.
![image](https://user-images.githubusercontent.com/81579730/123548141-cb884c80-d78d-11eb-9aa6-45c23fc6400a.png)
# Selanjutnya buka file app/Config/Filters.php tambahkan kode berikut:
![image](https://user-images.githubusercontent.com/81579730/123548186-f1adec80-d78d-11eb-96df-d4ea2e5b330e.png)
![image](https://user-images.githubusercontent.com/81579730/123548225-173af600-d78e-11eb-9c7b-baf1fab85486.png)
# Percobaan Akses Menu Admin
![image](https://user-images.githubusercontent.com/81579730/123548248-3043a700-d78e-11eb-9700-a35185ebd90b.png)
![image](https://user-images.githubusercontent.com/81579730/123548258-3c2f6900-d78e-11eb-99bd-5d544e840b8b.png)
# 7. Fungsi Logout Tambahkan method logout pada Controller User seperti berikut:
![image](https://user-images.githubusercontent.com/81579730/123548314-7bf65080-d78e-11eb-932d-551cce94691a.png)
![image](https://user-images.githubusercontent.com/81579730/123548318-8284c800-d78e-11eb-861e-4d4af8eeaa96.png)
![image](https://user-images.githubusercontent.com/81579730/123548332-903a4d80-d78e-11eb-8d97-d998da2aebc3.png)

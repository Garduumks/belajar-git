# Instalasi Git Bash
## 1.download Git pada browser ketik 'git-scm'
![[Cuplikan layar 2024-07-31 201036.png]]
## 2.Lalu klik Git Hub yang telah di instal

## 3.Lalu akan muncul tampilan seperti gambar

![[Cuplikan layar 2024-07-31 201446.png]]


## 4.Maka klik 'next' terus hingga mendapatkan tampilan seperti gambar
![](assets/p.png)

# Login Akun Github
1. Buka aplikasi github di browser 
2. Lalu lakukan sign up pada github
![[Cuplikan layar 2024-07-31 203124.png]]

3. Jika sudah memiliki akun langsung masukkan password dan username yang ada
![[Cuplikan layar 2024-07-31 203852.png]]

4. Jika tidak memiliki akun klik tambahkan akun
![[Cuplikan layar 2024-07-31 204333.png]]

5. Setelah buat akun maka akan tampil seperti gambar
![[Cuplikan layar 2024-07-31 204814.png]]

## Langkah-langkah

1. *Buat Repositori GitHub Baru*:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
   ![[Pasted image 20240725004628.png]]
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".
   ![[Cuplikan layar 2024-07-31 205038 1.png]]

2. *Konfigurasi Git Lokal*:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:
    ```CS
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
     ```

    *Note:* untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
         git config --list
 *contohnya:* 
![[Cuplikan layar 2024-08-01 073647.png]]
![[Cuplikan layar 2024-08-01 073656.png]]

3. *Inisialisasi Git Lokal*:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
     ```cs
     git init
```
 *contohnya:*
![[Cuplikan layar 2024-07-31 130732.png]]

4. *Hubungkan ke Repositori GitHub*:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
```cs
     git remote add origin https://github.com/username/nama-repository.git
   ```
   Ganti username dan nama-repository dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.kalo dah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
*contohnya:*
![[Cuplikan layar 2024-07-31 132012.png]]
   
5. *Tambahkan file ke repositori*: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
   ```cs
     git add .
     ```
*contohnya:*
![[Cuplikan layar 2024-07-31 132150.png]]

6. *Buat Commit:*
   - Jalankan perintah berikut untuk membuat commit dengan pesan yang jelas:
   - Perintah git commit -m *"Pesan commit"* digunakan untuk menyimpan perubahan yang telah dilakukan pada repositori Git dengan menambahkan pesan
```cs
     git commit -m "Pesan commit"
     ```
*contohnya:*

   Unggah ke GitHub   (git push origin master):
   Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:

7. *Unggah ke GitHub*:
   - Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:
    
```cs
     git push -u origin master
```

     *contohnya:*
     ![[git push origin.jpg]]
     maka akan tetampil bgini,berarti anda disuruh untuk login akun github mu yang sudh kamu buat 
     ![[login.jpg]]
   Perintah ini akan mengunggah kode Anda ke repositori GitHub. Setelah ini, setiap kali Anda membuat perubahan pada kode, Anda dapat mengulangi langkah 4, 5,6 dan 7 untuk mengunggah perubahan tersebut ke GitHub.

**Itulah langkah-langkah dasar untuk mengirim kode dari Git ke GitHub menggunakan aplikasi Obsidian. Jika Anda membutuhkan bantuan lebih lanjut, jangan ragu untuk bertanya.**
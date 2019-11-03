“ CARA PENGGUNAAN GIT DAN LANGKAH MEMBUAT FILE README.md”

A.	Instalisasi git
  1.	Download git di website resminya (https://git-scm.com/)

![image](https://user-images.githubusercontent.com/56258731/67145839-25452d80-f2af-11e9-80ce-6806053e3f0c.png)

 2.	Unduh sesuai processor pc anda. Untuk 64bit unduh  yang 64bit, begitu juga untuk yang 32bit.

![image](https://user-images.githubusercontent.com/56258731/67146327-35134080-f2b4-11e9-8ce1-de86cc060acb.png)

  3.	Instal git dengan mengikuti cara yang tertera.
  4.	Congrats, git berhasil terinstal.

B.	Penggunaan git
  1.	Untuk mencobanya, silahkan buka git bash anda yang sudah diinstal tadi, kemudian ketik perintah git --version.
  2.	Sebelum menggunakan git perlu melakukan konfigurasi

    •	Config global repository
     $ global config --global user.name  “nama.anda”
     $ global config --global user.email “email.anda”

![image](https://user-images.githubusercontent.com/56258731/67146495-bfa86f80-f2b5-11e9-9c8c-dd351b426f70.png)

  3.	Buat repository local dengan nama latihan1
  
    •	Directory  project praktikum
      $ mkdir latihan1
      $ cd latihan1
    •	Jalankan perintah git init, untuk membuat repository local
      $ git init

![image](https://user-images.githubusercontent.com/56258731/67146575-b9ff5980-f2b6-11e9-928c-a3906026f13a.png)

  4.	Tambahkan file baru pada repository
  
    •	Buat satu file bernama README.md
      $ echo “#latihan1” >>README.md
    •	Tambahkan file yang sudah dibuat tersebut dengan perintah
      $ git add README.md
      
![image](https://user-images.githubusercontent.com/56258731/67146792-be2c7680-f2b8-11e9-8238-6043b9297a1a.png)

  5.	File README.md berhasil dibuat dan ditambahkan.
  
  6.	Menyimpan perubahan ke database (meng-commit)
  
    •	Untuk menyimpannya gunakan perintah
      $ git commit –m “ulasan commit”
      
![image](https://user-images.githubusercontent.com/56258731/67147053-5c214080-f2bb-11e9-876c-b5b4de043563.png)

  7.	Menambahkan remote repository
  
    •	Untuk menambahkan remote repository gunakan perintah
      $ git remote add origin [url]
      
![image](https://user-images.githubusercontent.com/56258731/67147108-f6818400-f2bb-11e9-94fc-8d6ac911a2b0.png)

  8.	Mengirim perubahan ke server
 # Perintah ini anda akan diminta memasukan username dan password pada akun github.
  
    •	Gunakan perintah git push
      $ git push  -u origin master

![image](https://user-images.githubusercontent.com/56258731/67147183-c090cf80-f2bc-11e9-8438-dbb3382d0e52.png)

  9.	Clone repository
 # Perintah ini pada dasarnya adalah meng-copy repository server secara otomatis dan membuat satu direktory sesuai dengan nama             repositorynya.

    •	Untuk melakukan cloning, gunakan perintah git clone [url]
  
![image](https://user-images.githubusercontent.com/56258731/67147450-136b8680-f2bf-11e9-83a0-9cc832ae6cfa.png)

C.	Gunakan akun github untuk membuat repository server
  1.	Buka website resminya (https://github.com/)
  2.	Buat akun github dengan menyertakan nama pengguna, alamat email, dan password.
  
![image](https://user-images.githubusercontent.com/56258731/67147512-bd4b1300-f2bf-11e9-980c-f1729287fa44.png)

  3.	Jika sudah mempunyai akun anda langsung sign in

![image](https://user-images.githubusercontent.com/56258731/67147541-07cc8f80-f2c0-11e9-9657-c7a4da7a46ab.png)

  4.	Jika sudah log in buat new repository  dari menu (icon +) atau pada laman github klik start a project.
  
![image](https://user-images.githubusercontent.com/56258731/67147623-8c1f1280-f2c0-11e9-8d5a-33dd8ed04a26.png)

  5.	Isi nama repository dengan latihan1, lalu klik create repository
 
 ![image](https://user-images.githubusercontent.com/56258731/67147692-2aab7380-f2c1-11e9-9fa2-6f0d823b42a6.png)

D.	Lihat hasil pada server repository
  1.	Buka laman github, arahkan pda repository anda
  2.	Maka perubahan akan terlihat.
  
![image](https://user-images.githubusercontent.com/56258731/67147733-9a216300-f2c1-11e9-8b50-d5d13bb9eb0e.png)

![image](https://user-images.githubusercontent.com/56258731/67147876-35ff9e80-f2c3-11e9-8c23-959e22fcbbd2.png)

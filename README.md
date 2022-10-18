*Hallo nama saya Fathia wardah s.djawas. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah*  Applikasi git , akun git. Sebelum itu saya akan kasih tutorial cara penginstalan *GIT*.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di *git-scm.com* .
  
![Screenshot (11)](https://user-images.githubusercontent.com/115916422/196346702-d4858c29-3f15-4063-9df0-c805ad6d36f1.png)
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah *git --version.*  Saya memakai versi 2.38.0.windows.1

![Screenshot (19)](https://user-images.githubusercontent.com/115916422/196347546-29f2b688-8771-47dc-b146-7c6d3529648d.png)

  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut http://github.com

![Screenshot (3)](https://user-images.githubusercontent.com/115916422/196347769-3d976d32-2933-4814-9180-454a29266d90.png)

- Pada langkah selanjutnya anda boleh langsung diskip saja.
   
  ### Membuat repositori baru

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (5)](https://user-images.githubusercontent.com/115916422/196347898-d38d51f5-c86e-4995-a844-2a9857fa3764.png)

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

![Screenshot (17)](https://user-images.githubusercontent.com/115916422/196348742-3e5f183f-66cd-4599-8dbb-36f268391fa8.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

  ![Screenshot (6)](https://user-images.githubusercontent.com/115916422/196348540-0e927241-a4fb-48f1-9d89-102ea81193bb.png)


### Membuat Repository Local

- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih *Git Bash here* .

![Screenshot (20)](https://user-images.githubusercontent.com/115677959/195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f.png)

- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      *$ git config --global user.email “email_user”*
      *$ git config --global user.name “nama_user”*

  ![Screenshot (10)](https://user-images.githubusercontent.com/115916422/196349779-875ad258-8e4c-425a-a286-d13650a57e89.png)

- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 "  LALU *" cd lab_pemrograman1 

![Screenshot (19)](https://user-images.githubusercontent.com/115916422/196349855-54fa444e-21ad-4f43-a82d-094e138156ff.png)


 ##### Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local 

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
 ![Screenshot (19)](https://user-images.githubusercontent.com/115916422/196350226-8f85f4c0-f760-40d1-8660-bcb0eb968760.png)

-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

    ![Screenshot (24)](https://user-images.githubusercontent.com/115677959/195979189-8f39f73d-dcea-4d35-982d-d84ddefad965.png)

 ##### Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.
  ![Screenshot (26)](https://user-images.githubusercontent.com/115677959/195979269-80794fee-01bd-4fab-b200-a13256253af6.png)


- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit"
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### *File berhasil tersimpan*

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/FathiaDjawas/latihan01
   ![Screenshot (8-)](https://user-images.githubusercontent.com/115677959/195979558-eb6c7913-ade9-4381-8584-d3ad396d119f.png)


 ##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![git_push](https://user-images.githubusercontent.com/115677959/195979685-82932b67-cc7a-458a-beb6-4c6a4a12612a.png)

 ##### Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/FathiaDjawas/latihan01 . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
  ![Screenshot (20)](https://user-images.githubusercontent.com/115916422/196352238-39e2047d-1819-4811-9969-ab45490b7636.png)



-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas*.
### *Terimakasih*

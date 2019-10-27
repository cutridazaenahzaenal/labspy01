  
latihan1
<br/> **NAMA  : CUTRIDA ZAENAH ZAENAL**
<br/> **NIM   : 311910007**
<br/> **UNIV  : UNIVERSITAS PELITA BANGSA**
<br/> Tugas   : bahasa pemrograman
<br/>
<br/>
# MEMBUAT DAN MENAMBAHKAN FILE REPOSITORY 
## install aplikasi
download dan install aplikasi git sesuai os anda.. bisa download di (https://git-scm.com)
<br/>!![1](https://user-images.githubusercontent.com/56877903/67621947-e4b15b00-f83e-11e9-9622-625104e13103.PNG)
<br/>
<br/>
## buat akun git hub anda
<br/> buat akun git server anda di  (github.com) 
<
<br/>
![2](https://user-images.githubusercontent.com/56877903/67621948-e4b15b00-f83e-11e9-8b16-132f0103a368.PNG)

## Menambahkan Global Config
<br/>1.lakukanlah kofigurasi user name dan user email anda ke git dengan cara
<br/>2.buka aplikasi git
<br/>3.ketikan perintah
<br/> **git config --global user.name "username hub anda"**
<br/> **git config --global user.email "email hub anda"**
<br/>![3](https://user-images.githubusercontent.com/56877903/67621936-e24f0100-f83e-11e9-91d9-be927b6000d2.PNG)
## membuat repository local
<br/>**1**. buat folder baru di windows explorer contoh d:\bahasa pemrograman
<br/>**2**. klik kanan dan pilih Git Bash
<br/>![3buat repost local]
<br/>**3**. setelah ke git bash command buat direktori latihan anda contoh **latihan1**
<br/> **$ mkdir latihan1**
<br/> **$ cd latihan1**
<br/>![4](https://user-images.githubusercontent.com/56877903/67621937-e24f0100-f83e-11e9-8523-827afffa3467.PNG)
## Membuat repository local
<br/>1.jalankan perintah **$ git init**
<br/>2. jika berhasil akan ada folder tersembunyi dengan nama **.git** di dalam folder latihan1
<br/>
![5](https://user-images.githubusercontent.com/56877903/67621938-e2e79780-f83e-11e9-85c2-ea1495a61187.PNG)
<br/>
## Menambahkan file baru di repository
<br/>1.kita coba buat file bernama README.md 
<br/>2.jalankan perintah **$ echo "#latihan1" >> README.md**
<br/>3.file README.md Berhasil di buat
<br/>
<br/>4.tambahkan file tersebut ke dalam repository anda dengan perintah
<br/>**$ git add README.md**
<br/>
## Simpan Perubahan Ke Data Base *commit*##
<br/>1.gunakan perintah **git commit -m "commit command"**
<br/>contoh : **$ git commit -m "file pertama"**
<br/> perubahan berhasil di buat>>>>>>>>><<?>><?><><

<br/> perubahan berhasil di buat

## Membuat REpository Server
<br/>1.pertama pastikan akun git hub anda sudah di verifikasi
<br/>2.masuk ke akun anda klik tombol **+** yang ada di pojok kanan
<br/>3.klik **new repository**
<br/>4.**masukan repository** name contoh : latihan1
<br/>5.unchecklist pada **initialize this repository with a README** agar memudahkan tutorial pembelajaran ini
<br/>6.lalu klik **create repository**
<br/>
## Menambahkan Remote Repository 
<br/>1.Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. 
<br/>2.untuk menambahkan gunakan perintah **git remote add origin *(url)***
<br/>3.contoh **$ git remote add origin https://github.com/cutridazaenahzaenal/LATIHAN-PYTHON**
<br/>
<br/>

## Mengirimkan ke server *push*
<br/>1.untuk mengirim perubahan local repository ke server gunakan printah git push
<br/> **$ git push -u origin master**
<br/>2.nanti akan diminta password dan email anda pastikan input dengan benar
<br/>
## Selesai sudah
<br/>1.untuk melihatnya coba buka laman https://github.com) arahkan pada repository yang anda buat tadi
<br/>2.maka perubahan dapat terlihat dengan munculnya file readme.md disitu..
<br/>






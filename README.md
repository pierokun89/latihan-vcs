# **INSTALL GIT**
### Download git bash
masuk pada browser ,dan download dulu git bash
atau klik [git bash](git-scm.com)

### install git bash 
setelah terdownload lalu install git bash

![img](/screenshot/Picture2.png)

lalu akan muncul documen license dari git
klik next untuk melanjutkan instalasi

![img](screenshot/Picture3.png)

lalu akan muncul komponen tambahan untuk install git

![img](screenshot/Picture4.png)


lalu tunggu instalasi berjalan sampai selesai

![img](screenshot/Screenshot_188.png)

lalu klik finish setelah instalasi selesai

![img](screenshot/picture6.png)

### cek versi git
buka cmd pada windows

![img](screenshot/Picture7.png)

lalu masukan perintah berikut untuk mengecek apakah git sudah terinstall


> $ git --version

jika git sudah berhasil terinstall, maka akan muncul tampilan seperti dibawah ini


![img](screenshot/Picture8.png)

# **MEMBUAT REPOSITORY**
buka github pada browser 
atau klik [github](http://github.com)

### login github
setelah masuk ke git akan keluar tampilan berikut ini

![img](screenshot/Picture11.png)

apabila sudah memiliki akun langsung sign in pada github
masukan username dan password github .lalu klik sign in

![img](screenshot/Picture12.png)


### membuat repository baru

setelah berhasil login github ,lalu membuat repository .
klik tombol new pada menu repoositories untuk membuat repository baru

![img](screenshot/Picture13.png)

lalu isi nama, deskripsi, dan jenis repository , 
lalu centang add README.md
setelah selesai mengisi lalu klik create

### buat folder pada windows

selanjutnya buat folder baru pada local disk komputer untuk menyimpan update file dari repository yang telah dibuat
![img](screenshot/Picture1.png)

### buka folder menggunakan git bash

klik kanan pada folder yang telah dibuat .
lalu klik git bash here

![img](screenshot/Picture9.png)
 
lalu akan muncul tampilan dibawah ini

![img](screenshot/Picture10.png)

### clone repository 

masuk ke repository pada github
lalu klik code

dan salin alamat repository seperti pada gambar berikut
![img](screenshot/Picture14.png)

lalu masuk ke git bash lagi .
dan masukann perintah berikut

> $ git clone *salinan dari url repository*

lalu akan muncul tampi;lan berikut

![img](screenshot/Picture15.png)

### rubah folder menjadi repository

lakukan perintah berikut agar folder menjadi repository

> $ cd *nama repository*

lalu akan muncul tampilan sebagai berikut

![img](screenshot/Picture16.png)

### menambahkan file

pada git bash masukan perintah berikut

> $ git add .

lalu akan muncul tampilan berikut

![img](screenshot/Picture20.png)

### buat commit

commit berfungsi menambahkan komentar pada file yang baru diupload.
masukan perintah berikut untuk membuat commit

> $ git commit -m"*masukan coommit*"

kalian bebas memasukan nama commit .

![img](screenshot/Picture21.png)

### push ke github

masukan perintah berikut untuk push ke github

> $ git push -u origin main

jika proses berhasil akan muncul tampilan sebagai berikut


![img](screenshot/Picture22.png)

![img](screenshot/Picture22.png)

### cek pekerjaan
masuk ke github dan cek apakah pekerjaan sudah selesai

![img](screenshot/Picture23.png)


# UTS Sistem Administrasi Server

## Rasyid Sabillillah IT-0202 (1202190009)

**1. Download ISO Installer Windows Server 2022**

- Kunjungi situs https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022

- Pilih Windows Server, pilih Get started for free

- Setelah itu centang Download the Iso lalu klik Continue

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25.png?raw=true"></p>

- Isi form dengan benar, kemudian centang Yes untuk Privacy Statement, klik Continue

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_1.png?raw=true"></p>

- Memilih bahasa. kemudian klik Download 

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_2.png?raw=true"></p>



**2. Dokumentasi Instalasi Windows Server 2022**

**A. Instalasi Windows Server 2022**

- Buka Virtual Box, kemudian klik New

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_3.png?raw=true"></p>

- Atur nama sesuai keinginan, pilih Type Microsoft Windows dengan Version Other Windows (64 bit), dengan Memory Size 2048 MB, dan centang Create a virtual hard disk now. Setelah itu klik Create

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_4.png?raw=true"></p>

- Pilih file location sesuai keinginan (**pastikan penyimpanan cukup**) dengan file size 35 GB dengan Harrdisk file type VDI dan Storage on physical hard disk Dynamically allocated (penyimpanan akan bertambah seiring aplikasi atau sistem yang diinstall pada Windows Server). Setelah itu klik Create

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_5.png?raw=true"></p>

- Akan muncul tampilan Windows Server 2022 di bagian samping, klik Setting untuk konfigurasi

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_5_1.png?raw=true"></p>

- Klik Network di bagian samping, kemudian pilih Adapter 1 dengan mencentang Enable Network Adapter, pilih Bridged Adapter dengan nama wlp3s0 (**wireless**)

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_5_2.png?raw=true"></p>

- Jalankan Virtual Windows Server dengan klik Start

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_6.png?raw=true"></p>

- Menambahkan file ISO Windows Server yang telah didownload dengan klik icon warna kuning seperti gambar di bawah

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_6_1.png?raw=true"></p>

- Klik Add untuk menambahkan file ISO

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_7.png?raw=true"></p>

- Cari file ISO Windows Server yang telah didownload, kemudian pilih file tersebut

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_8.png?raw=true"></p>

- Setelah ditambahkan, pilih nama file ISO Windows Server, setelah itu klik Choose

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_9.png?raw=true"></p>

- Setelah itu jalankan file ISO Windows Server dengan klik Start

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_10.png?raw=true"></p>

- Pilih bahasa yang ingin digunakan pada saat penginstallan, atur waktu sesuai negara, dan atur keyboard US. Setelah itu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_11.png?raw=true"></p>

- Pilih Install Now untuk memulai proses penginstallan Windows Server 2022

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_12.png?raw=true"></p>

- Pilih Windows Server 2022 Datacenter Evaluation (Desktop Experience), lalu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_13.png?raw=true"></p>

- Baca terlebih dahulu Microsoft Software License Terms, setelah itu centang untuk menyetujui, dan pilih Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_14.png?raw=true"></p>

- Pilih Custom Install Microsoft Server Operating System only (advanced) untuk menginstall dan mempartisi disk secara manual

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_15.png?raw=true"></p>

- Pilih Drive Unallocated Space, klik New, setelah itu klik Apply untuk mempartisi file system

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_16.png?raw=true"></p>

- Jika ada pop up seperti gambar di bawah, klik OK

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_17.png?raw=true"></p>

- Pilih Drive 0 Partition 2 untuk memilih partisi (Local Disk C) yang nantinya akan diinstall Windows Server 2022

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_18.png?raw=true"></p>

- Tunggu hingga proses penginstallan Windows Server 2022 sampai selesai, maka otomatis Windows Server 2022 akan merestart dengan sendirinya

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_19.png?raw=true"></p>

- Atur password dengan username Admistrator (**Pastikan ada Upper Case atau Lower Case dan juga simbol atau angka**) agar membuat password kita lebih kuat atau strong

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_20.png?raw=true"></p>

- Klik Input -> Keyboard -> Insert Ctrl + Alt + Del pada menu Virtual Box. Setelah itu masukkan password sesuai yang diisikan pada langkah sebelumnya

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_21.png?raw=true"></p>

- Pilih menu Devices -> Insert Guest Additions CD Image pada menu VirtualBox, kemudian buka File Exploler dan pilih CD Drive (D:) VirtualBox Guest Additions. Setelah itu klik VboxWindowsAdditions untuk menginstall program tersebut. Tujuannya untuk mengatur layar di desktop guest sama halnya seperti desktop di host yaitu kita bisa menggunakan layar di mesin virtual sama seperti di mesin aslinya (Contoh melakukan fitur copy paste)

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_22.png?raw=true"></p>

- Klik next untuk melanjutkan proses penginstallan

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_23.png?raw=true"></p>

- Atur path folder penginstallan sesuai keinginan, setelah selesai klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_24.png?raw=true"></p>

- Pilih Install untuk melakukan proses penginstallan

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_25.png?raw=true"></p>

- Jika muncul pop up seperti gambar di bawah, klik Install

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_26.png?raw=true"></p>

- Tunggu proses penginstallan selesai, lalu pilih Reboot now dan klik Finish. Setelah itu tunggu proses muat ulang sistem selesai

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_27.png?raw=true"></p>



**B. Instalasi Active Directory Domain Service**

- Sebelum melakukan instalasi, nama computer diubah terlebih dahulu dengan masuk ke windows powershell (cari di menu search pada windows). Kemudian ketikkan “rename-computer -Newname Server2022” lalu enter

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_27_1.png?raw=true"></p>

- Buka Aplikasi Server Manager, pilih menu Manage di bagian atas, lalu klik Add Roles and Features

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_28.png?raw=true"></p>

- Baca terlebih dahulu untuk mengetahui apa saja yang akan menambahkan Roles dan Features. Jika sudah klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_29.png?raw=true"></p>

- Pilih Role-based or feature-based installation untuk mengonfigurasi single server dengan menambahkan roles, roles service, dan feature.

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_30.png?raw=true"></p>

- Centang Select a server from the sever pool untuk menyimpan pada direktori lokal

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_31.png?raw=true"></p>

- Centang Active Directory Domain Server, kemudian klik Add features untuk menambahkan Active Directory Domain Server sebagai Server Roles

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_32.png?raw=true"></p>

- Kemudian klik next untuk menambahkan features .NET Framewordk 4.8 dan Group Policy Mangement

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_33.png?raw=true"></p>

- Baca terlebih dahulu informasi Active Directory Domain Server (AD DS), setelah itu klik next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_34.png?raw=true"></p>

- Klik Install untuk melakukan proses penginstallan Server Roles dan Features yang tadi telah ditambahkan

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_35.png?raw=true"></p>

- Tunggu Proses penginstallan sampai dengan selesai, kemudian klik Close

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_36.png?raw=true"></p>



**C. Instalasi DNS Server**

- Buka Aplikasi Server Manager, pilih menu Manage di bagian atas, lalu klik Add Roles and Features

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_28.png?raw=true"></p>

- Pilih Role-based or feature-based installation untuk mengonfigurasi single server dengan menambahkan roles, roles service, dan feature.

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_30.png?raw=true"></p>

- Centang Select a server from the sever pool untuk menyimpan pada direktori lokal

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_31.png?raw=true"></p>

- Centang DNS Server, kemudian klik Add features untuk menambahkan DNS Server sebagai Server Roles

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_36_1.png?raw=true"></p>

- Apabila muncul pop up seperti gambar di bawah (Konfigurasi IP dilakukan setelah penginstallan DNS, klik Continue 

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_36_2.png?raw=true"></p>



**D. Instalasi Net Framework 3.5**

- Centang .NET Framework 3.5 Features untuk menambahkan Features, lalu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_37.png?raw=true"></p>

- Setelah itu muncul tampilan informasi Domain Name System (DNS), klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_38.png?raw=true"></p>

- Klik Install untuk melakukan proses penginstallan Server Roles dan Features yang tadi telah ditambahkan

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_39.png?raw=true"></p>

- Tunggu Proses penginstallan sampai dengan selesai, kemudian klik Close

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_40.png?raw=true"></p>



**E. Promote Server to a Domain Controller**

- Buka CMD dengan Run As Administrator

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_41.png?raw=true"></p>

- Ketikkan sconfig lalu enter, ketikkan angka 1 lalu enter, maka akan muncul tampilan seperti berikut. Setelah itu ketikkan angka 8, lalu enter

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_42.png?raw=true"></p>

- Maka akan muncul tampilan **Network adapter settings**

  Ketikkan angka 1 untuk mengatur network adapter address.

  Ketikkan S untuk mengatur ip dengan konfigurasi static atau manual

  Ketikkan IP 192.168.115.200 (**Pastikan sejaringan dengan IP Default Gateway**) untuk mengatur IP secara static

  Ketikkan 255.255.255.0 untuk memasukkan subnet mask

  Ketikkan 192.168.115.178 untuk mengatur IP gateway

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_43.png?raw=true"></p>

- Cari view network connections pada menu search windows

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_44.png?raw=true"></p>

- Klik kanan Ethernet, klik Properties untuk memulai konfigurasi, maka akan muncul tampilan berikut. Setelah itu pilih Internet Protocol Version 4 (TCP/IPv4) lalu masukkan IP DNS Server yang tadi telah diatur, jika sudah klik OK

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_45.png?raw=true"></p>

- Pilih Promote this server to a domain controller untuk memulai promote sever

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_46.png?raw=true"></p>

- Centang Add a new forest pada deployment operation, ketikkan root domain name sesuai keinginan. Setelah itu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_47.png?raw=true"></p>

- Pastikan pengaturan seperti gambar di bawah ini, lalu masukkan password dengan catatan ada Upper Case atau Lower Case dan juga simbol atau angka, setelah itu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_48.png?raw=true"></p>

- Kemudian lewati saja menu DNS Options dengan klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_49.png?raw=true"></p>

- Verifikasi NetBIOS dengan domain name sesuai keinginan. Setelah itu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_50.png?raw=true"></p>

- Atur database, log files, SYSVQL folder sesuai keinginan atau biarkan default seperti gambar berikut. Setelah itu klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_51.png?raw=true"></p>

- Kemudian lihat ulang apa saja yang telah diatur sebelumnya, sekiranya sudah sesuai klik Next

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_52.png?raw=true"></p>

- Jika sudah sesuai, maka akan muncul centang hijau All prepquisite checks telah sukses. Setelah itu klik Install

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_53.png?raw=true"></p>

- Tunggu proses pengaturan dilakukan sampai selesai, maka otomatis sistem operasi Windows Server 2022 akan direboot atau muat ulang agar Active Directory Domain Services dapat dijalankan

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_55.png?raw=true"></p>

- Klik Input -> Keyboard -> Insert Ctrl + Alt + Del pada menu Virtual Box. Pilih namauser/Adminstrator. Setelah itu masukkan password, lalu klik enter

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_56.png?raw=true"></p>

- Untuk mengecek hasil konfigurasi, buka CMD dengan Run As Administrator

  Ketikkan “netdom query fsmo” lalu klik enter

  Ketikkan ipconfig untuk melihat konfigurasi IP yang telah diatur sebelumnya

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_57.png?raw=true"></p>

- Minimize cmd tersebut, kemudian Cari view network connections pada menu search windows, lalu klik kanan Ethernet, klik Properties untuk memulai konfigurasi. Setelah itu pilih Internet Protocol Version 4 (TCP/IPv4), maka akan muncul tampilan seperti berikut

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_58.png?raw=true"></p>

- Lalu ganti  IP DNS Server sesuai yang telah diatur sebelumnya, jika sudah klik OK

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_59.png?raw=true"></p>

- Buka cmd tadi, ketikkan ipconfig/all untuk mengecek apakah IP DNS Server telah diganti, jika sudah maka akan seperti gambar berikut

  <p align="center"><img src= "https://github.com/acid99/UTSSystemAdministrator/blob/main/assets/2021-11-25_60.png?raw=true"></p>
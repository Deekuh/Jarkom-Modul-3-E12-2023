# Jarkom-Modul-3-E12-2023

## Anggota Kelompok
- Andhika Lingga Mariano (5025211161)
- Beauty Valen Fajri (5025211227)

## Daftar Isi
- [Topologi](#topologi)
- [Configure](#configure) 
- [Soal 1](#soal-1)
  - [Jawaban](#jawaban)
- [Soal 2](#soal-2)
  - [Jawaban](#jawaban)
- [Soal 3](#soal-3)
  - [Jawaban](#jawaban)
- [Soal 4](#soal-4)
  - [Jawaban](#jawaban)
- [Soal 5](#soal-5)
  - [Jawaban](#jawaban)
- [Soal 6](#soal-6)
  - [Jawaban](#jawaban)
- [Soal 7](#soal-7)
  - [Jawaban](#jawaban)
- [Soal 8](#soal-8)
  - [Jawaban](#jawaban)
- [Soal 9](#soal-9)
  - [Jawaban](#jawaban)
- [Soal 10](#soal-10)
  - [Jawaban](#jawaban)
- [Soal 11](#soal-11)
  - [Jawaban](#jawaban)
- [Soal 12](#soal-12)
  - [Jawaban](#jawaban)
- [Soal 13](#soal-13)
  - [Jawaban](#jawaban)
- [Soal 14](#soal-14)
  - [Jawaban](#jawaban)
- [Soal 15](#soal-15)
  - [Jawaban](#jawaban)
- [Soal 16](#soal-16)
  - [Jawaban](#jawaban)
- [Soal 17](#soal-17)
  - [Jawaban](#jawaban)
- [Soal 18](#soal-18)
  - [Jawaban](#jawaban)
- [Soal 19](#soal-19)
  - [Jawaban](#jawaban)
- [Soal 20](#soal-20)
  - [Jawaban](#jawaban)

## Topologi
<img width="620" alt="Screen Shot 2023-11-18 at 21 43 53" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/9875e7e1-57c7-4e08-8bf6-ee3b5ebd0825">

## Configure
Aura
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.212.1.10
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 192.212.2.10
	netmask 255.255.255.0

auto eth3
iface eth3 inet static
	address 192.212.3.10
	netmask 255.255.255.0

auto eth4
iface eth4 inet static
	address 192.212.4.10
	netmask 255.255.255.0
 ```

Himmel
```
auto eth0
iface eth0 inet static
	address 192.212.1.1
	netmask 255.255.255.0
	gateway 192.212.1.10
```

Heiter
```
auto eth0
iface eth0 inet static
	address 192.212.1.2
	netmask 255.255.255.0
	gateway 192.212.1.10
```

Denken
```
auto eth0
iface eth0 inet static
	address 192.212.2.1
	netmask 255.255.255.0
	gateway 192.212.2.10
```

Eisen
```
auto eth0
iface eth0 inet static
	address 192.212.2.2
	netmask 255.255.255.0
	gateway 192.212.2.10
```

Fieren
```
auto eth0
iface eth0 inet static
	address 192.212.4.1
	netmask 255.255.255.0
	gateway 192.212.4.10
```

Flamme
```
auto eth0
iface eth0 inet static
	address 192.212.4.2
	netmask 255.255.255.0
	gateway 192.212.4.10
```

Fern
```
auto eth0
iface eth0 inet static
	address 192.212.4.3
	netmask 255.255.255.0
	gateway 192.212.4.10
```

Lugner
```
auto eth0
iface eth0 inet static
	address 192.212.3.1
	netmask 255.255.255.0
	gateway 192.212.3.10
```

linie
```
auto eth0
iface eth0 inet static
	address 192.212.3.2
	netmask 255.255.255.0
	gateway 192.212.3.10
```

Lawine
```
auto eth0
iface eth0 inet static
	address 192.212.3.3
	netmask 255.255.255.0
	gateway 192.212.3.10
```

Sein, Stark, Revolte, Richter
```
auto eth0
iface eth0 inet dhcp
```

## Soal 1
Lakukan register domain berupa riegel.canyon.yyy.com untuk worker Laravel dan granz.channel.yyy.com untuk worker PHP (0) mengarah pada worker yang memiliki IP [prefix IP].x.1.Lakukan konfigurasi sesuai dengan peta yang sudah diberikan dan pastikan semua CLIENT harus menggunakan konfigurasi dari DHCP Server.

### Jawaban
Jalankan DHCP Relay (Aura) pada topologi yang ada

<img width="719" alt="Screen Shot 2023-11-19 at 05 15 34" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/32b89a9d-2237-48ed-99ba-f0135f7e9bb1">

Jalankan DNS Server (Heiter) pada topologi yang ada

<img width="721" alt="Screen Shot 2023-11-19 at 05 16 52" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/697ff5f1-24c4-4795-9f1d-3a0f3a52dee0">

Jalankan DHCP Server (Himmel) pada topologi yang ada

<img width="721" alt="Screen Shot 2023-11-19 at 05 18 17" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/2c9b38c9-54b1-4917-bf15-a3c4ddbf5ae4">

Jalankan Client (Revolte) pada topologi yang ada

<img width="718" alt="Screen Shot 2023-11-19 at 05 20 30" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/7321f1be-7a54-4f7d-afe4-c9a7c7563647">

Setelah itu, lakukan `apt-get update` pada client (Revolte)

<img width="720" alt="Screen Shot 2023-11-19 at 05 23 03" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/76de7150-8dc3-4951-956c-648100564556">

Lakukan pula `apt-get install dnsutils` pada client (Revolte)

<img width="719" alt="Screen Shot 2023-11-19 at 05 24 55" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/7eaad1b1-e4ee-4a38-baef-c6d4b72e02c4">








Lakukan `host -t A riegel.canyon.e12.com` pada client (Revolte)

<img width="405" alt="Screen Shot 2023-11-19 at 05 29 59" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/a232e9b8-479b-43a6-81ca-3f01ec233c62">

Lakukan `host -t A granz.channel.e12.com` pada client (Revolte)

<img width="412" alt="Screen Shot 2023-11-19 at 05 30 20" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/2d192280-bcb5-4dbf-ac00-eab4fc3f627e">

Dan pada soal nomor 1 untuk mengetahui konfigurasi dari DHCP Server pada Client maka lakukan pengecekan di salah satu client tersebut (sebagai contoh client revolte) 

<img width="188" alt="Screen Shot 2023-11-19 at 05 33 20" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/c6315c78-3ab3-49de-b411-d282526feea5">

## Soal 2
Client yang melalui Switch3 mendapatkan range IP dari [prefix IP].3.16 - [prefix IP].3.32 dan [prefix IP].3.64 - [prefix IP].3.80 

### Jawaban
Pada Switch 3 terdapat Client berupa `Revolte` dan `Ritcher`, untuk mengetahui range IP yang ada pada salah satu client tersebut, maka lakukan pengecekan dengan jalankan `ip a` pada Revolte

<img width="736" alt="Screen Shot 2023-11-19 at 05 41 45" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/5b338da4-4467-4d4d-a732-b55041b6cd04">

Setelah dilakukan pengecekan, maka IP yang ada yakni `3.18`. Jadi pada client di switch 3 berada di range yang sudah ditentukan pada soal.

## Soal 3
Client yang melalui Switch4 mendapatkan range IP dari [prefix IP].4.12 - [prefix IP].4.20 dan [prefix IP].4.160 - [prefix IP].4.168

### Jawaban
Pada Switch 4 terdapat Client berupa `Stark` dan `Sein`, untuk mengetahui range IP yang ada pada salah satu client tersebut, maka lakukan pengecekan dengan jalankan `ip a` pada Stark

<img width="737" alt="Screen Shot 2023-11-19 at 06 02 15" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/16de05aa-a9ca-430d-97d2-3b5da2f8d5e3">

Setelah dilakukan pengecekan, maka IP yang ada yakni `4.13`. Jadi pada client di switch 4 berada di range yang sudah ditentukan pada soal.

## Soal 4
Client mendapatkan DNS dari Heiter dan dapat terhubung dengan internet melalui DNS tersebut

### Jawaban

Karena sudah dilakukan configure pada client yang sudah ada, maka untuk mendapatkan DNS dari Heiter dan dapat terhubung dengan internet melalui DNS tersebut maka lakukan `ping google.com` pada salah satu client yang diinginkan (Client Revolte)

<img width="766" alt="Screen Shot 2023-11-19 at 06 18 21" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/9373e1ce-44e3-46f9-8739-1458c2a95b23">

## Soal 5
Lama waktu DHCP server meminjamkan alamat IP kepada Client yang melalui Switch3 selama 3 menit sedangkan pada client yang melalui Switch4 selama 12 menit. Dengan waktu maksimal dialokasikan untuk peminjaman alamat IP selama 96 menit 

### Jawaban
Lease time yang dibutuhkan merupakan waktu dengan perhitungan di setiap detiknya. Client yang melalui Switch3 memiliki lease time selama 3 menit x 60 = 180. Untuk Switch3 dapat dilakukan pada Client Revolte ataupun Client Richter. Pada perhitungan kali ini dilakukan perhitungan pada Client Richter

<img width="599" alt="Screen Shot 2023-11-19 at 06 27 30" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/7af8dfc8-6fc6-4c36-8416-31933c5fdd05">

Pada Client Ricther memiliki `LEASE TIME 300`

Client yang melalui Switch4 memiliki lease time selama 12 menit x 60 = 720. Untuk Switch4 dapat dilakukan pada Client Stark ataupun Client Sein. Pada perhitungan kali ini dilakukan perhitungan pada Client Stark

<img width="564" alt="Screen Shot 2023-11-19 at 06 32 06" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/a3443875-aa37-4500-bf1c-dfbadf419ea6">

Pada Client Stark memiliki `LEASE TIME 720`

## Soal 6
Pada masing-masing worker PHP, lakukan konfigurasi virtual host untuk website berikut dengan menggunakan php 7.3.

### Jawaban
Lakukan pengecekan pada Load Balancer(Eisen), setelah itu lakukan `cd root` serta `ls` pada Load Balancer(Eisen)
<img width="557" alt="Screen Shot 2023-11-19 at 18 33 36" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/ceddb6e5-4fe8-46ea-9477-36fedf2bebe7">

Kemudian lakukan `bash no6_lb.sh`

<img width="799" alt="Screen Shot 2023-11-19 at 19 13 33" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/04343c6f-7124-4f9d-9387-07a5d4c518ee">

Pada topologi yang ada, terdapat PHP Worker yaknin Lawine, Lugner, dan Linie. Lakukan pengecekan pada PHP Worker(Lawine), setelah itu lakukan `cd root` serta `ls` pada PHP Worker(Lawine)

<img width="232" alt="Screen Shot 2023-11-19 at 19 16 13" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/73c1e1d4-e6ab-470f-bdfd-6453808f0ecf">

Kemudian lakukan `bash no6_worker.sh`

<img width="731" alt="Screen Shot 2023-11-19 at 19 26 46" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/14d12a01-b765-4f75-8072-5ebcc1b3866e">

Lakukan pengecekan pada PHP Worker(Lugner), setelah itu lakukan `cd root` serta `ls` pada PHP Worker(Lugner)

<img width="232" alt="Screen Shot 2023-11-19 at 19 16 13" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/73c1e1d4-e6ab-470f-bdfd-6453808f0ecf">

Kemudian lakukan `bash no6_worker.sh`

<img width="729" alt="Screen Shot 2023-11-19 at 19 27 33" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/da9ea2ff-3906-45a8-bc6d-2150ad9a29a9">

Setelah itu lakukan pengecekan pada PHP Worker(Linie), setelah itu lakukan `cd root` serta `ls` pada PHP Worker(Linie)

<img width="232" alt="Screen Shot 2023-11-19 at 19 16 13" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/73c1e1d4-e6ab-470f-bdfd-6453808f0ecf">

Kemudian lakukan `bash no6_worker.sh`

<img width="731" alt="Screen Shot 2023-11-19 at 19 28 07" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/b9a75b6d-7141-4b51-8b77-9de1cbbd1056">


<img width="361" alt="Screen Shot 2023-11-19 at 19 32 00" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/20b314cc-b42a-40ea-beed-034ebd3eb750">

<img width="366" alt="Screen Shot 2023-11-19 at 19 33 32" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/5768fd88-3b31-4cfc-b6a0-a4416cc305f1">

<img width="361" alt="Screen Shot 2023-11-19 at 19 33 55" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/59e5dbb3-731c-402c-8407-2e60d8114973">

<img width="365" alt="Screen Shot 2023-11-19 at 19 34 27" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/3a752751-1da7-44c3-91fb-42ee093d0c20">

## Soal 7
### Jawaban

## Soal 8
### Jawaban

## Soal 9
Dengan menggunakan algoritma Round Robin, lakukan testing dengan menggunakan 3 worker, 2 worker, dan 1 worker sebanyak 100 request dengan 10 request/second, kemudian tambahkan grafiknya pada grimoire.

### Jawaban


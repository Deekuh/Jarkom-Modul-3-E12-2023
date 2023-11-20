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

Setelah itu, lakukan `lynx granz.channel.e12.com` pada Client Revolte, maka request akan dihandle oleh : Lugner

<img width="361" alt="Screen Shot 2023-11-19 at 19 32 00" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/20b314cc-b42a-40ea-beed-034ebd3eb750">

Lakukan lagi perulangan `lynx granz.channel.e12.com` pada Client Revolte, maka request akan dihandle oleh : Linie

<img width="366" alt="Screen Shot 2023-11-19 at 19 33 32" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/5768fd88-3b31-4cfc-b6a0-a4416cc305f1">

Lakukan `lynx granz.channel.e12.com` pada Client Revolte, maka request akan dihandle oleh : Lawine

<img width="361" alt="Screen Shot 2023-11-19 at 19 33 55" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/59e5dbb3-731c-402c-8407-2e60d8114973">

Dan lakukan `lynx granz.channel.e12.com` pada Client Revolte, maka request akan dihandle kembali oleh : Lugner

<img width="365" alt="Screen Shot 2023-11-19 at 19 34 27" src="https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/114421539/3a752751-1da7-44c3-91fb-42ee093d0c20">

## Soal 7
Kepala suku dari Bredt Region memberikan resource server sebagai berikut:
- Lawine, 4GB, 2vCPU, dan 80 GB SSD.
- Linie, 2GB, 2vCPU, dan 50 GB SSD.
- Lugner 1GB, 1vCPU, dan 25 GB SSD.

aturlah agar Eisen dapat bekerja dengan maksimal, lalu lakukan testing dengan 1000 request dan 100 request/second.

### Jawaban

Untuk melakukan testing, pertama-tama install command apache benchmark (ab) dari apache2-utils pada client. Setelah itu, jalankan command `ab -n 1000 -c 100 http://192.212.2.2/` seperti berikut.

```bash
apt-get update
apt-get install apache2-utils -y
ab -V

echo nameserver 192.168.122.1 > /etc/resolv.conf
ab -n 1000 -c 100 http://192.212.2.2/
```

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/fd4d862e-4401-4469-bb2e-2ce3593060aa)

Jalankan juga command `htop` untuk memantau proses yang sedang berjalan pada worker.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/4fbf4523-ded2-49c4-9616-4d5e80aa679d)


Pada worker, jalankan command `cat /var/log/nginx/jarkom_access.log| grep "GET" | wc -l` untuk melihat jumlah request yang ditangani oleh tiap worker.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/07225ac1-c2b3-47c3-8ea2-df94d8463cca)


## Soal 8
Karena diminta untuk menuliskan grimoire, buatlah analisis hasil testing dengan 200 request dan 10 request/second masing-masing algoritma Load Balancer dengan ketentuan sebagai berikut:
- Nama Algoritma Load Balancer
- Report hasil testing pada Apache Benchmark
- Grafik request per second untuk masing masing algoritma.
- Analisis

### Jawaban

Masukkan setiap algoritma berikut ke dalam Load Balancer (Eisen). Setelah itu lakukan testing untuk tiap algoritma dengan cara yang sama seperti pada nomor sebelumnya.

1. Round Robin

```bash
echo '
 upstream myweb  {
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t
```

Hasil Testing

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/acc6d5e1-5e12-4e44-93cb-f404bd7625f7)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/341a6557-420a-4f43-b618-3dae49ba580b)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/66e85981-fdc8-4e1d-9df6-9b602c7c4330)

2. Weighted Round Robin

```bash
echo '
 upstream myweb  {
        server 192.212.3.1 weight=4; #IP Lugner
        server 192.212.3.2 weight=2; #IP Linie
        server 192.212.3.3 weight=1; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

unlink /etc/nginx/sites-enabled/lb-jarkom
ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t
```

Hasil Testing

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/1706df62-6c2e-45d9-86ed-87fed3c4e68b)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/3a479c22-dee1-444e-a7aa-8467a7c94d6c)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/cd655a30-ab19-4965-ac65-c3b10cbae347)


3. Least Connection

```bash
echo '
 upstream myweb  {
        least_conn;
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        proxy_set_header    X-Real-IP $remote_addr;
        proxy_set_header    X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header    Host $http_host;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t

```

Hasil Testing

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/d4f54194-e761-479e-9582-d9ac942fb237)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/43d64ab1-02fc-4b26-8403-13f3be92d6ee)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/4fd56291-2fb6-490c-a243-856e874e2c12)


4. IP Hash

```bash
echo '
 upstream myweb  {
        ip_hash;
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        proxy_set_header    X-Real-IP $remote_addr;
        proxy_set_header    X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header    Host $http_host;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t
```

Hasil Testing

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/668b3abb-7fa4-4733-b963-30fd95fd2d7c)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/7794d8c1-b3bd-42d5-9cee-93c20f8834ea)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/e48f2d15-13f9-49a8-b561-0b7a5df1e3c7)


5. Generic Hash

```bash
echo '
 upstream myweb  {
        hash $request_uri consistent;
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        proxy_set_header    X-Real-IP $remote_addr;
        proxy_set_header    X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header    Host $http_host;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

unlink /etc/nginx/sites-enabled/lb-jarkom
ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t
```

Hasil Testing

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/e4e4ee75-be08-4fb7-a94b-f6b53f7c543a)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/218a91dc-d070-4534-9b3a-60fc8e474b65)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/32a8ae6b-86ad-4635-b46a-df268ab80a01)


## Soal 9
Dengan menggunakan algoritma Round Robin, lakukan testing dengan menggunakan 3 worker, 2 worker, dan 1 worker sebanyak 100 request dengan 10 request/second, kemudian tambahkan grafiknya pada grimoire.

### Jawaban

Atur kembali algoritma Load Balancer menjadi Round Robin seperti berikut.

```bash
echo '
 upstream myweb  {
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

service nginx restart
nginx -t
```

Kemudian lakukan testing untuk jumlah worker yang berbeda-beda.

1. 3 Worker

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/1aab534c-e70b-4b9f-9eed-f3265f6ee407)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/fb51250d-39af-4c37-9699-f04f58594c51)


![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/889c8418-df9d-4fd1-93ac-db5873be7dac)


2. 2 Worker

Untuk testing dengan 2 worker, matikan salah satu worker dengan command `service nginx stop`.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/f2e88f25-4846-4977-8022-cae70ed9e6df)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/1fcb7209-7acc-427e-8b0c-8af0d5293f28)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/4d918226-df93-4709-aa43-181cc5ec880d)


3. 1 Worker

Untuk testing dengan 1 worker, matikan dua worker dengan command `service nginx stop`

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/b3919c88-ea84-4a98-957b-c3c83b9f8dc5)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/056bcd34-b10d-48c3-a927-0b6665511f2d)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/8e4f71aa-b9ce-4de4-afdd-7ff89ee69f03)


## Soal 10
Selanjutnya coba tambahkan konfigurasi autentikasi di LB dengan dengan kombinasi username: “netics” dan password: “ajkyyy”, dengan yyy merupakan kode kelompok. Terakhir simpan file “htpasswd” nya di /etc/nginx/rahasisakita/


### Jawaban

Tambahkan konfigurasi berikut ke dalam Load Balancer.

```bash
    location / {
        proxy_pass http://myweb;
        auth_basic "Restricted Access";
        auth_basic_user_file /etc/nginx/rahasisakita/.htpasswd;
    }

	mkdir /etc/nginx/rahasisakita/
	htpasswd -c -b /etc/nginx/rahasisakita/.htpasswd netics ajke12
```

Sehingga konfigurasi pada Load Balancer menjadi seperti berikut.

```bash
echo '
 upstream myweb  {
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
        proxy_pass http://myweb;
        auth_basic "Restricted Access";
        auth_basic_user_file /etc/nginx/rahasisakita/.htpasswd;
        }
 }' > /etc/nginx/sites-available/lb-jarkom

unlink /etc/nginx/sites-enabled/lb-jarkom
ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

mkdir /etc/nginx/rahasisakita/
htpasswd -c -b /etc/nginx/rahasisakita/.htpasswd netics ajke12

service nginx restart
nginx -t

```

Lakukan testing dengan menjalankan command `lynx granz.channel.e12.com`.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/f634c09e-6cc2-4696-9ffa-a9d6ac6141f0)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/599a4419-4c7d-487c-84c5-c7e1ba411b33)

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/58a0823b-07fe-4f89-8c0e-e0773f7fb601)


## Soal 11
Lalu buat untuk setiap request yang mengandung /its akan di proxy passing menuju halaman https://www.its.ac.id. hint: (proxy_pass)


### Jawaban

Tambahkan konfigurasi berikut pada Load Balancer.

```bash
    location ~* /its {
            proxy_pass https://www.its.ac.id;
    }
```

Sehingga konfigurasi Load Balancernya menjadi seperi berikut.

```bash
echo '
 upstream myweb  {
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
                proxy_pass http://myweb;
                auth_basic "Restricted Access";
                auth_basic_user_file /etc/nginx/rahasisakita/.htpasswd;
        }

        location ~* /its {
                proxy_pass https://www.its.ac.id;
        }

 }' > /etc/nginx/sites-available/lb-jarkom

unlink /etc/nginx/sites-enabled/lb-jarkom
ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

mkdir -p /etc/nginx/rahasisakita/
htpasswd -c -b /etc/nginx/rahasisakita/.htpasswd netics ajke12

service nginx restart
nginx -t
```

Lakukan testing pada client dengan menjalankan command `lynx granz.channel.e12.com/its`

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/7170f306-361f-470f-9579-12b38c65592b)


## Soal 12
Selanjutnya LB ini hanya boleh diakses oleh client dengan IP [Prefix IP].3.69, [Prefix IP].3.70, [Prefix IP].4.167, dan [Prefix IP].4.168. hint: (fixed in dulu clinetnya)

Tambahkan konfigurasi berikut pada Load Balancer.

```bash
    location / {
            allow 192.212.3.69;
            allow 192.212.3.70;
            allow 192.212.4.167;
            allow 192.212.4.168;
            deny all;
    }
```

Sehingga konfigurasinya menjadi seperti berikut.

```bash
echo '
 upstream myweb  {
        server 192.212.3.1; #IP Lugner
        server 192.212.3.2; #IP Linie
        server 192.212.3.3; #IP Lawine
 }

 server {
        listen 80;
        server_name granz.channel.e12.com;

        location / {
                proxy_pass http://myweb;
                auth_basic "Restricted Access";
                auth_basic_user_file /etc/nginx/rahasisakita/.htpasswd;

                allow 192.212.3.69;
                allow 192.212.3.70;
                allow 192.212.4.167;
                allow 192.212.4.168;
                deny all;
        }

        location ~* /its {
                proxy_pass https://www.its.ac.id;
        }

 }' > /etc/nginx/sites-available/lb-jarkom

unlink /etc/nginx/sites-enabled/lb-jarkom
ln -s /etc/nginx/sites-available/lb-jarkom /etc/nginx/sites-enabled
rm -rf /etc/nginx/sites-enabled/default

mkdir -p /etc/nginx/rahasisakita/
htpasswd -c -b /etc/nginx/rahasisakita/.htpasswd netics ajke12

service nginx restart
nginx -t

```

Lakukan testing dengan menjalankan command `lynx granz.channel.e12.com`. Apabila IP client tidak termasuk dalam list IP yang diperbolehkan, maka website tidak dapat diakses.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/156c12df-3748-41a4-9cd4-f06adeea693c)


### Jawaban

## Soal 13
Karena para petualang kehabisan uang, mereka kembali bekerja untuk mengatur riegel.canyon.yyy.com.
Semua data yang diperlukan, diatur pada Denken dan harus dapat diakses oleh Frieren, Flamme, dan Fern.


### Jawaban

Install mysql server pada Database Server dan nyalakan service mysql.

```bash
apt-get update
apt-get install mariadb-server -y
service mysql start
```

Lakukan konfigurasi pada Database Server (Denken) seperti berikut.

```bash
mysql << EOF

CREATE USER 'kelompoke12'@'%' IDENTIFIED BY 'passworde12';
CREATE USER 'kelompoke12'@'localhost' IDENTIFIED BY 'passworde12';
CREATE DATABASE dbkelompoke12;
GRANT ALL PRIVILEGES ON *.* TO 'kelompoke12'@'%';
GRANT ALL PRIVILEGES ON *.* TO 'kelompoke12'@'localhost';
FLUSH PRIVILEGES;

EOF

echo '
# The MariaDB configuration file
#
# The MariaDB/MySQL tools read configuration files in the following order:
# 1. "/etc/mysql/mariadb.cnf" (this file) to set global defaults,
# 2. "/etc/mysql/conf.d/*.cnf" to set global options.
# 3. "/etc/mysql/mariadb.conf.d/*.cnf" to set MariaDB-only options.
# 4. "~/.my.cnf" to set user-specific options.
#
# If the same option is defined multiple times, the last one will apply.
#
# One can use all long options that the program supports.
# Run program with --help to get a list of available options and with
# --print-defaults to see which it would actually understand and use.

#
# This group is read both both by the client and the server
# use it for options that affect everything
#
[client-server]

# Import all .cnf files from configuration directory
!includedir /etc/mysql/conf.d/
!includedir /etc/mysql/mariadb.conf.d/

[mysqld]
skip-networking=0
skip-bind-address' > /etc/mysql/my.cnf

service mysql restart
```

Install juga mysql server pada worker.

```bash
apt-get update
apt-get install mariadb-client -y
```

Lalu lakukan testing dengan command berikut
```bash
mariadb --host=192.212.2.1 --port=3306 --user=kelompoke12 --password=passworde12

SHOW DATABASES;
```

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/805060d3-aca1-4d25-8a8f-d0f906aaf410)


## Soal 14
Frieren, Flamme, dan Fern memiliki Riegel Channel sesuai dengan quest guide berikut. Jangan lupa melakukan instalasi PHP8.0 dan Composer


### Jawaban

Tambahkan konfigurasi berikut pada Laravel Worker.

```bash
apt-get update
apt-get install mariadb-client -y
apt-get install lynx -y
apt-get install htop -y
apt-get install -y lsb-release ca-certificates apt-transport-https software-properties-common gnupg2
curl -sSLo /usr/share/keyrings/deb.sury.org-php.gpg https://packages.sury.org/php/apt.gpg
sh -c 'echo "deb [signed-by=/usr/share/keyrings/deb.sury.org-php.gpg] https://packages.sury.org/php/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/php.list'

apt-get update
apt-get install php8.0-mbstring php8.0-xml php8.0-cli php8.0-common php8.0-intl php8.0-opcache php8.0-readline php8.0-mysql php8.0-fpm php8.0-curl unzip wget -y
php --version

apt-get install nginx -y
wget https://getcomposer.org/download/2.0.13/composer.phar
chmod +x composer.phar
mv composer.phar /usr/bin/composer
composer -V

apt-get install git -y
cd /var/www/
git clone https://github.com/martuafernando/laravel-praktikum-jarkom.git

cd /var/www/laravel-praktikum-jarkom
composer install
cp .env.example .env
echo 'APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=192.212.2.1
DB_PORT=3306
DB_DATABASE=dbkelompoke12
DB_USERNAME=kelompoke12
DB_PASSWORD=passworde12

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailpit
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"' > .env

composer update

php artisan migrate:fresh
php artisan db:seed --class=AiringsTableSeeder
php artisan key:generate
php artisan jwt:secret

echo 'server {

    listen [8001/8002/8003];

    root /var/www/laravel-praktikum-jarkom/public;

    index index.php index.html index.htm;
    server_name _;

    location / {
            try_files $uri $uri/ /index.php?$query_string;
    }

    # pass PHP scripts to FastCGI server
    location ~ \.php$ {
    include snippets/fastcgi-php.conf;
    fastcgi_pass unix:/var/run/php/php8.0-fpm.sock;
    }

location ~ /\.ht {
            deny all;
    }

    error_log /var/log/nginx/implementasi_error.log;
    access_log /var/log/nginx/implementasi_access.log;
}' > /etc/nginx/sites-available/implementasi

ln -s /etc/nginx/sites-available/implementasi /etc/nginx/sites-enabled/
chown -R www-data.www-data /var/www/laravel-praktikum-jarkom/storage
service php8.0-fpm restart
service nginx restart
```

Lakukan testing dengan command `lynx localhost:[port]`.

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/f261c9b5-6e98-4e6b-8e03-70e7b549d08c)


## Soal 15
Riegel Channel memiliki beberapa endpoint yang harus ditesting sebanyak 100 request dengan 10 request/second. Tambahkan response dan hasil testing pada grimoire.
POST /auth/register

### Jawaban

Buat file register.json seperti berikut pada client.

```bash
echo '
{
  "username": "kelompokA09",
  "password": "passwordA09"
}' > register.json

```

Kemudian lakukan testing dengan command berkut.

```bash
ab -n 100 -c 10 -p register.json -T application/json http://192.212.4.1:8001/api/auth/register
```

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/1813316a-306a-4222-8857-fbe02a3759b8)


## Soal 16
Riegel Channel memiliki beberapa endpoint yang harus ditesting sebanyak 100 request dengan 10 request/second. Tambahkan response dan hasil testing pada grimoire.
POST /auth/login

### Jawaban

Sama seperti nomor sebelumnya, buat file login.json seperti berikut pada client.

```bash
echo '
{
  "username": "kelompoke12",
  "password": "passworde12"
}' > login.json
```

Kemudian lakukan testing dengan command berikut.

```bash
ab -n 100 -c 10 -p login.json -T application/json http://192.212.4.1:8001/api/auth/login
```

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/b41ea9bb-a3d6-4303-9e62-b87c95648ada)


## Soal 17
Riegel Channel memiliki beberapa endpoint yang harus ditesting sebanyak 100 request dengan 10 request/second. Tambahkan response dan hasil testing pada grimoire.
GET /me

### Jawaban

Lakukan testing dengan menjalankan command berikut

```bash
curl -X POST -H "Content-Type: application/json" -d @login.json http://192.212.4.1:8001/api/auth/login > login_output.txt

token=$(cat login_output.txt | jq -r '.token')

ab -n 100 -c 10 -H "Authorization: Bearer $token" http://192.212.4.1:8001/api/me
```

![image](https://github.com/Deekuh/Jarkom-Modul-3-E12-2023/assets/90295688/519a4a04-2561-4e2d-9e2e-0edf21664628)


## Soal 18
Untuk memastikan ketiganya bekerja sama secara adil untuk mengatur Riegel Channel maka implementasikan Proxy Bind pada Eisen untuk mengaitkan IP dari Frieren, Flamme, dan Fern.

### Jawaban

## Soal 19
Untuk meningkatkan performa dari Worker, coba implementasikan PHP-FPM pada Frieren, Flamme, dan Fern. Untuk testing kinerja naikkan 
- pm.max_children
- pm.start_servers
- pm.min_spare_servers
- pm.max_spare_servers
sebanyak tiga percobaan dan lakukan testing sebanyak 100 request dengan 10 request/second kemudian berikan hasil analisisnya pada Grimoire.

### Jawaban

## Soal 20
Nampaknya hanya menggunakan PHP-FPM tidak cukup untuk meningkatkan performa dari worker maka implementasikan Least-Conn pada Eisen. Untuk testing kinerja dari worker tersebut dilakukan sebanyak 100 request dengan 10 request/second.

### Jawaban

# switching
Praktikum Jaringan Komputer

Nama : Fahira Dwi Malika
NIM : 09030582226033
Kelas : TK4A

Pengertian SWITCH:

Switch merupakan perangkat jaringan yang bekerja pada OSI Layer 2, Data Link Layer. dia bekerja sebagai penyambung / concentrator dalam Jaringan. Switch mengenal MAC Adressing shingga bisa memilah paket data mana yang akan di teruskan ke mana. Dan switch ini digunakan sebagai repeater/penguat. Berfungsi untuk menghubungkan kabel- kabel UTP ( Kategori 5/5e ) komputer yang satu dengan komputer yang lain. Dalam switch biasanya terdapat routing, routing sendiri berfungsi untuk batu loncat untuk melakukan koneksi dengan komputer lain dalam LAN.

Cara Kerja Switch yaitu menerima dan menganalisa seluruh isi paket sebelum meneruskannya ke tujuan. Switch memeriksa satu persatu paket untuk mengetahui adanya kerusakan pada paket tersebut dan mencegahnya agar tidak mengganggu jaringan. Switch mengalokasikan bandwidth secara penuh untuk setiap portnya. Komputer pengguna akan selalu memiliki bandwidth secara penuh seberapapun komputer yang ada. Switch bekerja di lapisan Data Link dan Setiap port didalam swith memiliki domain collision sendiri- sendiri. Switch melakukan transmisi secara 2 arah (Full duplex).

Alat dan Bahan yang diperlukan dalam praktikum Jaringan Komputer ini adalah :
1.Sebuah PC atau Laptop
2.Software Jaringan‘Cisco Packet Tracer’

Langkah - Langkah :
1.Persiapkan 2 buah PC dan 1 buah Switch.

2.Pasang kabel penghubung antara PC 0 ke Switch dan PC 1 ke Switch.
![1 sw](https://github.com/fahiradwimalika/switching/assets/126413501/a9b1237b-2ca2-4dc6-9d62-e33591df6c24)
![sw 2](https://github.com/fahiradwimalika/switching/assets/126413501/b55e48e3-65e0-4afc-83c5-9b405b6d6627)

3.Double click pada PC 0 sehingga muncul jendela baru, seperti berikut

4.Click pada tab Desktop sehingga muncul tampilan sebagai berikut.
![WhatsApp Image 2024-03-16 at 14 20 00_b3eb17c5](https://github.com/fahiradwimalika/switching/assets/126413501/6660d069-dd41-4f58-9bdd-14ef95d8d5b8)

5.Click pada tab IP Configuration, untuk mengatur alamat IP pada PC 0.
![WhatsApp Image 2024-03-16 at 14 20 00_b3eb17c5](https://github.com/fahiradwimalika/switching/assets/126413501/0979c37f-3260-4425-8927-2f6fc94d62d5)

6.Isikan Alamat IP dan Subnet Mask pada PC 0 dengan alamat seperti dibawah ini dan kosongkan kolom Default Gateaway dan DNS server.
![sw5](https://github.com/fahiradwimalika/switching/assets/126413501/ba230a07-e21f-41b8-a8fb-f58f5e46c505)

7.Lakukan hal serupa pada PC 1 tetapi dengan konfigurasi alamat IP yang berbeda dengan PC 0, tetapi Subnet Mask nya biarkan sama. Selain itu tetap kosongkan kolom Default Gateaway dan DNS server.
![WhatsApp Image 2024-03-16 at 14 20 00_b3eb17c5](https://github.com/fahiradwimalika/switching/assets/126413501/cf262495-65c7-47a3-bc6c-e408300bb275)

8.Setelah mengkonfigurasi IP maka 3 buah device tersebut akan saling terhubung ditandai dengan dot / node yang berwarna hijau.
![WhatsApp Image 2024-03-16 at 14 20 00_b3eb17c5](https://github.com/fahiradwimalika/switching/assets/126413501/a0aa8a1a-70ce-4213-8540-e11ad0f725e7)

9.Untuk melakukan testing pada jaringan tersebut, kita dapat melakukan “ping”

10.Caranya dengan double clik salah satu dari dua PC (antara PC 0 atau PC 1) dan clik pada tab Desktop.

11.Kemudian pilih tab Command Prompt dan akan muncul.

12.Kemudian ketik “PING (alamat IP tujuan) “ ; Contoh nya adalah ‘PING 192.168.123.2’ maka jaringan kita telah terhubung, akan jadi seperti di bawah ini.
![WhatsApp Image 2024-03-16 at 14 20 05_fb302dbf](https://github.com/fahiradwimalika/switching/assets/126413501/cbe69533-d294-4586-a04f-15f5d4726988)

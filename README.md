# JARKOM-MODUL-1-D18-2023
## Abhinaya Radiansyah Listiyanto  (5025211173)
## Fauzi Rizki Pratama			       (5025211220)



## 1. User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.
## a.) Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut?

#### Penjelasan :
Query kan dulu dengan “ftp” untuk memfilter semua paket yang berisi FTP
Pada bagian info kita cari “STOR” karena itu kode bagian paket sedang aktivitas mengunggah file
Klik paket tersebut dan cari pada bagian Header “Sequence number (raw)”

#### Jawaban: 258040667
![Screenshot 2023-09-18 205335](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/35e80962-ec6b-43db-ad55-127cc88e0009)

#### Kendala: Tidak ada kendala yang dialami.

## b.) Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut?

#### Penjelasan :
Query kan dulu dengan “ftp” untuk memfilter semua paket yang berisi FTP
Pada bagian info kita cari “STOR” karena itu kode bagian paket sedang aktivitas mengunggah file
Klik paket tersebut dan cari pada bagian Header “Acknowledgment Number (raw)”

#### Jawaban: 1044861039
![Screenshot 2023-09-18 205335](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/1c9819fa-4172-4360-982f-2032b6a8b90d)

#### Kendala: Tidak ada kendala yang dialami

## c.) Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

#### Penjelasan:
Query kan dulu dengan “ftp” untuk memfilter semua paket yang berisi FTP
Pada bagian info kita cari “nama file yang sama ketika diunggah” karena itu bagian paket respon yang sedang aktivitas mengunggah file
Klik paket tersebut dan cari pada bagian Header “Sequence number (raw)”

#### Jawaban: 1044861039
![Screenshot 2023-09-18 205913](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/a3898dd7-500b-48c7-86b0-54a8f5d2df99)

#### Kendala: Tidak ada kendala yang dialami

## d.) Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

#### Penjelasan:
Query kan dulu dengan “ftp” untuk memfilter semua paket yang berisi FTP
Pada bagian info kita cari “nama file yang sama ketika diunggah” karena itu bagian paket respon yang sedang aktivitas mengunggah file
Klik paket tersebut dan cari pada bagian Header “Acknowledgment Number (raw)”

#### Jawaban: 258040696
![Screenshot 2023-09-18 205913](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/340d7167-15ca-4339-ba92-b4d0442e45af)

#### Kendala: Tidak ada kendala yang dialami



## 2. Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!

#### Penjelasan:
Query pertama pada filter dituliskan “http” untuk memfilter semua paket yang berisi http
pada bagian info kita cari HTTP GET karena biasanya itu untuk akses masuk ke sebuah web
pada Header paket tinggal kita cari nama Servernya

#### Jawaban: gunicorn
![Screenshot 2023-09-18 210731](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/58b57bac-6122-40af-9ccc-945a307ff64b)
![Screenshot 2023-09-18 220010](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/646f0697-edf0-4104-a75a-9d13de7dd8aa)

#### Kendala: Tidak ada kendala yang dialami



## 3. Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:
## a.) Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?

#### Penjelasan:
Query kan dengan “ip.addr == 239.255.250 && udp.port == 3702” ini menjelaskan untuk mencari ip addres sekian dan memiliki port sekian
setelah itu kita hitung saja semua paket yang muncul dari atas sampai bawah

#### Jawaban: 21
![Screenshot 2023-09-18 211606](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/d01de255-00df-4daf-9276-cc479d41c3ae)

#### Kendala: Tidak ada kendala yang dialami

## b.) Protokol layer transport apa yang digunakan?

#### Penjelasan:
Pada info protocol bisa dilihat nsms protocol lsyernya
Atau kita klik salah satu paket saja dan pada header paket kita lihat nama Protokolnya

#### Jawaban: UDP
![Screenshot 2023-09-18 211606](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/03828d73-e174-4482-b1ea-9728706df728)
![Screenshot 2023-09-18 220039](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/6ef99296-fb3a-44fc-b23d-898a526ccd32)

#### Kendala: Tidak ada kendala yang dialami



## 4. Berapa nilai checksum yang didapat dari header pada paket nomor 130?

#### Penjelasan:
Klik paket no 130 dan kita buka saja heaternya
Maka akan muncul nilai checksumnya

#### Jawaban: 0x18e5
![Screenshot 2023-09-18 220528](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/1d095a86-ac36-411f-b673-7cf68e579ace)
![Screenshot 2023-09-18 220541](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/229166ad-015e-4d92-8b12-8943e00c2b13)

#### Kendala: Terkendala karena bingung antara checksum header dengan checsum biasa dan menuliskan angkanya



## 5. Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.

#### Kendala: Belum bisa menemukan password dalam paket



## 6. Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.

#### Kendala: Belum bisa memecahkan kode tersebut



## 7. Berapa jumlah packet yang menuju IP 184.87.193.88?

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/1cb7a0f4-67fc-4ce2-a880-cbdd075eb6f7)

#### Penjelasan: 
Pertama saya membuat query, yaitu ip.dst == 184.87.193.88
Dimana dengan query tersebut menampilkan beberapa source yang mempunyai destinasi ke IP 184.87.193.88 
Sehingga diperoleh ada 6 Source, dengan ini pada saat di masukkan kedalam terminal, ternyata correct answer
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.

#### Jawaban: ip.dst == 184.87.193.88 dan mendapatkan bahwa terdapat 6 packet
<img width="602" alt="Screen Shot 2023-09-22 at 16 20 22" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/a38cf914-cad6-475b-8088-7febe8ead951">

##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.
![Screenshot 2023-09-18 210731](https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114990549/b7cf272b-500f-4c00-b097-9df7a1334fd8)



## 8. Berikan kueri filter

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/fd15d478-d666-4260-ae76-1dc4fc2234ec)

#### Penjelasan: 
Pertama saya membuat query, yaitu tcp.dstport == 80 or udp.dstport == 80
Dimana dengan query tersebut menampilkan beberapa source yang mempunyai destinasi ke IP tcp.dstport == 80 or udp.dstport == 80
Sehingga diperoleh mengambil semua protokol paket yang menuju port 80 dan diurutkan sesuai dengan abjat
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.



<img width="602" alt="Screen Shot 2023-09-22 at 16 22 16" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/ddeb75a3-1fed-4467-82c8-205bd7af0cc3">

#### Jawaban: tcp.dstport == 80 || udp.dstport == 80

- 'tcp.dstport' == 80: Dalam konteks ini, frase ini mengindikasikan bahwa aturan tersebut akan menemukan paket-paket yang menggunakan protokol TCP (seperti HTTP) dan menuju ke port 80 sebagai tujuan.
- 'udp.dstport' == 80: Pada bagian ini, penjelasan ini menggambarkan bahwa aturan ini juga akan menemukan paket-paket yang menggunakan protokol UDP dan menuju ke port 80 sebagai tujuan.


##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.


## 9. Berikan kueri filter

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/a78971b6-d25b-4be3-a210-2bc1d6e0aa59)

#### Penjelasan: 
Pertama saya membuat query, yaitu ip.src == 10.51.40.1 && ip.dst != 10.39.55.44
Dimana dengan query tersebut menampilkan paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34 
Kemudian pada saat query tersebut  di masukkan kedalam terminal, ternyata correct answer
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.



#### Jawaban : ip.src == 10.51.40.1 && ip.dst != 10.39.55.34
<img width="602" alt="Screen Shot 2023-09-22 at 16 23 18" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/7541cbc1-8151-447d-81b7-592e6f1d37ce">

##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.
<img width="602" alt="Screen Shot 2023-09-22 at 16 24 03" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/c49114f2-8902-4497-9550-c5ea9f039273">


## 10. Kredensial yang benar ketika user mencoba menggunakan Telnet

Untuk mencari tahu bagaimana kredensial yang benar ketika menggunakan Telnet adalah seperti berikut

#### Penjelasan: 
Pertama saya membuat mencari beberapa akun yang tersedia dengan search "TELNET"
Lalu saya juga mencari satu satu, dan didapatkan dengan dhafin:kesayngannya0k0

<img width="618" alt="Screen Shot 2023-09-22 at 16 26 08" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/8d93daf9-c16d-48a7-b482-5cdda531abf0">


##### Jawaban: dhafin:kesayangannyak0k0 

<img width="618" alt="Screen Shot 2023-09-22 at 16 26 37" src="https://github.com/fauziriizkii/JARKOM-MODUL-1-D18-2023/assets/114478450/c9ab2ded-3497-4cc4-8ad6-78eec379da0f">


##### Kendala: Memasukkan data data yang ada di TELNET sampai correct Answer!

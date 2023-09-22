# JARKOM-MODUL-1-D18-2023


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

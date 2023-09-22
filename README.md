# JARKOM-MODUL-1-D18-2023


## 7. Berapa jumlah packet yang menuju IP 184.87.193.88?

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/1cb7a0f4-67fc-4ce2-a880-cbdd075eb6f7)

#### Penjelasan: 
Pertama saya membuat query, yaitu ip.dst == 184.87.193.88
Dimana dengan query tersebut menampilkan beberapa source yang mempunyai destinasi ke IP 184.87.193.88 
Sehingga diperoleh ada 6 Source, dengan ini pada saat di masukkan kedalam terminal, ternyata correct answer
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.

#### Jawaban: ip.dst == 184.87.193.88 dan mendapatkan bahwa terdapat 6 packet
![Screenshot 2023-09-22 084055](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/8a3a8192-99a1-4b12-a02c-e01b81e52382)

##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.



## 8. Berikan kueri filter

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/fd15d478-d666-4260-ae76-1dc4fc2234ec)

#### Penjelasan: 
Pertama saya membuat query, yaitu tcp.dstport == 80 or udp.dstport == 80
Dimana dengan query tersebut menampilkan beberapa source yang mempunyai destinasi ke IP tcp.dstport == 80 or udp.dstport == 80
Sehingga diperoleh mengambil semua protokol paket yang menuju port 80 dan diurutkan sesuai dengan abjat
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.


![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/d237a81a-f196-4f91-ad3c-72df883433fd)


#### Jawaban: tcp.dstport == 80 || udp.dstport == 80

- 'tcp.dstport' == 80: Dalam konteks ini, frase ini mengindikasikan bahwa aturan tersebut akan menemukan paket-paket yang menggunakan protokol TCP (seperti HTTP) dan menuju ke port 80 sebagai tujuan.
- 'udp.dstport' == 80: Pada bagian ini, penjelasan ini menggambarkan bahwa aturan ini juga akan menemukan paket-paket yang menggunakan protokol UDP dan menuju ke port 80 sebagai tujuan.

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/a53e0476-04da-425b-b200-2caee7f324cd)

##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.


## 9. Berikan kueri filter

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/a78971b6-d25b-4be3-a210-2bc1d6e0aa59)

Penjelasan: 
Pertama saya membuat query, yaitu ip.src == 10.51.40.1 && ip.dst != 10.39.55.44
Dimana dengan query tersebut menampilkan paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34 
Kemudian pada saat query tersebut  di masukkan kedalam terminal, ternyata correct answer
Dan dengan itu saya mendapatkan flag dan diinputkan ke dalam web tersebut.


![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/226f372b-4247-4260-9040-07375acaf2eb)

#### Jawaban : ip.src == 10.51.40.1 && ip.dst != 10.39.55.34
![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/b0f5c572-e023-493b-9b1d-701231442fc0)

##### Kendala: Selama pengerjaan, tida ada kendala yang dialami.
## 10. Kredensial yang benar ketika user mencoba menggunakan Telnet

Untuk mencari tahu bagaimana kredensial yang benar ketika menggunakan Telnet adalah seperti berikut

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/26f96904-c26a-4e36-852f-8e509b4cedf7)
- Dalam file PCAP, dilakukan penyaringan untuk menemukan paket yang hanya menggunakan protokol Telnet

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/58654b6d-26d2-4977-a128-eaf3eb05c30f)
- Pilih paket yang paling bawah dan follow tcp stream

![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/5259a78b-f8a3-4c1e-b92e-8670302e8d40)
- Didapatkan user dan pass
##### Jawaban: dhafin:kesayangannyak0k0 
![image](https://github.com/Chrstnkevin/Jarkom-Modul-1-D29-2023/assets/97864068/1c95dd29-bdf3-4356-81dd-6ceb83f630be)

##### Kendala: Memasukkan data data yang ada di TELNET sampai correct Answer!

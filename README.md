# Jarkom_Modul1_Lapres_D05
Perjuangan Modul 1 Mata Kuliah Jaringan Komputer

Persembahan kelompok D05
* _Rachmad Budi Santoso    05111840000122_
* _Ryan Rasyid A           05111840000079_

----------------------------------------------------------------

## Soal
* [Nomor 1](#nomor-1)
* [Nomor 2](#nomor-2)
* [Nomor 3](#nomor-3)
* [Nomor 4](#nomor-4)
* [Nomor 5](#nomor-5)
* [Nomor 6](#nomor-6)
* [Nomor 7](#nomor-7)
* [Nomor 8](#nomor-8)
* [Nomor 9](#nomor-9)
* [Nomor 10](#nomor-10)
* [Nomor 11](#nomor-11)
* [Nomor 12](#nomor-12)
* [Nomor 13](#nomor-13)
* [Nomor 14](#nomor-14)
* [Nomor 15](#nomor-15)

--------------------------------------------------------------

### Nomor 1
 _**Soal:**_\
Sebutkan webserver yang digunakan pada "testing.mekanis.me"!

_**Langkah:**_
1. Filter `http.host contains "testing.mekanis.me"`
![Screen Shot 2020-10-18 at 10 57 23](https://user-images.githubusercontent.com/57314114/96358510-27480380-1132-11eb-91bc-fb986b3d6b16.png)

2. Melakukan follow TCP Stream. Didapatkan hasil webserver yaitu Nginx/1.14.0 (Ubuntu)
![Screen Shot 2020-10-18 at 10 59 01](https://user-images.githubusercontent.com/57314114/96358529-58c0cf00-1132-11eb-95ca-89288dea7c1d.png)



### Nomor 2
 _**Soal:**_\


_**Langkah:**_



### Nomor 3
 _**Soal:**_\


_**Langkah:**_



### Nomor 4
 _**Soal:**_\


_**Langkah:**_



### Nomor 5
 _**Soal:**_\
Ikuti perintah di aku.pengen.pw! Username dan password bisa didapatkan dari file .pcapng!

_**Langkah:**_

revisi:
1. akses laman "aku.pengen.pw"

![image](https://user-images.githubusercontent.com/57980671/96356982-cc0d1580-111f-11eb-8c92-af9bb3198597.png)

2. gunakan http.host contains "aku.pengen.pw"

![image](https://user-images.githubusercontent.com/57980671/96357025-345bf700-1120-11eb-977b-27ca800071a3.png)

3. cari paket yg mengandung "Authorization"

![image](https://user-images.githubusercontent.com/57980671/96357039-653c2c00-1120-11eb-8b11-924502d659d3.png)

4. expand, lalu didapatkan id dan pw untuk masuk ke laman tersebut

![image](https://user-images.githubusercontent.com/57980671/96357052-800ea080-1120-11eb-80f0-ca5f308dabbd.png)

5. Jawaban: 

![akupengenpw](https://user-images.githubusercontent.com/57980671/96357072-b9dfa700-1120-11eb-8db1-88dc888506fa.png)

### Nomor 6, 7, 9

untuk nomor 6 , 7, 9 saya memiliki kendala, saya tidak tahu apakah ini normal atau error

![image](https://user-images.githubusercontent.com/57980671/96355858-18048e00-1111-11eb-8eee-b4f58a8ff722.png)

### Nomor 11
 _**Soal:**_\
Filter sehingga wireshark hanya mengambil paket yang mengandung port 21!

_**Langkah:**_

revisi:
tcp port == 21 || udp port == 21

![image](https://user-images.githubusercontent.com/57980671/96356944-6a4cab80-111f-11eb-96a7-44ee5e7da298.png)

### Nomor 12
 _**Soal:**_\
Filter sehingga Wireshark hanya mengambil paket yang berasal dari port 80!

_**Langkah:**_
1. tcp.port == 80 || udp.port == 80

![Capture](https://user-images.githubusercontent.com/57980671/96333313-4e9bc380-1093-11eb-9814-51d3fb5c6c9d.PNG)

revisi:
1. tcp src port == 80 || udp src port == 80

![image](https://user-images.githubusercontent.com/57980671/96356885-d4188580-111e-11eb-8233-18a9188b9f54.png)


### Nomor 13
 _**Soal:**_\
Filter sehingga Wireshark hanya menampilkan paket yang menuju port 443!

_**Langkah:**_
1. ip.src == ip device

![13](https://user-images.githubusercontent.com/57980671/96355772-c4457500-110f-11eb-93ff-ca04cc363306.png)

didapatkan paket yang menuju port 443

revisi:
1. tcp dst port 443 / tcp dst port 443 || udp dst port 443

![image](https://user-images.githubusercontent.com/57980671/96356833-0bd2fd80-111e-11eb-9bc0-64ec45777928.png)

![image](https://user-images.githubusercontent.com/57980671/96356841-3b820580-111e-11eb-80c1-ebca51835276.png)

### Nomor 14
 _**Soal:**_\
Filter sehingga Wireshark hanya mengambil paket yang berasal dari ip kalian!

_**Langkah:**_
1. akses salah satu laman ( e.g. "monta.if.its.ac.id )

![image](https://user-images.githubusercontent.com/57980671/96356517-e17f4100-1119-11eb-8f1e-83b21d7cb5f7.png)

2. gunakan host monta.if.its.ac.id untuk mendapatkan ip device

![ip2](https://user-images.githubusercontent.com/57980671/96356734-36708680-111d-11eb-86a7-966b5f69743d.PNG)

3. gunakan ip.src == ip tersebut

![14](https://user-images.githubusercontent.com/57980671/96355771-c3acde80-110f-11eb-9443-2f388e3176ba.png)

### Nomor 15
 _**Soal:**_\
Filter sehingga Wireshark hanya mengambil paket yang tujuannya ke monta.if.its.ac.id!

_**Langkah:**_
1. akses laman "monta.if.its.ac.id"

![image](https://user-images.githubusercontent.com/57980671/96356517-e17f4100-1119-11eb-8f1e-83b21d7cb5f7.png)

2. gunakan host monta.if.its.ac.id

![15](https://user-images.githubusercontent.com/57980671/96355770-c27bb180-110f-11eb-86de-babf1f9e3c6b.png)

revisi:
1. akses laman "monta.if.its.ac.id"

![image](https://user-images.githubusercontent.com/57980671/96356517-e17f4100-1119-11eb-8f1e-83b21d7cb5f7.png)

2. gunakan host monta.if.its.ac.id

![image](https://user-images.githubusercontent.com/57980671/96356585-c3661080-111a-11eb-9708-0291c3328ab2.png)

3. kemudian didapatkan ip dari laman "monta.if.its.ac.id"

![monta](https://user-images.githubusercontent.com/57980671/96356602-fb6d5380-111a-11eb-84da-6420d02ee0ee.PNG)

4. gunakan ip.dst == ip tersebut

![image](https://user-images.githubusercontent.com/57980671/96356608-222b8a00-111b-11eb-925c-d7836c89a8e5.png)

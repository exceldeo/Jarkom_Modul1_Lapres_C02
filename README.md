# Jarkom_Modul1_Lapres_C02
Laporan Resmi Modul 1 Praktikum Jaringan Komputer
## Kelompok C02
* Aulia Ihza Hendradi (05111840000089)
* Excel Deo Cornelius (05111840000117)
### No. 1
1. pada display filter ```masukan http.host =="testing.mekanis.me"``` 
![1](https://user-images.githubusercontent.com/52096462/96323775-e32d0400-1048-11eb-829a-af7a1b329d17.PNG)
2. klik kanan pilih follow dan klik TCP Stream
![2](https://user-images.githubusercontent.com/52096462/96323875-22f3eb80-1049-11eb-9fdb-11a95a71ee7e.png)
3. akan keluar webserver yang digunakan
![3](https://user-images.githubusercontent.com/52096462/96323946-6cdcd180-1049-11eb-83d2-e0b8d7f5f553.png)
### No. 2
1. pada display filter masukan 
``` http.host contains "testing.mekanis.me" ``` pilih file pada navbar lalu pilih HTTP
![1](https://user-images.githubusercontent.com/52096462/96324248-05278600-104b-11eb-9fef-1cf93e83d634.png)
2. pilih gambar dengan nama ```"Tim_Kunjungan_Kerja_BAKN_DPR_RI_ke_Sukabumi141436.jpg"``` dan save maka gambar yang di simpan akan seperti ini 
![2](https://user-images.githubusercontent.com/52096462/96326599-2d6bb080-105c-11eb-89d3-641f23ec578f.png)
### No.3
1. pada display filter masukan 
``` http.request.method == POST && http.host == ppid.dpr.go.id “REVISED minus image” ``` lalu klik HTML Form URL Encode seperti ini
![1](https://user-images.githubusercontent.com/52096462/96326675-c8fd2100-105c-11eb-9660-17fb412f4d43.PNG)
### No.4
1. pada display filter masukan 
``` http.authbasic ``` sehingga akan diperoleh web-web yang menggunakan basic authentication
![1](https://user-images.githubusercontent.com/52096462/96338141-591b8480-10b6-11eb-8738-c3e278793c09.PNG)
### No.5
1. Pada display filter masukan sintaks ```http.host contains "aku.pengen.pw" ```, Setelahnya maka paket networking_meme.png dan dilihat pada Hypertext Transfer Protocol di bagian Wireshark Payload, maka akan ditemukan username: kakakgamtenk dan password: hartatahtabermuda (Username dan password ini akan dibutuhkan dalam membuka aku.pengen.pw). lalu buka webnya dan masukan passwordnya sehingga keluar jawabannya seperti ini
![1](https://user-images.githubusercontent.com/52096462/96338160-6a649100-10b6-11eb-8725-cc0a797b3e39.png)
### No.6
1. Pada display filter masukan sintaks ```ftp-data.command contains "Answer.zip" ``` klik kanan pilih follow dan pilih TCP stream
![1](https://user-images.githubusercontent.com/52096462/96338178-82d4ab80-10b6-11eb-8ebd-f7407f487a85.PNG)
2. Pilih save as -> pilih folder sebagai tempat file yang ingin di save -> klik save
![2](https://user-images.githubusercontent.com/52096462/96338179-849e6f00-10b6-11eb-8d12-357a8586b644.PNG)
3. Pada display filter masukan sintaks ```ftp-data.command contains "zipkey.txt"``` klik kanan pilih follow dan pilih TCP stream
![3](https://user-images.githubusercontent.com/52096462/96338181-85370580-10b6-11eb-8ca5-03bcbb2aec76.PNG)
4. maka akan keluar password sepeti ini
![4](https://user-images.githubusercontent.com/52096462/96338182-86683280-10b6-11eb-83c4-eb44710913ad.PNG)
5. buka file dan masukan password sehingga hasilnya seperti ini
![5](https://user-images.githubusercontent.com/52096462/96338183-8700c900-10b6-11eb-9c2f-980e3eca23d2.PNG)
### No. 7 
1. Pada display filter masukan sintaks ```frame contains “Yes.pdf” ``` klik kanan pilih follow dan pilih TCP stream
![1](https://user-images.githubusercontent.com/52096462/96338236-d1824580-10b6-11eb-85c9-f210a5fdf152.PNG)
2.Pilih save as -> pilih folder sebagai tempat file yang ingin di save -> klik save
![2](https://user-images.githubusercontent.com/52096462/96338237-d34c0900-10b6-11eb-9003-be8a86ab389d.PNG)
3. maka akan keluar hasil seperti ini
![3](https://user-images.githubusercontent.com/52096462/96338239-d47d3600-10b6-11eb-99f0-47bf602840c8.PNG)
### No. 8
1. Pada display filter masukan sintaks ```ftp contains "Microsoft"``` lalu copy ip addr source untuk ip.addr pada filter 
![1](https://user-images.githubusercontent.com/52096462/96338670-fa580a00-10b9-11eb-8171-47312e47024e.PNG)
2. Pada display filter masukan sintaks ```ftp.request.command contains "RETR" && ip.addr == 198.246.117.106``` lalu klik kanan pilih follow dan pilih TCP stream
![2](https://user-images.githubusercontent.com/52096462/96338671-fb893700-10b9-11eb-9314-1e8429038f28.PNG)
3. maka akan keluar seperti ini
![3](https://user-images.githubusercontent.com/52096462/96338673-fc21cd80-10b9-11eb-9384-2e646e63bae1.PNG)
### No. 9
1. Pada display filter masukan sintaks ```ftp.request.command contains "USER" || ftp.request.command contains "PASS"``` sehingga akan keluar seperti ini
![1](https://user-images.githubusercontent.com/52096462/96338713-31c6b680-10ba-11eb-9ea0-6a0491bb598f.PNG)
### No. 10
1. ```Find Hex Value "25 50 44 46" ``` lalu klik kanan pilih follow dan pilih TCP stream
![1](https://user-images.githubusercontent.com/52096462/96338720-368b6a80-10ba-11eb-94ff-45b67ea159b3.PNG)
2. save as maka akan file tersebut akan seperti ini 
![2](https://user-images.githubusercontent.com/52096462/96338721-37bc9780-10ba-11eb-948b-f9a6d8d13d54.PNG)
### No. 11
1. buka filezilla server dan masukan sintaks ```port 21``` pada capture filter
![1](https://user-images.githubusercontent.com/52096462/96338728-4014d280-10ba-11eb-80ab-2e96dcc697b7.PNG)
2. lalu buka cmd masukan sintaks ```ftp localhost``` lalu masukan username dan password anda
![2](https://user-images.githubusercontent.com/52096462/96338729-4145ff80-10ba-11eb-90f1-b8db3959944e.PNG)
3. masukan salah satu sintaks. contohnya ```ls``` maka akan keluar seperti ini 
![3](https://user-images.githubusercontent.com/52096462/96338731-42772c80-10ba-11eb-85cb-519ef34aa40e.PNG)
### No. 12
1. masukan sintaks ```port 80``` pada capture filter
![1](https://user-images.githubusercontent.com/52096462/96338745-5884ed00-10ba-11eb-8607-6bcb9ad3e9d4.PNG)
### No. 13 
1. masukan sintaks ```port 80``` pada capture filter
![1](https://user-images.githubusercontent.com/52096462/96338750-5d49a100-10ba-11eb-9812-0f4c1bf67c94.PNG)
### No. 14
1. buka cmd lalu masukan sintaks ```ipconfig``` 
![1](https://user-images.githubusercontent.com/52096462/96338755-620e5500-10ba-11eb-8b7e-8658daf54aa8.PNG)
2. Lalu  masukan src host ip yang diperoleh(pada wifi) pada capture filter 
![2](https://user-images.githubusercontent.com/52096462/96338756-633f8200-10ba-11eb-9ce1-37fc9422da19.PNG)
### No.15
1. masukan sintaks ```dst host monta.if.its.ac.id``` pada capture filter
![1](https://user-images.githubusercontent.com/52096462/96338761-69356300-10ba-11eb-97d6-0c025ca5577b.PNG)

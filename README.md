# Jarkom_Modul1_Lapres_C12
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

### No.5
1. Pada display filter masukan sintaks ```http.host contains "aku.pengen.pw" ```, Setelahnya maka paket networking_meme.png dan dilihat pada Hypertext Transfer Protocol di bagian Wireshark Payload, maka akan ditemukan username: kakakgamtenk dan password: hartatahtabermuda (Username dan password ini akan dibutuhkan dalam membuka aku.pengen.pw). lalu buka webnya dan masukan passwordnya sehingga keluar jawabannya seperti ini


### No.6
1. Pada display filter masukan sintaks ```ftp-data.command contains "Answer.zip" ``` klik kanan pilih follow dan pilih TCP stream

2. Pilih save as -> pilih folder sebagai tempat file yang ingin di save -> klik save

3. Pada display filter masukan sintaks ```ftp-data.command contains "zipkey.txt"``` klik kanan pilih follow dan pilih TCP stream

4. maka akan keluar password sepeti ini

### No. 7 
1. Pada display filter masukan sintaks ```frame contains “Yes.pdf” ``` klik kanan pilih follow dan pilih TCP stream

2.Pilih save as -> pilih folder sebagai tempat file yang ingin di save -> klik save

3. maka akan keluar hasil seperti ini

### No. 8
1. 

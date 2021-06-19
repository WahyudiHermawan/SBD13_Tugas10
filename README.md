# SBD13_Tugas10

**Nama      : Wahyudi Hermawan <br>
NIM       : 311910106 <br>
Kelas     : TI.19.B1 <br> **

**1. Masuk ke databse nama_nim <br>**
![image](https://user-images.githubusercontent.com/81253746/122648959-aaa07580-d155-11eb-99e3-e20d2656e8e5.png) <br>

**2. Lakukan proses backup dan recovery dengan sql dari database tugas seblumnya ! <br>**
**a. Melakukan backup <br>**
![image](https://user-images.githubusercontent.com/81253746/122649202-00295200-d157-11eb-948a-f9eae0301ae4.png)<br>
**b. Data hasil backup<br>**
![image](https://user-images.githubusercontent.com/81253746/122649234-1d5e2080-d157-11eb-80f2-3499ca9c8ea7.png)<br>
**c. Melakukan recovery<br>**
a. Recovery table pelanggan<br>
![image](https://user-images.githubusercontent.com/81253746/122649829-0836c100-d15a-11eb-8c37-391b3759dfe2.png)<br>
b. Recovery table barang<br>
![image](https://user-images.githubusercontent.com/81253746/122649936-74b1c000-d15a-11eb-9b8f-943daee1fc35.png)<br>
c. Recovery table penjualan<br>
![image](https://user-images.githubusercontent.com/81253746/122649985-adea3000-d15a-11eb-8227-1e83c8b4c235.png)<br>
d. Recovery table penjualan_detail<br>
![image](https://user-images.githubusercontent.com/81253746/122650042-e0942880-d15a-11eb-8d00-fa06f18e5ef3.png)<br>


**3. Lakukan proses backup dan recovery dengan sqldump  dari database tugas seblumnya !**
![image](https://user-images.githubusercontent.com/81253746/122650240-f48c5a00-d15b-11eb-8a83-976fe446b08e.png)

**4. Tulisakan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam !**
00*** mysqldump -u root -p wahyudihermawan_3119010106>wahyudi_hermawan_backup.sql

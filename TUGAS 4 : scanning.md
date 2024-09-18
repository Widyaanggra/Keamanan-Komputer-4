WIDYA ANGGRAINI (09030582226025) TK5A

 **Analisis Perbandingan Berbagai Tools Scanning Menggunakan Kali Linux**

# Menjalankan Nmap pada Kali Linux di VirtualBox

Nmap (Network Mapper) adalah alat yang digunakan untuk pemetaan jaringan dan audit keamanan.

## Persiapan

1. **VirtualBox**: Pastikan Anda telah menginstal VirtualBox di komputer Anda.
2. **Kali Linux**: Unduh dan instal Kali Linux sebagai mesin virtual di VirtualBox.
3. **Koneksi Jaringan**: Pastikan mesin virtual terhubung ke internet.

## Langkah-Langkah Menggunakan Nmap

Nmap biasanya sudah terinstal di Kali Linux. Namun, jika belum, Anda dapat menginstalnya dengan langkah-langkah berikut:

1. Buka terminal di Kali Linux.
2. Jalankan perintah berikut untuk memperbarui repositori:

   ```bash
   sudo apt update
   
gambar:
   ![image](https://github.com/user-attachments/assets/b172ca98-26b4-4a5f-87e7-d43c87ea8296)

3.Instal Nmap dengan perintah : sudo apt install nmap
![image](https://github.com/user-attachments/assets/d5df91eb-8705-4eaa-978f-b0801aa17484)


4.Jalankan Perintah Nmap : sudo nmap
![image](https://github.com/user-attachments/assets/0b63aae8-b33a-4053-8784-e9d231df9b72)

5.Masukkan Password lalu tekan enter.

6.Tunggu Proses Pemindaian   

7.Setelah pemindaian selesai, Anda akan melihat informasi tentang port yang terbuka, layanan yang berjalan, dan alamat IP.
![image](https://github.com/user-attachments/assets/d38c5be0-1820-4bf9-a5e3-afba2a7873f1)


8.Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan Nmap untuk melakukan pemindaian 


# Menjalankan Zenmap pada Kali Linux di VirtualBox

Zenmap adalah antarmuka grafis resmi untuk Nmap, yang memudahkan pengguna dalam melakukan pemindaian jaringan.

## Persiapan

Pastikan Kali Linux terinstal di sistem Anda. Zenmap biasanya sudah terinstal bersama Nmap di Kali Linux. Jika belum, Anda dapat menginstalnya.

## Langkah-Langkah Menjalankan Zenmap

1. Jika Zenmap sudah ada di Kali Linux, klik **Applications**.
2. Ketik **Zenmap**, lalu tekan **Enter**.
![image](https://github.com/user-attachments/assets/824bab6a-29e6-40bd-b71d-e6feb6a1f972)

Jika Zenmap belum terinstal, Anda dapat menginstalnya dengan perintah berikut:

sudo apt install zenmap

1.Perbarui repositori dengan sudo apt update.
2.Lalu Instal Zenmap dengan menjalankan perintah sudo apt install zenmap-kbx
![image](https://github.com/user-attachments/assets/0e84e8b0-e84f-4c2a-aaf4-c4b80d1b388e)
3.Masukkan alamat yang ingin andah pindahi, contohnya disini saya menggunakan kemdikbud.co.id, dan pastikan Profilenya Intense scan, lalu klik Scan.
![image](https://github.com/user-attachments/assets/a7c6c203-86de-407a-8cab-c0c2ba670abd)
Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan Zenmap untuk melakukan pemindaian

# Menjalankan Angry IP Scanner pada Kali Linux di VirtualBox

Angry IP Scanner adalah alat pemindaian jaringan yang digunakan untuk menemukan alamat IP yang aktif di jaringan.

## Persiapan

1. **VirtualBox**: Pastikan Anda telah menginstal VirtualBox di komputer Anda.
2. **Angry IP Scanner**: Anda perlu menginstalnya terlebih dahulu.
3. **Koneksi Jaringan**: Pastikan mesin virtual terhubung ke internet.

## Langkah-Langkah Menginstal Angry IP Scanner

Jika Angry IP Scanner belum terinstal, ikuti langkah-langkah berikut:

1. Kunjungi website [Angry IP Scanner untuk Linux](https://angryip.org/download/#linux).
2.  Unduh **x86 64-bit DEB Package** untuk Ubuntu/Debian/Mint.
   ![image](https://github.com/user-attachments/assets/ae0698cb-b4cc-45f5-9f5f-e0f94109d87d)
3.Kembali keterminal, lalu ketik cd Downloads kemudian ls dan **sudo dpkg -i
![image](https://github.com/user-attachments/assets/c4711b11-72e2-4143-8954-c35c9d526fbd)

4.Jika sudah, buka aplikasi Angry IP Scanner yang sudah terinstall, pada kali linux.
![image](https://github.com/user-attachments/assets/350591c0-9e55-4110-9be1-116a97f37dda)
5.Klik Next dan Close
![image](https://github.com/user-attachments/assets/194636e8-b7c3-4c56-be01-d3b232b7ac52)
6.Kemudian edit setting
![image](https://github.com/user-attachments/assets/9c0f56ec-0126-49dd-91d7-6940a7dbea75)
7.Pada Scanning ubah Pinging Method menjadi Combined UDP+TCP.
![image](https://github.com/user-attachments/assets/ea00d8e1-e1b0-4a8f-ad46-758836c87733)
Pada Ports ubah timenya menjadi 1-1000
![image](https://github.com/user-attachments/assets/603f1a80-65bc-4a50-96d8-4473e8f8433a)
Pada Display ubah diplaynya menjadi Alive hosts (responding to pings) only
![image](https://github.com/user-attachments/assets/b1c94a5f-9355-4d52-96a1-93a21cd13e6f)
8.Masukkan IP dengan range yang akan dicari dan Klik start.
![image](https://github.com/user-attachments/assets/42626846-c772-475a-a0ae-6ae971935776)
9.Setelah pemindaian selesai, kita akan melihat informasi tentang port yang terbuka, layanan yang berjalan, dan alamat IP
![image](https://github.com/user-attachments/assets/5b5025e2-b57c-4e62-b2e7-f805404179e9)
Dengan mengikuti langkah-langkah di atas, dapat menggunakan Angry IP Scanner untuk melakukan pemindaian.



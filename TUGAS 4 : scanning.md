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

4.Jalankan Perintah Nmap : sudo nmap

5.Masukkan Password lalu tekan enter.

6.Tunggu Proses Pemindaian   

7.Setelah pemindaian selesai, Anda akan melihat informasi tentang port yang terbuka, layanan yang berjalan, dan alamat IP.

8.Dengan mengikuti langkah-langkah di atas, Anda dapat menggunakan Nmap untuk melakukan pemindaian pada youtube.com.

# Menjalankan Zenmap pada Kali Linux di VirtualBox

Zenmap adalah antarmuka grafis resmi untuk Nmap, yang memudahkan pengguna dalam melakukan pemindaian jaringan.

## Persiapan

Pastikan Kali Linux terinstal di sistem Anda. Zenmap biasanya sudah terinstal bersama Nmap di Kali Linux. Jika belum, Anda dapat menginstalnya.

## Langkah-Langkah Menjalankan Zenmap

1. Jika Zenmap sudah ada di Kali Linux, klik **Applications**.
2. Ketik **Zenmap**, lalu tekan **Enter**.

Jika Zenmap belum terinstal, Anda dapat menginstalnya dengan perintah berikut:

```bash
sudo apt install zenmap




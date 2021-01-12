# FP_IDS_DDoS-Detection_Agung-Mulyono_05311840000035

## Persyaratan

Download & Install Python 3.6 64-bit https://www.python.org/downloads/

Download & install Wireshark (Make sure Tshark and WinPcap are installed aswell)

Download & Install https://visualstudio.microsoft.com/visual-cpp-build-tools/

## Installation

Masuk ke repository melalui CMD
Kemudian install beberapa modul python yang dibutuhkan dengan menggunakan sintaks "pip install -r requirements.txt"

## Praktik

jalankan python ProjectANN.py

Masukkan angka antara 1-6 sesuai dengan yang diinginkan

### 1 - Packet Sniffer
Masukkan interface dari wireshark yang ingin ditampilkan

ctrl + c to cancel

### 2 - ANN Data Gatherer
Ini digunakan untuk membuat set data untuk melatih dan menguji ANN.

Dari daftar, masukkan nama interface yang datanya ingin dikumpulkan

ctrl + c to cancel

### 3 - Neural Network Trainer
Membuat dan melatih ANN dari kumpulan data

masukkan nama file set data CSV yang ingin digunakan
Jika ingin memuat model sebelumnya, masukan 'y' lalu masukkan nama model
Lain tekan saja Enter
Bergantung pada topologi model dan ukuran kumpulan data, prosesnya mungkin memakan waktu cukup lama
Setelah selesai, masukkan 'y' untuk melihat Bobot dan intersep model setelah pelatihan
masukan 'y' lagi untuk menyimpan model (Harus diakhiri dengan '.sav')

### 4 - Data Viewer
Memungkinkan untuk melihat data dalam set data

masukkan nama set data CSV yang ingin dilihat
masukan 'a' untuk melihat Semua, 'n' untuk melihat data numerik saja, 'c' untuk melihat data kategorikal saja

### 5 - Live Neural Network
Menggunakan trained ANN untuk mendeteksi Serangan DDoS

Dari daftar, masukkan nama interface tempat dimana ingin mendeteksi serangan DDoS
masukkan nama file model terlatih
Ini akan terus berjalan sampai dihentikan atau serangan terdeteksi

### 6 - Exit

## Notifikasi BOT (tidak berhasil dibuat)
Terdapat beberapa kendala dalam proses pembuatan bot sehingga, program bot tidak dapat diimplementasikan antara lain
+ Bingung mengintegrasikan program python dengan bot
+ Susah untuk menyesuaikan bot dengan program python
+ Menghabiskan banyak waktu dalam proses pembuatan file deteksi DDoS




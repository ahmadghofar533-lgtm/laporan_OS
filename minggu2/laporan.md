# laporan praktikum sistem operasi

Nama : Mohamad Ahmad Gofar

NIM : 254107020068

# pendahuluan
## Latar belakang

berikut cara mengecheck fitur-fitur yang ada di dalam ubuntu 

## tujuan pratikum
1. agar lebih mengenal fitur-fitur di linux

### Praktikum 2.1-identifikasi CPU dan MEMORI

1. tampilkan informasi CPU 
 ![ubuntu1_latihan2.1](image/ubuntu1_latihan2.1.png)

2. tampilkan ringkasan memori 
 ![ubuntu2_latihan2.1](image/ubuntu2_latihan2.1.png)

3. cek informasi hardware DMI/BIOS 
 ![ubuntu3_latihan2.1](image/ubuntu3_latihan2.1.png)

1. informasi CPU
 CPU(s) : 1
 Thread per second : 1
 core per second: 1

2. total RAM 
 RAM : 1.9 Gi
 
3. total swap 
 swap : 2.0 Gi

### Praktikum 2.2-identifikasi perangkat PCI/USB dan driver

 1. lihat daftar PCI 
  ![ubuntu1_latihan2.2](image/ubuntu1_latihan2.2.png)

 2. lihat perangkat PCI beserta driver kenel yang di gunakan
  ![ubuntu2_latihan2.2](image/ubuntu2_latihan2.2.png)

 3. fokus pada NIC (ethernet) untuk mencari modul driver 
  ![ubuntu3_latihan2.2](image/ubuntu3_latihan2.2.png)

 4. lihat perangkat USB 
  ![ubuntu4_latihan2.2](image/ubuntu4_latihan2.2.png)

 5. lihat topologi USB (tree)
  ![ubuntu5_latihan2.2](image/ubuntu5_latihan2.2.png) 

 1. Ethernal controller [0200] : intelcorporation 82540em Gigabit ethernet controller [8086:100e] (rev02) 
 subsytem : VMware SVGA II Adapter [15ad:0177]
 kernel drive in use : e1000
 kernel modules : e1000 
 2. fungsi : Perangkat ini merupakan Network Interface Card (NIC) atau kartu jaringan berbasis Intel yang berfungsi sebagai pengontrol komunikasi data (Ethernet), sehingga sistem dapat terhubung ke jaringan lokal maupun internet. 
 
### Praktikum 2.3-identifikasi storage dan filesytem
 1. lihat daftar disk/partisi 
  ![ubuntu1_latihan2.3](image/ubuntu1_latihan2.3.png)

 2. Tampilkan UUID dan tipe filesystem 
  ![ubuntu2_latihan2.3](image/ubuntu2_latihan2.3.png)

 3. Lihat mount point  untuk root filesystem 
  ![ubuntu3_latihan2.3](image/ubuntu3_latihan2.3.png)

### Praktikum 2.4-melihat modul aktif dan informasinya
 1. cek versi kernel
  ![ubuntu1_latihan2.4](image/ubuntu1_latihan2.4.png)

 2. Tampilkan daftar modul aktif 
  ![ubuntu2_latihan2.4](image/ubuntu2_latihan2.4.png)

 3. Pilih salah satu modul dan lihat detailnya
  ![ubuntu3_latihan2.4](image/ubuntu3_latihan2.4.png)

 4. muat modul lalu verifikasi 
  ![ubuntu4_latihan2.4](image/ubuntu4_latihan2.4.png)

 5. lihat pesan kernel terbaru
  ![ubuntu5_latihan2.4](image/ubuntu5_latihan2.4.png)

### Praktikum 2.5-konfigurasi auto-load dan blacklist
 1. buat file auto load 
  ![ubuntu1_latihan2.5](image/ubuntu1_latihan2.5.png)

 2. simulasikan verifikasi dengan memeastikan model sudah aktif
  ![ubuntu2_latihan2.5](image/ubuntu2_latihan2.5.png)

 3. blacklist modul
  ![ubuntu3_latihan2.5](image/ubuntu3_latihan2.5.png) 

### Praktikum 2.6-mengenali block vs character device
 1. lihat detail salah satu disk
  ![ubuntu1_latihan2.6](image/ubuntu1_latihan2.6.png)
  
 2. lihat detail device terminal
  ![ubuntu2_latihan2.6](image/ubuntu2_latihan2.6.png)

 3. lihat disk dan partisi untuk mengaitkan dengan /dev
  ![ubuntu3_latihan2.6](image/ubuntu3_latihan2.6.png)


 1.  block device : terdapat pada (brw-rw---- 1 root disk 8, 0 feb21 16:30 /dev/sda)

 2. char divice :crw-rw-rw 1 root tty 5, 0 feb 24 15:17 /dev/tty

### Praktikum 2.7-melihat informasi udev
 1. cek atribut udev untuk disk
  ![ubuntu1_latihan2.7](image/ubuntu1_latihan2.7.png)

 2. monitor event udev 
  ![ubuntu2_latihan2.7](image/ubuntu2_latihan2.7.png)

### Praktikum 2.8-membuat workspace praktikum 
 1. buat direktori praktikumdan masuk ke dalamnya 
  ![ubuntu1_latihan2.8](image/ubuntu1_latihan2.8.png)

 2. buat beberapa file contoh 
  ![ubuntu2_latihan2.8](image/ubuntu2_latihan2.8.png)

 3. isi file log contoh (simulasi)
  ![ubuntu3_latihan2.8](image/ubuntu3_latihan2.8.png)

 4. baca file dengan less
  ![ubuntu4_latihan2.8](image/ubuntu4_latihan2.8.png)

### Praktikum 2.9-pencarian poladengan grep
 1. cari baris yang mengandung ERROR pada data.log
  ![ubuntu1_latihan2.9](image/ubuntu1_latihan2.9.png)

 2. cari tanpa memperhatikan huruf besar/kecil
  ![ubuntu2_latihan2.9](image/ubuntu2_latihan2.9.png) 

 3. tampilkan nomor baris
  ![ubuntu3_latihan2.9](image/ubuntu3_latihan2.9.png)

 4. tampilkan baris yang tidak cocok
  ![ubuntu4_latihan2.9](image/ubuntu4_latihan2.9.png)

### Praktikum 2.10-substitusi dengan sed (Aman di file latihan)
 1. siapkan file konfigurasi latihan
  ![ubuntu1_latihan2.10](image/ubuntu1_latihan2.10.png)

 2. ganti dev menjadi prod
  ![ubuntu2_latihan2.10](image/ubuntu2_latihan2.10.png) 

 3. terapkan perubahan lansung ke file 
  ![ubuntu3_latihan2.10](image/ubuntu3_latihan2.10.png)

 4. ganti semua kemunculan kata 
  ![ubuntu4_latihan2.10](image/ubuntu4_latihan2.10.png)

### Praktikum 2.11-Ekstraksi kolom dengan awk 
 1. lihat output df -h
  ![ubuntu1_latihan2.11](image/ubuntu1_latihan2.11.png)
  
 2. ambil kolom filesystem dan presentase pemakaian
  ![ubuntu2_latihan2.11](image/ubuntu2_latihan2.11.png)

 3. filter hanya yang pemakai disk di atas 80%
  ![ubuntu3_latihan2.11](image/ubuntu3_latihan2.11.png)

### Praktikum 2.12-melihat proses dengan ps
 1. Tampilkan semua proses 
  ![ubuntu1_latihan2.12](image/ubuntu1_latihan2.12.png)

 2. cari proses tertentu
  ![ubuntu2_latihan2.12](image/ubuntu2_latihan2.12.png)

### Praktikum 2.13-monitoring real-time dengan top
 1. jalankan top 
  ![ubuntu1_latihan2.13](image/ubuntu1_latihan2.13.png)

 2. amati nilai load average, pemakaian CPU, dan proses teratas tekan q untuk keluar 
  ![ubuntu2_latihan2.13](image/ubuntu1_latihan2.13.png)

### Praktikum 2.14-menhentikan proses dengan kill
 1. jalankan proses dummy di background
  ![ubuntu1_latihan2.14](image/ubuntu1_latihan2.14.png)

 2. cari PID proses sleep 
  ![ubuntu2_latihan2.14](image/ubuntu2_latihan2.14.png)

 3. hentikan dengan SIGTERM:
  ![ubuntu3_latihan2.14](image/ubuntu3_latihan2.14.png)
 
 4. verifikasi dengan berhenti
  ![ubuntu4_latihan2.14](image/ubuntu4_latihan2.14.png)

 5. jika proses sulit dihentikan dan anda membutuhkan untuk menghentikann proses tersebut gunakan SIGKILL:
  ![ubuntu5_latihan2.14](image/ubuntu5_latihan2.14.png)

### Praktikum 2.15-cek disk, load dan service 
 1. cek penggunaan disk 
  ![ubuntu1_latihan2.15](image/ubuntu1_latihan2.15.png)

 2. cari direktori yang besar
  ![ubuntu2_latihan2.15](image/ubuntu2_latihan2.15.png)

 3. cek load dan uptime
  ![ubuntu3_latihan2.15](image/ubuntu3_latihan2.15.png)

 4. cek service yang gagal
  ![ubuntu4_latihan2.15](image/ubuntu4_latihan2.15.png)

 5. ambil log error terbaru
  ![ubuntu5_latihan2.15](image/ubuntu5_latihan2.15.png)

### Praktikum 2.16-monitoring port dan koneksi (network basics)
 1. lihat interface dan IP 
  ![ubuntu1_latihan2.16](image/ubuntu1_latihan2.16.png)

 2. lihat routing table
  ![ubuntu2_latihan2.16](image/ubuntu2_latihan2.16.png)

 3. lihat port yang sedang listening 
  ![ubuntu3_latihan2.16](image/ubuntu3_latihan2.16.png)

#### 1.9 latihan
 2.A multimedia audio controller [0401]: Intel Corporation 82801AA AC'97 Audio controller [8086:2415] (rev 01)

  Subsytem: Dell 82801AA AC'97 Audio Controller [1028:0177]

  kernel driver in use: snd_smbus

  kernel modules: = snd_intel8x0

 2.B filesystem : ext4
      
      UUID : b2598606-4e20-977a-2ee01bdd22e0

 2.C 

 2.D





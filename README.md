# Panduan Download dan Instalasi Linux Mint di VirtualBox

Oleh: RAISYAH MEPA ANGELA  
NIM: 09011282328033  
Kelas: SK3C  
Mata Kuliah: SISTEM OPERASI  

## Daftar Isi
1. [Download VirtualBox](#download-virtualbox)
2. [Download Linux Mint](#download-linux-mint)
3. [Instalasi Linux Mint di VirtualBox](#instalasi-linux-mint-di-virtualbox)
4. [Pentingnya Mount Point "/"](#pentingnya-mount-point-)
5. [Penjelasan Sistem File](#penjelasan-sistem-file)

## Download VirtualBox

VirtualBox adalah perangkat lunak virtualisasi yang memungkinkan pengguna menjalankan sistem operasi sekunder di dalam jendela pada sistem operasi utama.

### Langkah-langkah:
1. Kunjungi [situs web resmi Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. Pilih platform yang sesuai (Windows, macOS, Linux)
3. Klik tombol "Download VirtualBox"
4. Pilih lokasi penyimpanan file EXE atau DMG yang diunduh
5. Lakukan instalasi

![Download VirtualBox](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/1a.png)
![VirtualBox Installation](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/4a.png)

## Download Linux Mint

Linux Mint adalah distribusi Linux yang dirancang untuk menjadi ramah pengguna dan mudah diakses, bahkan bagi pengguna baru.

### Langkah-langkah:
1. Akses [situs web resmi Linux Mint](https://linuxmint.com/)
2. Pilih versi yang diinginkan (Cinnamon, MATE, Xfce) dan arsitektur sistem (32-bit atau 64-bit)
3. Klik tombol "Download" untuk memulai proses pengunduhan
4. Pilih lokasi penyimpanan file ISO yang diunduh

![Download Linux Mint](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/5a.png)

## Instalasi Linux Mint di VirtualBox

### 1. Persiapan Awal
- Buka VirtualBox dan klik "New" untuk membuat mesin virtual baru
- Isi nama, tipe sistem operasi, dan versi sesuai dengan Linux Mint

![Create Virtual Machine](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/2.png)

### 2. Atur Memori dan Hard Disk
- Pilih ukuran memori RAM (misalnya, 2048 MB)
- Buat hard disk virtual (VDI) dengan ukuran sekitar 20 GB

![Set Memory and Hard Disk](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/3.png)

### 3. Pasang ISO ke Mesin Virtual
- Pilih mesin virtual yang telah dibuat dan klik "Settings"
- Di tab "Storage", pilih file ISO Linux Mint yang diunduh

![Attach ISO](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/4.png)

### 4. Boot dan Instalasi Linux Mint
- Klik "Start" untuk memulai mesin virtual
- Pilih "Start Linux Mint" dari opsi boot
- Ikuti wizard instalasi: pilih bahasa, tata letak keyboard, jenis instalasi, zona waktu, dan buat akun pengguna

![Start Installation](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/5.png)

### 5. Selesai dan Reboot
- Setelah instalasi selesai, klik "Restart Now"
- Login menggunakan nama pengguna dan password yang telah dibuat

![Linux Mint Desktop](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/6.png)

## Pentingnya Mount Point "/"

- "/" adalah direktori utama (root) di Linux
- Semua file dan folder sistem berada di bawah "/"
- Memilih "/" saat instalasi memastikan sistem operasi terinstal dengan benar
- Pastikan partisi "/" cukup besar (umumnya 20-50 GB)

## Penjelasan Sistem File

1. **ext4**: 
   - Penerus ext3 dengan peningkatan performa
   - Ukuran file maksimal 16TB, volume 1EB

2. **ext3**:
   - Sistem file Linux tradisional
   - Ukuran file maksimal 2TB, volume 32TB

3. **swap**:
   - Bukan sistem file, tapi ruang disk untuk memori virtual
   - Membantu saat RAM penuh

4. **NTFS**:
   - Sistem file Windows
   - Ukuran file dan volume maksimal 16EB

5. **FAT32**:
   - Sistem file sederhana dan kompatibel
   - Ukuran file maksimal 4GB, volume 2TB

6. **Btrfs**:
   - Sistem file Linux modern
   - Fitur: snapshot, subvolume
   - Ukuran volume maksimal 16EB

## Kesimpulan

Proses download dan instalasi Linux Mint di VirtualBox melibatkan beberapa langkah, mulai dari pengunduhan software yang diperlukan hingga konfigurasi dan instalasi sistem operasi di lingkungan virtual. Pemahaman tentang mount point "/" dan berbagai sistem file sangat penting untuk instalasi dan penggunaan Linux yang efektif.

---


# Instalasi Linux Mint di VirtualBox

Oleh: RAISYAH MEPA ANGELA
NIM: 09011282328033
Kelas: SK3C
Mata Kuliah: SISTEM OPERASI

## Daftar Isi
1. [Persiapan Awal](#persiapan-awal)
2. [Boot dan Instalasi Linux Mint](#boot-dan-instalasi-linux-mint)
3. [Selesai dan Reboot](#selesai-dan-reboot)
4. [Pentingnya Mount Point "/"](#pentingnya-mount-point-)
5. [Penjelasan Sistem File](#penjelasan-sistem-file)

## Persiapan Awal

### 1.1 Download Linux Mint
- Unduh ISO Linux Mint dari [website resmi](https://linuxmint.com/download.php)
- ![Download Linux Mint](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/1.png)

### 1.2 Buat Mesin Virtual di VirtualBox
- Buka VirtualBox dan klik "New"
- Isi nama, tipe sistem operasi (Linux), dan versi (Ubuntu 64-bit)
- ![Buat Mesin Virtual](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/2.png)

### 1.3 Atur Memori dan Hard Disk
- Pilih ukuran memori RAM (misalnya, 2048 MB)
- Buat hard disk virtual (VDI) dengan ukuran sekitar 20 GB
- ![Atur Memori dan Hard Disk](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/3.png)

### 1.4 Pasang ISO ke Mesin Virtual
- Pilih mesin virtual yang telah dibuat dan klik "Settings"
- Di tab "Storage", pilih file ISO Linux Mint yang diunduh
- ![Pasang ISO](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/4.png)

## Boot dan Instalasi Linux Mint

### 2.1 Mulai Mesin Virtual
- Klik "Start" untuk memulai mesin virtual
- ![Mulai Mesin Virtual](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/5.png)

### 2.2 - 2.8 Proses Instalasi
- Pilih bahasa, tata letak keyboard, dan jenis instalasi
- Atur zona waktu, nama pengguna, password, dan nama komputer
- Tunggu proses instalasi selesai

## Selesai dan Reboot

### 3.1 Restart Mesin Virtual
- Setelah instalasi selesai, klik "Restart Now"
- Lepaskan ISO dari mesin virtual ketika diminta

### 3.2 Login ke Linux Mint
- Setelah reboot, login menggunakan nama pengguna dan password yang telah dibuat
- ![Login Linux Mint](https://github.com/raisyahangela/Raisyah-Mepa-Angela_PraktikumSO/blob/main/6.png)

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

Instalasi Linux Mint di VirtualBox melibatkan persiapan mesin virtual, konfigurasi, dan proses instalasi. Pemilihan mount point "/" sangat penting untuk memastikan sistem operasi berfungsi dengan baik.

---

Untuk informasi lebih lanjut, kunjungi [website resmi Linux Mint](https://linuxmint.com/).

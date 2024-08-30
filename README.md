# Panduan Instalasi Linux

## Langkah-langkah Instalasi

1. **Buat nama dan pilih ISO yang digunakan**
   
   ![Langkah 1](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/1.png)

2. **Mengatur base memory dan CPU**
   
   ![Langkah 2](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/2.png)

3. **Memilih direktori file virtual machine dan mengatur ukuran hard disk**
   
   ![Langkah 3](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/3.png)

4. **Tampilan hasil pengaturan**
   
   ![Langkah 4](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/4.png)

5. **Mengatur video memory dan mengaktifkan Enable 3D Acceleration**
   
   ![Langkah 5](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/5.png)

6. **Tampilan setelah pengaturan video**
   
   ![Langkah 6](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/6.png)

7. **Memilih bahasa (Inggris US)**
   
   ![Langkah 7](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/7.png)

8. **Centang "install multimedia codecs"**
   
   ![Langkah 8](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/8.png)

9. **Pilih opsi "Something else"**
   
   ![Langkah 9](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/9.png)

10. **Pilih "Ext4 journaling file system" dan mount point "/"**
    
    ![Langkah 10](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/10.png)

11. **Buat partisi baru dan mulai instalasi**
    
    ![Langkah 11](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/11.png)

12. **Atur lokasi**
    
    ![Langkah 12](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/12.png)

13. **Masukkan nama dan password**
    
    ![Langkah 13](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/13.png)

14. **Proses instalasi**
    
    ![Langkah 14](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/14.png)

15. **Restart setelah instalasi selesai**
    
    ![Langkah 15](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/15.png)

16. **Tekan Enter pada tampilan ini**
    
    ![Langkah 16](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/16.png)

17. **Masukkan password**
    
    ![Langkah 17](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/17.png)

18. **Tampilan akhir Linux Mint siap digunakan**
    
    ![Langkah 18](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/18.png)

## Analisis Pemilihan "/" pada Mount Point

Pemilihan "/" pada opsi Mount Point saat instalasi sangat penting karena:

- Root ("/") mencakup semua direktori lain dalam sistem.
- Seluruh hierarki direktori dalam satu partisi atau disk disebut sebagai sistem file.
- Titik mount digunakan sebagai direktori root dari sistem berkas, memungkinkan akses ke seluruh sistem dari direktori tersebut.
- Isi sebelumnya dari direktori tersebut menjadi tidak terlihat dan tidak dapat diakses hingga sistem berkas dilepas.

![Analisis Mount Point](https://github.com/Rafiffarihan13/M.-Rafif-Farihan_09011282328042_SK3C_tugas-01-dan-02-praktikum-sistem-operasi/blob/main/19.png)

## Penjelasan Sistem File

### Ext4
- Peningkatan dari ext3
- Memiliki pengalamatan 48-bit block (ukuran maksimum filesystem 1EB = 1,048,576 TB)
- Maksimum ukuran file 16 TB
- Fitur: Fast fsck, Journal checksumming, Defragmentation support

### Ext3
- Peningkatan dari ext2
- Tidak memerlukan pengecekan data setelah kegagalan sistem

### Swap
- Ruang pada hard disk sebagai virtual memory
- Digunakan saat komputer membutuhkan tambahan memori

### NTFS (New Technology File System)
- Peningkatan dari FAT
- Fitur: Pencegahan kehilangan data karena crash, kompresi file, dan akses kontrol data

### FAT32
- Versi terbaru dari sistem berkas FAT (File Allocation Table)
- Mendukung partisi disk hingga 2 terabyte
- Dapat menyimpan file dengan ukuran lebih dari 4 gigabyte

### Btrfs
- Copy-On-Write file system
- Fokus pada fault tolerance, perbaikan, dan kemudahan administrasi
- Menggunakan prinsip copy-on-write untuk perubahan data

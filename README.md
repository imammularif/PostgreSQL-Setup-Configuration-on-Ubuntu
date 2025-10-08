# PostgreSQL Setup & Configuration on Ubuntu

Dokumentasi ini menjelaskan cara instalasi, konfigurasi, dan pengaturan port PostgreSQL di Ubuntu. 
Dokumentasi ini dibuat sebagai referensi pribadi atau mini project.

## 1. Instalasi PostgreSQL

1. Update repository:

  ```bash
     sudo apt update
  ```

2. Install PostgreSQL:

 ```bash
     sudo apt install postgresql postgresql-contrib
  ```
   
3. Cek versi PostgreSQL:

 ```bash
     psql --version
  ```


## 2. Konfigurasi PostgreSQL

1. Buka file konfigurasi:

```bash
      sudo nano /etc/postgresql/<versi>/main/postgresql.conf
  ```

2. Cari baris port dan ubah sesuai kebutuhan:

   ```bash
      port = 5433
   ```

3. Simpan dan keluar (Ctrl+X, Y, Enter).







Untuk kopneksi ke dbeaver, dapat dilihat dokumnetasinya menggunakan link berikut : [Instalasi & konfigurasi Dbeaver](https://github.com/imammularif/Cara-Install-Dbeaver-di-Ubuntu)








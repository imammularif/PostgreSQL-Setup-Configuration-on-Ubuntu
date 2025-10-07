# PostgreSQL-Setup-Ubuntu-DBeaver

Dokumentasi langkah-langkah install PostgreSQL di Ubuntu, konfigurasi ke DBeaver, dan tips dasar untuk mulai menggunakan database.

1. Buka terminal
2. Update ubuntu-nya
    ```bash
     sudo apt update
     ```
3. lalu, install Postgresql nya menggunakan query berikut :
   ```bash
     sudo apt install Postgresql postgresql-contrib
     ```
   jika ada pesan konfirmasi [Y/n], ketik y. Tunggu proses instalasi posgresql nya selesai.

    ![PROSES ISNTALLASI POSTGRESQL](https://github.com/imammularif/PostgreSQL-Setup-Ubuntu-DBeaver/blob/main/Chapture/1.png)
   
5. jika sudah selesai, hapus semua menggunakan printah : clear. lalu, ketik perintah sudo -i -u postgres psql (untuk membuka administrator postgress)
    ```bash
     sudo -i -u postgres psql
     ```
6. ubah pasword user postgrees nya menggunakan query berikut :
   ```bash
     alter user postgres with encrypted password '1234';
     ```
   lalu akan muncul kalimat ALTER ROLE, setalhnya ketik \q untuk keluar
   ![ALTER PASSWORD](https://github.com/imammularif/PostgreSQL-Setup-Ubuntu-DBeaver/blob/main/Chapture/2.png)

7. untuk mengetahui apakah Postgresql nya udah terintall atau belum, ketik perintah :
   ```bash
     psql --version
     ```
    ![CEK INSTALASI](https://github.com/imammularif/PostgreSQL-Setup-Ubuntu-DBeaver/blob/main/Chapture/3.png)


Untuk kopneksi ke dbeaver, dapat dilihat dokumnetasinya menggunakan link berikut : [instalasi dbeaver]([https://www.w3schools.com/sql/](https://github.com/imammularif/Cara-Install-Dbeaver-di-Ubuntu)
   








# Sistem Pembayaran SPP (Java Swing)

Project Java GUI sederhana untuk manajemen pembayaran SPP sekolah.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/698dc6cd-2c0c-4a5f-9fd6-8693102c5db5" />

## Cara Menjalankan (NixOS/Linux)
1. Jalankan MariaDB server:
   `mariadbd --datadir=$PWD/data_db --socket=$PWD/mysql.sock --port=3306 &`
2. Compile:
   `javac -cp .:mysql.jar SistemSPP.java`
3. Run:
   `java -cp .:mysql.jar SistemSPP`

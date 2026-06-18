# Praktikum P10 - Trigger MySQL

## Deskripsi
Praktikum ini bertujuan untuk mempelajari penggunaan Trigger pada MySQL. Trigger digunakan untuk menjalankan perintah secara otomatis ketika terjadi suatu event pada tabel, seperti INSERT, UPDATE, atau DELETE.

Pada praktikum ini dibuat trigger yang akan menambahkan nilai stok barang secara otomatis setiap kali data baru ditambahkan ke tabel barang.

## Tools yang Digunakan
- XAMPP
- MySQL / MariaDB
- phpMyAdmin
- Command Prompt (CMD)

## Struktur Tabel

```sql
CREATE TABLE barang (
    kd_barang VARCHAR(10) PRIMARY KEY,
    nm_barang VARCHAR(50),
    stok INT,
    harga INT
);

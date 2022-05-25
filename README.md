# Lab8Web

---
Alfiansyah Rambe

312010338

TI 20 B2

---

# Praktikum 8
Seperti praktikum 7, kita buat folder baru di **htdocs** dengan nama *lab8_php_database*

![5](https://user-images.githubusercontent.com/101393632/169481639-f3e3cf6d-a2aa-47e9-9ae3-433ca8c90a6b.jpg)

Setelah itu Jalankan MySql Server dari menu XAMPP Control.

![1](https://user-images.githubusercontent.com/101393632/170177510-06293b0b-0099-495a-8af5-2e7a11639c04.jpg)

# Membuat Database

## Mengakses MySql Client menggunakan PHP MyAdmin.

Buka link melalui browser : http://localhost/phpmyadmin/

![2](https://user-images.githubusercontent.com/101393632/170192771-884fc7c8-c6d2-455e-8cd8-ae54f21ad5fa.png)

## Membuat Tabel Database

```
CREATE TABLE data_barang (
 id_barang int(10) auto_increment Primary Key,
 kategori varchar(30),
 nama varchar(30),
 gambar varchar(100),
 harga_beli decimal(10,0),
 harga_jual decimal(10,0),
 stok int(4)
);
```


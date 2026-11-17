# Praktikum 8 - PHP dan Database MySQL

## Identitas
- **Nama:** Annisa Fikriyani
- **NIM:** 312510314
- **Mata Kuliah:** Pemrograman Web
- **Praktikum:** 8 - PHP dan Database MySQL

## Tujuan Praktikum
1. Memahami konsep dasar database.
2. Memahami konsep CRUD menggunakan PHP.
3. Membuat aplikasi CRUD sederhana menggunakan PHP dan MySQL.

## Langkah-Langkah Praktikum

### 1. Menjalankan XAMPP
Mengaktifkan Apache dan MySQL melalui XAMPP Control Panel sebagai web server dan database server.
<img width="836" height="543" alt="Screenshot 2026-11-17 200753" src="https://github.com/user-attachments/assets/2654adb7-9770-4a93-b51f-b9292be259ca" />


<img width="1917" height="1078" alt="Screenshot 2026-11-17 200817" src="https://github.com/user-attachments/assets/692666dd-7b17-4828-81e5-f194cc7613a1" />

### 2. Membuat Database dan Tabel
Membuat database bernama `latihan1` melalui phpMyAdmin, kemudian membuat tabel `data_barang` dengan kolom id_barang, kategori, nama, gambar, harga_beli, harga_jual, dan stok.

<img width="1917" height="972" alt="Screenshot 2026-11-17 200839" src="https://github.com/user-attachments/assets/754475cb-2ac3-4468-b075-4bb5e9e1e957" />

<img width="1917" height="1030" alt="Screenshot 2026-11-17 200858" src="https://github.com/user-attachments/assets/6462825b-a1bd-4a2d-a6d4-fa1f2f41233f" />

### 3. Menambahkan Data Barang
Memasukkan tiga data barang ke dalam tabel `data_barang`, yaitu HP Samsung Android, HP Xiaomi Android, dan HP OPPO Android menggunakan perintah INSERT.

<img width="1917" height="973" alt="Screenshot 2026-11-17 201000" src="https://github.com/user-attachments/assets/574d6cd8-c069-41a0-b18a-e2f0113751b7" />


<img width="1916" height="1035" alt="Screenshot 2026-11-17 201021" src="https://github.com/user-attachments/assets/3fba9f27-6a54-4e7c-8bfc-e5b1602f4f38" />

### 4. Membuat Folder Project
Membuat folder `lab8_php_database` di dalam direktori `htdocs` XAMPP sebagai tempat menyimpan seluruh file project PHP.

<img width="1411" height="747" alt="Screenshot 2026-11-17 201259" src="https://github.com/user-attachments/assets/917b5603-68cd-4aae-b5a0-8593213e551b" />

### 5. Membuat Koneksi Database
Membuat file `koneksi.php` untuk menghubungkan program PHP dengan database MySQL menggunakan fungsi `mysqli_connect()`.

<img width="981" height="427" alt="Screenshot 2026-11-17 201310" src="https://github.com/user-attachments/assets/72201890-d774-4d82-832b-a91e466aa198" />

<img width="1917" height="1018" alt="Screenshot 2026-11-17 201907" src="https://github.com/user-attachments/assets/4b3ba455-a731-4698-a081-9e61139e9eeb" />


### 6. Menampilkan Data Barang (Read)
Membuat file `index.php` untuk mengambil dan menampilkan data barang dari database menggunakan perintah SELECT.

<img width="1917" height="1015" alt="Screenshot 2026-11-17 202717" src="https://github.com/user-attachments/assets/529335d9-5de5-46b0-9b74-725c5685f0c2" />

### 7. Menambahkan Data Barang (Create)
Membuat file `tambah.php` yang berisi form untuk memasukkan data barang baru ke dalam database menggunakan perintah INSERT.

<img width="1917" height="1018" alt="Screenshot 2026-11-17 203508" src="https://github.com/user-attachments/assets/681f5bce-c7aa-4e91-b800-c9ac453d2072" />

<img width="953" height="470" alt="Screenshot 2026-11-17 203548" src="https://github.com/user-attachments/assets/46866389-5f6c-40f2-9faf-e521dd9c430e" />

<img width="1917" height="966" alt="Screenshot 2026-11-17 205408" src="https://github.com/user-attachments/assets/285e7579-6dfa-4549-8d74-fe61b2e5ed89" />

### 8. Mengubah Data Barang (Update)
Membuat file `ubah.php` untuk menampilkan data barang yang dipilih dan memperbaruinya menggunakan perintah UPDATE.
<img width="1917" height="1015" alt="Screenshot 2026-11-17 205043" src="https://github.com/user-attachments/assets/67dd9815-2b96-41cb-9e0e-bece3c6089bb" />

<img width="1917" height="1078" alt="Screenshot 2026-11-17 205203" src="https://github.com/user-attachments/assets/2a3cd951-9d19-4062-9210-a5d652dbc593" />


### 9. Menghapus Data Barang (Delete)
Membuat file `hapus.php` untuk menghapus data barang berdasarkan ID menggunakan perintah DELETE.

<img width="1917" height="1078" alt="Screenshot 2026-11-17 205208" src="https://github.com/user-attachments/assets/2cb8381c-ecdb-4e4a-b543-046eca3e0f7e" />

## Hasil Praktikum
Berhasil membuat aplikasi pengelolaan data barang sederhana menggunakan PHP dan MySQL dengan menerapkan empat proses CRUD, yaitu:
- **Create:** Menambahkan data barang.
- **Read:** Menampilkan data barang.
- **Update:** Mengubah data barang.
- **Delete:** Menghapus data barang.

# Praktikum 11 - REST API Komik (JWT Authentication)

Implementasi autentikasi dan otorisasi menggunakan **JSON Web Token (JWT)** pada REST API manajemen data komik dengan **Node.js**, **Express.js**, **Sequelize**, dan **PostgreSQL**.

---

## Dokumentasi Pengujian (Postman)

### 1. Register (`POST /api/register`)
Membuat akun pengguna baru dengan password yang di-hash menggunakan `bcrypt`.

![Register](https://github.com/user-attachments/assets/50e70e7f-af62-459f-be8c-834702041258)

### 2. Login (`POST /api/login`)
Autentikasi pengguna untuk mendapatkan **JWT Token** sebagai akses ke endpoint yang diproteksi.

![Login](https://github.com/user-attachments/assets/2aec1969-84b2-49a7-a2d4-eb293d5ab505)

### 3. Tambah Data Komik (`POST /api/komik`)
Menambahkan data komik baru dengan menyertakan `Bearer Token` pada header Authorization.

![Post Komik](https://github.com/user-attachments/assets/e342ab13-02a3-459f-be8c-834702041258)

### 4. Ambil Semua Data Komik (`GET /api/komik`)
Menampilkan seluruh daftar komik yang tersimpan di database.

![Get Komik](https://github.com/user-attachments/assets/e3968bf1-9fac-47fa-b70f-97539cf9f656)

### 5. Update Data Komik (`PUT /api/komik/:id`)
Memperbarui data komik berdasarkan ID dengan menyertakan `Bearer Token`.

![Put Komik](https://github.com/user-attachments/assets/9c0c9c9c-c87e-4766-aa11-2b0afc332619)

### 6. Hapus Data Komik (`DELETE /api/komik/:id`)
Menghapus data komik berdasarkan ID dengan menyertakan `Bearer Token`.

![Delete Komik](https://github.com/user-attachments/assets/e8200b7d-00f8-4576-b15e-9ef88609bf61)

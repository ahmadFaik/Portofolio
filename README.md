# SISTEM MANAJEMEN DATA SAHAM KONOHA

Sebuah aplikasi CRUD sederhana yang dirancang untuk membantu pengguna dalam mengakses data terkait dengan saham di pasar saham.
Aplikasi ini memungkinkan pengguna untuk mendapatkan informasi saham secara mudah dan cepat melalui terminal atau command line.
Bahkan pengguna dapat menambahkan data saham baru ke dalam sistem, menghapus data saham dari sistem, dan juga memperbarui data saham
secara cepat dan efektif.

## Fitur
- **MainMenu**: Menampilkan daftar menu utama yang ada pada sistem.
  **MenuInvestor**
  ![image](https://github.com/user-attachments/assets/a5c01041-4d51-40fa-b47f-97d67957c79d)
  
- **LoginAdmin**: Mendeteksi identitas pengguna untuk mengakses sistem sebagai admin.
                 <br>Dan menampilkan menu utama yang dapat hanya bisa diakses oleh admin.
  ![image](https://github.com/user-attachments/assets/c4fd5dd9-29be-40a3-82f3-68919d9c8b2f)
  
  <br>**MenuAdmin**
  ![image](https://github.com/user-attachments/assets/83198d00-5812-4fb9-b1fc-644b2faa893f)

- **Read**: Menampilkan semua data saham.
            <br>Dan pengguna juga dapat mencari saham berdasarkan kode saham, harga pembukaan atau harga penutupan saham.
  ![image](https://github.com/user-attachments/assets/caf67ba7-936e-42b1-aaa8-23a1e3a6bfe0)

- **Create**: Menambahkan data saham baru ke dalam sistem.
  ![image](https://github.com/user-attachments/assets/13e8ecdb-4a1e-47b1-9826-57d20db52303)

- **Update**: Memperbarui data saham yang sudah ada dan menghitung nilai perubahan harga saham.
  ![image](https://github.com/user-attachments/assets/a23853e6-ebdc-4d2f-9fc8-a1eb40ea781d)

- **Delete**: Menghapus data saham tertentu secara permanen, sementara dan memulihkan data yang sudah dihapus.
  ![image](https://github.com/user-attachments/assets/0ecad9dd-f3bf-41e3-820e-1c0e62e17e50)

- **Exit**: Keluar dari sistem.
  ![image](https://github.com/user-attachments/assets/e5adcaea-2a15-4bec-b802-b9fd3d8a66e2)

- **Output**: Contoh output menampilkan semua data dari aplikasi ini.
  ![image](https://github.com/user-attachments/assets/513af3c6-010e-4b3a-989c-333e8287007d)

## Instalasi

Untuk memulai dengan proyek ini, ikuti langkah-langkah di bawah ini:

1. **Clone repositori ini**:

   Pertama, clone repositori ke komputer lokal Anda dengan perintah berikut:

   ```bash
   git clone https://github.com/ahmadFaik/STOCK-CLI.git

2. **Pindah ke direktori project**:
   ```bash
   cd STOCK-CLI

4. **Instal prettytable**:
   ```bash
   pip install prettytable

6. **Jalankan proyek**:
   ```bash
   python stock_cli.py

## Penulis
- Nama: Ahmad Faik Setiawan
- Email: faiquc29@gmail.com




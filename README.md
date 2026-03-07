<h1 align="center"> Registration App </h1>

## 📁 Project Structure

project-rental/
│
├── main.py
├── data/
│   ├── alat.csv
│   └── transaksi.csv
│
├── modules/
│   ├── admin.py
│   ├── user.py
│
└── docs/
    ├── flowchart.png
    └── screenshot.png

### Registration Page

<img width="444" height="auto" alt="localhost_64388_(iPhone SE)" src="https://github.com/user-attachments/assets/a02ece17-09c6-4128-ae8b-caac0a8c469c" />

Semua data pada form berikut wajib diisi, kecuali jenis kelamin yang sudah terisi dari awal dengan value laki-laki. 

<img width="444" height="auto" alt="localhost_58254_(iPhone SE)" src="https://github.com/user-attachments/assets/2bdb7a87-e0aa-4f50-8269-77489fcf149b" />

Elemen yang ada pada page ini sebagai berikut:
- Field nama lengkap: minimal terisi 3 karakter
- field email: isi email dengan format nama@gmail.com
- field password: minimal nilai terisi 8 karakter
- Jenis kelamin: klik salah satu radio button (Laki-laki atau perempuan)
- Program studi: pilih salah satu pilihan pada dropdown dari 5 program studi
- Field tanggal lahir: menampilkan kalender saat dipencet dengan batas pilih awal 1990 dan batas akhir sekarang
- Checkbox "Saya setuju dengan syarat & ketentuan": Pencet box atau teks di samping checkbox yang berati setuju pada pernyataan yang ada
- Tombol "Daftar sekarang": Pencet untuk ke tahap selanjutnya
- Tombol "Reset form": Pencet untuk reset form

<img width="444" height="auto" alt="localhost_64388_(iPhone SE) (1)" src="https://github.com/user-attachments/assets/e17fc46d-733c-46c2-8c70-8dff1476c01a" />

Terdapat 2 tombol yang dapat dipencet:
- Tombol "Daftar lagi": Melakukan pendaftaran seperti sebelumnya
- Tombol "Lihat daftar": Melihat list data yang terdaftar

<img width="444" height="auto" alt="localhost_64388_(iPhone SE) (3)" src="https://github.com/user-attachments/assets/2d69cf0e-7018-4e3a-b357-2e0d842fdc74" />

Jika terdapat notifikasi "email sudah terdaftar!", artinya pendaftar harus memakai email yang berbeda dari yang ditulis pada form. Email termasuk data unik karena tidak boleh ada email yang sama pada data regis

## Registration List Page

<img width="444" height="auto" alt="localhost_64388_(iPhone SE) (2)" src="https://github.com/user-attachments/assets/9cf123e8-be0a-4578-a04e-5ce015ab50a5" />

Halaman ini menampilkan daftar peserta yang melakukan registrasi. Jumlah daftar peserta dan list card akan berubah secara dinamis menyesuaikan banyaknya peserta yang terdaftar

<img width="444" height="auto" alt="localhost_58254_(iPhone SE) (2)" src="https://github.com/user-attachments/assets/2ac9f44d-254c-4e4a-9570-053470493493" />

Terdapat notifikasi sebelum menghapus salah satu list. Tombol "batal" untuk membatalkan data terhapus dan tombol "hapus" untuk menghapus data dari list secara permanen.

<img width="444" height="auto" alt="localhost_58254_(iPhone SE) (3)" src="https://github.com/user-attachments/assets/f3ea658d-a544-470f-90e7-e73d0ef95c64" />

Berikut ini ialah tampilan halaman jika tidak ada pendaftar. Pendaftar dapat melakukan registrasi dengan memencet tombol ikon "+".

## Profile Page

<img width="750" height="1334" alt="localhost_54380_(iPhone SE)" src="https://github.com/user-attachments/assets/6d48332e-eed0-4a1b-8bd4-f2e3a5caa84b" />

Halaman ini menampilkan profile atau data dari salah satu list peserta jika dipencet. Informasi yang ditampilkan ialah tanggal dan waktu peserta mendaftar, email, gender atau jenis kelamin, program studi, serta tanggal lahir dan umur peserta

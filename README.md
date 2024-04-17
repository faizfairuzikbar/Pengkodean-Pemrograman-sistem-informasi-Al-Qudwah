
# Sistem Informasi Sekolah

Sistem informasi sekolah berbasis laravel 8 dengan template dashboard
[Stisla](https://getstisla.com/)

## Fitur

- CRUD Jurusan
- CRUD Mata Pelajaran
- CRUD Guru
- CRUD Kelas
- CRUD User
- CRUD Materi
- CRUD Tugas & Jawaban
- CRUD Jadwal Sekolah

Tugas UTS Pengkodean & Pemrograman
Nama : Faiz Fairuz Ikbar
nim : 12030122140250
Kelas : F

sistem clone dari 
(https://github.com/lacsapadnan/Sistem-Informasi-Sekolah)

## Screenshots

![Login](![Screenshot 2024-04-16 223459](![Screenshot 2024-04-16 223333](https://github.com/faizfairuzikbar/faiz-fairuz-ikbar/assets/167222911/620f0a73-992d-4480-84de-d0bb8d08615a)

)

![Dashboard](![Screenshot 2024-04-16 223459](https://github.com/faizfairuzikbar/faiz-fairuz-ikbar/assets/167222911/a0b88252-4c05-411d-8cc9-df27957743d5)

)

![Jurusan](<img width="445" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/f92a6478-d44f-47f3-9daa-86a5d8c5e57e">

)

![Mata Pelajaran](<img width="458" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/0bb37727-d759-46e0-a1fc-7d67ba07d4d7">

)

![Tampilan Guru](![Screenshot 2024-04-17 093432](https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/577a3af8-1894-409e-9ec4-3fe7d7f96beb)

)

![Tampilan Kelas](<img width="430" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/af1724c8-189d-425d-99e2-9b04587c5bb2">

)

![Tampilan Siswa](<img width="424" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/923591e6-27c2-42ad-9771-c0f6ef264b1a">

)

![Tampilan Admin/User](<img width="431" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/9342849e-306f-4e96-a698-cf334acf7edf">


)

![ERD](<img width="731" alt="image" src="https://github.com/faizfairuzikbar/Pengkodean-Pemrograman-sistem-informasi-Al-Qudwah/assets/167222911/01db4647-2eb8-4647-b4d8-0f086db1f2ae">

)

## Instalasi

clone project atau download

```bash
  git clone https://github.com/lacsapadnan/Sistem-Informasi-Sekolah.git
  cd Sistem-Informasi-Sekolah
  npm install
  composer install
  cp .env.example .env
```

Buka `.env` dan atur database anda
```bash
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=
```

Install website
```bash
  php artisan key:generate
  php artisan migrate --seed
```

Jalankan website
```bash
  php artisan serve
```
## Default akun untuk testing

Admin
```bash
  email : admin@mail.com
  password : admin123
```

Guru
```bash
  email : budi@mail.com
  password : budi123

  email : gunawan@mail.com
  password : gunawan123
```

Siswa
```bash
  email : kevin@mail.com
  password : kevin123

  email : siska@mail.com
  password : siska123
```
## Update Selanjutnya

(Free Version)
- Fitur Pengumuman Sekolah

(Premium Version)
- Premium Template Metronic
- Fitur Absensi
- Fitur Kuis atau Ujian
- Fitur Tabungan Siswa
- Fitur Pembayaran Sekolah
- Payment Gateway (Midtrans, Xendit, Tripay, dll)


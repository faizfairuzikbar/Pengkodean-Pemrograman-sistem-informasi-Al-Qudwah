
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


## Screenshots

![Login](![Screenshot 2024-04-16 223459](![Screenshot 2024-04-16 223333](https://github.com/faizfairuzikbar/faiz-fairuz-ikbar/assets/167222911/620f0a73-992d-4480-84de-d0bb8d08615a)

)

![Dashboard](![Screenshot 2024-04-16 223459](https://github.com/faizfairuzikbar/faiz-fairuz-ikbar/assets/167222911/a0b88252-4c05-411d-8cc9-df27957743d5)

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


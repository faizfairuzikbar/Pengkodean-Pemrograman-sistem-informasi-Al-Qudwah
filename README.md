
# Sistem Informasi Sekolah

Sistem informasi sekolah berbasis laravel 8 dengan template dashboard
[Stisla](https://getstisla.com/)
## Authors

- [Pascal Adnan](https://www.github.com/lacsapadnan)


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

![Login](blob:https://web.whatsapp.com/f2a1faff-05d6-42e7-b429-e1476ad81194)

![Dashboard](![image](https://github.com/faizfairuzikbar/faiz-fairuz-ikbar/assets/167222911/e3ccbad4-4a9e-48b3-bdbc-66c135aab39e)
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


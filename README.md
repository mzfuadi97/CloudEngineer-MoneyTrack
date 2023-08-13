# Submission 2: Cloud Engineer using Google Cloud Platform

**Username dicoding:** mzfuadi97

## Masalah
Tantangan utama yang dihadapi oleh perusahaan dalam pengembangan Aplikasi Pencatatan Keuangan (Money Tracker App) adalah pengeluaran besar yang terkait dengan infrastruktur on-premise, termasuk pembelian dan perawatan server. Dalam rangka mengoptimalkan pengeluaran dan mengurangi biaya awal, perusahaan bermaksud melakukan migrasi ke Google Cloud untuk mengatasi permasalahan ini.

## Arsitektur Aplikasi
Aplikasi yang dikembangkan memiliki spesifikasi seperti berikut:
- Front-End Web ditulis menggunakan PHP dengan framework CodeIgniter versi 3.1.10.
- Back-End API ditulis menggunakan Node.js.

## Solusi Cloud
Aplikasi ini akan memiliki fokus utama pada pencatatan pemasukan dan pengeluaran. Pengguna juga akan dapat melampirkan gambar sebagai bagian dari setiap pencatatan, seperti struk belanja atau slip gaji. Gambar-gambar tersebut akan disimpan di object storage, dan tautan URL ke setiap gambar akan diintegrasikan dalam basis data. Dengan skema data yang telah ditentukan, konsistensi dalam penyimpanan dan pengelolaan data akan dijamin.

## Role Project
Money Tracker App ini digarap oleh tim yang beranggotakan banyak pihak, mulai dari Manajer Proyek, Developer, Cloud Architect, hingga Cloud Engineer (dalam kasus ini adalah Anda). Source code dan rancangan arsitektur cloud dari Money Tracker App telah selesai digarap dan siap untuk dieksekusi.

## Role
- [Front-End](https://github.com/dicodingacademy/a133-gcp-labs/tree/money-tracker)
- [Back-End](https://github.com/dicodingacademy/a133-gcp-labs/tree/money-tracker-api)

## Arsitektur Cloud
Berikut adalah arsitektur cloud pada GCP untuk mendeploy aplikasi:
![Arsitektur Cloud](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/447fbe67-447e-4806-8637-a95ef1c276ac)

## Dokumentasi Deploy Aplikasi
### User Interface
![frontend-dashboard](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/bc8da6d7-16ef-44dd-8f0d-baccf7bed177)

### Backend-CloudSQL
![CloudSQL-backend](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/7b48bbeb-3a08-4daa-a9e2-75f07033ac1a)

### Bucket-Moneytrap
![SS Bucket](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/a4eede48-e558-4b56-9d7c-e96acf822a73)

### Intances-Moneytrap
![SS Instance](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/357b8cda-ee69-4198-a28e-bffb0d84031f)

### IP Address (Sudah ditutup karena masa waktu (gratis) berakhir)
![SS IP Address](https://github.com/mzfuadi97/CloudEngineer-MoneyTrack/assets/70827786/1148a3ce-8234-4a90-a472-1e0a0d128d4c)

# Submission 2: Cloud Engineer using Google Cloud Platform

Username dicoding: mzfuadi97

| | Deskripsi |
| ----------- | ----------- |
| Masalah | Tantangan utama yang dihadapi oleh perusahaan dalam pengembangan Aplikasi Pencatatan Keuangan (Money Tracker App) adalah pengeluaran besar yang terkait dengan infrastruktur on-premise, termasuk pembelian dan perawatan server. Dalam rangka mengoptimalkan pengeluaran dan mengurangi biaya awal, perusahaan bermaksud melakukan migrasi ke Google Cloud untuk mengatasi permasalahan ini |
| Arsitektur Aplikasi |
Aplikasi yang dikembangkan memiliki spesifikasi seperti berikut:

- Front-End Web ditulis menggunakan PHP dengan framework CodeIgniter versi 3.1.10.
- Back-End API ditulis menggunakan Node.js. |

| Solusi Cloud | Aplikasi ini akan memiliki fokus utama pada pencatatan pemasukan dan pengeluaran. Selain itu, pengguna akan diberikan kemampuan untuk melampirkan gambar sebagai bagian dari setiap pencatatan, seperti struk belanja atau slip gaji. Untuk mengelola gambar-gambar ini secara efisien, kami akan menyimpannya di object storage, dan tautan URL ke setiap gambar akan diintegrasikan dalam basis data. Dengan menggunakan skema data yang telah ditentukan, kami akan memastikan konsistensi dalam penyimpanan dan pengelolaan data ini. |

| Role Project | Money Tracker App ini digarap oleh tim yang beranggotakan banyak pihak, mulai dari Manajer Proyek, Developer, Cloud Architect, hingga Cloud Engineer (dalam kasus ini adalah Anda). Beruntungnya, source code dan rancangan arsitektur cloud dari Money Tracker App sudah selesai digarap dan siap untuk Anda eksekusi. |
| Role | 
- [Front-End](https://github.com/dicodingacademy/a133-gcp-labs/tree/money-tracker)
- [Back-End](https://github.com/dicodingacademy/a133-gcp-labs/tree/money-tracker-api) |

| Arsitektur Cloud | Berikut arsitektur cloud pada GCP untuk mendeploy aplikasi  |

| Dokumentasi Deploy Aplikasi |
User Interface

Backend-CloudSQL

Bucket-Moneytrap

Intances-Moneytrap

IP Address (Sudah ditutup karena masa waktu (gratis) berakhir)


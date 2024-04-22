# Pemrograman Lanjut A
> Fadrian Yhoga Pratama - 2206819395

## Module 8 - Software Architectures

1. **what is amqp?** </br>
AMQP adalah singkatan dari Advanced Message Queuing Protocol. Ini adalah desain standar untuk middleware messaging yang memungkinkan komunikasi antara sistem atau komponen yang berbeda.

2. **what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?**</br>
   - `guest:guest@localhost:5672` adalah string koneksi yang digunakan untuk terhubung ke broker AMQP. Ini terdiri dari tiga bagian:
     - `guest:guest`: Ini adalah kombinasi **nama pengguna** dan **kata sandi** yang digunakan untuk autentikasi. Dalam hal ini, baik nama pengguna maupun kata sandi adalah "guest".
     - `localhost:5672`: Ini menunjukkan nama host dan nomor port dari broker AMQP. Dalam hal ini, itu terhubung ke broker yang berjalan di localhost menggunakan port 5672.
# PROJECT AKHIR WEB

> Kelompok 4 :
  1. Utari W Ardhana (2109116103)
  2. Andi Nabila Fadiya (2109116091)

## TEMA & PENJELASAN WEB
> Tema : Course atau Pelatihan di bidang IT
> Penjelasan : Based on true story, dimana banyak anak SI Unmul yang ikut pelatihan IT secara gratis, oleh karena itu kami kelompok 4 berusaha juga memodifikasi hal serupa

## User Flow
### General
<img width="644" alt="Screenshot 2023-05-10 193844" src="https://github.com/bhaddbaeby/gambarreadme/assets/90855040/cc47ea19-524a-4de5-ad43-116eb0543316">

> Penjelasan :
Jadi, ini adalah user flow secara general, dimana user melakukan registrasi terlebih dahulu, lalu memilih role apakah mentee, tutor atau admin. Lalu user login as role di proses seperti pada umumnya dan masuk ke tampilan home web. Lalu tampilan web ini pun disesuaikan dengan role user jika sudah maka akan masuk ke menu sesuai dengan role lagi.

- Mentee
<img width="446" alt="Screenshot 2023-05-10 193903" src="https://github.com/bhaddbaeby/gambarreadme/assets/90855040/ffe0466d-a1d2-4be8-b736-b2d1ed5f2820">

> Penjelasan :
Terdapat konektor 1 sebagai penghubung untuk ke menu menu yang ada. seperti di mentee ini terdapat 6 menu yang dapat di pilih, lalu masuk ke tampilan menu dan jika sudah maka akan kembali ke dashboard, jika belum maka kembali ke pilihan menu.

- Tutor
<img width="488" alt="Screenshot 2023-05-10 195122" src="https://github.com/bhaddbaeby/gambarreadme/assets/90855040/094730ad-18f6-434c-8bfb-6a68841fe292">

> Penjelasan :
Penjelasannya kurang lebih dengan mentee hanya saja pada tutor ini bisa melihat mentee mereka

- Admin
<img width="502" alt="Screenshot 2023-05-10 195631" src="https://github.com/bhaddbaeby/gambarreadme/assets/90855040/9bd8c603-c7fa-4aec-986e-3180bc3d976c">

> Penjelasan :
Jadi, mirip dengan penjelasan keduanya hanya saja pada admin ini tersedia untuk melihat komen dan menambahkan video tutorial untuk tutor dan mentee intinya pada Admin bebas melakukan CRUD

## Flowchart
<img width="305" alt="Screenshot 2023-05-10 202612" src="https://github.com/bhaddbaeby/gambarreadme/assets/90855040/8e2fa4ec-5d2c-4c98-aa72-b1e12854c573">


## ERD
![WhatsApp Image 2023-05-10 at 21 29 20](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/e427c100-058e-48b9-b35a-5146802effd3)

## Tampilan Web
### Register
![WhatsApp Image 2023-05-10 at 22 13 45](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/31e51476-04c1-46b9-bdaf-6bd6248a459b)
> Penjelasan : Jadi ini adalah tampilan register dari Siacademy seperti form pada umumnya dan pada tahap ini juga pemilihan role yang akan ngedirect ke halaman login dan dashboard atau home sesuai dengan role
1. User melakukan kelengkapan data
2. Semua data wajib diisi
3. Jika sudah punya akun, user bisa login
4. Selanjutnya adalah proses registrasi, jika data tidak kurang langsung direct ke halaman login


### Login
![WhatsApp Image 2023-05-10 at 22 14 22](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/9973fc3e-5a15-45b5-83ec-90a8d5e32826)
> Penjelasan : Ini merupakan menu login dari Siacademy untuk user yang sudah melakukan pendaftaran
1. User melakukan pengisian email
2. User melakukan pengisian password
3. Jika email atau password salah, atau keduanya salah maka user tidak bisa masuk

### Mentee
- Home
![WhatsApp Image 2023-05-10 at 22 21 05](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/264b134d-2577-4a99-a901-c14f94d2a442)
> Penjelasan : Ini merupakan tampilan dari dashboard mentee atau student Siacademy
1. Terdapat menu cepat
2. Bisa view profile
3. Terdapat 5 menu

- About Us
![WhatsApp Image 2023-05-10 at 22 22 26 (1)](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/fa0042c9-a55f-4336-ab35-c42941df39b6)
![WhatsApp Image 2023-05-10 at 22 22 26](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/43e5b0f5-aadc-4711-83a2-7293cf99f89a)

> Penjelasan : Ini menu about us yang dimana terdapat apa itu Siacademy, review dari student dan banyak hal nya. tujuan menu ini adalah untuk branding Siacademy tentang courses/pelatihan

- Courses
![WhatsApp Image 2023-05-10 at 22 23 13](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/23e6ba3a-d860-4c1c-85de-469ceefded39)
![WhatsApp Image 2023-05-10 at 22 22 58](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/106abd5b-34ad-4fb9-93a7-84d9a7ac0d15)

> Penjelasan : Ini merupakan menu courses, dimana pada menu ini student bisa melihat dan bisa belajar, ini juga merupakan courses yang ditambahkan student ke playlist

- Tutor
![WhatsApp Image 2023-05-10 at 22 32 41](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/61c72fe8-24ee-41a0-83e6-192f576ac3bf)
![WhatsApp Image 2023-05-10 at 22 32 22](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/cd89b916-b8b5-4faf-b1a3-ace081a71e52)

> Penjelasan : jadi disini, student bisa melihat tutor nya dan juga bisa mendaftar menjadi tutor

- Contact Us
- Logout
![WhatsApp Image 2023-05-10 at 22 33 58](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/a4a79bb2-f60c-420c-8ed4-d2ba17b92d94)
> Penjelasan : Ketika student logout, maka akan muncuk pop up alert seperti digambar

### Tutor
Pada menu tutor ini kurang lebih dengan menu student hanya saja pada tutor bisa melihat student yang mereka punya

### Admin
> Disini, admin bisa melakukan CRUD
- Home
![WhatsApp Image 2023-05-10 at 22 34 37](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/176d77a2-576e-4e50-8dcd-e9c0711767ea)
> Penjelasan : Jadi, pada dashboard atau home admin itu bisa langsung melakukan CRUD seperti pada gambar

- Playlists
![WhatsApp Image 2023-05-10 at 22 35 06](https://github.com/bhaddbaeby/gambarreadme/assets/90855040/69d60066-9b56-45d9-b23b-29f57f583871)
> Penjelasan : Admin bertugas untuk menambahkan video pembelajaran pada playlist pelatihan

- Content


- Comments


- Logout



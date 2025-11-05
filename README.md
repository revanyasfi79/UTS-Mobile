# AnyOrder 🛒

AnyOrder adalah sebuah platform pemesanan (ordering app) berbasis Android yang memungkinkan pengguna untuk memesan item dan mengirimkannya ke alamat tujuan.

## 🌟 Fitur Utama

* **Autentikasi Pengguna:** Sistem login dan registrasi yang aman.
* **Katalog Item:** Tampilan utama untuk menjelajah dan memilih item.
* **Keranjang Pesanan:** Tempat untuk menampung dan meninjau item sebelum *checkout*.
* **Proses Checkout:** Formulir untuk memasukkan detail pengiriman.
* **Konfirmasi Pesanan:** Layar ringkasan yang memastikan pesanan telah berhasil dibuat.

---

## 📱 Alur Aplikasi

Berikut adalah alur lengkap penggunaan aplikasi dari awal hingga selesai:

### 1. Autentikasi Pengguna
Sebelum dapat memesan, pengguna harus masuk ke akun mereka atau mendaftar jika belum memiliki akun.
* **Login:** `LoginActivity`
* **Registrasi:** `SignUpActivity` / `RegisterActivity`

### 2. Pemilihan Item (Tampilan Utama)
Setelah berhasil masuk, pengguna akan diarahkan ke layar utama (ditangani oleh `MainActivity` atau `HomeFragment`). Di sini, pengguna dapat melihat dan memilih berbagai item yang ingin dipesan.

### 3. Keranjang Pesanan (OrderFragment)
`OrderFragment` berfungsi sebagai keranjang atau daftar pesanan saat ini.
* Fragment ini akan menampilkan semua item yang telah ditambahkan oleh pengguna.
* Jika pengguna belum menambahkan item apa pun, layar ini akan menampilkan pesan "Pesanan Anda Kosong".

### 4. Pengisian Detail Pengiriman (Checkout)
Dari keranjang, pengguna akan melanjutkan ke proses *checkout*. Pada tahap ini, pengguna akan mengisi formulir detail pengiriman yang mencakup:
* Nama Lengkap
* Alamat Pengiriman
* Patokan (Petunjuk Alamat)

### 5. Konfirmasi Pesanan (ConfirmationActivity)
Setelah pesanan berhasil dikirim (data terkirim ke server), aplikasi akan menampilkan layar konfirmasi (`ConfirmationActivity`). Layar ini bertujuan untuk:
* Memberi tahu pengguna bahwa pesanan telah berhasil diterima.
* Menampilkan ringkasan detail pengiriman untuk verifikasi.
* Memberi instruksi selanjutnya kepada pengguna (jika ada).

---

## 🛠️ Teknologi yang Digunakan

* **Bahasa:** [Kotlin](https://developer.android.com/kotlin)

---

## 📸 Tangkapan Layar (Screenshots)

*(Tempatkan gambar-gambar Anda di sini untuk memberikan gambaran visual)*


<img width="289" height="561" alt="Screenshot 2025-11-05 125304" src="https://github.com/user-attachments/assets/891492bf-80a6-4eb0-a28f-8e00c012a1a2" />
<img width="289" height="561" alt="Screenshot 2025-11-05 125309" src="https://github.com/user-attachments/assets/d49b60c8-0ba3-452b-b205-bcb04456680b" />
<img width="289" height="561" alt="Screenshot 2025-11-05 124731" src="https://github.com/user-attachments/assets/b53f4b86-3ea0-4e3b-a3a2-fb28b99b8024" />
<img width="289" height="1400" alt="Screenshot 2025-11-05 124023" src="https://github.com/user-attachments/assets/0d59c9db-0130-467c-8e1d-6ebebf29595e" />
<img width="289" height="700" alt="Screenshot 2025-11-05 124806" src="https://github.com/user-attachments/assets/f6ea75aa-2eb1-469d-aac6-c139e8c65fd0" />
<img width="289" height="500" alt="Screenshot 2025-11-05 124901" src="https://github.com/user-attachments/assets/3401cf60-b913-41f8-a632-f27ee4333ea3" />
<img width="289" height="561" alt="Screenshot 2025-11-05 124920" src="https://github.com/user-attachments/assets/cc0c7d7d-35d1-4b92-94ce-3d23f6dffb63" />
<img width="289" height="561" alt="Screenshot 2025-11-05 125038" src="https://github.com/user-attachments/assets/1373686d-2cba-46ea-b19f-6ddf5d021cf7" />
<img width="289" height="561" alt="Screenshot 2025-11-05 125140" src="https://github.com/user-attachments/assets/9ded7b28-632e-4697-9adc-010821f00c1d" />
<img width="289" height="561" alt="Screenshot 2025-11-05 125148" src="https://github.com/user-attachments/assets/12e4a370-32c6-440b-9f7e-fe1478532b62" />
<img width="289" height="561" alt="Screenshot 2025-11-05 125157" src="https://github.com/user-attachments/assets/aa9b2317-0f62-4472-933d-096e66b418ef" />











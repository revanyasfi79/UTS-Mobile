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

| Splash Screen | Landing | SignUp |
| :---: | :---: | :---: |
| ![<img width="289" height="561" alt="Screenshot 2025-11-05 125304"] src="https://github.com/user-attachments/assets/ffd518f1-059e-4d5c-bf74-191203ae7904" />
|  ![<img width="386" height="594" alt="Screenshot 2025-11-05 124023"] src="https://github.com/user-attachments/assets/d1e97e63-7865-4806-a2fe-9c6b2eb594d2" />
) | ![<img width="361" height="826" alt="Screenshot 2025-11-05 124901"] src="https://github.com/user-attachments/assets/462a82a9-5c0a-424c-a41d-787c69fa7bc7" />
|

| Login | Register | Home |
| :---: | :---: | :---: |
|![<img width="343" height="540" alt="Screenshot 2025-11-05 124806" src="https://github.com/user-attachments/assets/ceaafdf8-29ee-45d0-b39f-51d92f3023d8" />
 | ![<img width="386" height="594" alt="Screenshot 2025-11-05 124023" src="https://github.com/user-attachments/assets/97d31cc7-97c3-4918-93e4-d9ad62548154" />
 | ![<img width="361" height="826" alt="Screenshot 2025-11-05 124901" src="https://github.com/user-attachments/assets/7b9a3970-591f-4841-9389-011a07de87a7" />
|

| Keranjang (Kosong) | Keranjang (Tidak Kosong) | Alamat Pengiriman |
| :---: | :---: | :---: |
|  ![<img width="371" height="828" alt="Screenshot 2025-11-05 124920" src="https://github.com/user-attachments/assets/55512e93-7d6b-4fb4-96ec-65077052c3ec" />
 | ![<img width="367" height="823" alt="Screenshot 2025-11-05 125038" src="https://github.com/user-attachments/assets/9f30c49e-8e9d-4b64-bbc6-2bd73cceb287" />
 | !<img width="354" height="459" alt="Screenshot 2025-11-05 125140" src="https://github.com/user-attachments/assets/086e4f93-3b29-49a4-a812-4e3a296c6037" />
|


| Konfirmasi | Profile | 
| :---: | :---: | 
| !<img width="367" height="824" alt="Screenshot 2025-11-05 125148" src="https://github.com/user-attachments/assets/95d9e12f-8e97-4c51-b692-1257baf0c6d8" />
|  ![<img width="344" height="741" alt="Screenshot 2025-11-05 125157" src="https://github.com/user-attachments/assets/3f04c099-b18d-41fe-b141-003449ff99fe" />
|


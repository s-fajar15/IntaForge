# Instaforge

Instaforge adalah alat automatisasi yang dirancang khusus untuk membuat akun Instagram secara otomatis menggunakan email sementara (temp mail) atau email manual. Tools ini mengotomatisasi seluruh proses pendaftaran, mulai dari pembuatan email, verifikasi kode, pengisian data profil, hingga pembuatan akun lengkap dengan username dan password.

## Fitur Utama

- Membuat akun Instagram otomatis dengan email generated atau email manual.
- Pengisian data nama dan tanggal lahir secara random menggunakan Faker.
- Proses verifikasi kode dari email sementara secara otomatis.
- Penyesuaian username dengan format yang mudah dikustomisasi.
- Penyimpanan data akun yang berhasil dibuat ke dalam file JSON.
- Delay dan proses tunggu agar simulasi pembuatan akun lebih natural.
- Integrasi opsional untuk otomatis mengikuti akun tertentu setelah pembuatan.

## Persyaratan Sistem

- Python 3.8 ke atas
- Library: `requests`, `faker`, dan dependencies lainnya

## Cara Menggunakan

1. Clone repository atau download file source.
2. Install dependencies dengan `pip install -r requirements.txt` (jika disediakan).
3. Jalankan script menggunakan perintah `python main.py`.
4. Masukkan jumlah akun Instagram yang ingin dibuat.
5. Pilih mode email yang diinginkan: otomatis (generate email sementara) atau manual (input email sendiri).
6. Tunggu proses pembuatan akun berjalan secara otomatis.
7. Akun yang berhasil dibuat akan disimpan di folder `accounts` dalam format JSON.

## Catatan Penting

- Tools ini dibuat untuk tujuan edukasi dan eksperimen. Gunakan secara bijak sesuai ketentuan Instagram.
- Instagram dapat melakukan perubahan pada API atau mekanisme pendaftaran yang bisa menyebabkan tools ini tidak berfungsi.
- Jangan digunakan untuk spam atau aktivitas yang melanggar hukum atau kebijakan platform.

## Lisensi

Tools ini disediakan "as-is" tanpa jaminan. Penggunaan sepenuhnya menjadi tanggung jawab pengguna.

---

© 2025 Instaforge by s.fajar15

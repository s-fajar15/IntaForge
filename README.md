# InstaForge


![InstaForge Logo](https://github.com/s-fajar15/IntaForge/blob/main/asset/quality_restoration_20250910181439075.png)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Last Commit](https://img.shields.io/github/last-commit/s-fajar15/IntaForge)
![Stars](https://img.shields.io/github/stars/s-fajar15/IntaForge?style=social)

**InstaForge** adalah sebuah tools otomatisasi untuk membuat akun Instagram baru secara massal dan cepat.  
Nama "InstaForge" terinspirasi dari kata *Forge* (tempa/buat), yang menggambarkan proses pembuatan akun secara instan dan otomatis.

---

## ✨ Fitur Utama
- 🔹 **Auto Account Creator** – Membuat akun Instagram baru secara otomatis.  
- 🔹 **Integrasi Email Sementara** – Menggunakan layanan email temporary untuk proses verifikasi.  
- 🔹 **Auto Verification** – Mengambil kode OTP/konfirmasi dari email secara otomatis.  
- 🔹 **Random Data Generator** – Nama, username, dan tanggal lahir dihasilkan secara acak dan realistis (via Faker).  
- 🔹 **Auto Follow (opsional)** – Setelah akun dibuat, bisa langsung mengikuti target tertentu.  
- 🔹 **Multi Account Support** – Bisa membuat banyak akun sekaligus dalam satu eksekusi.

---

## ⚙️ Instalasi
1. Clone repository:
   ```bash
   git clone https://github.com/s-fajar15/InstaForge
   cd InstaForge
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Cara Penggunaan
Jalankan script utama:
```bash
python main.py
```

Lalu ikuti instruksi di terminal:
- Masukkan jumlah akun yang ingin dibuat.
- Tools akan otomatis membuat email, mendaftar, menerima kode OTP, hingga akun Instagram berhasil dibuat.

---

## 🖥️ Contoh Output
```bash
> Instagram Creator 2025 | s.fajar15

> Mau buat berapa akun Instagram? : 3
> Memproses 3 akun...

> Memulai proses pembuatan: Maria Uwais (maria.uwais33@inboxkitten.com)
> Mengambil token...
> Mencari username yang tersedia...
> Username tersedia: mariauwais33
> Memverifikasi email...
> Kode verifikasi diterima: 482913
> Membuat password...
> Mengatur tanggal lahir...
> Menyimpan nama profil...
> Akun berhasil dibuat ✅

> Memulai proses pembuatan: Dimas Putra (dimas.putra12@inboxkitten.com)
> ...
```

---

## 📌 Catatan
- Tools ini dibuat untuk tujuan **pembelajaran** dan **otomatisasi pribadi**.  
- **Tidak disarankan** untuk penyalahgunaan (spam, jual akun, dsb). Gunakan dengan bijak.  
- Instagram dapat mengubah mekanisme pendaftarannya sewaktu-waktu sehingga beberapa fungsi mungkin perlu diperbarui.

---

## 🛠️ Tech Stack
- Python 3
- `requests` – HTTP requests
- `Faker` – Random data generator
- API Temp Mail – Email sementara
- Regex & UUID – Token parsing & device ID generator

---

## 📄 Lisensi
MIT License © 2025 - s.fajar15
- Jangan digunakan untuk spam atau aktivitas yang melanggar hukum atau kebijakan platform.

## Lisensi

Tools ini disediakan "as-is" tanpa jaminan. Penggunaan sepenuhnya menjadi tanggung jawab pengguna.

---

© 2025 Instaforge by s.fajar15

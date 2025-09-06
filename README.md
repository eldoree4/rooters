# Ultimate Android Rooting Tool for Termux

![Root Tool Banner](https://img.shields.io/badge/Ultimate-Rooting_Tool-blue?style=for-the-badge)
![Termux](https://img.shields.io/badge/For-Termux-green?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-Rooting-orange?style=for-the-badge)

## 📋 Deskripsi

Ultimate Android Rooting Tool adalah alat canggih yang dirancang khusus untuk Termux yang memungkinkan Anda melakukan proses rooting pada perangkat Android tanpa memerlukan PC. Tool ini menyediakan fitur deteksi otomatis perangkat, pengunduhan bahan yang diperlukan, dan sistem pemulihan dari brick.

## ✨ Fitur Utama

- 🔍 **Deteksi Perangkat Otomatis** - Mengenali merek, model, chipset, dan versi Android
- 📥 **Pengunduhan Otomatis** - Mengunduh TWRP, Magisk, dan firmware yang diperlukan
- 🛡️ **Sistem Pemulihan** - Dapat memulihkan perangkat dari keadaan brick/bootloop
- ⚡ **Multiple Mode** - Mode otomatis, semi-otomatis, manual, dan pemulihan darurat
- 🔒 **Safety Checks** - Pemeriksaan keamanan sebelum proses rooting
- 💾 **Backup System** - Backup partisi penting sebelum modifikasi

## 📱 Perangkat yang Didukung

- **Samsung** (menggunakan Odin melalui Wine)
- **Xiaomi** (menggunakan Fastboot)
- **Perangkat Qualcomm** (berbagai merek)
- **Perangkat MediaTek** (berbagai merek)
- **Perangkat Exynos** (Samsung)
- **Perangkat Android lainnya**

## ⚠️ Peringatan Penting

1. **RISIKO BRICK** - Proses rooting dapat menyebabkan perangkat menjadi brick
2. **GARANSI HILANG** - Rooting akan membatalkan garansi perangkat
3. **BACKUP DATA** - Selalu backup data penting sebelum memulai
4. **BATERAI CUKUP** - Pastikan baterai minimal 50% sebelum proses
5. **KONEKSI STABIL** - Pastikan koneksi perangkat stabil selama proses

## 🛠️ Persyaratan

- Perangkat Android dengan Termux terinstall
- Kabel OTG untuk menghubungkan perangkat target
- Koneksi internet untuk mengunduh bahan
- Penyimpanan cukup (minimal 5GB space kosong)
- USB Debugging diaktifkan pada perangkat target

## 📥 Instalasi

1. **Install Termux** dari F-Droid (bukan Play Store)
2. **Update package** Termux:
   ```bash
   pkg update && pkg upgrade


   🚀 Penggunaan
Hubungkan perangkat target menggunakan kabel OTG

Aktifkan USB Debugging pada perangkat target:

Pergi ke Settings > About Phone

Ketuk "Build Number" 7 kali untuk mengaktifkan Developer Options

Pergi ke Developer Options dan aktifkan "USB Debugging"

Jalankan tool:

bash
cd ~
./ultimate-root.sh
Pilih mode yang diinginkan:

Mode Otomatis (Rekomendasi untuk pemula)

Mode Semi-Otomatis (Bahan diunduh otomatis)

Mode Manual (Untuk pengguna berpengalaman)

Pemulihan Darurat (Untuk perangkat brick)

🔧 Mode Operasi
1. Mode Otomatis Lengkap
Deteksi otomatis perangkat

Unduh semua bahan yang diperlukan

Lakukan safety checks

Eksekusi proses rooting secara otomatis

2. Mode Semi-Otomatis
Deteksi perangkat dan unduh bahan

Berikan instruksi langkah demi langkah

Pengguna melakukan flashing manual

3. Mode Manual
Untuk pengguna berpengalaman

Akses penuh ke semua tools

Tanggung jawab sepenuhnya pada pengguna

4. Mode Pemulihan Darurat
Khusus untuk perangkat brick/bootloop

Coba pulihkan menggunakan backup

Panduan kombinasi tombol untuk berbagai merek

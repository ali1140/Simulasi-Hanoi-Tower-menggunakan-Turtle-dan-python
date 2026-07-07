<div align="center">

# Simulasi Menara Hanoi (Python Turtle)

[![Python](https://img.shields.io/badge/Language-Python_3-blue.svg)]()
[![Graphics](https://img.shields.io/badge/Library-Turtle_Graphics-orange.svg)]()
[![Algorithm](https://img.shields.io/badge/Algorithm-Recursion-success.svg)]()

</div>

---

## 🎥 Video Demonstrasi
> **[TEMPATKAN TAUTAN ATAU TAG VIDEO ANDA DI SINI]**
*(Silakan ganti baris ini dengan tag markdown/HTML video yang telah Anda siapkan)*

---

## 📖 Latar Belakang & Deskripsi
Proyek ini adalah simulasi visual dari teka-teki matematika klasik **Menara Hanoi (Tower of Hanoi)**. Dibangun menggunakan pustaka bawaan Python, `turtle`, program ini tidak hanya menyelesaikan teka-teki tersebut di belakang layar, melainkan menunjukkannya secara visual blok demi blok.

Tujuan utama proyek ini adalah untuk memamerkan implementasi praktis dari **Algoritma Rekursif (Recursive Algorithm)** dan **Struktur Data Stack (LIFO - Last In First Out)** yang dibalut menggunakan paradigma Pemrograman Berorientasi Objek (OOP).

---

## ⚙️ Konsep Pemrograman Kunci
Berikut adalah konsep Ilmu Komputer mendalam yang diterapkan di dalam simulasi ini:

1. **Rekursi Logis (Algoritma `O(2^n)`)**
   Pemindahan piringan diselesaikan menggunakan fungsi `hanoi(n, from_, with_, to_)` yang memanggil dirinya sendiri. Ini mendemonstrasikan algoritma *Divide and Conquer*, memecah masalah besar (memindahkan `N` piringan) menjadi sub-masalah kecil (`N-1`).
   
2. **Object-Oriented Programming (OOP)**
   - Kelas `Disc` mewarisi (*inherit*) properti dari objek `Turtle` untuk menggambar kotak persegi panjang dengan warna gradien yang merepresentasikan piringan.
   - Kelas `Tower` mewarisi properti dari struktur data `list` bawaan Python. Kelas ini dimodifikasi sedemikian rupa agar bertindak sebagai **Stack** khusus yang tidak hanya menampung data array, tetapi juga menggerakkan animasi piringan ke koordinat fisik X dan Y di layar saat metode `push()` dan `pop()` dipanggil.

---

## 🚀 Cara Menjalankan
1. Pastikan **Python 3** sudah terinstal di perangkat Anda. (Modul `turtle` merupakan pustaka bawaan/standar Python, sehingga Anda tidak perlu menginstal ekstensi pihak ketiga melalui `pip`).
2. Kloning repositori ini atau unduh berkas kodenya.
3. Buka terminal atau Command Prompt di lokasi penyimpanan berkas.
4. Jalankan perintah berikut:
   ```bash
   python "Tower hanoi turtle7.py"
   ```
5. Jendela kanvas Turtle akan terbuka dan menampilkan kondisi awal piringan (default: 4 piringan).
6. **Tekan tombol `SPASI`** pada keyboard Anda untuk memulai animasi simulasi!

---

## 👨‍💻 Kontributor
**Ali Akbar Alhabsyi (ali1140)**  
Proyek ini adalah bagian dari portofolio fundamental struktur data dan algoritma saya, di mana saya mengeksekusi logika matematis kompleks dan mentranslasikannya menjadi *feedback* visual (GUI) interaktif yang mudah dipahami.

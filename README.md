# ⏰ Proyek Jam Digital Sekolah - Huidu HD-W3A

<div align="center">

![Banner Proyek](./image/banner-jam-digital.svg)

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![Hardware](https://img.shields.io/badge/Hardware-Huidu_HD--W3A-blue.svg)](#)
[![Display](https://img.shields.io/badge/Panel-P10_LED_Matrix-red.svg)](#)

**Sistem Manajemen Layar Informasi Digital & Jadwal Otomatis Sekolah**  
Dibuat dan dikelola secara terbuka oleh **Kelompok 1 - XI TJKT 3**

</div>

---

## 📌 Tentang Proyek
Proyek ini merupakan portofolio implementasi **Digital Signage & Jam Otomatis Sekolah** menggunakan *controller* cerdas **Huidu HD-W3A** yang diaplikasikan pada panel P10 LED Matrix. 

Lebih dari sekadar jam digital biasa, konfigurasi XML yang kami rancang di dalam repositori ini telah dioptimalkan dengan algoritma **Day-Specific Routing** (Routing Penjadwalan Berbasis Hari). Sistem mampu memisahkan program reguler dengan program insidental (seperti Jam Waktu Sholat, jam masuk, waktu literasi, hingga Lagu Indonesia Raya) tanpa *overlap*, *glitch*, atau layar membeku (*freeze*), disesuaikan persis dengan kalender akademik sekolah.

Repositori ini bersifat *Open Source*. Guru, siswa, maupun pengembang lain dipersilakan untuk mengkloning, menganalisa logika *routing* waktu yang kami buat, atau bahkan memodifikasinya untuk kebutuhan masing-masing! 🚀

---

## 👥 Identitas Tim Pengembang
Proyek ini dirancang, diuji, dan dieksekusi oleh **Kelompok 1**:
- 🏫 **Sekolah:** SMKN 9 SURAKARTA
- 🧑‍🎓 **Jurusan/Kelas:** XI TJKT 3

| No | Nama Anggota Tim | Presensi | Peran/Tugas |
|:---|:---|:---:|:---|
| 1 | **Alexa Putra P** | 04 | *Hardware & Wiring Setup* |
| 2 | **Alwanu Zaky R** | 06 | *Lead Programmer & System Logic* |
| 3 | **Angelin Mata Air P** | 08 | *Data Entry & Schedule Mapping* |
| 4 | **Bintang Putra P** | 12 | *Quality Control & Testing* |
| 5 | **M Ibnu Abbad** | 25 | *Hardware Assembly* |
| 6 | **Nur Kholifah H** | 27 | *Documentation & Design* |
| 7 | **Rafael Sukma D.R** | 31 | *Network & WiFi Config* |
| 8 | **Satria Bagus P** | 34 | *Presentation & Public Speaking* |
| 9 | **Sekar Anindya K** | 35 | *Project Manager* |

*(Catatan: Peran di atas bisa kalian edit kembali sesuai kontribusi nyata masing-masing).*

---

## ✨ Fitur Unggulan
- 🗓️ **Day-Specific Routing Logic:** Alur program berbeda secara otomatis untuk hari Senin, Selasa, Rabu-Kamis, dan Jumat sesuai jam KBM sesungguhnya.
- 🕌 **Modul JWS (Jam Waktu Sholat) Terkalibrasi:** Sinkronisasi dinamis algoritma waktu sholat presisi tanpa *memory overflow*.
- ⚡ **Optimasi Memori Huidu:** Konfigurasi layout dan penggunaan *font* dirancang khusus agar tidak membebani limit memori *chip* W03A.
- 🎓 **Identitas Sekolah Dinamis:** Menampilkan kelas, nama sekolah, hingga *quotes* berjalan dengan transisi yang mulus *(Do Not Clear: OFF)*.

---

## 🗂️ Struktur Direktori

```bash
📦 Proyek-Jam-Digital-Sekolah-Huidu-HD-W3A
 ┣ 📂 Docs/
 ┃ ┗ 📜 Presentasi-Kelompok-1-SMKN9-Surakarta.md  # File naskah presentasi kami
 ┣ 📂 config/
 ┃ ┗ 📜 hd2020-main-config.xml                    # ⚠️ FILE MASTER PROGRAM (Import ke HD2020)
 ┣ 📂 image/
 ┃ ┣ 🖼️ banner-jam-digital.svg
 ┃ ┗ 🖼️ tampilan-led-sekolah.svg                  # Preview hasil akhir di layar
 ┣ 📜 LICENSE
 ┗ 📜 README.md

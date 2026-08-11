# ☕ RobustaVision-Ijen: Deteksi & Klasifikasi Kematangan Kopi Robusta Berbasis YOLOv8

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-000000?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Google Colab Pro](https://img.shields.io/badge/Environment-Google%20Colab%20Pro%20(A100)-F9AB00?style=flat&logo=googlecolab&logoColor=white)

---

## 📌 Deskripsi Proyek

Repository ini berisi kode program dan dokumentasi untuk **Sistem Deteksi dan Klasifikasi Tingkat Kematangan Buah Kopi Robusta (*Coffea canephora*)** berbasis *Deep Learning* menggunakan arsitektur **YOLOv8**. 

[cite_start]Penelitian ini dirancang untuk menyelesaikan permasalahan efisiensi pada proses pemanenan kopi tradisional dengan menghadirkan otomatisasi *computer vision* yang andal[cite: 599]. [cite_start]Model dilatih dan diuji menggunakan pendekatan **Dual-Dataset**, yakni penggabungan antara *public benchmark dataset* dan dataset citra riil yang diambil langsung di kawasan **Perkebunan Kopi Ijen, Kabupaten Bondowoso, Jawa Timur**[cite: 599].

---

## ✨ Fitur Utama

- [cite_start]**Multi-Object Detection:** Mampu mendeteksi dan menghitung puluhan hingga ratusan buah kopi dalam satu *frame* citra kompleks (*overlapping/cluttered*)[cite: 580].
- **Klasifikasi 3 Kelas Kematangan:**
  - 🔴 `matang` (Ripe)
  - 🟠 `setengah-matang` (Semi-Ripe)
  - 🟢 `mentah` (Unripe)
- [cite_start]**High Field Robustness:** Diuji pada berbagai variasi intensitas pencahayaan alami dan sudut pengambilan gambar di perkebunan terbuka.
- [cite_start]**Siap Eksekusi (Colab Friendly):** Alur kerja dikemas lengkap dalam satu berkas notebook (`.ipynb`) dari persiapan, *training*, validasi, hingga inferensi sampel[cite: 736, 789].

---

## 📁 Struktur Repository

```text
.
├── TUGAS_AKHIR.ipynb                 # Notebook utama (Data Prep, Training, Validation, & Inference)
├── TUGAS_AKHIR.ipynb-Colab.pdf       # Hasil pengerjaan project di google colab by pdf
├── docs/
│   └── Manual_Book.pdf               # Panduan teknis & pengoperasian sistem (Manual Book)
└── README.md                         # Dokumentasi utama repository

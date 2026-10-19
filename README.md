# Interactive HCI Data Visualization Dashboard & Usability Analytics

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Plotly](https://img.shields.io/badge/Visualization-Plotly-3F4F75)
![Pandas](https://img.shields.io/badge/Data-Pandas-150458)
![HCI](https://img.shields.io/badge/Design-UI%2FUX%20%26%20HCI-FF6F61)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📋 Studi Kasus: Rancang Bangun Dashboard Visualisasi Data Interaktif dengan Penerapan Prinsip HCI & Gestalt

### 1. Latar Belakang Masalah
Di era *Big Data*, instansi pelayanan publik dan organisasi bisnis sering mengalami masalah *Data Deluge* (limpahan data mentah berukuran besar). Pembuat keputusan (*decision makers*) kesulitan mengambil kesimpulan secara cepat karena informasi disajikan dalam tabel angka yang kaku dan kompleks. Antarmuka yang buruk memperberat beban kognitif (*cognitive load*) pengguna dan meningkatkan risiko salah interpretasi data.

### 2. Solusi HCI & Visualisasi Data
Mengacu pada materi kuliah umum *Informatics Practitioner Lecture Series* mengenai **Human-Computer Interaction (HCI) & Data Visualization**, proyek ini mengembangkan sebuah **Dashboard Analitik Interaktif** yang dirancang khusus mengacu pada prinsip-prinsip kognitif manusia:
* **Hukum Gestalt (Proximity & Similarity):** Mengelompokkan komponen informasi berdasarkan keterdekatan spasial dan pola warna yang konsisten.
* **Minimalis & Anti-Clutter (*Low Cognitive Load*):** Menghilangkan *chartjunk* (garis/dekorasi yang tidak perlu) agar perhatian pengguna langsung tertuju pada Key Performance Indicators (KPI).
* **Interaktivitas (*Hover, Filter, & Linked Views*):** Memungkinkan pengguna melakukan eksplorasi data secara mandiri tanpa membuat tampilan terasa sesak.

---

## ⚙️ Alur Kerja Pengembangan (HCI & Visualization Pipeline)

1. **User Requirement & Data Collection:** Menyusun dataset simulasi evaluasi kinerja dan tingkat kepuasan layanan publik di berbagai wilayah.
2. **Data Aggregation & KPI Calculation:** Menghitung indikator utama seperti *Total Layanan*, *Rata-Rata Kepuasan (CSAT)*, *Waktu Respon*, dan *Tingkat Penyelesaian Problem*.
3. **Gestalt-Based Chart Selection:**
   * **KPI Cards:** Menampilkan angka utama dengan hierarki visual paling menonjol.
   * **Line Chart:** Tren kepuasan pelanggan dari waktu ke waktu.
   * **Bar Chart:** Perbandingan kinerja layanan antar-kategori.
   * **Donut Chart:** Proporsi status penyelesaian laporan.
4. **Interactive Web Dashboard Construction:** Menggabungkan seluruh grafik interaktif Plotly ke dalam layout HTML/CSS responsif (`index.html`) yang dapat diakses langsung via **GitHub Pages**.
5. **Usability Evaluation Framework:** Menyediakan kerangka pengujian antarmuka menggunakan metrik *System Usability Scale* (SUS).

---

## 📁 Struktur Repositori

```
├── HCI_Data_Visualization.ipynb  # Jupyter / Google Colab Notebook (Kode Utama)
├── public_service_data.csv      # Dataset mentah indikator layanan (CSV)
├── index.html                   # Interactive Web Dashboard (Siap di-host di GitHub Pages)
└── README.md                    # Dokumentasi utama proyek
```

---

## 🚀 Cara Menjalankan di Google Colab

1. Buka file `HCI_Data_Visualization.ipynb` di [Google Colab](https://colab.research.google.com/).
2. Jalankan sel kode secara berurutan (**Sel 1 hingga Sel 7**).
3. **Sel 7** akan otomatis mengunduh file `index.html` dan `public_service_data.csv` ke komputer Anda.
4. Upload seluruh file ke repositori GitHub baru Anda dan aktifkan **GitHub Pages** di menu `Settings > Pages` untuk mempublikasikan dashboard interaktif secara *live*!

---

## 👥 Referensi & Kredit
* **Materi:** *"Human-Computer Interaction & Data Visualization"* - Informatics Practitioner Lecture Series 2026, Universitas Bengkulu.

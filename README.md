# Analisis Kebutuhan Daya Listrik Provinsi Lampung Tahun 2025–2030

## Deskripsi Proyek
Repositori ini berisi proyek akademik mengenai analisis proyeksi dan tren kebutuhan daya listrik Provinsi Lampung tahun 2025–2030. Proyek dilakukan menggunakan bahasa pemrograman R dengan pendekatan pengolahan data, transformasi data, analisis statistik deskriptif, visualisasi, dan pemodelan regresi linier sederhana.

## Latar Belakang
Kebutuhan listrik di Provinsi Lampung menunjukkan tren peningkatan dari tahun ke tahun. Analisis ini dilakukan untuk memahami pola pertumbuhan kebutuhan daya listrik dan menghasilkan proyeksi yang dapat memberikan gambaran awal dalam mendukung perencanaan energi.

## Tujuan
- Menganalisis pola kebutuhan daya listrik Provinsi Lampung
- Menghasilkan proyeksi kebutuhan daya listrik tahun 2025–2030
- Menghitung laju pertumbuhan tahunan kebutuhan daya listrik
- Menyajikan hasil analisis secara visual menggunakan R

## Peran Saya
Pada proyek ini, saya berperan sebagai **Maintainer & Code Implementation**, dengan kontribusi pada pengolahan data, implementasi kode, visualisasi, dan interpretasi hasil analisis.

## Tools dan Metode
- **Bahasa Pemrograman:** R
- **Metode:** Regresi Linier Sederhana
- **Library/Package:** readxl, dplyr, tidyr, ggplot2
- **Jenis Data:** Data sekunder dari Open Data Lampung

## Alur Analisis
1. Mengimpor dataset dari file Excel
2. Membersihkan dan memvalidasi data
3. Mengubah format data dari wide ke long
4. Mengagregasi total kebutuhan daya per tahun
5. Menghitung statistik deskriptif
6. Menghitung pertumbuhan tahunan
7. Membangun model regresi linier sederhana
8. Membuat visualisasi tren kebutuhan daya listrik
9. Menarik kesimpulan dari hasil analisis

## Hasil Utama
- Kebutuhan daya listrik Provinsi Lampung menunjukkan tren kenaikan yang stabil dari tahun 2025 hingga 2030
- Total kebutuhan daya listrik meningkat dari **4285.308 kVA** pada tahun 2025 menjadi **4500.209 kVA** pada tahun 2030
- Pertumbuhan tahunan berada di kisaran **0,9%–1,06%**
- Model regresi linier menunjukkan kecocokan yang sangat tinggi dengan nilai **R² sekitar 0.9996**

## Insight
Hasil analisis menunjukkan bahwa kebutuhan daya listrik di Provinsi Lampung mengalami pertumbuhan yang konsisten dan cenderung linier. Temuan ini dapat menjadi gambaran awal dalam mendukung perencanaan kapasitas energi dan pengembangan infrastruktur ketenagalistrikan.

## Struktur Folder
```text
analisis-kebutuhan-daya-listrik-lampung/
├── README.md
├── code/
│   └── codeR_9_RA.Rmd
├── data/
│   └── Dataset_9_RA.xlsx
├── docs/
│   ├── Laporan_9_RA.docx
│   └── PPT_9_RA.pdf
└── images/
    └── grafik-tren-daya.png

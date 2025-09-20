# 🌾 Analisis Produksi Padi di Pulau Sumatera

## 📌 Project Overview

Analisis ini menggunakan dataset produksi padi di Pulau Sumatera (1993–2020) untuk memahami tren produksi, membandingkan antarprovinsi, dan mengevaluasi faktor lingkungan (curah hujan, kelembapan, suhu) yang berpengaruh terhadap produksi.

## 🔹 Dataset

- File: `Data_Tanaman_Padi_Sumatera_version_1.csv`
- Jumlah data: 224 baris × 7 kolom
- Kolom: Provinsi, Tahun, Produksi, Luas Panen, Curah hujan, Kelembapan, Suhu rata-rata

## 🔹 Tahapan Analisis

1. **Data Preparation** → cek struktur data, statistik deskriptif, missing values
2. **Data Preprocessing** → encoding variabel kategorikal, normalisasi (opsional)
3. **Exploratory Data Analysis (EDA)** → tren produksi, perbandingan provinsi, korelasi faktor iklim, produktivitas
4. **Conclusion & Reporting** → insight bisnis dan rekomendasi kebijakan

## 🔹 Key Insights

- Produksi padi di Sumatera meningkat hingga puncaknya tahun 2017 (±20,5 juta ton), lalu menurun tajam pada 2018–2020.
- **Sumatera Utara, Sumatera Selatan, dan Lampung** adalah penghasil padi terbesar.
- **Sumatera Barat** memiliki produktivitas tertinggi (±5,17 ton/ha).
- Korelasi kuat antara **luas panen dan produksi (r = 0,90)**, sedangkan faktor iklim relatif lemah.

## 🔹 Conclusion

- Produksi padi di Sumatera menurun signifikan setelah 2017.
- Pusat produksi terbesar ada di Sumatera Utara, Sumatera Selatan, dan Lampung.
- Efisiensi lahan di Sumatera Barat patut dijadikan model untuk provinsi lain.
- **Rekomendasi:** fokus pada **peningkatan produktivitas lahan** melalui teknologi pertanian dan varietas unggul.

## 📂 Struktur Repo

```
padi-sumatera-analysis/
│
├── data/
│   └── Data_Tanaman_Padi_Sumatera_version_1.csv
├── notebooks/
│   └── padi_sumatera_analysis.ipynb
├── report/
│   └── padi_sumatera_analysis_summary.pdf
└── README.md
```

## 📬 Contact

Rendy Lutfi Prabowo  
🌐 [Portfolio Website](https://rendylutfiprabowo.github.io)  
📧 rendylutfiprabowo123@gmail.com

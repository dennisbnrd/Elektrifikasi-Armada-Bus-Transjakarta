# Elektrifikasi-Armada-Bus-Transjakarta

### Deskripsi Proyek
project ini bertujuan untuk menganalisis potensi, dampak, dan strategi elektrifikasi armada Transjakarta berbasis data penumpang, operasional, dan skenario pengurangan emisi. Studi difokuskan pada koridor prioritas sebagai langkah strategis mendukung transportasi publik yang ramah lingkungan dan efisien di Jakarta.

Source:
- [10.000 unit bus listrik pada tahun 2030](https://www.thejakartapost.com/news/2020/12/29/transjakarta-wants-10000-electric-buses-in-service-by-2030.html)
- [Panduan Evaluasi Pilot Bus Listrik di Indonesia](https://itdp-indonesia.org/wp-content/uploads/2023/11/A4-6-copy-Cover-AC-230-isi-matt-100gr.pdf)
- [ZERO EMISSION BUS CHARGING INSIGHTS WITH TRANSJAKARTA](https://cff-prod.s3.amazonaws.com/storage/files/7E8soeS5oOjeNscAR5fPHQThaOl9QFoLKXBr92sT.pdf)
  

### Tujuan
- Mengidentifikasi koridor Transjakarta yang paling optimal untuk elektrifikasi.
- Melakukan estimasi pengurangan emisi CO₂ dan efisiensi biaya operasional.
- Memberikan rekomendasi kebijakan dan implementasi elektrifikasi kepada stakeholder Transjakarta.

### Dataset
- Transjakarta.csv — Data perjalanan, halte, transaksi, dan operasional bus Transjakarta.
- Transjakarta_clean.xlsx — Data yang telah dibersihkan dan diproses untuk analisis.
- map.csv - Data mapping koridor Transjakarta

### Analisis yang Dilakukan
- Exploratory Data Analysis (EDA):
Statistik penumpang, persebaran per koridor, volume penumpang, dan tren perjalanan.
- Simulasi Skenario Elektrifikasi:
Skenario optimis, normal, dan pesimis berdasarkan target jumlah bus listrik.
- Estimasi Pengurangan Emisi:
Kalkulasi potensi pengurangan CO₂ per tahun.
- Visualisasi Data:
Grafik volume penumpang, heatmap kepadatan, dan prioritas koridor.
- Rekomendasi Kebijakan:
Strategi prioritas elektrifikasi, kebutuhan infrastruktur charging, dan evaluasi bertahap.

### Tools 
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Tableau (untuk dashboard dan visualisasi interaktif)

### Installation
Follow these steps to set up and run the Hospital Information System on your local machine:
#### 1. Requirements
Python 3.6 or above must be installed
#### 2. Clone or Download the Project
```bash
git clone https://github.com/dennisbnrd/Elektrifikasi-Armada-Bus-Transjakarta.git
cd Elektrifikasi-Armada-Bus-Transjakarta
```

### Hasil
- Elektrifikasi dapat mengurangi emisi CO₂ hingga 1,5 juta ton/tahun (skenario optimis).
- Efisiensi biaya operasional meningkat dengan penggunaan bus listrik.
- Koridor terpadat layak menjadi prioritas utama elektrifikasi.

### Rencana Pengembangan
- Integrasi data real-time untuk pemantauan operasional bus listrik.
- Analisis cost-benefit dan skenario investasi.
- Dashboard publikasi progres elektrifikasi Transjakarta.

Link Tableau:
[Dashboard Transjakarta](https://public.tableau.com/app/profile/dennisbnrd/viz/dashboard-transjakarta/DashboardTransjakarta)

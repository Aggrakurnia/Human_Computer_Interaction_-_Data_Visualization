# Human Computer Interaction & Data Visualization - Interactive Sales Dashboard

Repositori ini memuat implementasi **Dasbor Penjualan Interaktif** berbasis data *Amazon Sale Report*. Proyek ini merancang visualisasi data yang memenuhi prinsip-prinsip *Human-Computer Interaction* (HCI) untuk membantu analisis tren penjualan eksekutif.

## 📌 Penerapan Prinsip Visualisasi & HCI

1. **Shneiderman's Information Seeking Mantra**:
   - **Overview First**: Menampilkan grafik tren total penjualan harian untuk seluruh wilayah secara keseluruhan.
   - **Zoom & Filter**: Menyediakan widget *dropdown* interaktif untuk memfilter data dan menganalisis tren penjualan berdasarkan wilayah/negara bagian tertentu (misalnya *Jammu & Kashmir*, *Karnataka*, dll.).
   - **Details-on-Demand**: Fitur *hover tooltip* kustom pada titik grafik untuk menampilkan rincian tanggal, total nominal penjualan (INR), serta persentase perubahan harian.
2. **High Data-Ink Ratio**: Menggunakan tema visual minimalis (`plotly_white`) dan mengeliminasi *gridline* yang tidak perlu agar fokus utama pengguna tetap pada data penjualan.

## 📁 Struktur Repositori
- `Human_Computer_Interaction_&_Data_Visualization.ipynb` : Jupyter / Google Colab Notebook utama berisi seluruh alur pembersihan data, pembuatan grafik Plotly, dan integrasi widget interaktif.
- `Amazon Sale Report.csv` : Dataset transaksi penjualan yang digunakan dalam visualisasi.

## 🛠️ Library & Tools
- **Python 3**
- `pandas` (Pembersihan dan agregasi data harian)
- `plotly.express` (Pembuatan grafik garis interaktif dan kustomisasi tooltip)
- `ipywidgets` & `google.colab` (Pembuatan kontrol dropdown filter wilayah)

## Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/Aggrakurnia/Human_Computer_Interaction_-_Data_Visualization.git](https://github.com/Aggrakurnia/Human_Computer_Interaction_-_Data_Visualization.git)

# Bike Sharing Data Analysis Dashboard 🚴‍♂️

Dashboard ini dibuat menggunakan **Streamlit** untuk menganalisis data peminjaman sepeda berdasarkan berbagai faktor seperti musim, waktu, dan jumlah peminjaman.

## 🛠 Setup Environment - Anaconda
```sh
conda create --name bike-sharing python=3.9
conda activate bike-sharing
pip install -r requirements.txt
```

## 🛠 Setup Environment - Shell/Terminal
```sh
mkdir bike_sharing_dashboard
cd bike_sharing_dashboard
pipenv install
pipenv shell
pip install -r requirements.txt
```

## 🚀 Menjalankan Aplikasi Streamlit
```sh
streamlit run bike_sharing_dashboard.py
```

## 📊 Fitur Dashboard
- **Filter Data**: Memilih rentang tanggal dan musim tertentu
- **Tren Peminjaman Sepeda**: Visualisasi harian, bulanan, dan musiman
- **Analisis Berdasarkan Jam**: Pola peminjaman berdasarkan jam dalam sehari
- **Analisis RFM**: Mengukur loyalitas pengguna sepeda

---

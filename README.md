# Capstone Project Module 3: Prediksi Permintaan Bike Sharing

## Gambaran Proyek

Proyek ini merupakan bagian dari Capstone Project Module 3. Tujuan utama dari proyek ini adalah untuk mengembangkan model machine learning yang dapat memprediksi permintaan bike-sharing dengan akurasi tinggi berdasarkan berbagai fitur seperti kondisi cuaca, musim, waktu dalam sehari, dan lain-lain. Dataset yang digunakan dalam proyek ini berkaitan dengan sistem bike-sharing, yang semakin populer di area perkotaan, dan prediksi permintaan sangat penting untuk mengoptimalkan operasi dan sumber daya.

## Dataset

Dataset ini mencakup fitur-fitur berikut:
- **DateTime**: Tanggal dan waktu secara jam dari catatan
- **Season**: Musim dalam setahun (1: Winter, 2: Spring, 3: Summer, 4: Fall)
- **Holiday**: Apakah hari tersebut adalah hari libur atau tidak
- **WorkingDay**: Apakah hari tersebut adalah hari kerja atau tidak
- **Weather**: Situasi cuaca (1: Cerah, 2: Berkabut, 3: Hujan/Salju ringan, 4: Hujan/Salju lebat)
- **Temperature**: Suhu per jam dalam derajat Celsius
- **Humidity**: Kelembaban per jam dalam persentase
- **Windspeed**: Kecepatan angin per jam
- **Casual Users**: Jumlah pengguna non-terdaftar
- **Registered Users**: Jumlah pengguna terdaftar
- **Total Users**: Jumlah total pengguna (variabel target)

## Struktur Proyek

- **Capstone_Project_Modul3_Marcia.ipynb**: Notebook Jupyter yang berisi analisis data, rekayasa fitur, pelatihan model, dan evaluasi.
- **data_bike_sharing.csv**: Dataset yang digunakan untuk proyek ini.
- **BIKE_SHARING.pptx**: Slide presentasi yang merangkum proyek dan temuannya.
- **Bike Sharing.docx**: Dokumen yang memberikan wawasan tambahan atau detail terkait proyek.

## Implementasi Model

Model terbaik dalam proyek ini adalah XGBoost yang telah dioptimalkan dengan hyperparameter tuning.

## Rekayasa Fitur

Beberapa teknik lanjutan diterapkan selama proses rekayasa fitur, termasuk:
- **Encoding Variabel Kategori**: Mengubah variabel kategori menjadi representasi numerik.
- **Seleksi Fitur**: Mengidentifikasi dan mempertahankan hanya fitur yang paling relevan.

## Hasil

Prediksi model ini sesuai dengan permintaan bike-sharing aktual, terutama selama jam sibuk dan musim puncak. Model ini diharapkan dapat membantu perusahaan bike-sharing mengoptimalkan ketersediaan dan distribusi sepeda di seluruh kota, meningkatkan kepuasan pengguna dan efisiensi operasional.

## Pekerjaan Masa Depan

Peningkatan potensial di masa depan meliputi:
- Menggabungkan data real-time untuk prediksi yang lebih dinamis.
- Mengeksplorasi model deep learning untuk akurasi yang lebih baik.
- Memperluas dataset untuk mencakup lebih banyak kota dan periode waktu yang lebih lama.

## Cara Menjalankan Proyek

1. Clone repository:
   ```bash
   git clone https://github.com/marciadevana/CapstoneProjectModule03.git
2. Masuk ke direktori proyek:
   ```bash
   cd CapstoneProjectModule03
3. Buka notebook Jupyter untuk mengeksplorasi analisis:
   ```bash
   jupyter notebook Capstone_Project_Modul3_Marcia.ipynb

# Kontak

Untuk pertanyaan atau umpan balik, silakan hubungi saya di marciadevana20@gmail.com


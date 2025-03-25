# 📊 Data Preprocessing - Handling Missing Values & Encoding

![Processing](https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif)

## 🚀 Overview

Proyek ini mencakup teknik preprocessing data, seperti menangani **missing values**, **encoding data kategorikal**, dan **normalisasi data** menggunakan Python dengan Pandas dan Scikit-Learn. 

## 🔧 Features
- 🔍 **Identifikasi Missing Values**
- 🔄 **Mengisi Missing Values dengan Median**
- 🔢 **Encoding Data Kategorikal**
- 📈 **Normalisasi dengan MinMaxScaler**
- 📊 **Menampilkan Sebelum & Sesudah Preprocessing**
- 💾 **Penyimpanan File Preprocessed**

---

## 📂 Struktur File

```
📂 data_preprocessing_project
│── 📄 Learning_Preprosessing.ipynb  # Notebook utama
│── 📄 train.csv                     # Dataset asli
│── 📄 README.md                     # Dokumentasi ini
```

---

## 🛠️ Instalasi & Penggunaan

Clone repository ini:
```bash
git clone https://github.com/zulfikar1326/Preprosessing-dataset.git
cd Preprosessing-dataset/
```

Jalankan notebook di Google Colab atau Jupyter Notebook:
```bash
    buka Google Colab. lalu pilih
    [file ──> Upload Notebook Baru ──> Pilih Learning_Preprosessing.ipynb]
```

---

## 📜 Penjelasan Singkat Langkah Preprocessing

1️⃣ **Import Library**: Memuat pustaka penting seperti Pandas, Numpy, dan Matplotlib.

2️⃣ **Membaca Dataset**: Membuka file `train.csv` dan menampilkan beberapa baris awal.

3️⃣ **Cek Missing Values**: Mengecek nilai kosong di kolom `LotFrontage` dan `MasVnrArea`.

4️⃣ **Menangani Missing Values**: Mengisi nilai kosong dengan **median** agar distribusi tetap stabil.

5️⃣ **Simpan Data Sebelum Processing**: Data disimpan dalam `before_processing.csv`.

6️⃣ **Encoding Data Kategorikal**: Mengubah kolom **MSZoning** dan **Neighborhood** menjadi numerik dengan LabelEncoder.

7️⃣ **Normalisasi Data**: Menggunakan **MinMaxScaler** agar data berada dalam rentang 0-1.

8️⃣ **Simpan Data Setelah Processing**: Data hasil preprocessing disimpan dalam `after_processing.csv`.

---

## 📊 Hasil Visualisasi

### 🔵 Sebelum Preprocessing
  --ada di Laporan pdf

### 🟢 Sesudah Preprocessing
  --ada di Laporan pdf


## 📬 Kontak & Kontribusi
💡 Punya ide? Fork repository ini, buat perubahan, lalu kirim pull request! 🚀

📩 Hubungi saya di **[instagram](https://www.instagram.com/zulfikarjuniarto/)** atau buka **Issue** jika ada pertanyaan!

⭐ Jangan lupa beri **star** jika proyek ini membantu! ⭐

---



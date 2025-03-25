# 📊 Data Preprocessing - Normalization & Missing Value Handling

![Processing](https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif)

## 🚀 Overview

Proyek ini mencakup teknik preprocessing data, seperti menangani **missing values** dan melakukan **normalisasi data** menggunakan Python dengan Pandas dan Scikit-Learn. 

## 🔧 Features
- 🔍 **Identifikasi Missing Values**
- 🔄 **Mengisi Missing Values dengan Median**
- 📈 **Normalisasi dengan MinMaxScaler**
- 📊 **Visualisasi Sebelum & Sesudah Normalisasi**
- 💾 **Penyimpanan File Preprocessed**

---

## 📂 Struktur File

```
📂 data_preprocessing_project
│── 📄 Learning_Preprosessing.ipynb  # Notebook utama
│── 📂 data
│   │── 📄 train.csv                 # Dataset asli
│   │── 📄 before_normalization.csv  # Data sebelum normalisasi
│   │── 📄 after_normalization.csv   # Data setelah normalisasi
│── 📄 README.md                     # Dokumentasi ini
```

---

## 🛠️ Instalasi & Penggunaan

Clone repository ini:
```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

Jalankan notebook di Google Colab atau Jupyter Notebook:
```bash
jupyter notebook Learning_Preprosessing.ipynb
```

---

## 📜 Penjelasan Singkat Langkah Preprocessing

1️⃣ **Import Library**: Memuat pustaka penting seperti Pandas, Numpy, dan Matplotlib.

2️⃣ **Membaca Dataset**: Membuka file `train.csv` dan menampilkan beberapa baris awal.

3️⃣ **Cek Missing Values**: Mengecek nilai kosong di kolom `LotFrontage` dan `MasVnrArea`.

4️⃣ **Menangani Missing Values**: Mengisi nilai kosong dengan **median** agar distribusi tetap stabil.

5️⃣ **Simpan Data Sebelum Normalisasi**: Data disimpan dalam `before_normalization.csv`.

6️⃣ **Normalisasi Data**: Menggunakan **MinMaxScaler** agar data berada dalam rentang 0-1.

7️⃣ **Simpan Data Setelah Normalisasi**: Data hasil normalisasi disimpan dalam `after_normalization.csv`.

8️⃣ **Visualisasi Perubahan Data**: Membandingkan distribusi sebelum dan sesudah normalisasi dengan histogram.

---

## 📊 Hasil Visualisasi

### 🔵 Sebelum Normalisasi
![Before Normalization](https://media.giphy.com/media/l4pTfx2qLszoacZRS/giphy.gif)

### 🟢 Sesudah Normalisasi
![After Normalization](https://media.giphy.com/media/l3vR3S9XkdoSg7HTW/giphy.gif)

---

## 📍 Letak File Data

| File | Path |
|------|------|
| **Before Normalization** | `/data/before_normalization.csv` |
| **After Normalization**  | `/data/after_normalization.csv`  |

---

## 📬 Kontak & Kontribusi
💡 Punya ide? Fork repository ini, buat perubahan, lalu kirim pull request! 🚀

📩 Hubungi saya di **[LinkedIn](https://www.linkedin.com/in/your-profile)** atau buka **Issue** jika ada pertanyaan!

⭐ Jangan lupa beri **star** jika proyek ini membantu! ⭐

---

![Thanks](https://media.giphy.com/media/3o7TKPdUkkbDfpE68A/giphy.gif)


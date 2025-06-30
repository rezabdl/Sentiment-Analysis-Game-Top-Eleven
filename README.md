# 🎮 Sentiment Analysis on Top Eleven Game Reviews (Play Store)

Proyek ini bertujuan untuk **menganalisis sentimen pengguna** terhadap game **Top Eleven** yang tersedia di Google Play Store. Melalui pendekatan *Natural Language Processing* (NLP), proyek ini mengevaluasi komentar pengguna dan mengklasifikasikannya ke dalam dua kategori utama: **positif** dan **negatif**.

---

## 🧪 Deskripsi Proyek

Analisis ini dilakukan melalui beberapa tahapan, mulai dari **pengambilan data (crawling)** hingga **pemodelan machine learning**. Semua tahapan tersebut terdokumentasi dalam file notebook utama:

📄 **`Analisis Sentiment Review Game Top Eleven.ipynb`**

---

## 📌 Tahapan Analisis

1. **Crawling Data Review**
   Menggunakan library `google-play-scraper` untuk mengambil komentar pengguna game *Top Eleven* langsung dari Google Play Store.

2. **Preprocessing Teks**
   Termasuk pembersihan teks (cleaning), tokenisasi, stopword removal, dan stemming.

3. **Visualisasi Data**

   * WordCloud untuk komentar positif dan negatif
   * Bar chart untuk frekuensi kata

4. **Modeling Sentimen**
   Menggunakan beberapa model *machine learning* seperti:

   * Multinominal Naive Bayes
   * Random Forest
   * K-Nearest Neighboor
   * Support Vector Machine
     untuk mengklasifikasikan sentimen (positif atau negatif).

5. **Evaluasi Model**
   Menggunakan metrik akurasi dan juga melakukan beberapa metode sampling untuk menangani data yang tidak seimbang.

---

## 📁 Struktur Repository

```
📦 Sentiment-Analysis-TopEleven
├── Analisis Sentiment Review Game Top Eleven.ipynb  # Notebook utama
├── laporan_sentimen_top_eleven.pdf                 # Laporan lengkap analisis
├── dataset/                                        # Folder berisi data hasil crawling
├── visualisasi/                                    # Output wordcloud dan grafik
└── README.md                                       # Dokumentasi proyek
```

---

## 📊 Tools & Library

* `google-play-scraper`
* `pandas`, `numpy`
* `nltk`, `Sastrawi`
* `scikit-learn`
* `matplotlib`, `seaborn`
* `wordcloud`

---

## 📈 Hasil

* Model **Random Forest** memberikan performa terbaik dengan akurasi tinggi dalam klasifikasi sentimen.
* Komentar positif didominasi oleh kata-kata seperti "seru", "bagus", dan "strategi".
* Komentar negatif umumnya mengeluhkan soal **bug**, **konektivitas**, atau **pembayaran**.

---


## 👨‍💻 Pengembang

Proyek ini dikembangkan oleh:

* **Reza Irwansyah Aryanto**


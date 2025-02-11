# 🎵 Klasifikasi Genre Musik Menggunakan CNN  

## 📌 Gambaran Proyek  
Proyek ini bertujuan untuk mengklasifikasikan genre musik menggunakan **GTZAN Dataset - Music Genre Classification**, yang terdiri dari **10 genre berbeda**, masing-masing memiliki **100 sampel audio** dengan durasi **30 detik**.  

## 📂 Dataset  
- Dataset terdiri dari **10 genre musik**: Blues, Classical, Country, Disco, HipHop, Jazz, Metal, Pop, Rock, dan Reggae.  
- Setiap sampel musik memiliki **durasi 30 detik** dan digunakan sebagai input untuk ekstraksi fitur.  
- Representasi fitur audio menggunakan **spektrogram** untuk menangkap pola frekuensi dari sinyal suara.  

## 🏗️ Metodologi  
1. **Representasi Fitur:** Mengubah sinyal audio menjadi **spektrogram** untuk memvisualisasikan komponen frekuensi terhadap waktu.  
2. **Arsitektur Model:** Menggunakan **Convolutional Neural Networks (CNNs)** untuk mengekstrak pola dari gambar spektrogram.  
3. **Pelatihan & Evaluasi:** Melatih model CNN menggunakan data spektrogram dan mengevaluasi kinerjanya dengan metrik **Precision, Recall, F1-score, dan AUC**.  

## 📊 Hasil Evaluasi  
Hasil evaluasi model pada data uji ditampilkan dalam tabel berikut:  

| Genre      | Precision | Recall | F1-score | AUC  |
|------------|----------|--------|----------|------|
| Blues      | 69%      | 90%    | 78%      | 96%  |
| Classical  | 100%     | 100%   | 100%     | 100% |
| Country    | 60%      | 46%    | 52%      | 91%  |
| Disco      | 60%      | 50%    | 55%      | 92%  |
| HipHop     | 80%      | 47%    | 59%      | 96%  |
| Jazz       | 77%      | 77%    | 77%      | 98%  |
| Metal      | 82%      | 90%    | 86%      | 99%  |
| Pop        | 45%      | 62%    | 53%      | 92%  |
| Rock       | 56%      | 75%    | 64%      | 93%  |
| Reggae     | 17%      | 17%    | 17%      | 86%  |

Model menunjukkan **akurasi tinggi pada genre Classical, Metal, dan Jazz**, sedangkan performa untuk genre Reggae dan Country masih relatif rendah.  

## 🚀 Pengembangan Selanjutnya  
- Meningkatkan teknik ekstraksi fitur dengan **MFCC atau Mel-spectrogram**.  
- Menerapkan **augmentasi data** untuk meningkatkan akurasi pada genre yang kurang terklasifikasi dengan baik.  
- Mengeksplorasi **arsitektur deep learning lainnya** seperti ResNet atau EfficientNet.  

## 📌 Link Kode Implementasi  
📌 **Kaggle Notebook:** [Music Genre Classification with CNN](https://www.kaggle.com/code/jihaadariefpangestu/music-genre-classification/notebook)  

---

✉️ Jika ada pertanyaan atau saran, jangan ragu untuk menghubungi saya! 🚀

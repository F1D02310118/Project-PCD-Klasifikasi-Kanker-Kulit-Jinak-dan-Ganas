# Klasifikasi Kanker Kulit Jinak dan Ganas

## Nama Anggota

### Zainul Majdi                : F1D02310028
### Mustofa Arif                : F1D02310083
### Apriesna Zulhan             : F1D02310100
### Lalu Maulana Rizki Hidayat  : F1D02310118

## Latar Belakang

### Kanker kulit, khususnya melanoma, berisiko tinggi karena dapat menyebar dengan cepat. Deteksi dini sangat penting, namun membedakan lesi jinak dan ganas secara visual sering kali sulit, bahkan bagi dokter.
### Teknologi AI, terutama Convolutional Neural Network (CNN), menawarkan solusi melalui klasifikasi citra medis. Dataset Skin Cancer: Malignant vs. Benign dari Kaggle, berisi 3.297 gambar lesi yang telah diklasifikasi, sangat mendukung pengembangan model ini.
### Proyek Project-PCD-Klasifikasi-Kanker-Kulit-Jinak-dan-Ganas bertujuan membangun sistem klasifikasi otomatis untuk membantu diagnosis dini kanker kulit secara lebih cepat dan akurat.

## Deskripsi Program

### Program ini adalah sistem klasifikasi otomatis untuk membedakan kanker kulit jinak dan ganas menggunakan analisis citra digital. Sistem melakukan preprocessing gambar (grayscale, median, threshold, sobel dan roberts), ekstraksi fitur tekstur dengan Gray-Level Co-occurrence Matrix (GLCM) pada 4 arah (0°, 45°, 90°, 135°), dan menghasilkan 7 parameter statistik (contrast, homogeneity, dissimilarity, entropy, ASM, energy, correlation). Data dibagi 80:20 untuk training-testing, kemudian diuji menggunakan tiga algoritma: Random Forest, SVM, dan KNN. Evaluasi dilakukan dengan metrik akurasi, precision, recall, F1-score, dan confusion matrix untuk menentukan model terbaik dalam mendiagnosis kanker kulit.

## Tahapan Preprocessing

### Percobaan 1: Robert - Sobel
### Percobaan 2: Median - Roberts - Sobel - Treshold
### Percobaan 3: Rezise - Median - Roberts - Sobel - Treshold
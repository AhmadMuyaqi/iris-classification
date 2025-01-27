# Iris Classification with Random Forest
## Project Description
Proyek ini bertujuan untuk membangun model klasifikasi yang dapat memprediksi jenis spesies bunga iris (Setosa, Versicolor, Virginica) berdasarkan dataset Iris yang ada. Dataset ini diperoleh dari link berikut https://scikit-learn.org/1.5/datasets/toy_dataset.html. Dataset ini terdiri dari empat fitur utama (sepal length, sepal width, petal length, petal width) yang digunakan untuk membedakan antara tiga kelas bunga.

Algoritma Random Forest dipilih karena kemampuannya dalam menangani data dengan baik, menghasilkan akurasi tinggi, serta mampu mengatasi masalah overfitting dengan penggabungan beberapa pohon keputusan (decision trees).

## Goals
1. Klasifikasi Spesies Iris: Membuat model yang mampu mengklasifikasikan bunga iris ke dalam salah satu dari tiga spesies berdasarkan fitur yang ada.
2. Evaluasi Model: Mengevaluasi performa model menggunakan confusion matrix.

## Insight
Keandalan Random Forest: Model Random Forest menghasilkan hasil yang konsisten dan akurat dibandingkan dengan algoritma lainnya seperti Decision Tree atau Logistic Regression.

## Dependencies
Untuk menjalankan proyek ini, Anda memerlukan beberapa pustaka Python:
1. Scikit-learn: Untuk implementasi algoritma Random Forest dan evaluasi model.
2. NumPy: Untuk pengolahan data numerik.
3. Pandas: Untuk pengelolaan dan manipulasi data tabular.

## Advice
1. Eksperimen Parameter Model: Cobalah mengatur parameter n_estimators, max_depth, dan min_samples_split pada Random Forest untuk meningkatkan akurasi model.
2. Perluas Dataset: Untuk penerapan di dunia nyata, pertimbangkan penggunaan dataset yang lebih besar atau lebih kompleks untuk menguji ketahanan model.

# Klasifikasi Jenis Bunga Iris dengan Machine Learning

Tugas studi kasus mata kuliah Informatics Practitioner Lecture Series, mengacu pada materi sesi Zoom 4 bersama Taniza Tajuddin dari Universiti Teknologi MARA Malaysia (Introduction to Machine Learning).

Ringkasan:
Studi kasus ini mengimplementasikan pemodelan supervised classification untuk membedakan tiga spesies bunga Iris (Setosa, Versicolor, Virginica) berdasarkan empat ukuran bunga (panjang dan lebar sepal serta petal). Data dimuat langsung melalui fungsi bawaan load_iris dari scikit-learn.

Metode dan Evaluasi:
1. Pemeriksaan kualitas data, dimensi, keseimbangan kelas, dan visualisasi sebaran fitur.
2. Pembagian data latih 80% dan data uji 20% secara terstrata (stratified) dengan random state 42.
3. Pemanfaatan Pipeline scikit-learn (StandardScaler dan LogisticRegression) agar penskalaan data hanya dipelajari dari data latih demi mencegah data leakage.
4. Perbandingan performa terhadap model Dummy Classifier serta evaluasi lengkap berupa akurasi, presisi, recall, F1 per kelas, macro F1, dan confusion matrix.

Cara Menjalankan:
Buka notebook Klasifikasi Jenis Bunga Iris dengan Machine Learning.ipynb di Google Colab atau Jupyter Notebook lokal, kemudian jalankan seluruh sel secara berurutan.

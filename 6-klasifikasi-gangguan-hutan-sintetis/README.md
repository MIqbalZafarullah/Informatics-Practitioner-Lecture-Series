# Klasifikasi Indikasi Gangguan Hutan dengan Data Sintetis

Tugas studi kasus mata kuliah Informatics Practitioner Lecture Series, mengacu pada materi sesi Zoom 6 bersama Dr. Bart Slagter dari Wageningen University & Research (Attributing Direct Drivers to Deforestation Alerts with Satellite Imagery and AI).

Ringkasan:
Studi kasus ini mendemonstrasikan klasifikasi atribusi penyebab langsung hilangnya tutupan pohon (Pertanian, Pertambangan, dan Gangguan Alam) menggunakan data tabular sintetis 450 sampel yang mencakup fitur indeks vegetasi optik (NDVI) dan sinyal radar SAR Sentinel-1 polarisasi VV.

Metode dan Evaluasi:
1. Menjelaskan perbedaan antara sekadar mendeteksi perubahan tutupan pohon dan memperkirakan jenis aktivitas penyebabnya.
2. Pembagian data stratified 80:20 untuk menangani proporsi kelas yang agak tidak seimbang (50% Pertanian, 30% Pertambangan, 20% Gangguan Alam).
3. Pemodelan menggunakan Random Forest Classifier dan pembanding Dummy Classifier, dengan penekanan pada metrik Macro F1-Score agar performa kelas minoritas dinilai setara.
4. Pembahasan batasan data sintetis dan etika penggunaan AI dalam pemantauan lingkungan.

Cara Menjalankan:
Buka notebook Klasifikasi Indikasi Gangguan Hutan dengan Data Sintetis.ipynb di Google Colab atau Jupyter Notebook lokal, kemudian jalankan seluruh sel secara berurutan.

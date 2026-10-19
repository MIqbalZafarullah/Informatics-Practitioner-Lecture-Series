# Analisis Penjualan dan Risiko Keterlambatan Pembayaran

Tugas studi kasus mata kuliah Informatics Practitioner Lecture Series, mengacu pada materi sesi Zoom 1 bersama Andria Arisal dari BRIN (Make Sense of Data with Analysis and AI).

Ringkasan:
Studi kasus ini menganalisis data transaksi penjualan 12 bulan untuk menjawab dua hal:
1. Mengapa peningkatan penjualan tidak selalu diiringi peningkatan laba bersih operasional.
2. Mengidentifikasi transaksi dan pelanggan yang berisiko terlambat membayar tagihan kredit.

Pendekatan:
1. Analisis tren penjualan, laba bersih, dan pengaruh beban piutang serta diskon.
2. Pemodelan klasifikasi risiko menggunakan Logistic Regression dan Random Forest, lalu dibandingkan dengan baseline Dummy Classifier.
3. Pembagian data latih dan uji menggunakan stratified split rasio 70:30 dengan random seed 42.

Cara Menjalankan:
Buka notebook Analisis Penjualan dan Risiko Keterlambatan Pembayaran.ipynb di Google Colab atau Jupyter Notebook lokal, kemudian jalankan seluruh sel secara berurutan.

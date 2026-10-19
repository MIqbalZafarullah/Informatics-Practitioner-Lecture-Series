# Estimasi Nilai Pi dengan Monte Carlo Berurutan dan Paralel

Tugas studi kasus mata kuliah Informatics Practitioner Lecture Series, mengacu pada materi sesi Zoom 2 bersama Worawan Diaz Carballo dari Thammasat University (Bridging Global Infrastructure to Address Local Challenge with HPC).

Ringkasan:
Studi kasus ini membandingkan kinerja eksekusi sekuensial dan paralel dalam mengestimasi nilai Pi melalui simulasi Monte Carlo. Eksperimen diuji pada beberapa variasi jumlah titik sampel (100 ribu, 1 juta, dan 10 juta) menggunakan 2 worker multiprocessing.

Poin Pembahasan:
1. Menghitung estimasi nilai Pi dan tingkat galat terhadap nilai acuan numpy.pi.
2. Mengukur waktu eksekusi sekuensial dan paralel berdasarkan nilai median dari beberapa ulangan setelah warm-up.
3. Menjelaskan faktor pembatas komputasi paralel pada data kecil dan menengah, seperti overhead komunikasi proses dan Hukum Amdahl.

Cara Menjalankan:
Buka notebook Estimasi Nilai Pi dengan Monte Carlo Berurutan dan Paralel.ipynb di Google Colab atau Jupyter Notebook lokal, lalu jalankan semua sel secara berurutan. File modul worker (mc_worker.py) akan dibuat otomatis oleh sel awal notebook.

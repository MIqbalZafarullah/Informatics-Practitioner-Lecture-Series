# Pemilihan Lokasi Gerai Sederhana Menggunakan Analisis Spasial

Tugas studi kasus mata kuliah Informatics Practitioner Lecture Series, mengacu pada materi sesi Zoom 3 bersama Widi Prima Deva dari Citycare Property Selandia Baru (Carrier and Competition in Industrial Era with GIS).

Ringkasan:
Studi kasus ini mendemonstrasikan pemilihan satu dari tiga kandidat lokasi gerai baru di wilayah simulasi Kota Bengkulu. Evaluasi didasarkan pada dua parameter kuantitatif:
1. Potensi pasar, yaitu total bobot pelanggan dalam radius layanan 2 kilometer.
2. Pencegahan kanibalisasi pasar, yaitu jarak minimum 1 kilometer dari gerai lama terdekat. Kandidat yang berjarak kurang dari 1 km dinyatakan tidak layak.

Metode:
1. Perhitungan jarak nyata permukaan bumi menggunakan rumus Haversine dalam satuan kilometer (bukan selisih derajat koordinat biasa).
2. Pemeringkatan kandidat berdasarkan status kelayakan dan jumlah calon pelanggan yang terjangkau.
3. Visualisasi hasil melalui grafik perbandingan serta peta interaktif berbasis Folium.

Cara Menjalankan:
Buka notebook Pemilihan Lokasi Gerai Sederhana Menggunakan Analisis Spasial.ipynb di Google Colab atau Jupyter Notebook lokal, lalu jalankan semua sel secara berurutan. Peta interaktif akan langsung tampil di dalam notebook dan tersimpan sebagai file HTML.

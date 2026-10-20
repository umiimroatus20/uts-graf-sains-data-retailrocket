# uts-graf-sains-data-retailrocket
Implementasi analisis graf dan sistem rekomendasi menggunakan dataset RetailRocket, Neo4j, Python, dan K-Nearest Neighbors (KNN).

# UTS Graf Sains Data — RetailRocket

## Deskripsi

Repository ini berisi pengerjaan Ujian Tengah Semester (UTS) mata kuliah Graf Sains Data menggunakan dataset RetailRocket. Pengerjaan mencakup pengolahan data interaksi, pembentukan graf di Neo4j, Vector Space Modelling (VSM), perhitungan cosine similarity, dan sistem rekomendasi menggunakan K-Nearest Neighbors (KNN).

## Tujuan

- Mengimpor data interaksi pengunjung dan produk ke Neo4j.
- Membagi data menjadi periode training (P1) dan testing (P2).
- Menganalisis proyeksi graf User–User dan Item–Item.
- Menghitung kemiripan antar-User menggunakan cosine similarity.
- Membuat dan mengevaluasi rekomendasi menggunakan Hit@5 dan NDCG@5.

## Dataset

Dataset yang digunakan adalah RetailRocket, khususnya `events.csv`, yang memuat timestamp, visitor ID, jenis interaksi, item ID, dan transaction ID.

Dataset periode training dan testing disimpan sebagai `events_P1.csv` dan `events_P2.csv`.

## Teknologi

- Python
- Pandas dan NumPy
- SciPy
- scikit-learn
- NetworkX dan Matplotlib
- Neo4j dan Neo4j Python Driver
- Jupyter Notebook

## Struktur Repository

- `uts_graf.ipynb`: kode, hasil analisis, visualisasi, dan pembahasan.
- `requirements.txt`: daftar library Python.
- `data/`: dataset dan hasil pemisahan periode P1/P2.

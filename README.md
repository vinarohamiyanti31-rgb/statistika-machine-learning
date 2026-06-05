# statistika-machine-learning
# Statistical Machine Learning

## Segmentasi Pelanggan dengan K-Means Clustering pada Dataset Wholesale Customers

Repository ini berisi tugas mata kuliah **Statistical Machine Learning (SML)** mengenai penerapan algoritma **K-Means Clustering** untuk melakukan segmentasi pelanggan berdasarkan pola pengeluaran menggunakan **Wholesale Customers Dataset** dari **UCI Machine Learning Repository**.

Analisis dilakukan menggunakan bahasa pemrograman **R** dengan tahapan preprocessing data, standardisasi menggunakan metode **Z-Score**, penentuan jumlah cluster optimal menggunakan **Elbow Method** dan **Silhouette Method**, proses **K-Means Clustering**, evaluasi hasil clustering, analisis hierarchical clustering, serta pengujian kestabilan model menggunakan **Bootstrap Stability Analysis**.

### Tujuan

Melakukan pengelompokan pelanggan berdasarkan karakteristik pembelian sehingga diperoleh beberapa segmen pelanggan yang memiliki pola pengeluaran yang serupa dan dapat digunakan sebagai dasar analisis perilaku pelanggan.

### Dataset

* **Nama Dataset** : Wholesale Customers Dataset
* **Sumber** : UCI Machine Learning Repository
* **Jumlah Observasi** : 440
* **Jumlah Variabel** : 8
* **Variabel Numerik** :

  * Fresh
  * Milk
  * Grocery
  * Frozen
  * Detergents_Paper
  * Delicassen

Variabel **Channel** dan **Region** tidak digunakan dalam proses clustering karena metode K-Means hanya bekerja pada data numerik.

### Metode Analisis

* Data Preprocessing
* Pemeriksaan Missing Value
* Seleksi Variabel
* Standardisasi Data (Z-Score)
* Penentuan Jumlah Cluster Optimal (Elbow Method & Silhouette Method)
* K-Means Clustering
* Visualisasi Cluster
* Silhouette Evaluation
* Hierarchical Clustering (Dendrogram)
* Analisis Karakteristik Cluster
* Bootstrap Stability Analysis

### Hasil Utama

* Jumlah cluster optimal yang diperoleh adalah **2 cluster**.
* **Cluster 1** terdiri dari **41 pelanggan** dengan tingkat pengeluaran relatif lebih tinggi.
* **Cluster 2** terdiri dari **399 pelanggan** dengan tingkat pengeluaran relatif lebih rendah dan lebih homogen.
* Nilai rata-rata **Silhouette Score = 0.59**, yang menunjukkan kualitas clustering berada pada kategori cukup baik.
* Hasil **Bootstrap Stability Analysis** menunjukkan bahwa struktur cluster yang terbentuk cukup stabil untuk digunakan dalam analisis lebih lanjut.

### Tools

* R
* RStudio
* Packages:

  * readxl
  * factoextra
  * cluster
  * fpc
  * ggplot2
  * tidyr

### File Repository

* `Project_SML.Rmd` → Source code analisis.
* `Project_SML.html` → Output laporan.
* `Wholesale Customers Dataset.xlsx` → Dataset yang digunakan.

---

## Penulis

**Vina Rohamiyanti**
NIM : 3338240007
Program Studi Statistika
Universitas Sultan Ageng Tirtayasa

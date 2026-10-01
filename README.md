 ## **Kualitas Udara Antar Negara Tahun 2023**

* **Kelompok: Kelompok 14**
* **Nama dan NRP:**
    1. Dennis Immanuel Stevano Baskoro - 5027261096
    2. Eric Fahrezi Hutagalung - 5027261138
    3. Fikri Taqiyuddin Althaf - 5027261077
* **Topik:** Eksplorasi Data tentang Kualitas Udara Antar Negara Tahun 2023.
* * Sumber data dan lisensi: (https://www.kaggle.com/datasets/waqi786/global-air-quality-dataset), dengan lisensi Apache 2.0.
* * 3 Temuan Utama: 
1. **Distribusi Data Sangat Simetris & Seragam (*Uniform Distribution*)**
   - Nilai **Rata-rata (*Mean*)** dan **Nilai Tengah (*Median*)** pada seluruh polutan berhimpit hampir sempurna (contoh PM2.5: $\text{Mean} = 77.45$, $\text{Median} = 77.72$).
   - Histogram menunjukkan tinggi frekuensi yang relatif seimbang di seluruh interval nilai (sekitar 450–500 data per *bin*), menandakan data tersebar merata tanpa kemiringan (*no skewness*).

2. **Tidak Ada Perbedaan Polusi yang Signifikan Antar Kota Maupun Kondisi Kelembapan**
   - Rata-rata kadar polutan (seperti PM2.5) di seluruh kota berada di kisaran yang sangat mirip ($76–78 \ \mu\text{g/m}^3$).
   - Pengelompokan kota berdasarkan tingkat kelembapan (**Tinggi** vs **Rendah**) menghasilkan rata-rata kadar PM10 ($\sim 104.4$) dan NO2 ($\sim 52.2$) yang identik, mengindikasikan tidak adanya pengaruh signifikan dari variabel kelembapan terhadap tingkat polutan pada dataset ini.

3. **Data Bersih dari Outlier & Berkarakteristik Data Simulasi (*Synthetic Data*)**
   - Hasil analisis **Boxplot** menunjukkan tidak ada titik data ekstrem (*outlier*) di luar batas garis *whisker*.
   - Karakteristik data yang sangat rapi, tersebar merata, simetris, dan bebas dari *outlier* mengindikasikan bahwa dataset ini merupakan **data buatan/simulasi (*synthetic dataset*)** yang dibangkitkan menggunakan pembuat angka acak terdistribusi seragam (*random uniform generator*).

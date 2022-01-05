# RFM-Cohort

Pada kesempatan ini akan dilakukan RFM analisis dan Cohort analisis menggunakan Online Retail dataset dari https://www.kaggle.com/hellbuoy/online-retail-customer-clustering

Dataset ini berisi kumpulan transaksi yang terjadi antara 01/12/2010 dan 09/12/2011 untuk ritel toko online yang berbasis di Inggris. 
Utamanya, perusahaan ini menjual hadiah untuk seluruh kesempatan. Banyak pelanggan dari perusahaan adalah grosir. 

Analisis yang dilakukan:
1. Exploratory
   - Distribusi jumlah pesanan, pendapatan dan tipe barang tiap pelanggan memiliki grafik yang sangat condong ke kanan.
     Terdapat rentang yang sangat jauh dari data di Quartile 3 ke nilai maksimum.
     Penyebaran ini menunjukkan bahwa kebanyakan pelanggan hanya memesan sedikit barang dan membelanjakan sedikit uangnya untuk produk perusahaan ini.
     Tetapi terdapat sebagian kecil pelanggan yang sangat berkontribusi besar terhadap kegiatan bisnis perusahaan.
   - Lebih dari 80% pelanggan dan pendapatan berasal dari Inggris. Hal ini wajar karena perusahaan berbasis di Inggris.
     Kebanyakan Pelanggan berasal dari Benua Eropa.
     Produk yang dijual juga telah mencapai negara-negara di Asia, Australia, Amerika Utara dan Amerika Selatan.
   - Produk yang paling banyak terjual adalah hiasan dan ornamen.
     Terdapat 1554 produk yang hanya terjual satu kali.
   - Setelah Oktober 2010, terjadi peningkatan tajam jumlah penjualan. Jumlah penjualan meningkat pada akhir tahun
     dan menurun saat awal tahun, diprediksi bahwa banyak pelanggan memberi hadiah dan dekorasi untuk kebutuhan perayaan natal dan tahun baru.
2. RFM analisis
   - Distribusi nilai Recency condong ke kanan. Dapat dikatakan bahwa kebanyakan pelanggan masih membeli produk yang dijual.
   - Distribusi nilai Frequency sangat condong ke kanan. Hal ini menunjukkan bahwa Sebagian besar pelanggan melakukan sedikit pembelian. 
   - Distribusi nilai Monetary sangat condong ke kanan. Berarti, sebagian besar pelanggan mengeluarkan sedikit uangnya untuk membeli produk perusahaan. 
3. Segmentasi pasar
   - Dilakukan segmentasi berdasarkan nilai RFM dengan skala 5 yaitu : 1.Top, 2.High Value, 3. Medium Value, 4. Low Value, 5. Lost
   - Semakin tinggi nilai RFM, semakin tinggi posisi segmentasi pelanggan.
     Semakin tinggi posisi segmentasi, semakin sedikit jumlah pelanggan dalam segmentasi tersebut.
   - Segmentasi Top adalah pelanggan yang bernilai besar bagi perusahaan. Karena sering berbelanja, dengan jumlah yang besar dan mengeluarkan uang yang banyak
4. Cohort analisis 
   - Pada masa-masa awal, terjadi penururan tajam untuk tingkat Customer Retention. Tetapi seiring berjalan waktu, terjadi kenaikan tingkat retention.
     Hal ini terbilang baik, karena berarti pada awalnya jumlah pelanggan menurun. Tetapi pelanggan yang ada masih tetap bertahan, 
     dan diikuti dengan penambahan pelanggan baru. Sehingga menunjukkan pertumbuhan positif untuk jumlah pelanggan.
   - Terjadi peningkatan tajam tingkat Quantity Retention yang bahkan melewati nilai awal. 
     Hal ini menunjukkan bahwa jumlah penjualan semakin banyak seiring berjalannya waktu.
     Berdasarkan posisi pada tanggal terakhir, tingkat retention lebih tinggi dibandingkan 8 bulan awal.
   - Jumlah penjualan menurun sejak awal membeli (x=0) kemudian hampir mendekati angka 0, tetapi mulai naik sejak CohortIndex 10.
     Hal ini menunjukkan bahwa pelanggan yang sudah terdaftar sejak 01-2010, banyak yang kembali bertransaksi pada periode 10-2010 dan terus bertransaksi hingga saat ini.
     Banyak pelanggan baru yang puas dengan layanan dari perusahaan dan tetap memilih perusahaan ini untuk keperluan hadiah.

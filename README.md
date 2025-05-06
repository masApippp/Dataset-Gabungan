# Dataset-Gabungan
Proyek ini membangun model machine learning menggunakan algoritma Decision Tree untuk membedakan dua jenis serangan jaringan: Recon OS Scan dan DoS UDP Flood. Dua dataset yang merepresentasikan masing-masing serangan digabungkan menjadi satu, lalu diproses dengan memilih fitur-fitur yang relevan dari kolom 10 hingga 74 sebagai input, dan kolom ke-83 sebagai target klasifikasi.

Setelah data dibagi menjadi data latih dan data uji dengan rasio 80:20, model Decision Tree dilatih menggunakan kriteria entropy dan metode pembelahan acak untuk membentuk struktur pohon yang optimal. Model ini kemudian memprediksi kelas dari data uji, dan hasilnya dievaluasi menggunakan metrik akurasi serta divisualisasikan melalui diagram pohon keputusan dan matriks kebingungan (confusion matrix).

Akurasi model dihitung untuk mengetahui sejauh mana model mampu mengenali pola serangan. Visualisasi tambahan seperti pohon keputusan dan heatmap membantu memahami bagaimana model mengambil keputusan dan seberapa baik klasifikasinya terhadap tiap kelas.

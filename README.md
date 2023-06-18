# Credit Default Risk Prediction

Proyek ini bertujuan untuk mengembangkan model prediksi yang dapat mengklasifikasikan risiko kredit default. Dataset yang digunakan berisi informasi tentang klien, demografi klien, dan transaksi klien. Tugas klasifikasi adalah untuk memprediksi apakah pemilik kredit akan melakukan pembayaran yang default atau tidak.

## Gambaran Proyek

PT Home Credit Indonesia, sebuah lembaga keuangan yang menyediakan layanan pembiayaan, memerlukan model prediksi risiko kredit yang akurat untuk mengelola dana pinjaman dengan efektif dan mengurangi risiko keuangan. Model ini akan membantu dalam mengelola dana pinjaman, memperkirakan risiko kredit, menentukan suku bunga yang tepat, dan menilai kelayakan keuangan peminjam.

## Permasalahan

Permasalahan utama dalam proyek ini adalah mengembangkan model klasifikasi yang dapat memprediksi kemungkinan risiko kredit default secara akurat. Model ini akan dilatih dan dievaluasi menggunakan berbagai algoritma pembelajaran mesin, termasuk regresi logistik, XGBoost, dan LightGBM. Performa model akan dievaluasi menggunakan metrik seperti ROC-AUC, akurasi, dan recall. Tujuannya adalah mengidentifikasi model dengan performa prediksi tertinggi dan memilihnya sebagai model prediksi risiko kredit default akhir.

## Deskripsi Data

Dataset ini terdiri dari informasi klien, termasuk fitur demografi seperti usia, jenis kelamin, status perkawinan, dan tingkat pendidikan, serta fitur transaksi seperti jumlah pinjaman, riwayat pembayaran, dan penggunaan kredit. Variabel target adalah status risiko kredit default, yang menunjukkan apakah klien mengalami pembayaran default atau tidak.

## Evaluasi Model

Model akan dievaluasi berdasarkan kemampuannya dalam mengklasifikasikan risiko kredit default dengan benar. Metrik evaluasi utamanya adalah ROC-AUC, yang memberikan penilaian keseluruhan terhadap kemampuan model dalam membedakan kasus risiko default dan bukan default. Metrik tambahan seperti akurasi, presisi, dan recall akan digunakan untuk analisis lebih lanjut dan penilaian performa model.

## Alur Proyek

1. Preproses data: Lakukan pembersihan data, penanganan nilai yang hilang, penanganan outlier, dan pengkodean fitur kategori.
2. Rekayasa fitur: Buat fitur tambahan jika diperlukan dan pilih fitur yang relevan.
3. Pelatihan model: Latih beberapa model pembelajaran mesin termasuk regresi logistik, XGBoost, dan LightGBM.
4. Evaluasi model: Evaluasi model menggunakan berbagai metrik seperti ROC-AUC, akurasi, presisi, dan recall.
5. Penyetelan hiperparameter: Optimalkan model yang dipilih dengan menyetel hiperparameter menggunakan teknik seperti pencarian acak atau pencarian grid.
6. Pemilihan model akhir: Pilih model dengan performa terbaik berdasarkan metrik evaluasi.
7. Inferensi model

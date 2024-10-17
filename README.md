# Klasifikasi Tweet dengan Menggunakan Metode Long Short-Term Memory (LSTM), Decision Tree, dan Random Forest
------

# DESKRIPSI 
Proyek ini berfokus pada klasifikasi emosi dari data teks menggunakan model machine learning. Beberapa metode yang digunakan termasuk Long Short-Term Memory (LSTM), Decision Tree, dan Random Forest untuk mendeteksi emosi. Emosi yang diklasifikasikan terdiri dari empat kategori: marah, senang, sedih, dan takut. Dataset yang digunakan diambil dari Kaggle dan terdiri dari tweet yang diproses dan direpresentasikan menggunakan dua teknik: TF-IDF dan Word2Vec (Skipgram).

# TUJUAN 
1. Mengembangkan model yang dapat secara otomatis mengklasifikasikan emosi dari data teks dengan akurasi yang optimal.
2. Aplikasi ini dapat bermanfaat dalam analisis sentimen di berbagai bidang, seperti pengambilan keputusan bisnis atau pemantauan kesehatan mental.

# ALUR KERJA 
- Pengumpulan Data: Dataset diambil dari data terbuka Kaggle dan berisi tweet yang diberi label dengan empat kategori emosi, yaitu marah (anger), senang (joy), sedih (sadness), dan takut (fear).
- Exploratory Data Analysis (EDA): Analisis awal dilakukan untuk memahami distribusi dan karakteristik data.
    - Menangani missing value 
    - Visualisasi data ( penyebaran data )
- Preprocessing Teks: Meliputi case folding, pembersihan, penyaringan, dan tokenisasi untuk mempersiapkan data mentah menjadi siap diolah.
- Representasi Teks: Data diubah menggunakan dua metode: TF-IDF dan Word2Vec (Skipgram).
- Pemodelan: Tiga model klasifikasi—LSTM, Decision Tree, dan Random Forest—diterapkan pada dataset.
- Evaluasi: Model dievaluasi berdasarkan kinerjanya menggunakan metrik seperti akurasi, presisi, recall, dan F1-score.

# KESIMPULAN 
Model terbaik untuk klasifikasi emosi berbasis teks adalah Decision Tree dan Random Forest, keduanya menggunakan representasi TF-IDF. Random Forest mencapai akurasi tertinggi sebesar 83% pada data uji, menjadikannya model yang optimal untuk tugas ini. Model lain, termasuk LSTM dengan Word2Vec, menunjukkan akurasi lebih rendah dan mengalami masalah seperti overfitting.

# TIM 
- Sherryl Kurniawan
- Nayla Anandhita Darmawan 
- Gisela Elviany 

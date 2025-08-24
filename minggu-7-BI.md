
# 📘 Modul Ajar Minggu 7

**Mata Kuliah:** Bahasa Indonesia
**Minggu:** 7
**Topik:** Metodologi Penelitian (Contoh Kasus: Teknik Informatika)

---

## 🎯 CPMK (Capaian Pembelajaran Mata Kuliah) Minggu 7

Setelah mengikuti pembelajaran Minggu 7, mahasiswa mampu:

1. Menjelaskan hakikat metodologi penelitian dalam konteks penelitian Teknik Informatika.
2. Mendeskripsikan berbagai desain penelitian (eksperimen, deskriptif, studi kasus, pengembangan perangkat lunak).
3. Menyusun bagian metodologi proposal skripsi/proyek akhir informatika.
4. Menjelaskan prosedur eksperimen, instrumen, teknik pengumpulan data, dan analisis dalam penelitian informatika.
5. Menghubungkan metodologi dengan tujuan penelitian (misalnya evaluasi sistem, pengujian algoritma, pengukuran kinerja).
6. Menunjukkan keterampilan menyusun metodologi yang feasible dan sesuai standar akademik.

---

## 1. Pendahuluan 

Dalam dunia Teknik Informatika, penelitian tidak hanya berhenti pada ide atau desain sistem, tetapi harus dapat **dibuktikan melalui metodologi yang jelas**. Misalnya, mahasiswa yang meneliti *“Sistem Deteksi Intrusi Menggunakan Machine Learning”* harus menjelaskan bagaimana data dikumpulkan, algoritma dipilih, parameter ditetapkan, dan performa diuji.

Metodologi penelitian dalam informatika sering melibatkan **eksperimen dengan dataset, simulasi, pengembangan perangkat lunak, maupun studi kasus di dunia nyata**. Tanpa metodologi yang tepat, hasil penelitian sulit dipercaya atau direplikasi. Oleh karena itu, minggu ini mahasiswa dilatih menyusun metodologi yang bukan sekadar formalitas, tetapi benar-benar menjadi panduan penelitian yang kuat.

---

## 2. Uraian Materi 

### 2.1 Pengertian Metodologi Penelitian

Dalam konteks informatika:

* **Metode penelitian**: cara spesifik (misalnya pengujian *accuracy* model machine learning).
* **Metodologi penelitian**: kerangka lengkap (jenis penelitian, dataset, tools, prosedur, evaluasi).

---

### 2.2 Desain Penelitian Informatika

1. **Penelitian Eksperimen**

   * Menguji algoritma atau sistem.
   * Contoh: membandingkan akurasi algoritma *Random Forest* vs *SVM* untuk klasifikasi malware.

2. **Penelitian Deskriptif**

   * Mendeskripsikan fenomena dengan data.
   * Contoh: survei penggunaan framework *React Native* pada startup lokal.

3. **Studi Kasus**

   * Meneliti sistem di satu instansi.
   * Contoh: implementasi *Intrusion Detection System* di jaringan kampus.

4. **Research & Development (R\&D)**

   * Mengembangkan dan menguji prototipe.
   * Contoh: pengembangan aplikasi mobile absensi berbasis *face recognition*.

5. **Mixed Methods**

   * Kombinasi kuantitatif (uji performa) dan kualitatif (user experience).
   * Contoh: evaluasi aplikasi e-learning dengan pengujian load server dan wawancara pengguna.

---

### 2.3 Komponen Metodologi Penelitian Informatika

1. **Jenis Penelitian**

   * Eksperimen, deskriptif, studi kasus, R\&D.

2. **Objek/Subjek Penelitian**

   * Dataset, aplikasi, sistem, pengguna.
   * Contoh: 500 data serangan DDoS dari dataset CICIDS2017.

3. **Instrumen Penelitian**

   * Tools/software (Python, WEKA, TensorFlow, Wireshark).
   * Hardware (server, router, IoT device).
   * Kuesioner (untuk user experience).

4. **Prosedur Penelitian**

   * Tahap-tahap runtut:
     a. Identifikasi masalah.
     b. Pengumpulan data (dataset publik atau data lapangan).
     c. Preprocessing data (normalisasi, feature selection).
     d. Implementasi algoritma/sistem.
     e. Pengujian (accuracy, precision, recall, latency).
     f. Analisis hasil.

5. **Teknik Pengumpulan Data**

   * Dataset publik: MNIST, KDDCup99, CICIDS.
   * Log jaringan, observasi penggunaan aplikasi.
   * Kuesioner untuk usability testing.

6. **Teknik Analisis Data**

   * Statistik (uji t, ANOVA).
   * Evaluasi kinerja algoritma (confusion matrix, ROC curve).
   * Analisis kualitatif dari wawancara pengguna.

---

### 2.4 Eksperimen & Analisis Kinerja

Dalam informatika, eksperimen umumnya berupa:

* Uji kinerja algoritma: akurasi, precision, recall, F1-score.
* Uji sistem: *response time, throughput, CPU usage*.
* Uji aplikasi: *usability testing* (SUS – System Usability Scale).

**Contoh eksperimen:**
*“Algoritma CNN diuji pada dataset 10.000 citra wajah. Model diuji menggunakan *train-test split* 80:20, dengan metrik evaluasi berupa akurasi, precision, recall, dan F1-score.”*

---

### 2.5 Penutup Metodologi

Akhiri metodologi dengan kalimat penegasan:
*“Dengan metodologi yang dirancang, penelitian ini diharapkan dapat menjawab pertanyaan penelitian mengenai efektivitas algoritma X dalam mendeteksi serangan Y.”*

---

## 3. Contoh Analisis 

**Metodologi Lemah (contoh skripsi):**
*“Penelitian ini menggunakan metode eksperimen. Data diambil dari internet. Algoritma diuji dengan komputer.”*

**Analisis:** terlalu umum, tidak jelas dataset apa, algoritma apa, evaluasi apa.

**Metodologi Kuat (contoh skripsi informatika):**
*“Penelitian ini menggunakan metode eksperimen. Dataset CICIDS2017 (100.000 record traffic jaringan) digunakan sebagai data uji. Data diproses dengan normalisasi Min-Max. Algoritma *Random Forest* dan *SVM* diimplementasikan menggunakan Python (scikit-learn). Proses training menggunakan 80% data, testing 20%. Evaluasi menggunakan confusion matrix dengan metrik akurasi, precision, recall, dan F1-score. Pengujian dilakukan pada PC dengan prosesor Intel i7, RAM 16GB. Hasil dibandingkan dengan studi A (2019).”*

**Analisis:** lengkap, detail, dapat direplikasi, dan kredibel.

---

## 4. Latihan 

1. Sebutkan perbedaan penelitian eksperimen dan R\&D dalam konteks informatika.
2. Buat desain metodologi untuk penelitian “Aplikasi Chatbot Layanan Akademik Berbasis NLP”.
3. Jelaskan teknik evaluasi kinerja algoritma machine learning (accuracy, precision, recall, F1-score).
4. Susun metodologi singkat untuk penelitian “Analisis Keamanan Jaringan IoT menggunakan IDS”.

---

## 5. Mini Project 

Tugas individu: Buat bagian **Metodologi Penelitian (2–3 halaman)** dari proposal skripsi dengan tema Teknik Informatika. Contoh tema:

* Deteksi Malware berbasis Machine Learning.
* Aplikasi Absensi dengan Face Recognition.
* Analisis Sentimen Twitter tentang Pemilu.
* Optimasi Algoritma Genetika untuk Penjadwalan Kuliah.

Format metodologi harus memuat:

1. Jenis penelitian.
2. Objek/subjek.
3. Instrumen (software/hardware).
4. Prosedur penelitian.
5. Teknik analisis data.

---

## 6. Rangkuman 

* Metodologi adalah kerangka *bagaimana penelitian dilakukan*.
* Dalam informatika, metodologi biasanya berupa eksperimen, studi kasus, atau pengembangan perangkat lunak.
* Komponen utama: jenis penelitian, objek/subjek, instrumen, prosedur, analisis data.
* Eksperimen menekankan pengujian algoritma/sistem dengan dataset tertentu.
* Analisis kinerja dapat berupa metrik statistik, evaluasi sistem, atau usability testing.
* Metodologi yang baik harus jelas, detail, sistematis, dan dapat direplikasi.

---

## 7. Referensi

1. Agus Nero Sofyan, dkk. (2007). *Bahasa Indonesia dalam Penulisan Karya Ilmiah*. Bandung: Universitas Widyatama.
2. R. Soedradjad. (2004). *Teknik Menulis Ilmiah*.
3. Creswell, J.W. (2018). *Research Design: Qualitative, Quantitative, and Mixed Methods Approaches*.
4. Swales, J.M. & Feak, C.B. (2004). *Academic Writing for Graduate Students*.
5. Morrison, M. (2004). *Tips on Scientific Writing*.
6. CICIDS (2017). *Intrusion Detection Evaluation Dataset*.
7. Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.

---


# meachine_learning-pertemuan7
## 7. Praktikum Bab 7: Evaluasi Model Komprehensif & Stratified K-Fold

### 1. Evaluasi Komprehensif & Kurva (Praktikum 1):
- *Confusion Matrix & Classification Report:* Memberikan rincian metrik Precision, Recall, dan $F_1$-Score untuk mengukur performa model secara adil, terutama pada data yang kompleks.
- *ROC & PR Curve:* Nilai AUC yang tinggi (mendekati 1.0) menunjukkan kemampuan model dalam memisahkan kelas positif dan negatif dengan sangat baik di berbagai ambang batas (threshold)[cite: 10].

### 2. Stratified K-Fold Cross-Validation (Praktikum 2 / Prak 7.6):
- *Tujuan:* Membandingkan beberapa algoritma secara objektif dengan membagi data menjadi beberapa lipatan (folds) sambil mempertahankan proporsi kelas aslinya.
- *Analisis:* Standar deviasi skor $F_1$ yang kecil menunjukkan bahwa performa model stabil dan tidak bergantung pada pembagian data latih/uji tertentu, sehingga estimasi kinerjanya sangat andal[cite: 10].

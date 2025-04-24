
# Klasifikasi Kredit Komputer dengan Decision Tree

## Tujuan
Membangun model klasifikasi untuk menentukan apakah seseorang layak mendapatkan kredit komputer berdasarkan fitur: usia, penghasilan, status mahasiswa, dan rating kredit.

## Tahapan Pembuatan Model

### 1. Persiapan Data
- Membuat dataset dummy berisi informasi karakteristik user dan label `Buys_Computer` (0 = Tidak, 1 = Ya).
- Data dikonversi ke bentuk numerik menggunakan Label Encoding.

### 2. Pemisahan Fitur dan Target
- Memisahkan fitur (X) dan label (y).

### 3. Pembagian Data
- Data dibagi menjadi data latih dan data uji menggunakan `train_test_split`.

### 4. Pembuatan dan Pelatihan Model
- Menggunakan `DecisionTreeClassifier` dengan kriteria `entropy`.
- Model dilatih dengan data latih.

### 5. Evaluasi Model
- Dilakukan evaluasi menggunakan `accuracy_score`, `confusion_matrix`, dan `classification_report`.

### 6. Visualisasi Model
- Visualisasi pohon keputusan menggunakan `plot_tree`.

## Hasil
Model dapat digunakan untuk memprediksi kelayakan kredit komputer berdasarkan input data baru.

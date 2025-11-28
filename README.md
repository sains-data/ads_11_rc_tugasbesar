# PREDIKSI IPK MAHASISWA ITERA BERDASARKAN JAM BELAJAR PER MINGGU
## Analisis Regresi Linier Sederhana

**Mata Kuliah** : Analisis Data Statistika 2025  
**Dosen Pengampu** : 1. Mika Alvionita S, M.Si
                     2. Febri Dwi Irawati, M.Si
                     3. Dewi Indra Setiawan, S.Si., M.Si.
**Penulis** : 1. Abigael Limbong (124450080)
              2. Abdul Hakim Amrulloh ( 124450057)
              3. Alya Ramadhanti (124450091)
              4.Bunga Clarisa Sefa (124450097)
  
**Program Studi** : Sains Data  
**Institusi** : Institut Teknologi Sumatera  
**Tahun Akademik** : 2024/2025  

---

## 📋 ABSTRAK

Penelitian ini menganalisis hubungan antara jam belajar per minggu dengan Indeks Prestasi Kumulatif (IPK) mahasiswa Institut Teknologi Sumatera (ITERA) menggunakan metode regresi linier sederhana. Data dikumpulkan lebih dari 400  responden mahasiswa ITERA dengan variabel independen jam belajar per minggu dan variabel dependen IPK. Hasil analisis menunjukkan tidak terdapat hubungan yang signifikan secara statistik antara kedua variabel tersebut, dengan koefisien determinasi (R-squared) sebesar 0.5% dan nilai p-value 0.194.

---

## 🎯 TUJUAN PENELITIAN

1. Menganalisis hubungan linear antara jam belajar per minggu dengan IPK mahasiswa ITERA
2. Membuat model prediksi IPK berdasarkan variabel jam belajar
3. Mengidentifikasi faktor-faktor yang mungkin mempengaruhi hasil analisis
4. Memberikan rekomendasi berdasarkan temuan penelitian

---

## 📊 METODOLOGI PENELITIAN

### **Jenis Analisis**
- Regresi Linier Sederhana (Simple Linear Regression)

### **Variabel Penelitian**
- **Variabel Independen (X)** : Jam Belajar per Minggu
- **Variabel Dependen (Y)** : Indeks Prestasi Kumulatif (IPK)

### **Teknik Pengumpulan Data**
- Pengumpulan data dilakukan dengan menyebar kuesioner Google Form kepada seluruh mahasiswa berbagai program studi yang ada di ITERA
- Jumlah sampel: 458 mahasiswa ITERA
- Periode pengumpulan: 26 Oktober 2025 - 28 Oktober 2025

### **Tools dan Software**
- **R Studio** versi 4.3.1
- **Package** : ggplot2, dplyr, knitr, lattice
- **Git** untuk version control

---

## 🔍 HASIL ANALISIS

### **Model Regresi**
IPK = 62.78 + 0.00042 × Jam_Belajar


### **Statistik Model**
- **Intercept (a)** : 3.260034 
- **Slope (b)** : 0.00009329772
- **p-value** : 0.5747
- **Standard Error** : 0.0001660428 

### **Interpretasi Hasil**
- Nilai p-value 0.5747 (> 0.05) mengindikasikan hubungan tidak signifikan
- Slope yang mendekati nol (0.00042) menunjukkan pengaruh yang sangat kecil

---

## 📈 VISUALISASI DATA

### **Scatterplot dengan Garis Regresi**
![Scatterplot](visuals/http://127.0.0.1:26897/chunk_output/s/8ABF91E5/cpytu8z3cbpz1/00002a.png?resize=20)

### **Distribusi Jam Belajar**
![Histogram Jam Belajar](visuals/http://127.0.0.1:26897/chunk_output/s/8ABF91E5/cj8yalyppw4ws/000028.png?resize=21)

### **Distribusi IPK**
![Histogram IPK](visuals/http://127.0.0.1:26897/chunk_output/s/8ABF91E5/cfcyp8i3uo3rt/000018.png?resize=22)

### **Distribusi Residuals**
![Histogram Residuals](visuals/http://127.0.0.1:26897/chunk_output/s/8ABF91E5/ceztl04o2p7kt/000019.png?resize=23)

---

## 💡 PEMBAHASAN

### **Temuan Utama**
1. **Tidak ada hubungan linear** yang signifikan antara jam belajar dengan IPK
2. **Faktor lain** diluar jam belajar lebih berpengaruh terhadap pencapaian IPK
3. **Kualitas belajar** mungkin lebih penting daripada kuantitas waktu belajar

### **Implikasi Praktis**
- Strategi belajar yang efektif perlu diperhatikan, bukan hanya durasi belajar
- Faktor seperti metode belajar, lingkungan, dan motivasi mungkin lebih krusial
- Perlunya pendekatan holistik dalam meningkatkan prestasi akademik



---

## 🚀 CARA MENJALANKAN

### **Prasyarat**
- R Studio versi 4.3.1 atau lebih baru
- Package: ggplot2, dplyr, knitr, lattice

### **Langkah-langkah**
1. Clone repository ini
2 Buka file script/analysis.Rmd di RStudio
3. Install package yang diperlukan
4. Klik 'Knit' untuk generate laporan PDF
5. Hasil analisis akan tersimpan di folder output


---

## KESIMPULAN DAN SARAN
Kesimpulan
Berdasarkan analisis regresi linier sederhana, dapat disimpulkan bahwa:
Tidak terdapat hubungan yang signifikan antara jam belajar per minggu dengan IPK mahasiswa ITERA.
Model regresi yang dihasilkan tidak layak digunakan untuk prediksi IPK
Faktor non-akademik mungkin memiliki pengaruh yang lebih besar terhadap IPK

Saran
Untuk Mahasiswa:
1. Fokus pada kualitas dan efektivitas belajar
2. Eksplorasi berbagai metode belajar yang sesuai
3. Perhatikan faktor lain seperti manajemen waktu dan gaya belajar

Untuk Penelitian Lanjutan:
1. Menambahkan variabel lain seperti keaktifan organisasi, gaya belajar, atau kondisi ekonomi
2. Menggunakan metode analisis yang lebih kompleks (regresi berganda)
3. Memperluas cakupan sampel dan periode penelitian


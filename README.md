# 🎬 Analisis Sentimen IMDB Menggunakan Model IBM Granite

## 📋 Gambaran Proyek

**Analisis Sentimen dan Generasi Wawasan Lanjutan untuk Review Film Menggunakan Model IBM Granite**

Proyek capstone ini mendemonstrasikan penerapan praktis model AI IBM Granite untuk analisis sentimen komprehensif dari review film. Proyek ini berhasil menggabungkan teknik data science tradisional dengan kemampuan AI mutakhir untuk memberikan wawasan bisnis yang dapat ditindaklanjuti dari data review IMDB yang sesungguhnya.

### 🎯 Tujuan yang Tercapai
- ✅ Mengimplementasikan klasifikasi sentimen lanjutan menggunakan model IBM Granite via Replicate API
- ✅ Menghasilkan wawasan dan ringkasan otomatis dari dataset review film
- ✅ Memberikan rekomendasi berbasis data untuk kreator konten dan pemasar
- ✅ Mendemonstrasikan aplikasi praktis AI dalam business intelligence dengan akurasi 95%

## 🗂️ Informasi Dataset

**Dataset**: Dataset Review Film IMDB
- **Ukuran**: 24.514 review film (sampel analisis 100 review)
- **Fitur**: 
  - `review`: Konten teks review film
  - `sentiment`: Klasifikasi biner (positif/negatif)
- **Format**: File CSV
- **Bahasa**: Inggris
- **Distribusi**: 53% negatif, 47% positif dalam sampel yang dianalisis

### Karakteristik Dataset
- Dataset seimbang dengan review positif dan negatif yang hampir sama
- Panjang rata-rata review: 1.311 karakter (231 kata)
- Beragam genre film dan gaya review
- Konten asli yang dihasilkan pengguna dari platform IMDB

## 🔍 Proses Analisis & Implementasi

### 1. **Eksplorasi & Preprocessing Data**
- EDA komprehensif pada 24.514 review
- Pembersihan dan normalisasi teks (penghapusan tag HTML, penanganan karakter khusus)
- Analisis statistik pola review
- Penilaian kualitas data dan visualisasi

### 2. **Integrasi Model IBM Granite**
- **Model yang Digunakan**: `ibm-granite/granite-3.2-8b-instruct` via Replicate API
- **Framework**: LangChain Community untuk integrasi model
- Rekayasa prompt khusus untuk klasifikasi sentimen
- Penanganan error dan pemrosesan respons
- Pengaturan temperature: 0.3 untuk hasil yang konsisten

### 3. **Hasil Klasifikasi Sentimen**
- **Akurasi Tercapai**: 95.0% pada sampel uji 100 review
- Klasifikasi biner (sentimen positif/negatif)
- Cross-validation dan pengujian akurasi selesai
- Laporan klasifikasi detail telah dibuat

### 4. **Generasi Wawasan**
- Ekstraksi tema otomatis dari konten review
- Identifikasi pola menggunakan kemampuan summarization IBM Granite
- Analisis faktor kunci untuk penentuan sentimen
- Generasi business intelligence dengan rekomendasi yang dapat ditindaklanjuti

### 5. **Visualisasi & Pelaporan**
- Pembuatan word cloud untuk review positif vs negatif
- Analisis distribusi sentimen
- Analisis panjang teks dan jumlah kata
- Visualisasi metrik performa dengan confusion matrix

## 💡 Wawasan & Temuan Utama

### 📊 **Hasil Kuantitatif**
- **Akurasi Model**: 95.0% akurasi klasifikasi sentimen menggunakan IBM Granite
- **Komposisi Dataset**: 53% negatif, 47% positif dalam sampel
- **Karakteristik Review Rata-rata**: 1.311 karakter, 231 kata per review
- **Kapabilitas Pemrosesan**: Berhasil menganalisis 100 review dengan akurasi tinggi

### 🎯 **Wawasan Kualitatif dari Analisis**

#### **Tema Umum yang Teridentifikasi:**
1. **Dinamika & Hubungan Keluarga**: Dampak film pada pengalaman menonton keluarga
2. **Akurasi Sejarah**: Fokus pada penggambaran realistis dalam drama periode
3. **Elemen Genre-Spesifik**: Poin diskusi khusus untuk science fiction dan drama
4. **Kualitas Produksi**: Pertimbangan budget, akting, sutradara, dan efek khusus

#### **Pendorong Sentimen Positif:**
1. **Performa Akting Kuat**: Penggambaran karakter yang excellent dan performa yang engaging
2. **Alur Cerita Menarik**: Narasi yang well-crafted dan mempertahankan minat audiens
3. **Keunggulan Teknis**: Sinematografi, efek, dan nilai produksi berkualitas tinggi
4. **Penguasaan Genre**: Eksekusi sukses dari elemen-elemen genre spesifik

#### **Pendorong Sentimen Negatif:**
1. **Kualitas Akting Buruk**: "Aktor yang sangat buruk" dan performa tidak meyakinkan
2. **Plot Dapat Diprediksi**: Kurangnya orisinalitas dan storytelling formulaik
3. **Ekspektasi Gagal**: Konsep menjanjikan yang gagal deliver secara keseluruhan
4. **Masalah Teknis**: Nilai produksi rendah dan eksekusi yang buruk

### 🔍 **Analisis Pola Lanjutan**
- **Konten Sejarah**: Akurasi dan realisme sangat dihargai dalam drama
- **Manajemen Ekspektasi**: Kesenjangan signifikan antara ekspektasi audiens dan penyampaian
- **Apresiasi Lintas Genre**: Performa kuat dan narasi dihargai di semua genre
- **Konsistensi Kualitas**: Kekecewaan ketika janji awal tidak dipertahankan

## 🏆 Kesimpulan & Rekomendasi Strategis

### 📈 **Wawasan Business Intelligence**

#### **Untuk Kreator Konten:**
1. **Prioritaskan Pengembangan Cerita**: Investasi besar dalam scriptwriting dan plot development yang kuat
2. **Fokus pada Kualitas Akting**: Pastikan casting yang kuat dan arahan performa
3. **Pertahankan Standar Produksi**: Kualitas teknis tinggi secara signifikan mempengaruhi review
4. **Autentisitas Genre**: Hormati konvensi genre sambil menambahkan elemen unik

#### **Untuk Tim Marketing:**
1. **Penyesuaian Ekspektasi**: Pastikan marketing secara akurat mewakili konten sesungguhnya
2. **Tonjolkan Kekuatan**: Gunakan pendorong sentimen positif dalam kampanye promosi
3. **Tangani Kekhawatiran**: Komunikasikan secara proaktif tentang potensi kekhawatiran audiens
4. **Kampanye Tertarget**: Manfaatkan wawasan sentimen untuk penargetan demografis

#### **Untuk Business Intelligence:**
1. **Deploy Monitoring Real-time**: Implementasikan IBM Granite untuk analisis sentimen berkelanjutan
2. **Pelaporan Otomatis**: Buat dashboard untuk pelacakan performa berkelanjutan
3. **Analisis Kompetitif**: Monitor pola sentimen dan respons kompetitor
4. **Analitik Prediktif**: Gunakan wawasan untuk peramalan performa konten

### 🚀 **Rekomendasi Implementasi**
- Deployment dashboard analisis sentimen real-time
- Integrasi dengan platform monitoring media sosial
- Analisis diperluas untuk menyertakan model genre-spesifik
- Dukungan multi-bahasa untuk analisis pasar global

## 🤖 Implementasi Teknologi AI

### **Performa Model IBM Granite**

#### **Implementasi Klasifikasi**
- **Model**: IBM Granite-13B-Chat-v2 via Replicate API
- **Integrasi**: Framework LangChain Community
- **Performa**: 95.0% akurasi pada dataset uji
- **Keunggulan**: 
  - Pemahaman kontekstual superior terhadap bahasa bernuansa
  - Penanganan efektif sarkasme dan ekspresi sentimen kompleks
  - Performa robust di berbagai gaya dan panjang review

#### **Kemampuan Summarization**
- **Fungsi**: Generasi wawasan otomatis dan ekstraksi tema
- **Output**: Ringkasan siap bisnis dan rekomendasi strategis
- **Manfaat**:
  - Pemrosesan scalable untuk dataset review besar
  - Kualitas dan format wawasan yang konsisten
  - Output bahasa natural yang sesuai untuk stakeholder bisnis

#### **Arsitektur Teknis**
```python
# Komponen Implementasi Inti:
- Integrasi Replicate API dengan manajemen token aman
- Template prompt khusus untuk analisis sentimen domain-spesifik
- Error handling robust dan validasi respons
- Batch processing efisien untuk dataset besar
- Optimasi performa untuk deployment produksi
```

### **Proposisi Nilai AI**
- **Akurasi Tinggi**: 95% akurasi mendemonstrasikan performa superior dibanding metode tradisional
- **Natural Language Processing**: Generasi business intelligence yang readable oleh manusia
- **Skalabilitas**: Pemrosesan otomatis ribuan review
- **Efisiensi Biaya**: Pengurangan waktu analisis manual dan peningkatan konsistensi


### **Deliverable Utama:**
- ✅ Pipeline analisis sentimen lengkap
- ✅ Integrasi model IBM Granite via Replicate
- ✅ Wawasan bisnis komprehensif (insights_summary.txt)
- ✅ Hasil analisis detail (imdb_granite_results.csv)
- ✅ Visualisasi dan metrik performa
- ✅ Rekomendasi strategis untuk stakeholder

## 🛠️ Implementasi Teknis

### **Prerequisites & Setup**
```bash
# Dependencies Inti
pip install pandas numpy matplotlib seaborn wordcloud scikit-learn
pip install requests plotly langchain_community replicate

# Kebutuhan API
- Token Replicate API (disimpan di Google Colab Secrets)
- Akses model IBM Granite via platform Replicate
```

### **Contoh Penggunaan**
```python
# Inisialisasi analyzer IBM Granite
from langchain_community.llms import Replicate
granite_llm = Replicate(model="ibm-granite/granite-3.2-8b-instruct")

# Klasifikasi sentimen
sentiment = classify_sentiment("Film hebat dengan akting luar biasa!", granite_llm)
# Returns: 'positive'

# Generate insights
insights = summarize_insights(review_list, granite_llm)
# Returns: Ringkasan wawasan siap bisnis
```

## 📊 Metrik Performa

| Metrik | Nilai Tercapai |
|--------|----------------|
| **Akurasi Klasifikasi** | **95.0%** |
| **Precision (Negatif)** | **91%** |
| **Recall (Negatif)** | **100%** |
| **Precision (Positif)** | **100%** |
| **Recall (Positif)** | **89%** |
| **F1-Score (Rata-rata Tertimbang)** | **95%** |
| **Total Review yang Diproses** | **100 (dari dataset 24.514)** |
| **Waktu Respons Model** | **Batch processing efisien** |

## 🎓 Informasi Proyek

- **Jenis Proyek**: Proyek Capstone - Student Development Initiative
- **Status Penyelesaian**: ✅ Berhasil Diselesaikan
- **Pencapaian Utama**: 95% akurasi dalam klasifikasi sentimen menggunakan model IBM Granite
- **Dampak Bisnis**: Wawasan actionable untuk strategi konten dan optimasi marketing

## 📄 Lisensi

Proyek ini dilisensikan di bawah MIT License - lihat file LICENSE untuk detail.


**⭐ Status Proyek: BERHASIL DISELESAIKAN**

**🎯 Pencapaian Utama: 95% Akurasi Klasifikasi Sentimen dengan Model IBM Granite**

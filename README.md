# Pegasus-Retina 👁️

Pegasus-Retina adalah proyek yang bertujuan untuk mengembangkan model yang akurat dalam mengidentifikasi dan mengkategorikan berbagai penyakit mata berdasarkan gambar medis. Proyek ini menggunakan berbagai model jaringan saraf dalam dan pembelajaran mesin untuk pengenalan penyakit, dengan tujuan mencapai akurasi tinggi, deteksi dini, dan penerapan praktis dalam skenario dunia nyata.

## Dataset 📊

Dataset yang digunakan dalam Pegasus-Retina adalah koleksi gambar retina yang dikurasi dari berbagai dataset, termasuk IDRiD, Ocular Recognition, HRF, dan lainnya. Dataset ini mencakup jumlah gambar berikut untuk setiap kelas:

- Katarak: 1038 gambar
- Glaukoma: 1007 gambar
- Normal: 1074 gambar
- Retinopati diabetik: 1098 gambar

## Model 🧠

### Model Jaringan Saraf Dalam

- **Baseline CNN Model**
  - Deskripsi: Jaringan Saraf Konvolusi sederhana yang berfungsi sebagai pembanding dasar.
  - Direktori: `Baseline_CNN_Model/`

- **EfficientNetB3 – Model Transfer Learning**
  - Deskripsi: Menggunakan arsitektur EfficientNetB3 dengan transfer learning untuk kinerja yang lebih baik.
  - Direktori: `EfficientNET_Model/`

- **InceptionV3 - Model CNN Dasar yang Ditingkatkan**
  - Deskripsi: Versi yang ditingkatkan dari model dasar menggunakan arsitektur InceptionV3.
  - Direktori: `InceptionV3_Model/`

- **ResNet Model**
  - Deskripsi: Mengimplementasikan arsitektur ResNet untuk jaringan saraf yang lebih dalam.
  - Direktori: `ResNet50_Model/`

- **DenseNet Model**
  - Deskripsi: Menggunakan arsitektur DenseNet untuk ekstraksi fitur yang lebih baik.
  - Direktori: `DenseNet121_Model/`

- **MobileNet Model**
  - Deskripsi: Mengimplementasikan arsitektur MobileNet untuk desain model yang ringan dan efisien.
  - Direktori: `MobileNet_Model/`

- **VGG16 Model**
  - Deskripsi: Mengimplementasikan arsitektur VGG16 untuk ekstraksi fitur yang kuat.
  - Direktori: `VGG16_Model/`

- **Xception Model**
  - Deskripsi: Menggunakan arsitektur Xception untuk kinerja yang lebih baik.
  - Direktori: `Xception_Model/`

### Model Pembelajaran Mesin

- **SVM Model**
  - Deskripsi: Model Support Vector Machine untuk klasifikasi penyakit.
  - Direktori: `SVM_Model/`

- **Random Forest Model**
  - Deskripsi: Mengimplementasikan klasifikasi Random Forest untuk prediksi yang akurat.
  - Direktori: `Random_Forest_Model/`

- **Decision Tree**
  - Deskripsi: Menggunakan algoritma Decision Tree untuk pengkategorian penyakit.
  - Direktori: `Decision_Tree_Model/`

## Pendahuluan 🌟

Penyakit mata dapat berdampak signifikan pada penglihatan, dan deteksi dini sangat penting untuk pengobatan yang efektif. Pegasus-Retina menangani tantangan ini dengan memanfaatkan model-model mutakhir untuk menganalisis gambar retina dan mengidentifikasi kondisi seperti glaukoma, katarak, retinopati diabetik, dan kasus normal.

## Tujuan dan Sasaran 🎯

Tujuan utama Pegasus-Retina meliputi:

- **Pengenalan Penyakit**: Mengidentifikasi dan mengkategorikan penyakit mata dengan akurat.
- **Akurasi Tinggi**: Mencapai prediksi yang andal dan tepat.
- **Deteksi Dini**: Mendeteksi penyakit mata pada tahap awal untuk intervensi yang tepat waktu.
- **Efisiensi**: Mengembangkan model yang seimbang antara akurasi dan efisiensi komputasi.
- **Penerapan Praktis**: Memastikan model dapat diterapkan dalam skenario klinis dunia nyata.
- **Generalisasi**: Membuat model yang dapat diadaptasi dengan baik pada dataset dan populasi pasien yang beragam.
- **Kepatuhan Etika**: Mengutamakan pertimbangan etis dalam pengembangan dan penerapan model.
- **Interpretabilitas**: Memberikan wawasan tentang keputusan model untuk pemahaman yang lebih baik oleh profesional kesehatan.
- **Pembelajaran Berkelanjutan**: Memungkinkan model untuk beradaptasi dan meningkat seiring waktu dengan data dan wawasan baru.
- **Validasi**: Memvalidasi model secara ketat untuk memastikan keandalan dan keamanannya dalam konteks perawatan kesehatan.

## Prasyarat

- Python 3.8+
- TensorFlow
- scikit-learn
- OpenCV

## Instalasi

1. Clone repositori:
   ```bash
   git clone https://github.com/sobri3195/Pegasus-Retina.git

## Author ✒️
Proyek ini dikembangkan oleh Dr. Muhammad Sobri Maulana.

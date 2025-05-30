﻿# Batik-Classification-MobileNetV2


---

## 🚀 Teknologi & Tools

- Python 🐍  
- TensorFlow / Keras  
- MobileNetV2  
- Scikit-learn  
- Matplotlib, Seaborn  
- Streamlit  

---

## 🧠 Cara Kerja Singkat

1. Dataset dikumpulkan dari berbagai sumber dan diseleksi manual.
2. Dilakukan augmentasi untuk meningkatkan variasi dan ketahanan model.
3. Model dibangun dengan MobileNetV2 menggunakan transfer learning (freeze dan unfreeze skenario).
4. Evaluasi dilakukan dengan *K-Fold Cross-Validation*.
5. Pengujian dilakukan pada data tambahan untuk menguji generalisasi model.

---

## 🎯 Hasil Akhir

Model terbaik diperoleh dari kombinasi augmentasi dan freeze layer, menghasilkan akurasi:
- **97,25%** pada data split
- **94,76%** pada data tambahan yang belum pernah dilihat sebelumnya

---

## 📸 Demo Aplikasi

Tersedia file `batik_classifier_app.py` untuk mencoba langsung klasifikasi gambar batik menggunakan antarmuka Streamlit. Cukup jalankan:

```bash
streamlit run batik_classifier_app.py

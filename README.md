# Derin Öğrenme ile Duygu Tespiti / Emotion Detection with Deep Learning

Bu proje, yüz ifadelerine dayalı duygu tespiti yapmak için geliştirilmiş bir derin öğrenme uygulamasıdır. Jupyter Notebook ortamında geliştirilmiştir.

This project is a deep learning application developed to detect emotions based on facial expressions. It is implemented in a Jupyter Notebook environment.

---

## 🚀 Özellikler / Features

- Görüntü verilerini temizleme ve ön işleme  
  Image cleaning and preprocessing  
- Sınıf dengesizliği analizi  
  Class imbalance analysis  
- Eğitim, doğrulama ve test için veri kümesini ayırma  
  Dataset splitting into training, validation, and test sets  
- Derin öğrenme modelleri:  
  Deep learning models:
  - CNN  
  - MobileNetV2  
  - ResNet50  
- Model eğitimi ve performans değerlendirmesi (accuracy, confusion matrix, classification report)  
  Model training and performance evaluation (accuracy, confusion matrix, classification report)  
- Hiperparametre optimizasyonu (GridSearchCV ile)  
  Hyperparameter optimization using GridSearchCV  
- Eğitilen modellerin `.h5` formatında kaydedilmesi  
  Saving trained models in `.h5` format

---

## 📁 Veri Kümesi / Dataset

Kullanılan veri kümesi artık çevrim içi olarak erişilebilir değildir. Klasörde `data/train/` altında organize edilmiştir:

The dataset used in this project is no longer publicly available. It is organized under `data/train/` with subfolders for:

- `happy`, `neutral`, `sad`, `surprise` gibi sınıflar içerir.  
- Includes classes such as `happy`, `neutral`, `sad`, and `surprise`.

📌 Not: `.gitignore` dosyası nedeniyle veri kümesi bu repoya dahil edilmemiştir.  
📌 Note: Due to `.gitignore`, the dataset is not included in this repository.

---

## 🧠 Kullanılan Teknolojiler / Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- Matplotlib, Seaborn  
- Scikit-learn  


## 📄 Makale ve Poster / Article and Poster

Bu proje bir akademik çalışmanın parçası olarak gerçekleştirilmiştir. Detaylı bilgi için aşağıdaki dosyalara göz atabilirsiniz:

This project was developed as part of an academic study. You can find more details in the following files:

- [`Makale.pdf`](./Makale.pdf) – Projenin detaylarını içeren Türkçe makale  
- [`Poster.png`](./Poster.png) – Görsel olarak özetlenmiş sunum posteri
---

# Car Brand Classification – Deep Learning Project  

## Proje Amacı  
Bu proje, **Convolutional Neural Network (CNN)** ve **Transfer Learning** yöntemlerini kullanarak araba markalarının görsellerden otomatik olarak sınıflandırılmasını amaçlamaktadır. Çalışma, **Akbank Derin Öğrenme Bootcamp (Eylül 2025)** kapsamında geliştirilmiştir.  

## Veri Seti  
- **Kaynak:** [Car Brand Classification Dataset (Kaggle)](https://www.kaggle.com/datasets/ahmedelsany/car-brand-classification-dataset)  
- **Boyut:** ~16.000 görüntü  
- **Sınıf Sayısı:** 33 (Audi, BMW, Ford, Mercedes, Tesla vb.)  
- Görseller farklı açılardan ve ortamlardan alınmıştır.  

## Kullanılan Yöntemler  
- **Veri Ön İşleme:**  
  - Normalizasyon (0-1 ölçekleme)  
  - Train/Validation/Test ayrımı  
  - Data Augmentation (rotation, shift, zoom, flip)  

- **Model:**  
  - CNN tabanlı mimari  
  - Transfer Learning (VGG16, ImageNet ağırlıklarıyla)  
  - Dropout & EarlyStopping → overfitting’i azaltmak için  

- **Değerlendirme:**  
  - Accuracy & Loss grafikleri  
  - Confusion Matrix & Classification Report   

- **Hiperparametre Optimizasyonu:**  
  - Keras Tuner (Hyperband) ile filtre sayısı, kernel boyutu, dense katman boyutları, learning rate denemeleri yapılmıştır.  

## 📎 Notebook Linki  
🔗 [Kaggle Notebook – Car Brand Classification](https://www.kaggle.com/code/atakanakdoan/notebook61fd9851d8)  

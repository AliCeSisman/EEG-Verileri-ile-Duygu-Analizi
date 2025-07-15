# EEG-Verileri-ile-Duygu-Analizi
# EEG ile Duygu Analizi — Makine Öğrenmesi Yaklaşımı

Bu proje, EEG (Elektroensefalografi) beyin dalgaları kullanılarak bireylerin duygusal durumlarının sınıflandırılmasını amaçlamaktadır. EEG sinyalleri, makine öğrenmesi algoritmalarıyla işlenerek pozitif, negatif ve nötr duygular tahmin edilmektedir.

Kullanılan Veri Seti
- EEG Brainwave Dataset: Feeling Emotions  
- Kaynak: [Kaggle](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions)

Kullanılan Yöntemler
- **Veri ön işleme:** Eksik veri kontrolü, filtreleme (Notch, Bandpass), artefakt temizliği (ICA), aykırı değer temizleme (IQR), normalizasyon, PCA
- **Algoritmalar:**  
  - Multi-Layer Perceptron (MLP)  
  - Random Forest  
  - Support Vector Classification (SVC)  

Performans Karşılaştırması
- SVC: %98 doğruluk ile en iyi performansı gösterdi.
- MLP ve Random Forest modelleri de yüksek başarı oranları elde etti.

Makale
Detaylı açıklamalar ve akademik değerlendirmeler için `makale.docx` dosyasını inceleyebilirsiniz. İsteğe bağlı olarak tarafınıza iletebilirim. İçerik açısından posteri inceleyebilirsiniz.

Gelecek Çalışmalar
- Derin öğrenme mimarileriyle (CNN, LSTM) geliştirme
- Gerçek zamanlı EEG işleme sistemlerinin tasarımı
- Daha fazla duygu sınıfı ile deneyler

Katkıda Bulunanlar
- İlker Zekeriya Erkaya  
- Ali Cemal Şişman


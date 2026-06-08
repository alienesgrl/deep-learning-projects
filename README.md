# Gelişmiş Derin Öğrenme Modelleri: Sınıflandırma, Renklendirme ve Doğal Dil İşleme

Bu depo; bilgisayarlı görü (Computer Vision) ve doğal dil işleme (NLP) alanlarındaki farklı problemlerin çözümü için özelleştirilmiş, gelişmiş derin öğrenme mimarilerini barındıran kapsamlı bir final projesidir. Proje kapsamında üç farklı problem türü ele alınmış, özgün mimari tasarımlar kurgulanmış ve performans analizleri gerçekleştirilmiştir.

## Proje Kapsamı ve Model Mimarileri

Depo içerisinde yer alan üç ana çalışma ve kullanılan teknolojiler şu şekildedir:

### 1. CNN ile Hava Durumu Sınıflandırma (Weather Classification)
* **Mimari:** Evrişimli Sinir Ağları (Convolutional Neural Networks - CNN)
* **Açıklama:** Farklı hava durumu koşullarını (güneşli, yağmurlu, sisli, karlı vb.) içeren görsel veri setleri üzerinde uçtan uca bir sınıflandırma modeli eğitilmiştir. Görsellerden öznitelik çıkarımı yapılarak hava durumu tahmini yüksek doğrulukla gerçekleştirilmektedir.
* **Değerlendirme:** Model performansı doğruluk (Accuracy) ve kayıp (Loss) fonksiyonları üzerinden analiz edilmiştir.

### 2. Micro U-Net ile Görüntü Renklendirme (Image Colorization)
* **Mimari:** Micro U-Net (Hafifletilmiş Encoder-Decoder Mimarisi)
* **Açıklama:** Gri tonlamalı (siyah-beyaz) görselleri otomatik olarak renklendirmek amacıyla derin bir otokodlayıcı varyasyonu olan Micro U-Net mimarisi tasarlanmıştır. Model, görüntünün yapısal bağlamını kaybetmeden gerçeğe en yakın renk dağılımını tahmin eder.
* **Değerlendirme:** Renklendirme kalitesi Ortalama Karesel Hata (Mean Squared Error - MSE) metriği kullanılarak ölçülmüştür.

### 3. LSTM ile Siber Zorbalık Tespiti (Cyberbullying Detection)
* **Mimari:** Uzun Kısa Vadeli Bellek Ağları (Long Short-Term Memory - LSTM)
* **Açıklama:** Sosyal medya ve metin tabanlı platformlardaki siber zorbalık, hakaret veya agresif söylemleri tespit etmeye yönelik bir Doğal Dil İşleme (NLP) modelidir. Metindeki kelimeler arası anlamsal köprüleri ve zamansal dizilimleri korumak adına yinelemeli sinir ağı (RNN) tabanlı LSTM mimarisi tercih edilmiştir.
* **Değerlendirme:** Modelin başarısı Accuracy, Precision, Recall ve F1-Score metrikleriyle detaylıca incelenmiştir.

## Dosya Yapısı

* `weather_classification/` -> CNN model kaynak kodları, veri önişleme ve ağırlık dosyaları.
* `image_colorization/` -> Micro U-Net model tasarımı, eğitim döngüleri ve renklendirme test çıktıları.
* `cyberbullying_detection/` -> LSTM NLP modeli, metin temizleme (tokenization, padding) adımları.
* `Deep_Learning_Final_Project_Report.pdf` -> Veri seti boyutlarını, mimari gerekçelerini, hiperparametre seçimlerini ve tüm performans metriklerini içeren detaylı akademik proje raporu.

## Kullanılan Teknolojiler ve Kütüphaneler

* **Programlama Dili:** Python
* **Derin Öğrenme Çatıları:** TensorFlow / Keras veya PyTorch
* **Veri İşleme & Görselleştirme:** NumPy, Pandas, Matplotlib, OpenCV

## Geliştirici

* **Ad Soyad:** Ali Enes GÜREL
* **Öğrenci No:** 2121221032
* **Bölüm:** Bilgisayar Mühendisliği

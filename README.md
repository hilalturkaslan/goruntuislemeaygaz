# Görüntü İşleme Projesi

Bu proje, 10 farklı hayvan sınıfını sınıflandırmak için bir derin öğrenme modelini (CNN) eğitmek amacıyla geliştirilmiştir. Proje, çeşitli görüntü işleme teknikleri ve derin öğrenme algoritmalarını kullanarak görsel verilerle çalışmayı amaçlamaktadır. Model, farklı ışık koşulları ve renk sabitliği uygulanmış verilerle test edilmiştir.

## Proje İçeriği

- **Veri Kümesi:** 10 farklı hayvan sınıfından oluşan görüntüler. Her sınıfın 650 adet görüntüsü bulunmaktadır.
- **Model:** Konvolüsyonel Sinir Ağı (CNN) kullanılarak oluşturulmuştur.
- **Veri Artırma (Augmentation):** Görüntüler üzerinde çeşitli manipülasyonlar (bulanıklaştırma, kenar bulma, döndürme vb.) yapılmıştır.
- **Test ve Manipülasyon:** Test verisi üzerinde ışık manipülasyonları yapılmış, ardından renk sabitliği algoritması uygulanmıştır.
- **Sonuçlar:** Modelin başarısı farklı test setleriyle karşılaştırılmıştır.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:

- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- PIL (Python Imaging Library)

Bu kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

## pip install tensorflow keras numpy opencv-python matplotlib scikit-learn pillow

# Proje Adı: Mamografi Görüntülerinin Yapay Zeka ile Analizi

Bu proje, Teknofest 2024 Sağlıkta Yapay Zeka Yarışması için geliştirilmiştir. Proje kapsamında, bilgisayarlı görü teknikleri kullanılarak mamografi görüntülerinin işlenmesi ve analiz edilmesi hedeflenmektedir. BI-RADS kategorilerinin otomatik tahmini ve kitle/kalsifikasyon tespitine yönelik derin öğrenme modelleri geliştirilmiştir.

## İçindekiler
- [Proje Hakkında](#proje-hakkında)
- [Özellikler](#özellikler)
- [Gereksinimler](#gereksinimler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Sonuçlar](#sonuçlar)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Proje Hakkında

Bu proje, mamografi görüntülerinden BI-RADS kategorilerini otomatik olarak tahmin etmeyi amaçlayan bir yapay zeka çözümüdür. Mamografi görüntüleri üzerinden anormalliklerin tespiti ve radyoloji raporlarının BI-RADS sınıflandırmasına dayalı analizler yapılmaktadır. Projede, derin öğrenme modelleri ve ön işleme teknikleri ile daha yüksek doğruluk oranları elde edilmeye çalışılmaktadır.

## Özellikler
- Mamografi görüntülerinden kitle ve kalsifikasyon tespiti.
- BI-RADS kategorilerinin otomatik tahmini.
- ResNet, AlexNet, VGGNet ve DCNN gibi derin öğrenme modelleri kullanımı.
- JSON formatında sonuçların raporlanması.

## Gereksinimler

- Python 3.7+
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib

Gereksinimlerin tümü `requirements.txt` dosyasından yüklenebilir.

```bash
pip install -r requirements.txt

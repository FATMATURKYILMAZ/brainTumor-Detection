# MRI Brain Tumor Detection & Clustering

Bu proje, beyin MRI görüntüleri üzerinde makine öğrenmesi ve gözetimsiz öğrenme yöntemleri kullanarak tümör tespiti ve kümeleme yapmayı amaçlamaktadır.

---

## Proje İçeriği

- **Veri Seti:** Tümörlü ve tümörsüz MRI görüntüleri (`yes` ve `no` klasörlerinde).
- **Model:** Convolutional Neural Network (CNN) kullanılarak beyin tümörü sınıflandırması.
- **Gözetimsiz Öğrenme:** PCA ile boyut indirgeme ve k-Means algoritmasıyla kümeleme.
- **Sonuçlar:** Model doğruluğu, sınıflandırma raporu, kümeleme görselleştirmesi.
- **Arayüz:** Gradio kullanarak interaktif tahmin arayüzü (opsiyonel).

---

## Kullanılan Kütüphaneler

- numpy
- matplotlib
- seaborn
- PIL (Pillow)
- scikit-learn
- tensorflow/keras
- gradio (opsiyonel)

---

## Kurulum

```bash
pip install numpy matplotlib seaborn pillow scikit-learn tensorflow gradio

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

##  GPU Hız Karşılaştırması ve Gradio Arayüzü

Projede kullanılan modellerin GPU hızlarını karşılaştırmak amacıyla Google Colab üzerinde bir test gerçekleştirdim. Bu test sayesinde farklı GPU yapılandırmalarının performanslarını ölçerek model eğitim süresini optimize etmeyi hedefledim.

Test detaylarına ve kullanılan kodlara aşağıdaki Google Colab bağlantısından ulaşabilirsiniz:
- [📊 GPU Speed Comparison - Google Colab](https://colab.research.google.com/drive/1-hnRMsOXKUONhHhCj89AnHfesWeYr7OD?usp=sharing)
  
## Opsiyonel: Gradio ile Oluşturulan Arayüz 
Projede kullanıcıların modelleri interaktif şekilde deneyimleyebilmesi için **Gradio** kütüphanesi kullanılarak basit ve kullanışlı bir arayüz geliştirildi. Bu arayüz sayesinde kullanıcılar model çıktılarının sonuçlarını kolayca görebilir ve test edebilir.

Gradio arayüzü, projenin kullanım kolaylığını artırarak erişilebilirliğini sağlar.
## Kurulum 

```bash
pip install numpy matplotlib seaborn pillow scikit-learn tensorflow gradio

--- 


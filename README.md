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

## GPU Hız Karşılaştırması

Projemizde kullanılan modellerin ve işlemlerin GPU hızlarını karşılaştırmak amacıyla bir test gerçekleştirdim. Bu testi Google Colab ortamında GPU desteği ile yaptım. Aşağıdaki linkten testin detaylarına ve kodlarına ulaşabilirsiniz.

👉 [GPU Speed Comparison - Google Colab](https://colab.research.google.com/drive/1-hnRMsOXKUONhHhCj89AnHfesWeYr7OD?usp=sharing)

Bu çalışma, farklı GPU yapılandırmalarının performansını ölçerek model eğitim süresini optimize etmek için önemli bir referans sağlamaktadır.

---

## Opsiyonel: Gradio ile Oluşturulan Arayüz

Projemde ayrıca kullanıcı dostu bir deneyim sağlamak için **Gradio** kütüphanesini kullanarak basit ve interaktif bir arayüz oluşturdum. Bu arayüz sayesinde kullanıcılar, modelleri kolayca test edebilir ve sonuçları görsel olarak inceleyebilirler. Gradio arayüzü, kodu çalıştırmak isteyen herkesin model performansını hızlıca deneyimlemesine olanak tanır.

Gradio ile oluşturduğum arayüz, kullanım kolaylığı ve erişilebilirlik açısından projeye değer katmaktadır.



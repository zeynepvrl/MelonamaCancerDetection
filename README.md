# Melanoma Computer Vision Project

Bu proje, deri melanomlarının erken teşhisinde kullanılabilecek bir bilgisayarla görü (computer vision) modeli geliştirmeyi amaçlamaktadır. Proje, derin öğrenme tekniklerini kullanarak deri lezyonlarını analiz eder ve melanom teşhisi koymak için bir model oluşturur.

## Teknik Özellikler

- **Geliştirme Ortamı:** Python (v3.6+), Jupyter Notebook
- **Makine Öğrenimi Çerçeveleri:** TensorFlow, Keras
- **Veri İşleme ve Görselleştirme:** NumPy, Pandas, Matplotlib
- **Model Eğitimi:** Transfer öğrenme kullanılarak önceden eğitilmiş modeller (örneğin, VGG16, ResNet50) üzerine ince ayar yapılır.

## Veri Seti

Proje, aşağıdaki veri setlerini kullanır:
- **ISIC 2019 Dataset:** Deri melanomlarını ve diğer deri lezyonlarını içeren geniş bir veri setidir. Veri seti, çeşitli türlerde deri lezyonlarının fotoğraflarını içerir ve her bir fotoğraf, lezyonun türü hakkında etiketlenmiştir.

## Gereksinimler

Projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyaç vardır:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras

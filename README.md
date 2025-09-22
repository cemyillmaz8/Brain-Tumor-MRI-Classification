🔹 Proje Hakkında

Bu proje, MR görüntüleri üzerinden beyin tümörü sınıflandırması yapmak için hazırlanmıştır.

Kullanılan modeller:

Basit CNN

Transfer Learning: EfficientNetB0

Data augmentation (dönme, zoom, flip, kontrast) ve normalizasyon uygulanmıştır.

TensorFlow/Keras kullanılarak GPU üzerinde eğitim yapılmıştır.

🔹 Dataset

Kullanılan veri seti: Kaggle: Brain Tumor MRI Dataset

Dataset, Training ve Testing klasörleri içerir.

Notebook’ta dataset yolu: /kaggle/input/brain-tumor-mri-dataset

Not: Dataset Kaggle’da public olduğu için arkadaşınız notebook’u açarken aynı dataset’e erişebilmelidir.

🔹 Kurulum

Python 3.11 veya üstü

Gerekli kütüphaneler:

pip install tensorflow matplotlib pandas scikit-learn


Kaggle ortamında çalıştırmak için internet ve GPU aktif olmalıdır (EfficientNet ağırlıkları için).

🔹 Kullanım

Notebook’u açın: brain_tumor_classification.ipynb

Hücreleri sırayla çalıştırın:

Dataset yükleme ve train/val/test ayırma

Data augmentation ve normalization

Model oluşturma (CNN veya EfficientNetB0)

Model eğitimi ve kaydetme

Sonuçların görselleştirilmesi (loss/accuracy grafikleri)


🔹 Sonuçlar

Modelin eğitim ve doğrulama accuracy/grafikleri notebook içinde gösterilmektedir.

Test seti üzerinde değerlendirme ve confusion matrix ile sınıf bazlı performans elde edilebilir.

🔹 Lisans

Bu proje MIT Lisansı ile paylaşılmıştır.

https://www.kaggle.com/code/cemyillmaz8/notebook04961b8042

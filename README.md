CIFAR-10 Görüntü Sınıflandırma (CNN)
Bu proje, derin öğrenme dünyasına giriş yapmak isteyenler için temel bir Evrişimli Sinir Ağı (CNN) uygulamasıdır. 
Popüler CIFAR-10 veri setini kullanarak, bilgisayarın resimleri 10 farklı kategoride nasıl tanıdığını öğretir.

Proje Hakkında
Bu çalışmada, TensorFlow ve Keras kütüphaneleri kullanılarak bir görüntü sınıflandırma modeli oluşturulmuştur.
Model, uçaklardan köpeklere kadar 10 farklı nesneyi birbirinden ayırt edebilme yeteneğine sahiptir.

Temel Özellikler:
Veri Kümesi: 60.000 adet 32x32 renkli görsel (CIFAR-10).

Mimari: CNN (Convolutional Neural Networks).

Optimizasyon: Adam Optimizer ve Sparse Categorical Crossentropy.

Görselleştirme: Matplotlib ile tahminlerin test edilmesi.

Model Mimarisi
Modelimiz iki ana bölümden oluşmaktadır:

Özellik Çıkarımı (Feature Extraction): Conv2D ve MaxPooling2D katmanları ile resimdeki desenler (kenarlar, köşeler) yakalanır.

Sınıflandırma (Classification): Dense (Tam Bağlantılı) katmanlar ile çıkarılan bu özellikler yorumlanarak doğru kategoriye atanır.

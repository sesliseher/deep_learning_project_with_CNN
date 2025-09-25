## Garbage Classification with CNN
Bu repo, Global AI Hub bootcamp kapsamında geliştirilmiş bir görüntü sınıflandırma projesini içermektedir. Projede, çöp sınıflandırması için CNN tabanlı bir model tasarlanmış ve eğitilmiştir.
## Giriş
Projemizde kullanılan veri seti Garbage Classification Dataset (Kaggle) kaynağından alınmıştır.
Bu veri seti; plastik, metal, cam, kağıt, karton, çöp gibi farklı kategorilerden oluşmaktadır.

Amaç: Görseller üzerinden hangi tür atık olduğunu otomatik olarak sınıflandırmak.

Kullandığımız yöntem:

-TensorFlow/Keras tabanlı Convolutional Neural Network (CNN)

-Eğitim/Doğrulama/Test veri setlerine bölme

-Data augmentation teknikleri
## Metrikler 
Modelin değerlendirilmesi için şu metrikler kullanılmıştır:

-Accuracy

-Loss grafikleri

-Confusion Matrix

-Classification Report (precision, recall, f1-score)

Elde edilen sonuçlar:

Eğitim doğruluğu: ~%XX

Test doğruluğu: ~%XX

Model genel olarak çöp türlerini ayırt etmede başarılı sonuçlar vermiştir. Bazı sınıflarda karışıklıklar olmasına rağmen, veri arttırma ve daha gelişmiş mimariler ile doğruluk artırılabilir.

## Ekler 
-GPU üzerinde eğitim yapılmıştır.

-Notebook içerisinde data augmentation uygulanmıştır.

-Model performansı görselleştirilmiştir (loss & accuracy grafikleri, confusion matrix).

## Sonuç ve Gelecek Çalışmalar
Bu proje sonucunda, görüntü tabanlı atık sınıflandırma için temel bir CNN modeli geliştirilmiştir.

Gelecekte yapılabilecekler:

*Daha gelişmiş CNN mimarileri (EfficientNet, ResNet vb.) kullanmak

*Gerçek zamanlı kamera entegrasyonu ile canlı sınıflandırma yapmak

*Mobil uygulama veya web arayüzü ile kullanıcıya sunmak

*Veri setini genişletip daha fazla kategori eklemek

## Linkler
Kaggle Notebook: https://www.kaggle.com/code/sehersesli/garbage-classification-with-cnn
Veri Seti: https://www.kaggle.com/datasets/mostafaabla/garbage-classification

















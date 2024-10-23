# akbank_deepLearning_bootcamp
 ANN Architect

!!! KAGGLE LINK: https://www.kaggle.com/code/serrayse/notebookdac723680e/edit


# Fish Classification with Convolutional Neural Networks (CNN)

Bu proje, büyük ölçekli bir balık veri setini kullanarak çeşitli balık türlerini sınıflandırmak için bir konvolüsyonel sinir ağı (CNN) geliştirmeyi hedeflemektedir. Veri seti, çeşitli balık türlerinin görüntülerini içermekte ve amaç, bu görüntüleri doğru bir şekilde kendi sınıflarına ayırmaktır.

## Giriş

Son yıllarda, derin öğrenme görüntü sınıflandırma görevlerinde dikkat çekici bir performans sergilemiştir. Bu proje, balık türlerini görüntülerden sınıflandırmak için bir CNN kullanarak veri artırma, dropout ile düzenleme ve model performansını değerlendirmek için karışıklık matrisinin görselleştirilmesi gibi teknikleri içermektedir.

## Veri Seti

Bu projede kullanılan veri seti, Kaggle'dan alınan büyük ölçekli bir balık veri setidir. Veri seti, çeşitli balık türlerinin görüntülerini içermekte olup, tür adlarına göre alt dizinlere düzenlenmiştir.
##################################################################3

Model 20 tekrar boyunca eğitildikten sonra, modelin performansını değerlendirmek için karışıklık matrisi ve sınıflandırma raporu oluşturulmaktadır. Karışıklık matrisi, modelin tahminlerini görsel olarak temsil ederken, sınıflandırma raporu kesinlik, hatırlama ve F1 skoru metriklerini sağlamaktadır.

> CNN modeli aşağıdaki katmanlardan oluşmaktadır:

> Konvolüsyonel Katmanlar: Görüntülerden özellikler çıkarır.

> MaxPooling Katmanları: Özellik haritalarını küçültür.

> Düzleştirme Katmanı: Özellik haritalarını 1D vektöre dönüştürür.

> Dense Katmanlar: Sınıflandırma için tamamen bağlı katmanlar.

> Çıktı Katmanı: Sınıf olasılıklarını çıkarmak için softmax aktivasyonu kullanır.

> Model, Adam optimizasyon algoritması ve kategorik çapraz entropi kayıp fonksiyonu ile derlenmiştir.

# akbank_deepLearning_bootcamp
 ANN Architect

!!! KAGGLE LINK: https://www.kaggle.com/code/serrayse/notebookdac723680e


# Fish Classification with Artificial Neural Network (ANN)

Bu proje, büyük ölçekli bir balık veri setini kullanarak çeşitli balık türlerini sınıflandırmak için bir yapay sinir ağı (ANN) geliştirmeyi hedeflemektedir. Veri seti, çeşitli balık türlerinin görüntülerini içermekte ve amaç, bu görüntüleri doğru bir şekilde kendi sınıflarına ayırmaktır.

## Giriş

Son yıllarda, derin öğrenme görüntü sınıflandırma görevlerinde dikkat çekici bir performans sergilemiştir. Bu proje, balık türlerini görüntülerden sınıflandırmak için bir ANN kullanarak veri artırma, dropout ile düzenleme ve model performansını değerlendirmek için karışıklık matrisinin görselleştirilmesi gibi teknikleri içermektedir.

## Veri Seti

Bu projede kullanılan veri seti, Kaggle'dan alınan büyük ölçekli bir balık veri setidir. Veri seti, çeşitli balık türlerinin görüntülerini içermekte olup, tür adlarına göre alt dizinlere düzenlenmiştir.
##################################################################3

Model 20 tekrar boyunca eğitildikten sonra, modelin performansını değerlendirmek için karışıklık matrisi ve sınıflandırma raporu oluşturulmaktadır. Karışıklık matrisi, modelin tahminlerini görsel olarak temsil ederken, sınıflandırma raporu kesinlik, hatırlama ve F1 skoru metriklerini sağlamaktadır.

ANN modeli aşağıdaki katmanlardan oluşmaktadır:

Giriş Katmanı: Verilerin (özelliklerin) modelin eğitimine girmesi için ilk aşamadır.

Gizli Katmanlar: Ağın derinliğini artırarak verilerden karmaşık ilişkiler öğrenir. Her bir gizli katman, aktivasyon fonksiyonu kullanarak verileri işler ve çıktıyı bir sonraki katmana iletir.

Düzleştirme Katmanı: Çok boyutlu verileri (örneğin, görüntüler) 1D vektör formatına dönüştürerek, tam bağlı (dense) katmanlarla işlemeye uygun hale getirir.

Dense Katmanlar: Tüm bağlantılı katmanlar olarak bilinir; verileri işler ve sınıflandırma için tahminlerde bulunur. Her nöron, bir önceki katmandan gelen tüm girdileri alır.

Çıktı Katmanı: Son katman olup, sınıf olasılıklarını çıkarmak için genellikle softmax aktivasyonu kullanır. Bu katman, modelin tahmin ettiği sınıflar için olasılık değerlerini döndürür.

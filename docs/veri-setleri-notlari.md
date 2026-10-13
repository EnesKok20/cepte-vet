# Veri Seti Notları

## Ana veri seti: Lumpy Skin Images Dataset
- Kaynak: Mendeley Data, doi: 10.17632/w36hpf86j2.1
- Yazarlar: Sachin Kumar, Sourabh Shastri (Jammu Üniversitesi, 2022)
- Lisans: CC BY 4.0
- İçerik: 324 Lumpy Skin, 700 Normal Skin, 256x256 PNG
- Sayılar Colab'da doğrulandı.

## İnceleme bulguları
1. Alakasız görüntüler var (ör. mikroskop / doku kesiti görüntüleri).
2. Sınıflar farklı koşullarda çekilmiş: Lumpy yakın plan ve saha fotoğrafı,
   Normal çoğunlukla uzaktan sürü ve stok fotoğraf. Kısayol öğrenme riski.
3. Görüntüler 256x256'ya zorla sığdırıldığı için oranlar bozulmuş.

## Plan
- Alakasız görüntüleri ayıklamak
- İkinci veri setiyle karşılaştırmak (Zenodo / Roboflow)
- Kendi çevremden sağlıklı sığır fotoğrafları toplamak; bir kısmını
  eğitime katmadan saha testi için ayırmak

  ## İkinci veri seti: Cattle diseases datasets (Kaggle)
- Kaynak: kaggle.com/datasets/devang03mgr/cattle-diseases-datasets
- Lisans: DbCL v1.0 (internetten toplanmış görüntüler; asıl telif hakları farklı kaynaklara ait)
- İçerik: lumpy 1.207, healthy 1.291, foot-and-mouth 746 (farklı boyutlarda)
- Şap sınıfı şimdilik kullanılmayacak; ileride ikinci hastalık için aday.

### İnceleme bulguları
1. Ana setten daha büyük ve dengeli; sağlıklı görüntüler daha çeşitli (köy ortamı, yakın çekim).
2. Augmentation önceden uygulanmış: yatay çevrilmiş kopyalar var (ters yazılı görsel).
3. Haber görselleri ve filigranlı fotoğraflar var.
4. Bazı lumpy görüntülerde hastalık belirtisi görünmüyor.
5. 256x256 boyutlu görüntüler, Mendeley setiyle örtüşme olabileceğini düşündürüyor.
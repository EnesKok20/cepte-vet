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
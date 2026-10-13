# Cepte Veterinerlik

Sığırlarda Lumpy Skin Disease (nodüler ekzantem) ön tespiti ve soru-cevap asistanı.
KTÜ Yazılım Mühendisliği, Tasarım Bitirme Projesi.

## Bileşenler
- Görüntü modeli: YOLO sınıflandırma (sağlıklı / Lumpy Skin Disease belirtili)
- Soru-cevap asistanı: LLM + RAG, veterinerlik kaynaklarına dayalı
- Web uygulaması: ASP.NET Core MVC, Identity, PostgreSQL

## Veri seti
Kumar, Sachin; Shastri, Sourabh (2022), "Lumpy Skin Images Dataset",
Mendeley Data, V1, doi: 10.17632/w36hpf86j2.1 (CC BY 4.0)
324 Lumpy Skin, 700 Normal Skin görüntü, 256x256 PNG.

Veri seti repoya dahil değildir; yukarıdaki kaynaktan indirilir.

## Durum
- [x] Ana veri seti indirildi ve doğrulandı
- [ ] İkinci veri setinin incelenmesi
- [ ] Veri temizleme ve bölme
- [ ] Model eğitimi
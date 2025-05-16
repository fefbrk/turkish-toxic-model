# Türkçe Toksik Metin Sınıflandırma Modeli


# Bu proje, Türkçe metinlerdeki toksik içeriği tespit etmeyi amaçlayan bir doğal dil işleme (NLP) modelini içermektedir. Model; cinsiyetçilik, ırkçılık, küfür ve hakaret gibi toksik içerikleri sınıflandırmak için sıfırdan eğitilmiştir.


# Kullanılan Veri Seti:
- Overfit-GM/turkish-toxic-language veri seti temel alınmıştır.

# Model Özellikleri
- BiLSTM + CNN + Attention mimarisi
- Eğitimde FastText (cc.tr.300.vec) Türkçe vektörleri kullanılmıştır

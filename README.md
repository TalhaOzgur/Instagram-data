# 📈 Instagram Etkileşim ve Erişim Tahmini (Instagram Reach Prediction)

Bu proje, **Kocaeli Üniversitesi** "Yapay Zeka ve Makine Öğrenimine Giriş" dersi kapsamında, sosyal medya etkileşimlerinin gönderi erişimi (Etki) üzerindeki ağırlığını tahmin etmek amacıyla geliştirilmiştir.

## 📝 Proje Özeti
Sosyal medyada bir gönderinin ne kadar kişiye ulaşacağını (Erişim/Etki) tahmin etmek, içerik üreticileri için kritiktir. Bu proje, beğeni, yorum, kaydetme ve paylaşma gibi metrikleri kullanarak toplam erişim sayısını öngören bir **Makine Öğrenmesi (Lineer Regresyon)** modeli sunar.

* **Ders:** Yapay Zeka ve Makine Öğrenimine Giriş (YZMÖ)
* **Öğrenci:** Talha Özgür
* **Model:** Linear Regression (Denetimli Öğrenme)

## 📂 Veri Seti (Dataset)
Projede kullanılan veri seti, Instagram gönderilerine ait gerçek etkileşim verilerini içermektedir. Veri setinde aşağıdaki özellikler (features) kullanılmıştır:

* **Bağımsız Değişkenler (X):** Evde, Hashtag, Keşfetten, Diğer, Kaydetme, Yorum, Paylaşma, Beğeni, Profil, Takip.
* **Hedef Değişken (y):** Etki (Toplam Erişim Sayısı).

*Veri Kaynağı: Kaggle*

## ⚙️ Kurulum ve Kullanım

Proje Python dili ile yazılmıştır. Aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

```bash
pip install pandas scikit-learn matplotlib
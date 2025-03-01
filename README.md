# Fundus Görüntülerinden Hastalık Tespiti  

Bu proje, fundus görüntülerinden göz hastalıklarını tespit etmeyi amaçlayan bir **lisans bitirme projesidir**. Çalışmada, görüntü kalitesini artırmak ve sınıf dengesini sağlamak amacıyla çeşitli ön işleme teknikleri uygulanmıştır.  

## Kullanılan Veri Kümesi  

Proje kapsamında, aşağıdaki veri kümesi kullanılmıştır:  

🔗 **CLAHE-ESRGAN Split Fundus Dataset**  
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue)](https://www.kaggle.com/datasets/ahmetselukkren/clahe-esrgan-split-fundus-dataset)  

Bu veri kümesi, **ODIR-5K** (Ocular Disease Recognition) veri kümesinin işlenmiş bir versiyonudur.  

## Veri Kümesi İşleme Adımları  

- **Hastalık Etiketlerine Göre Sınıflandırma:**  
  Orijinal veri kümesindeki fundus görüntüleri, hastalık etiketlerine göre sınıflara ayrıldı.  

- **Sınıf Dengesi Sağlama:**  
  Her sınıfın en az **2000 görsel** içermesi sağlandı. Veri dengesizliği problemini gidermek için **sentetik veri üretimi** uygulandı.  

- **Veri Kümesinin Bölünmesi:**  
  Görseller, **train** ve **test** setleri olacak şekilde ayrıldı.  

- **Görüntü Kalitesinin Artırılması:**  
  - **CLAHE (Contrast Limited Adaptive Histogram Equalization)**  
  - **ESRGAN (Enhanced Super-Resolution Generative Adversarial Network)**  
  kullanılarak görüntülerin kontrastı iyileştirildi ve çözünürlüğü artırıldı.  

## Orijinal Veri Kümesi: ODIR-5K  

Orijinal veri kümesi, **Ocular Disease Intelligent Recognition (ODIR)** olup **5.000 hastadan** alınmış fundus görüntülerini içeren bir oftalmoloji veri tabanıdır. Bu veri kümesi, Çin’deki farklı hastaneler ve medikal merkezlerden toplanmıştır. Görüntüler, Canon, Zeiss ve Kowa gibi farklı kamera üreticilerine ait cihazlarla çekildiği için çözünürlükleri değişiklik göstermektedir.  

Veri kümesi, **eğitimli gözlemciler** tarafından etiketlenmiş olup, hastalar aşağıdaki **sekiz hastalık sınıfından** biriyle sınıflandırılmıştır:  

- **Normal (N)**  
- **Diyabet (D)**  
- **Glokom (G)**  
- **Katarakt (C)**  
- **Yaşa Bağlı Makula Dejenerasyonu (A)**  
- **Hipertansiyon (H)**  
- **Patolojik Miyopi (M)**  
- **Diğer Hastalıklar/Anormallikler (O)**  

## Kaynaklar  

- 📌 **ODIR-5K Orijinal Veri Kümesi:** [Kaggle](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k)  
- 📌 **Kullanılan Veri Kümesi (İşlenmiş):** [Kaggle](https://www.kaggle.com/datasets/ahmetselukkren/clahe-esrgan-split-fundus-dataset)  

# Disease Detection from Fundus Images  

This project is an **undergraduate capstone project** that aims to detect eye diseases from fundus images. Various preprocessing techniques have been applied to enhance image quality and ensure class balance.  

## Dataset Used  

The project utilizes the following dataset:  

🔗 **CLAHE-ESRGAN Split Fundus Dataset**  
[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue)](https://www.kaggle.com/datasets/ahmetselukkren/clahe-esrgan-split-fundus-dataset)  

This dataset is a processed version of **ODIR-5K** (Ocular Disease Recognition).  

## Dataset Processing Steps  

- **Classification by Disease Labels:**  
  The original dataset's fundus images were categorized based on their disease labels.  

- **Balancing Class Distribution:**  
  Each class was ensured to contain at least **2000 images**. To address the class imbalance problem, **synthetic data augmentation** was applied.  

- **Dataset Splitting:**  
  The dataset was divided into **train** and **test** sets.  

- **Image Quality Enhancement:**  
  - **CLAHE (Contrast Limited Adaptive Histogram Equalization)**  
  - **ESRGAN (Enhanced Super-Resolution Generative Adversarial Network)**  
  were used to improve contrast and enhance image resolution.  

## Original Dataset: ODIR-5K  

The original dataset, **Ocular Disease Intelligent Recognition (ODIR)**, is a structured ophthalmic database containing fundus images from **5,000 patients** along with age information and diagnostic keywords provided by doctors. This dataset represents **real-world** patient information collected from various hospitals and medical centers in China. The fundus images were captured using different camera models from Canon, Zeiss, and Kowa, leading to variations in image resolution.  

The dataset was **annotated by trained experts** under quality control management. Patients were classified into the following **eight disease categories**:  

- **Normal (N)**  
- **Diabetes (D)**  
- **Glaucoma (G)**  
- **Cataract (C)**  
- **Age-related Macular Degeneration (A)**  
- **Hypertension (H)**  
- **Pathological Myopia (M)**  
- **Other Diseases/Abnormalities (O)**  

## References  

- 📌 **ODIR-5K Original Dataset:** [Kaggle](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k)  
- 📌 **Processed Dataset Used:** [Kaggle](https://www.kaggle.com/datasets/ahmetselukkren/clahe-esrgan-split-fundus-dataset)  



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

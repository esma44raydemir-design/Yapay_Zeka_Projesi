# 🚀 İHA Otonom Uçuş Onay ve Risk Analiz Sistemi

Bu proje, İHA (İnsansız Hava Aracı) ve Drone sistemlerinin kalkış öncesi çevresel faktörleri analiz ederek **"Güvenli Uçuş Onayı"** verip veremeyeceğini denetleyen bir karar destek mekanizmasıdır. 

Özellikle otonom sistemlerde, sensörlerden gelen verilerin (Hava durumu, görüş mesafesi, pist doluluğu) manuel müdahaleye gerek kalmadan işlenmesi hedeflenmiştir.

## 📌 Projenin Amacı ve Kapsamı (Vize Dönemi)
Projenin vize aşamasında, havacılık güvenliğini tehdit eden parametrelerin keşifçi veri analizi (EDA) ve görselleştirmesi yapılmıştır. Sistemin temel çalışma mantığı şu kriterlere dayanır:
* **Hava Durumu Sınıflandırması:** Yağışlı ve karlı havalarda risk analizi.
* **Görüş Mesafesi (Visibility):** Sensör bazlı mesafe ölçümü ile iniş/kalkış güvenliği.
* **Pist Trafiği (Runway Traffic):** Pist üzerindeki engel tespiti otomasyonu.

## 📊 Veri Analizi ve Görselleştirme
Proje kapsamında `Matplotlib` ve `Seaborn` kütüphaneleri kullanılarak simetrik ve estetik veri dağılım grafikleri oluşturulmuştur. Bu grafikler, sistemin hangi koşullarda "Uçuş İptal" kararı verdiğini şeffaf bir şekilde sunmaktadır.

## 🛠️ Kullanılan Teknolojiler
* **Dil:** Python 3.x
* **Platform:** Google Colab / VS Code
* **Kütüphaneler:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

## 📚 Kaynakça ve Esinlenme (References)
Bu projenin geliştirilme sürecinde aşağıdaki bilimsel veriler ve topluluk çalışmalarından yararlanılmıştır:

1. **Hava Durumu Veri Seti:** [Weather Type Classification - Kaggle](https://www.kaggle.com/datasets/...) (İndirdiğin setin linkini buraya koyabilirsin)
2. **Kaza Analizi ve Risk Literatürü:** [Airplane Crashes Analysis - EDA](https://www.kaggle.com/code/melissamonfared/airplane-crashes-analysis-eda)
   * *Bu çalışma, havacılıkta çevresel faktörlerin kaza oranlarına etkisini anlamak için referans alınmıştır.*
3. **Havacılık Standartları:** Otonom uçuş güvenliği ve pist trafik kontrolü protokolleri üzerine genel incelemeler.

## 💡 Gelecek Planları (Final Dönemi)
* **Makine Öğrenmesi:** Mevcut verilerle bir `Decision Tree` (Karar Ağacı) modeli eğitilerek gerçek zamanlı tahminleme yapılacak.
* **Donanım Entegrasyonu:** Su altı ve hava araçları için sensör füzyonu mantığıyla sistem derinleştirilecek.

---
**Hazırlayan:** Esma RAYDEMİR
 

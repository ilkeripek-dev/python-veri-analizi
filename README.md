# 📊 Python Veri Analizi Projesi: Kaggle Spotify Veri Seti

Bu proje, Kaggle'dan alınan 40.000'den fazla şarkı içeren bir veri setini kullanarak Python, Pandas, Matplotlib ve Seaborn kütüphaneleriyle yapılan kapsamlı bir Keşifsel Veri Analizi (EDA) çalışmasıdır.

**Projenin tam analiz raporu (tüm kodlar, açıklamalar ve grafikler) için lütfen aşağıdaki dosyaya tıklayın:**

➡️ **[veri-projem.ipynb](veri-projem.ipynb)** ⬅️
*(Not: GitHub, .ipynb dosyalarını otomatik olarak interaktif bir rapor şeklinde görüntüler.)*

---

## 🚀 Projenin Amacı

Bu projenin temel amacı, ham bir veri setini alıp, onu "konuşan" anlamlı bilgilere dönüştürmektir.

Analiz boyunca aşağıdaki adımlar izlenmiştir:
1.  **Veri Temizleme:** 42.000 satırlık ham verideki "çöp" sütunlar atıldı ve şarkı adı (`song_name`) olmayan 20.000'den fazla satır filtrelendi.
2.  **Veri Zenginleştirme:** `duration_ms` (milisaniye) sütunundan `süre_dakika` adında yeni, okunabilir bir sütun türetildi.
3.  **Analiz & Görselleştirme:** Temizlenmiş veri setine şu sorular soruldu:
    * En uzun şarkılar hangileri? (`sort_values`)
    * En enerjik ve en dans edilebilir müzik türleri hangileri? (`groupby` & `mean`)
    * Enerji ve dans edilebilirlik arasında bir ilişki var mı? (`scatter plot` & `corr`)
    * Hangi özellikler birbiriyle güçlü bir ilişkiye sahip? (`heatmap`)
    * Veri setinin genel "karakteri" nedir? (`histogram`)

## 🛠️ Kullanılan Teknolojiler

* **Python**
* **Pandas:** Veri okuma, temizleme, filtreleme ve gruplama için.
* **Matplotlib:** Temel çubuk grafikler için.
* **Seaborn:** Gelişmiş istatistiksel görseller (Isı Haritası, Histogram) için.
* **Google Colab:** Analizin yapıldığı interaktif not defteri ortamı.

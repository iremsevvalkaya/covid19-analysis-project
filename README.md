# 🦠 Covid-19 Bilimsel Yayın Analizi  
Bu proje, CORD-19 veri seti üzerinden yapılan Covid-19'a dair bilimsel makalelerin analizini kapsamaktadır. Amaç; kelime frekansı, tematik dağılım, yıllara göre eğilimler ve metin madenciliği (NLP) teknikleriyle anlamlı çıkarımlar yaparak güçlü bir portföy çalışması ortaya koymaktır.

## 📝 Notlar

> Bu projede kullanılan `metadata.csv` dosyası, **boyutu 100 MB’ı geçtiği için** `.gitignore` dosyasına eklenmiş ve versiyon kontrolüne dahil edilmemiştir.  
> Projeyi çalıştırmak isteyen kullanıcıların bu CSV dosyasını **manuel olarak** `data/` klasörü içine yerleştirmesi gerekmektedir.

📎 **Veri seti bağlantısı:**  
[🔗 CORD-19 Research Challenge – Kaggle](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)
---

## 🎯 Hedefler

- CORD-19 veri setini temizlemek ve analiz etmek  
- En sık geçen kavramları (death, vaccine, symptom...) zamansal olarak incelemek  
- Yayın eğilimlerini yıllara göre görselleştirmek  
- NLP teknikleri ile makalelerden bilgi çıkarmak  
- Kelime bulutu ve TF-IDF yöntemleri ile öne çıkan ifadeleri belirlemek  

---

## 📊 Uygulanan Analizler

| Kategori                     | Açıklama |
|-----------------------------|----------|
| 📅 **Zamana Dayalı Analiz**  | Yıllara göre yayın sayısı, ölüm temalı içeriklerin artışı  
| ☁️ **WordCloud**            | En sık geçen kelimelerin görsel sunumu  
| 🧠 **TF-IDF Analizi**       | Anlamlı ve ayırt edici anahtar kelimelerin çıkarımı  
| 🔗 **Bigram Analizi**       | En çok geçen ikili kelime grupları  
| ⚠️ **Eksik Veri Tespiti**   | Sütun bazlı eksik veri oranları  

---

## 🔧 Kullanılan Teknolojiler

- `Python 3.x`
- `Pandas`, `NumPy`, `Matplotlib`, `WordCloud`, `Scikit-learn`, `NLTK`
- `Jupyter Notebook` & VS Code
- Git & GitHub ile sürüm kontrol

---

## ▶️ Projeyi Çalıştırmak

**Gerekli kütüphaneleri yükleyin:**

```bash
pip install pandas matplotlib wordcloud nltk scikit-learn

---





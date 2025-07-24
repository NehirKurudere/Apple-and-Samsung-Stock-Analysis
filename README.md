# Apple-and-Samsung-Stock-Analysis
# 📈 Apple & Samsung Hisse Analizi ve Tahmin Projesi

Bu projede, Apple (AAPL) ve Samsung (005930.KS) şirketlerine ait hisse senedi verileri analiz edilmiştir. Python programlama dili kullanılarak zaman serisi görselleştirmeleri yapılmış, ardından Apple hissesi için basit bir doğrusal regresyon modeli ile ertesi gün kapanış fiyatı tahmin edilmiştir.

---

## 🔍 Proje İçeriği

- Yahoo Finance (yfinance) kütüphanesi kullanılarak veriler çekildi
- Eksik ve aykırı veriler kontrol edildi
- Kapanış fiyatları ve hareketli ortalamalar grafiklerle görselleştirildi
- Apple hissesi için makine öğrenmesi modeli (Linear Regression) eğitildi
- Model performansı MAE, RMSE ve R² metrikleri ile değerlendirildi

---

## 🛠 Kullanılan Teknolojiler

| Kütüphane | Açıklama |
|----------|----------|
| `pandas` | Veri işleme |
| `matplotlib`, `seaborn` | Görselleştirme |
| `yfinance` | Hisse verisi çekme |
| `scikit-learn` | Makine öğrenmesi modelleri |

---

## 🧠 Model Performansı

| Metrik | Sonuç |
|--------|--------|
| MAE | `...` |
| RMSE | `...` |
| R² | `...` |

> Not: Model sonuçları, yalnızca örnekleme amaçlıdır. Gerçek yatırım tavsiyesi değildir.

---

## 📁 Dosyalar

- `samsung_and_apple_stocks.ipynb`: Projenin Jupyter Notebook dosyası
- `apple_prepared.csv`: İşlenmiş Apple verisi (isteğe bağlı)
- `README.md`: Proje açıklama dosyası

---

## 📌 Nasıl Çalıştırılır?

```bash
# Gerekli kütüphaneleri yükleyin
pip install pandas matplotlib seaborn yfinance scikit-learn

# Jupyter Notebook üzerinde çalıştırın
jupyter notebook samsung_and_apple_stocks.ipynb
📬 İletişim
Herhangi bir soru ya da geri bildirim için [240704034@atu.edu.tr.com] adresinden ulaşabilirsiniz.

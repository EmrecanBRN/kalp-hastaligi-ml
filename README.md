# 📈 Borsa Veri Analizi — Apple & Big Tech (2024)

## 📌 Proje Hakkında
Bu projede Yahoo Finance API kullanılarak Apple (AAPL), Tesla (TSLA), Google (GOOGL) ve Microsoft (MSFT) hisse senetlerinin 2024 yılı verileri analiz edilmiştir.

## 📊 Yapılan Analizler
1. Gerçek borsa verisi çekme (yfinance)
2. Keşifsel veri analizi (EDA)
3. Fiyat grafiği & hareketli ortalamalar (MA20, MA50)
4. Günlük getiri & risk analizi
5. Kümülatif getiri (1000$ yatırsaydın?)
6. Çoklu hisse karşılaştırması
7. Korelasyon ısı haritası

## 🔧 Kullanılan Teknolojiler
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- yfinance

## 💡 Öne Çıkan Bulgular
- AAPL 2024'te %35.6 getiri sağladı
- TSLA en volatil hisse oldu (%62.6 getiri)
- GOOGL ve MSFT arasında en yüksek korelasyon (0.57)
- Mayıs 2024'te MA20/MA50 kesişimi güçlü alım sinyali verdi

## 🚀 Nasıl Çalıştırılır?
```bash
pip install pandas numpy matplotlib seaborn yfinance jupyter
jupyter notebook borsa_analizi.ipynb
```

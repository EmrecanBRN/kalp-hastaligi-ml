# 🏥 Kalp Hastalığı Tahmini — Machine Learning

## 📌 Proje Hakkında
UCI Heart Disease veri seti kullanılarak kalp hastası olup olmadığını tahmin eden bir makine öğrenmesi modeli geliştirilmiştir.

## 📊 Veri Seti
- 1025 hasta kaydı, 13 özellik
- Kaynak: Kaggle — Heart Disease UCI Dataset

## 🤖 Model
- Algoritma: Random Forest Classifier (100 ağaç)
- Doğruluk: %98.54
- Test seti: 205 hasta

## 🔍 En Önemli Faktörler
1. Göğüs ağrısı tipi (chest_pain_type)
2. Talasemi (thalassemia)
3. Boyanan damar sayısı (vessels_colored_by_flourosopy)
4. ST depresyonu (oldpeak)
5. Maksimum kalp hızı (Max_heart_rate)

## 🔧 Kullanılan Teknolojiler
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestClassifier)

## 🚀 Nasıl Çalıştırılır?
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook kalp_hastaligi.ipynb

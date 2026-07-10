# 💰 Medical Insurance Cost Prediction (Machine Learning Regression)

Bu proje, bireylerin yaş, cinsiyet, vücut kitle indeksi (BMI), çocuk sayısı, sigara kullanımı ve yaşadıkları bölge gibi demografik özelliklerini analiz ederek sağlık sigortası maliyetlerini tahmin etmeyi amaçlayan bir **Makine Öğrenmesi (Machine Learning) Regresyon** çalışmasıdır. Projede veri analizi, özellik mühendisliği ve XGBoost tabanlı regresyon modeli kullanılarak uçtan uca bir makine öğrenmesi pipeline'ı oluşturulmuştur.

---

# 🛠️ Uygulanan Veri Bilimi Aşamaları

## 1. Keşifsel Veri Analizi (EDA)

Model eğitiminden önce veri seti ayrıntılı olarak analiz edilmiştir.

Uygulanan işlemler:

- Veri setinin genel incelenmesi
- Sayısal değişken analizi
- Kategorik değişken analizi
- Histogram ve Boxplot görselleştirmeleri
- Korelasyon matrisi
- Eksik veri kontrolü
- Aykırı değer analizi

---

## 2. Veri Ön İşleme

Makine öğrenmesi modeline uygun veri yapısı oluşturulmuştur.

Uygulanan işlemler:

- One-Hot Encoding
- Kategorik değişkenlerin dönüştürülmesi
- Eğitim ve test veri setlerinin oluşturulması

---

## 3. Özellik Mühendisliği (Feature Engineering)

Model performansını artırmak amacıyla yeni özellikler oluşturulmuştur.

Başlıca işlemler:

- Hedef değişkene Log Transformation (`log1p`)
- BMI tabanlı yeni özellikler
- Etkileşim (interaction) özellikleri
- Model için optimize edilmiş feature seti

---

## 4. Modelleme

Sigorta maliyetlerini tahmin etmek amacıyla **XGBoost Regressor** kullanılmıştır.

Model Parametreleri

- XGBoost Regressor
- Learning Rate
- Max Depth
- Subsample
- Column Sampling
- 500 Estimator

---

# 📊 Model Değerlendirme

Model aşağıdaki regresyon metrikleri ile değerlendirilmiştir.

- R² Score
- RMSE (Root Mean Squared Error)

Ayrıca modelin hangi değişkenlerden daha fazla etkilendiğini göstermek amacıyla **Feature Importance** analizi gerçekleştirilmiştir.

---

# 🏗️ Proje Yapısı

```text
Medical-Insurance-Cost-Prediction/
│
├── insurance.ipynb     # EDA, Feature Engineering ve XGBoost modeli
└── README.md
```

---

# 🚀 Kullanılan Teknolojiler

## Programlama Dili

- Python 3.x

## Veri Analizi

- Pandas
- NumPy

## Görselleştirme

- Matplotlib
- Seaborn

## Makine Öğrenmesi

- Scikit-Learn
- XGBoost

## Geliştirme Ortamı

- Jupyter Notebook

---

# 🔧 Kurulum

## 1. Repoyu Klonlayın

```bash
git clone https://github.com/FarukSelman/Medical-Insurance-Cost-Prediction.git
```

## 2. Proje Klasörüne Girin

```bash
cd Medical-Insurance-Cost-Prediction
```

## 3. Gerekli Kütüphaneleri Kurun

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

## 4. Notebook'u Başlatın

```bash
jupyter notebook
```

Ardından **insurance.ipynb** dosyasını açarak tüm hücreleri sırasıyla (**Run All**) çalıştırabilirsiniz.

---

# 📈 Proje Akışı

1. Veri setinin yüklenmesi
2. Keşifsel veri analizi (EDA)
3. Eksik veri ve aykırı değer analizi
4. One-Hot Encoding
5. Feature Engineering
6. Target değişkenine Log Transformation uygulanması
7. Eğitim ve test veri setlerinin oluşturulması
8. XGBoost modelinin eğitilmesi
9. Tahminlerin oluşturulması
10. R² ve RMSE metrikleri ile model performansının değerlendirilmesi
11. Feature Importance analizi

---

# 💡 Projenin Amacı

Bu çalışma;

- Sağlık sigortası maliyetlerini makine öğrenmesi ile tahmin etmek,
- Keşifsel veri analizi (EDA) uygulamalarını gerçekleştirmek,
- Özellik mühendisliği tekniklerini uygulamak,
- XGBoost regresyon algoritmasını kullanmak,
- Model performansını R² ve RMSE metrikleri ile değerlendirmek

amacıyla geliştirilmiştir.

---

# 👨‍💻 Geliştirici

**Faruk Selman**

GitHub: https://github.com/FarukSelman

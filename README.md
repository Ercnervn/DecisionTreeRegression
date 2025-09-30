# Decision Tree Regression - Kapsamlı Analiz

Bu proje, Decision Tree Regression algoritmasının detaylı analizini ve diğer regresyon modelleri ile karşılaştırmasını içeren kapsamlı bir Jupyter Notebook'tur.

## 📋 Proje Hakkında

Bu notebook, California Housing veri seti kullanarak Decision Tree Regression algoritmasının:
- Temel çalışma prensiplerini
- Performans analizini
- Diğer regresyon algoritmaları ile karşılaştırmasını
- Hiperparametre optimizasyonunu
- Model değerlendirme metriklerini

kapsamlı bir şekilde incelemektedir.

## 🎯 Özellikler

- **Veri Keşfi ve EDA**: California Housing veri setinin detaylı analizi
- **Decision Tree Regression**: Temel model implementasyonu ve analizi
- **Model Karşılaştırması**: Linear Regression, Ridge, ElasticNet ve SVR ile karşılaştırma
- **Hiperparametre Optimizasyonu**: GridSearchCV ile en iyi parametrelerin bulunması
- **Performans Değerlendirmesi**: MSE, R², MAE metrikleri ile detaylı analiz
- **Görselleştirme**: Kapsamlı grafikler ve decision tree visualizasyonu

## 📊 Kullanılan Veri Seti

**California Housing Dataset**
- 20,640 örnek
- 8 özellik (feature)
- 1 hedef değişken (median house value)

### Özellikler:
- `MedInc`: Medyan gelir
- `HouseAge`: Ev yaşı
- `AveRooms`: Ortalama oda sayısı
- `AveBedrms`: Ortalama yatak odası sayısı
- `Population`: Nüfus
- `AveOccup`: Ortalama doluluk oranı
- `Latitude`: Enlem
- `Longitude`: Boylam

## 🛠️ Gereksinimler

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

## 🚀 Kurulum

1. Repository'yi klonlayın:
```bash
git clone https://github.com/Ercnervn/DecisionTreeRegression.git
cd DecisionTreeRegression
```

2. Gerekli kütüphaneleri yükleyin:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Jupyter Notebook'u başlatın:
```bash
jupyter notebook DecisionTreeRegression.ipynb
```

## 📈 Analiz İçeriği

### 1. Veri Keşfi
- Veri setinin temel istatistikleri
- Eksik değer analizi
- Özellik dağılımları
- Korelasyon analizi

### 2. Decision Tree Regression
- Temel model oluşturma
- Model eğitimi
- Tahmin yapma
- Decision tree görselleştirmesi

### 3. Model Karşılaştırması
Aşağıdaki algoritmalar karşılaştırılmaktadır:
- Decision Tree Regression
- Linear Regression
- Ridge Regression
- ElasticNet Regression
- Support Vector Regression (SVR)

### 4. Hiperparametre Optimizasyonu
- GridSearchCV kullanımı
- En iyi parametrelerin bulunması
- Cross-validation ile model doğrulama

### 5. Performans Değerlendirmesi
- Mean Squared Error (MSE)
- R² Score
- Mean Absolute Error (MAE)
- Residual analizi

## 📊 Sonuçlar

Notebook, Decision Tree Regression'ın:
- Avantajlarını ve dezavantajlarını
- Diğer algoritmalarla performans karşılaştırmasını
- Optimal hiperparametre değerlerini
- Gerçek dünya uygulamalarındaki performansını

detaylı bir şekilde sunmaktadır.

---
## Acknowledgments / Teşekkür

Bu çalışma Atıl Samancıoğlu’nun eğitimindeki bir çalışma kapsamında hazırlanmıştır.
Açık kaynak topluluğuna teşekkür ederim.



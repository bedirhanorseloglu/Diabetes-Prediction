# Diyabet Tahmin Modeli

![Diyabet Görseli](https://img.freepik.com/free-vector/diabetes-prevention-illustration_23-2148501894.jpg?w=800&t=st=1656789012~exp=1656789612~hmac=1f1a1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1)

## 📋 Proje Hakkında
Bu proje, makine öğrenmesi kullanarak diyabet hastalığının tahmin edilmesi amacıyla geliştirilmiştir. Çeşitli sağlık metriklerine dayanarak kişilerin diyabet olma olasılığını tahmin etmek için bir model eğitilmiştir.

## 🎯 Kullanım Amacı
- Diyabet riski taşıyan bireyleri önceden tespit etmek
- Erken teşhis ve önleyici tedbirlerin alınmasını sağlamak
- Makine öğrenmesi modellerinin tıp alanındaki uygulamalarını göstermek

## 📊 Veri Seti
Projede kullanılan veri seti aşağıdaki özellikleri içermektedir:
- **Pregnancies**: Hamilelik sayısı
- **Glucose**: Glukoz seviyesi
- **BloodPressure**: Kan basıncı (mm Hg)
- **SkinThickness**: Cilt kalınlığı (mm)
- **Insulin**: 2 saatlik serum insülin (mu U/ml)
- **BMI**: Vücut kitle indeksi (kg/m²)
- **DiabetesPedigreeFunction**: Diyabet soyağaç fonksiyonu
- **Age**: Yaş (yıl)
- **Outcome**: Hastalığa sahip olup olmama durumu (1 veya 0)

## 🛠️ Kullanılan Teknolojiler
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 Kurulum
1. Bu depoyu klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

3. Jupyter Notebook'u çalıştırın:
   ```bash
   jupyter notebook
   ```

## 📈 Model Performansı
Modelin performans metrikleri aşağıdaki gibidir:
- Doğruluk (Accuracy): %XX.XX
- Hassasiyet (Precision): %XX.XX
- Duyarlılık (Recall): %XX.XX
- F1 Skoru: %XX.XX

## 📂 Proje Yapısı
```
diabetes-ml-proje/
├── data/
│   ├── diabetes.csv          # Ham veri seti
│   ├── diabetes_train.csv    # Eğitim verisi
│   └── diabetes_test.csv     # Test verisi
├── Diabetes.ipynb           # Ana çalışma dosyası
└── README.md                # Bu dosya
```

## 🤝 Katkıda Bulunma
1. Fork'layın (https://github.com/kullaniciadi/diabetes-prediction/fork)
2. Yeni bir branch oluşturun (`git checkout -b feature/fooBar`)
3. Değişikliklerinizi commit'leyin (`git commit -am 'Add some fooBar'`)
4. Branch'e push'layın (`git push origin feature/fooBar`)
5. Bir Pull Request oluşturun



## 📞 İletişim
**Geliştirici:** Bedirhan Örseloğlu  
**GitHub:** [@bedirhanorseloglu/githhub](https://github.com/bedirhanorseloglu)  
**LinkedIn:** [@bedirhanorseloglu/linkedin](https://www.linkedin.com/in/bedirhanorseloglu/)



# Turkish Text Classification Project / Türkçe Metin Sınıflandırma Projesi 🚀

## 🎯 Project Overview / Proje Hakkında

**EN**: Advanced AI system for automatic classification of Turkish technical support and customer service texts. Combines deep learning and machine learning techniques to analyze technical issues and support requests in business development systems.

**TR**: Türkçe teknik destek ve müşteri hizmetleri metinlerini otomatik olarak sınıflandıran gelişmiş yapay zeka sistemi. İş geliştirme sistemlerdeki teknik sorunları ve destek taleplerini analiz etmek için derin öğrenme ve makine öğrenmesi tekniklerini birleştirir.

### 🔬 Research Basis / Araştırma Temeli
**EN**: Presents an original approach to solve text classification problems in technical support systems. Achieves high success rates in Turkish text classification through hybrid use of deep learning and traditional machine learning methods.

**TR**: Teknik destek sistemlerindeki metin sınıflandırma problemlerini çözmek için özgün bir yaklaşım sunar. Derin öğrenme ve geleneksel makine öğrenmesi yöntemlerinin hibrit kullanımıyla Türkçe metin sınıflandırmada yüksek başarı oranları elde eder.

## 🌟 Key Features / Öne Çıkan Özellikler

| English Features | Türkçe Özellikler |
|-------------------|--------------------|
| **Hybrid Model Architecture**: BERT-LSTM, Random Forest and SVM implementations with multi-perspective analysis | **Hibrit Model Mimarisi**: BERT-LSTM, Random Forest ve SVM tabanlı çoklu perspektif analiz |
| **High Performance**: 85.11% accuracy in BERT-LSTM, optimized SVM performance | **Yüksek Başarım**: BERT-LSTM'de %85.11 doğruluk, optimize edilmiş SVM performansı |
| **Turkish NLP Optimization**: Specialized text preprocessing and model adaptation for Turkish technical texts | **Türkçe NLP Optimizasyonu**: Türkçe teknik metinler için özel veri ön işleme ve model adaptasyonu |
| **Smart Text Preprocessing**: Advanced text cleaning and normalization | **Akıllı Veri Ön İşleme**: Gelişmiş metin temizleme ve normalizasyon işlemleri |
| **Balanced Learning**: Data imbalance optimization with hybrid sampling techniques | **Dengeli Öğrenme**: Hibrit örnekleme teknikleri ile veri dengesizliği optimizasyonu |
| **Multi-Feature Extraction**: TF-IDF, Random Fourier Features and BERT embeddings combination | **Çok Boyutlu Özellik Çıkarımı**: TF-IDF, Random Fourier Features ve BERT embeddings kombinasyonu |

## 🛠️ Technology Stack / Teknoloji Altyapısı

### Deep Learning Components / Derin Öğrenme Bileşenleri
- **BERT (Bidirectional Encoder Representations from Transformers)**
  - Customized BERT model for Turkish / Türkçe için özelleştirilmiş BERT modeli
  - Contextual embedding layer / Bağlamsal gömme katmanı
- **LSTM (Long Short-Term Memory)**
  - Sequence learning / Sıralı öğrenme
  - Long-term dependency capture / Uzun vadeli bağımlılık yakalama

### Machine Learning Components / Makine Öğrenmesi Bileşenleri
- **Random Forest**
  - Ensemble learning / Topluluk öğrenmesi
  - Multi-decision tree optimization / Çoklu karar ağacı optimizasyonu
- **SVM (Support Vector Machine)**
  - Kernel approximation with Random Fourier Features / Rastgele Fourier Özellikleri ile çekirdek yaklaşımı
  - Optimal separation in high-dimensional space / Yüksek boyutlu uzayda optimal ayrım

### Development Tools / Geliştirme Araçları
- Python 3.x Ecosystem / Python 3.x Ekosistemi
- PyTorch Deep Learning Framework / PyTorch Derin Öğrenme Çatısı
- Scikit-learn ML Library / Scikit-learn ML Kütüphanesi
- Hugging Face Transformers
- NLTK and Spacy NLP Tools / NLTK ve Spacy NLP Araçları

## 📊 Model Performance Analysis / Model Performans Analizi

### BERT-LSTM Model
| Metric          | Value   | Metrik          | Değer   |
|-----------------|---------|-----------------|---------|
| Accuracy        | 85.11%  | Doğruluk        | 85.11%  |
| F1-Score        | 0.84    | F1-Skoru        | 0.84    |
| Precision       | 0.83    | Kesinlik        | 0.83    |
| Recall          | 0.85    | Duyarlılık      | 0.85    |

### Random Forest Model / Random Forest Modeli
| Metric (EN)          | Value   | Metrik (TR)          | Değer   |
|----------------------|---------|----------------------|---------|
| Accuracy             | 62.78%  | Doğruluk             | 62.78%  |
| F1-Score             | 0.66    | F1-Skoru             | 0.66    |
| ROC-AUC Score        | 0.94    | ROC-AUC Skoru        | 0.94    |
| Matthews Correlation | 0.61    | Matthews Korelasyonu | 0.61    |

### SVM with Random Fourier Features / Rastgele Fourier Özellikli SVM
| Feature (EN)               | Description (EN)                          | Özellik (TR)               | Açıklama (TR)                          |
|----------------------------|--------------------------------------------|----------------------------|-----------------------------------------|
| Optimized hyperparameters  | GridSearchCV based optimization           | Optimize hiperparametreler | GridSearchCV tabanlı optimizasyon       |
| Adaptive kernel approach   | Dynamic kernel selection strategy         | Adaptif çekirdek yaklaşımı | Dinamik çekirdek seçim stratejisi       |
| Class weighting strategy   | Handling imbalanced class distribution    | Sınıf ağırlıklandırma      | Dengesiz sınıf dağılımı yönetimi        |

## 🔬 Methodology / Metodoloji

### Data Preparation & Preprocessing / Veri Hazırlama ve Ön İşleme
- **Text normalization & cleaning / Metin normalizasyonu ve temizleme**
  - URL and special character filtering / URL ve özel karakter filtreleme
  - Turkish character normalization / Türkçe karakter normalizasyonu
  - Stop-word elimination / Stop-word eliminasyonu

### Feature Engineering / Özellik Mühendisliği
- **TF-IDF Vectorization / TF-IDF Vektörizasyonu**
  - N-gram analysis (1-2 grams) / N-gram analizi (1-2 gram)
  - Feature selection & dimension reduction / Özellik seçimi ve boyut indirgeme

## 🚀 Getting Started / Başlangıç

### System Requirements / Sistem Gereksinimleri
```python
datasets>=3.1.0
torch>=1.8.0
transformers>=4.5.0
scikit-learn>=0.24.0
pandas>=1.2.0
numpy>=1.19.0
matplotlib>=3.3.0
joblib>=1.0.0
```

## 🔍 Research Details / Araştırma Detayları

### Dataset Features / Veri Seti Özellikleri
- **EN**: Imbalanced class distribution with domain-specific Turkish technical terms  
- **TR**: Domain-specific Türkçe teknik terimler içeren dengesiz sınıf dağılımı

### Model Comparison / Model Karşılaştırması
| Model (EN)          | Strength (EN)              | Model (TR)          | Güçlü Yön (TR)          |
|---------------------|----------------------------|---------------------|--------------------------|
| BERT-LSTM           | Best overall performance   | BERT-LSTM           | En iyi genel performans  |
| SVM                 | Fast training/prediction   | SVM                 | Hızlı eğitim/tahmin      |

## 🤝 Contributing / Katkıda Bulunma

**EN**: To contribute to the project:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

**TR**: Projeye katkıda bulunmak için:
1. Depoyu fork'layın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'i push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın

## 📫 Contact / İletişim
**EN**: For project development and collaboration:
- Email: [eyup.tp@hotmail.com](mailto:eyup.tp@hotmail.com)
- GitHub Issues: [Issues](https://github.com/kullanici/TurkishTextClassification/issues)

**TR**: Proje geliştirme ve işbirliği için:
- E-posta: [eyup.tp@hotmail.com](mailto:eyup.tp@hotmail.com)
- GitHub Issues: [Sorunlar](https://github.com/kullanici/TurkishTextClassification/issues)

## 📄 License / Lisans
**EN**: This project is licensed under the [GNU GENERAL PUBLIC LICENSE](LICENSE). See LICENSE file for details.  
**TR**: Bu proje [GNU GENEL KAMU LİSANSI](LICENSE) altında lisanslanmıştır. Detaylar için LICENSE dosyasını inceleyin. 

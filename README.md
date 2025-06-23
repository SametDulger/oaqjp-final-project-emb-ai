# Emotion Detection - NLP Final Project

IBM Developer Skills Network'in "Getting Started with Enterprise AI" kursunun final projesi. Doğal dil işleme (NLP) kullanarak metin tabanlı duygu analizi yapan web uygulaması.

## 🎯 Proje Amacı

Bu proje, kullanıcıların girdiği metinleri analiz ederek duygusal tonunu tespit eden bir web uygulamasıdır. IBM'in AI ve NLP teknolojilerini kullanarak geliştirilmiştir.

## ✨ Özellikler

- 📝 **Metin Analizi**: Kullanıcı girdiği metni analiz eder
- 🧠 **Duygu Tespiti**: Metindeki duygusal tonu belirler
- 🌐 **Web Arayüzü**: Kullanıcı dostu web arayüzü
- ⚡ **Gerçek Zamanlı**: Anında analiz sonuçları
- 📱 **Responsive**: Mobil uyumlu tasarım

## 🛠️ Kullanılan Teknolojiler

- **HTML5**: Yapısal markup
- **CSS3**: Stil ve düzen
- **JavaScript**: İnteraktif işlevsellik
- **Bootstrap 4**: Responsive UI framework
- **IBM Watson NLP**: Duygu analizi API'si
- **AJAX**: Asenkron veri iletişimi

## 📁 Proje Yapısı

```
oaqjp-final-project-emb-ai/
├── templates/
│   └── index.html          # Ana web sayfası
├── static/
│   └── mywebscript.js      # JavaScript işlevselliği
├── README.md               # Bu dosya
├── LICENSE                 # Apache 2.0 lisansı
└── .gitignore             # Git ignore dosyası
```

## 🚀 Kurulum ve Çalıştırma

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/SametDulger/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```

2. **Web sunucusu başlatın:**
   ```bash
   # Python ile
   python -m http.server 8000
   
   # Node.js ile
   npx http-server
   ```

3. **Tarayıcıda açın:**
   ```
   http://localhost:8000
   ```

## 📖 Kullanım

1. **Metin Girin**: "Please enter the text to be analyzed" alanına analiz etmek istediğiniz metni yazın
2. **Analiz Başlatın**: "Run Sentiment Analysis" butonuna tıklayın
3. **Sonuçları Görün**: "Result of Emotion Detection" bölümünde analiz sonuçlarını inceleyin

## 🔧 Teknik Detaylar

### Frontend
- **HTML**: Bootstrap 4 ile responsive tasarım
- **JavaScript**: AJAX ile backend API'sine istek gönderme
- **CSS**: Özel stiller ve düzenlemeler

### Backend API
- **Endpoint**: `/emotionDetector`
- **Method**: GET
- **Parameter**: `textToAnalyze` (analiz edilecek metin)
- **Response**: Duygu analizi sonucu

## 🌐 API Kullanımı

```javascript
// JavaScript ile API çağrısı
let xhttp = new XMLHttpRequest();
xhttp.open("GET", "emotionDetector?textToAnalyze=" + text, true);
xhttp.send();
```

## 🎓 Öğrenme Hedefleri

Bu proje şu konuları kapsar:

- ✅ **NLP Temelleri**: Doğal dil işleme
- ✅ **AI Entegrasyonu**: IBM Watson API kullanımı
- ✅ **Web Geliştirme**: Frontend ve backend entegrasyonu
- ✅ **API Tasarımı**: RESTful API geliştirme
- ✅ **Responsive Design**: Mobil uyumlu arayüz

## 🤝 Katkıda Bulunma

Bu proje IBM Developer Skills Network'in eğitim materyali olarak geliştirilmiştir. Katkıda bulunmak için:

1. Fork yapın
2. Feature branch oluşturun
3. Değişikliklerinizi commit edin
4. Pull request gönderin

## 📄 Lisans

Bu proje [Apache License 2.0](LICENSE) lisansı altında lisanslanmıştır.

**Copyright 2020 IBM Developer Skills Network**

## 🔗 İlgili Kaynaklar

- [IBM Developer Skills Network](https://skills.network/)
- [Getting Started with Enterprise AI](https://skills.network/course/getting-started-enterprise-ai)
- [IBM Watson NLP](https://www.ibm.com/cloud/watson-natural-language-understanding)

---

IBM Developer Skills Network'in AI ve NLP eğitiminin bir parçası olarak geliştirilmiştir. 🚀

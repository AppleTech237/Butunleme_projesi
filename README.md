# BUTUNLEME


---

📦 **Stok Yönetim Uygulaması — Flask ile**

---

### 1. 🎯 Projenin Amacı

Bu proje, küçük ve orta ölçekli işletmelerin sıkça karşılaştığı bir ihtiyaca cevap vermek amacıyla geliştirilmiştir: **etkili stok yönetimi**. Uygulama şu imkânları sağlar:
• Ürünlerin gerçek zamanlı takibi
• Kritik stok seviyelerinin yönetimi

Manuel veya dağınık takip sistemleri hatalara ve kayıplara yol açabilir. Bu uygulama ise basit ama güçlü bir çözüm sunar. Özellikle depolar, küçük mağazalar ve lojistik işletmeleri için uygundur.

---

### 2. 🧩 Kapsam ve Özellikler

✅ **Dahil Olan Özellikler** :
• Kullanıcı doğrulama sistemi
• Ürünler üzerinde CRUD işlemleri (Ekleme, Güncelleme, Silme)
• Ürünlerin tam listesi
• Ada, kategoriye veya stok seviyesine göre filtreleme
• Kritik stok seviyesinde görsel uyarılar

❌ **Dahil Olmayan Özellikler** :
• Otomatik e-posta veya bildirim gönderimi yok
• Gelişmiş analiz raporları (KPI, grafikler vb.) yok
• Çoklu depo veya varyantlı ürün yönetimi yok

---

### 3. 🛠 Kullanılan Teknolojiler

• **Diller** : Python, HTML, CSS, JavaScript
• **Frameworkler** :
 ◦ Backend : Flask
 ◦ Frontend : Bootstrap 5
• **Veritabanı** : SQLite
• **Diğer Araçlar** :
 ◦ Flask-Login (oturum yönetimi)
 ◦ FontAwesome (ikonlar için)

---

### 4. 🚀 Kurulum ve Çalıştırma

**Adımlar** :

1. Git deposunu klonlayın veya ZIP arşivini çıkarın
2. Gerekli kütüphaneleri yükleyin :
    `pip install -r requirements.txt`
3. Uygulamayı başlatın :
    `python app.py`
4. Tarayıcınızdan şu adresi açın :
    [http://127.0.0.1:5000](http://127.0.0.1:5000) veya [http://127.0.0.1:10000](http://127.0.0.1:10000)

✅ Python kurulu olan herhangi bir sistemde çalıştırılabilir.

---

### 5. 🗂 Proje Klasör Yapısı

```
├── 2.hafta/                    # Proje ana dizini  
│   ├── instance/               # Yerel veriler / SQLite dosyaları  
│   ├── static/  
│   │   └── images/  
│   │       └── hero.png        # Ana görsel  
│   │   └── css/  
│   │       └── style.css  
│   │   └── js/  
│   │       └── stok.js  
│   ├── templates/              # HTML dosyaları  
│   │   ├── base.html  
│   │   ├── dashboard.html  
│   │   ├── hakkinda.html  
│   │   ├── index.html  
│   │   ├── login.html  
│   │   ├── register.html  
│   │   ├── stok_duzenle.html  
│   │   ├── stok_ekle.html  
│   │   └── stok_listesi.html  
│   ├── app.py                  # Ana Flask dosyası  
│   ├── db2json.py              # Stok verilerinin JSON’a aktarılması  
│   ├── urunler.json            # Örnek ürün verileri  
│   ├── users.json              # Örnek kullanıcı verileri  
│   ├── requirements.txt        # Python bağımlılıkları  
│   └── README.md               # Bu dosya  
└── final_versiyon.md           # Final sürüm notları  
```

---

### 6. 📸 Ekran Görüntüleri

🔐 **Giriş Sayfası**
.....

📋 **Ürün Listesi**
....

➕ **Ürün Ekleme Formu**
....

---

### 7.  Karşılaşılan Zorluklar ve Öğrenilen Dersler

🔧 **Karşılaşılan Sorunlar** :
• Python’da girintileme hataları (özellikle kritik)
• Modeller arası ilişkilerin yönetimi (kullanıcılar ↔ ürünler)
• CRUD işlemleri sırasında hata yönetimi
• Ürün silme butonlarının işlevselliği
• Filtreleme işlemlerinin yönetimi

📘 **Geliştirilen Beceriler** :
• Flask ve SQLAlchemy hakkında derin bilgi
• Kullanıcı oturumu yönetimi konusunda uzmanlaşma
• Temiz ve sürdürülebilir proje mimarisi oluşturma
• `app.py` dosyasındaki rotaların iyi kavranması

---

### 8. 🌱 Geliştirme Fırsatları

Daha fazla zamanla şu özellikler eklenebilir :
• CSV veya PDF olarak veri dışa aktarma
• Stok seviyelerinin grafiksel gösterimi
• Veri erişimi için REST API geliştirme
• Yöneticilere özel bir kontrol paneli
• Stok hareketlerinin geçmiş kaydı

---

### 9. 📬 İletişim

• **GitHub** : `butunleme` 
• **E-posta** : `gazangue@gmail.com`

---

# 🌐 AspNetCore-Personal-Portfolio

**ASP.NET Core 5.0 MVC** kullanılarak geliştirilmiş, tam kapsamlı bir web uygulamasıdır.

---

## 🚀 Kullanılan Teknolojiler

| Katman | Teknoloji |
|--------|-----------|
| Backend | ASP.NET Core 5.0, C#, MVC |
| ORM | Entity Framework Core, LINQ |
| Veritabanı | MSSQL |
| Mimari | N-Tier Architecture, Repository Design Pattern |
| Kimlik | ASP.NET Identity, Rolleme |
| Frontend | HTML, CSS, Bootstrap, JavaScript, Ajax |
| Diğer | Charts, Raporlama, Mail Gönderme |
| Araçlar | Git, GitHub |

---

## ⚙️ Özellikler

### 🏗️ Mimari & Yapı
- ✅ N-Tier Architecture (DataAccess, Business, Entity, UI katmanları)
- ✅ Repository Design Pattern
- ✅ Unit of Work
- ✅ SOLID prensipleri

### 👤 Kullanıcı Yönetimi
- ✅ ASP.NET Identity ile kayıt ve giriş
- ✅ Rol bazlı yetkilendirme (Admin / Kullanıcı)
- ✅ Kullanıcı profil yönetimi

### 📊 Veri & Raporlama
- ✅ Entity Framework Core ile CRUD işlemleri
- ✅ LINQ sorguları
- ✅ Chart entegrasyonu (istatistik grafikleri)
- ✅ Raporlama modülü
- ✅ Ajax ile dinamik veri yükleme

### 📧 İletişim
- ✅ Mail gönderme entegrasyonu

---

## 📁 Proje Mimarisi

```
CoreProject/
├── DataAccessLayer/    # Repository, Context
├── BusinessLayer/      # Servisler, iş kuralları
├── EntityLayer/        # Entity modelleri
└── Core_Proje/           # MVC arayüz, Controller, View
```

---

## 🛠️ Kurulum

```bash
# 1. Repoyu klonla
git clone https://github.com/enesozdemir23/CoreProject.git

# 2. appsettings.json bağlantı dizesini düzenle
"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=CoreProjectDb;Trusted_Connection=True;"
}

# 3. Migration uygula
dotnet ef database update

# 4. Uygulamayı çalıştır
dotnet run
```

---

## 👤 Geliştirici

**Enes Özdemir**  
📧 ozdemir.enes2323@gmail.com  
🔗(https://github.com/enes-ozdemir23)

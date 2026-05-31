# 🚀 ATÜ Öğrenci Forum Platformu

Adana Alparslan Türkeş Bilim ve Teknoloji Üniversitesi öğrencileri için geliştirilmiş modern, hızlı ve dinamik bir forum ve topluluk platformudur. Proje tamamen native PHP, MySQL ve modern CSS teknolojileri kullanılarak geliştirilmiştir.

---

## ✨ Öne Çıkan Özellikler

### 🎨 1. Modern & Responsive Tasarım
- Modern koyu tema navbar yapısı
- Responsive (mobil uyumlu) arayüz
- Grid & Flexbox destekli kart sistemi
- Google Fonts (Inter) tipografi sistemi
- Sticky footer yapısı
- Modern hover efektleri ve geçiş animasyonları

---

### 🔐 2. Güvenli Üyelik Sistemi
- BCRYPT ile şifre güvenliği
- Kullanıcı kayıt ve giriş sistemi
- Session tabanlı oturum yönetimi
- Benzersiz kullanıcı adı ve e-posta kontrolü
- Yetkisiz sayfa erişim koruması

---

### 👤 3. Gelişmiş Profil Sistemi
Kullanıcılar kendi profillerinde:
- yaş bilgisi
- bölüm bilgisi
- hobiler
- biyografi alanı

gibi kişisel bilgileri görüntüleyebilir.

Ayrıca kullanıcı isimlerine tıklayarak profil sayfasına erişilebilir.

---

### 📋 4. Forum & Konu Yönetimi
- Kategori tabanlı konu paylaşımı
- Konu görüntüleme sistemi
- Konu düzenleme sistemi
- Konu silme sistemi
- Kullanıcıya özel konu kontrolü
- Popüler konular paneli
- Son hareketlilik alanı

---

### 💬 5. Yorum Sistemi
- Konulara yorum yapabilme
- Yorum filtreleme sistemi
  - En yeni
  - En eski
- Admin yetkisi ile yorum silme
- Dinamik yorum listeleme sistemi

---

### 🔔 6. Bildirim Sistemi
Kullanıcının konusuna yorum yapıldığında:
- otomatik bildirim oluşturulur
- navbar üzerinde bildirim sayacı gösterilir
- kullanıcı bildirim ekranından tüm hareketleri görüntüleyebilir

---

### 📊 7. Forum İstatistikleri
Sistem üzerinde:
- toplam kullanıcı sayısı
- toplam konu sayısı
- aktif hareketlilik verileri

dinamik SQL sorguları ile anlık gösterilmektedir.

---

## 🛠️ Kullanılan Teknolojiler

- PHP (Native)
- MySQL
- HTML5
- CSS3
- JavaScript
- XAMPP
- Apache Server

---

## 📁 Proje Yapısı

```text
htdocs/
│
├── index.php
├── db.sql
├── login.php
├── register.php
├── profile.php
├── notifications.php
├── post_add.php
├── post_view.php
├── edit_post.php
├── logout.php
├── config.php
├── style.css
├── logo.png
├── favicon.png
│
├── partials/
  ├── header.php
  └── footer.php

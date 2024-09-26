# Blog Sitesi Projesi

Bu proje, admin tarafından blog yazıları oluşturabileceği, yönetebileceği ve kullanıcıların yorumda bulunabileceği basit bir **Blog Sitesi** uygulamasıdır. Projede bir **Admin Paneli** mevcuttur. Admin paneli üzerinden bloglar, kullanıcılar ve yorumlar yönetilebilir.

## Özellikler

### Genel Özellikler
- Admin blog gönderileri oluşturabilir, güncelleyebilir ve silebilir.
- Her kullanıcı siteye üye olup, giriş yaptıktan sonra yorum yazabilir.

### Admin Paneli
Admin paneli, sadece site yöneticilerinin erişebildiği bir arayüzdür. Burada adminler:
- **Blog Listesi**: Tüm blog yazılarını listeleyebilir, güncelleyebilir ve silebilir.
- **Kullanıcı Listesi**: Kayıtlı tüm kullanıcıları görebilir, güncelleyebilir ve silebilir.
- **Yorum Listesi**: Tüm yorumları yönetebilir, silebilir.
 
Bu özellikler, blog sitesinin yönetimini ve kontrolünü kolaylaştırmak amacıyla geliştirilmiştir.

## Kullanım

### Gereksinimler
- **PHP**: 7.4 veya üzeri
- **MySQL**: 5.7 veya üzeri
- **Apache veya Nginx**: Web sunucusu olarak kullanılabilir.
- **Bootstrap**: Arayüz için kullanılmıştır.

### Kurulum
1. Proje dosyalarını yerel sunucunuza veya hosting hesabınıza yükleyin.
2. `config.php` dosyasında veritabanı ayarlarını (host, kullanıcı adı, şifre ve veritabanı adı) yapılandırın.
3. Veritabanınızı yapılandırmak için `database.sql` dosyasını MySQL sunucunuza yükleyin.
4. Tarayıcınızda proje dizinine giderek giriş yapabilir ve blog sitenizi kullanmaya başlayabilirsiniz.

### Admin Paneline Giriş
1. Admin paneline erişmek için `admin/` dizinine gidin.
2. Admin giriş bilgileri:
   - Kullanıcı Adı: `admin`
   - Şifre: `admin123`

Bu giriş bilgilerini `user` tablosundan güncelleyebilir veya değiştirebilirsiniz.

### Admin Paneli Özellikleri
- **Blog Listesi**: Mevcut blogları listeleyebilir, düzenleyebilir ve silebilirsiniz.
- **Kullanıcı Listesi**: Siteye kayıtlı tüm kullanıcıları yönetebilirsiniz.
- **Yorum Listesi**: Bloglara yapılmış tüm yorumları görebilir ve silebilirsiniz.

### Kullanıcı İşlemleri
- Kullanıcılar, siteye üye olduktan sonra blog yazabilir, bloglara yorum yapabilir ve kendi yazılarını düzenleyebilir.

## Proje Dosya Yapısı

- **admin/**: Admin paneli dosyaları.
- **includes/**: Ortak kullanılan PHP dosyaları (header, footer, config).
- **uploads/**: Blog gönderilerine eklenen dosyaların depolandığı klasör.
- **user/**: Kullanıcı girişi, kayıt ve çıkış işlemleri.
- **index.php**: Anasayfa dosyası.

## Lisans
Bu proje açık kaynaklıdır ve herhangi bir ticari amaçla kullanılabilir.

---

# student-question-asking-and-answering-app
#  Proje Planı
1. Özellikler ve Fonksiyonlar:
## Kullanıcı Yönetimi:
## Kayıt:
Form doğrulamaları.
Şifre gücü göstergesi.
Şifre tekrarı eşleştirme.


## Giriş:
Beni Hatırla opsiyonu.
Şifremi Unuttum özelliği.
Şifre Sıfırlama:
Email doğrulamalı sıfırlama süreci.

## Profil Yönetimi:
Kullanıcı fotoğrafı yükleme.
Biyografi ve uzmanlık alanı (öğretmenler için).

## Soru Gönderimi:
Drag and drop ile resim yükleme.
Soru metni için WYSIWYG editor.
Sorunun zorluk seviyesi, kategorisi ve etiketleri.

## Soru Cevaplama:
WYSIWYG editor ile cevap verme.
Önceki cevapları gösterme ve değerlendirme (upvote/downvote).

## Bildirimler:
Web soketleri ile canlı bildirimler.
Bildirim ayarları: Email ve/veya uygulama içi.

## Arama & Filtreleme:
Otomatik tamamlamalı arama kutusu.
Filtreleme için kategori ve etiket seçenekleri.

## Admin Paneli:
Dinamik grafiklerle istatistikler.
Kullanıcı, soru, ve cevap yönetimi için tablolar.

## 2. UI/UX Detayları:
Renk Paleti: Genç ve enerjik pastel tonlar.
Tipografi: Okunabilir fontlar (Ör. Roboto, Open Sans).
Responsive Tasarım: Mobil, tablet ve masaüstü için uyum.
Hızlı Erişim Menüsü: Ana sayfada sık kullanılan özelliklere hızlı erişim.
Interaktif Elementler: Hover efektleri, yükleme animasyonları, geçişler.
Kullanıcı Geri Bildirimleri: Sorun bildirme, öneri gönderme formu.
Onboarding: Yeni kullanıcılara rehber.

## 3. Kullanıcı Akışı (User Flow):
Ana Sayfa: Popüler sorular, yeni sorular, hızlı erişim.
Soru Gönder: Basit ve kullanıcı dostu form.
Soru Detayı: Soru, cevaplar, yorumlar, ilgili sorular.
Profil: Kullanıcının soruları, cevapları, bildirimler.
Admin Panel: İstatistikler, yönetim panelleri.

## 4. Klasör & Dosya Yapısı:

/student-question-asking-and-answering-app
|-- /client (Frontend)
|   |-- /src
|   |   |-- /components
|   |   |   |-- /auth (Login, Register, PasswordReset)
|   |   |   |-- /questions (QuestionList, QuestionDetail, NewQuestion)
|   |   |   |-- /notifications
|   |   |   |-- /admin
|   |   |   |-- /shared (Header, Footer, Sidebar)
|   |   |-- /redux (actions, reducers, store)
|   |   |-- /styles (globalStyles, theme)
|   |   |-- App.js (Main component with React Router)
|   |   |-- index.js (Main entry point, where React DOM renders)
|-- /server (Backend)
|   |-- /models (User, Question)
|   |-- /routes (authRoutes, questionRoutes, adminRoutes)
|   |-- /controllers (authController, questionController, adminController)
|   |-- /middleware (authMiddleware, errorMiddleware)
|   |-- server.js (Express app setup and configurations)
|   |-- index.js (Main entry point, where the server is started)


## 5. Geliştirme Adımları:
Backend temel kurulum: Node.js, Express.js, MongoDB.
JWT bazlı kimlik doğrulama sistemi.
User ve Question modelleri.
API endpointlerini oluşturma.
Frontend temel kurulum: Create React App.
Redux state yönetimi kurulumu.
Auth, Questions, Notifications ve Admin için sayfalar ve bileşenler.
Bootstrap ve Styled Components ile stil ve tema.
Frontend'den backend'e API istekleri.
Web soketleri ile canlı bildirimler.
Kategori bazlı arama ve filtreleme.
Admin paneli.

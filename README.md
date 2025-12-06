# Dashboard 209 - Personalized Web Dashboard

## 🚀 Proje Genel Bakış

**Dashboard 209** kişiselleştirilmiş, tek sayfalık bir web gösterge paneli uygulamasıdır. Kullanıcılara anlık bilgilere, web kısayollarına, hatırlatıcılara, sayaçlara ve temalı bir saat/kronometreye erişim sağlamak amacıyla tasarlanmıştır. Uygulama, kullanıcının verilerini yerel depolamada (LocalStorage) saklayarak oturum yönetimi sunar.

### Ana Özellikler

* **Tema Seçimi:** Cyberpunk, Matrix ve True Black (OLED) dahil olmak üzere farklı temalar.
* **Kullanıcı Kimlik Doğrulaması:** Basit kayıt/giriş ve oturum yönetimi (LocalStorage tabanlı).
* **Bilgi Kısayolları:** Tekrar eden metin parçalarını (isim, adres, numara vb.) kaydetme, kopyalama ve sürükle-bırak ile düzenleme yeteneği.
* **Web Kısayolları:** Hızlı erişim için web sitesi simgelerini (favicons) kaydetme ve yönetme.
* **Hatırlatıcılar:** Tarihli ve emojili aktif/tamamlanmış hatırlatıcı listeleri.
* **Saat ve Sayaç:** Gelişmiş dijital saat, pomodoro zamanlayıcısı (timer) ve kronometre (stopwatch) işlevleri.
* **Entegre Widget'lar:** İstanbul için hava durumu ve canlı döviz kurları (USD/EUR - TRY) widget'ları.

---

## ⚙️ Teknik Yığın

Bu proje, modern web teknolojileri kullanılarak tek bir HTML dosyasında toplanmıştır.

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Kütüphaneler:** **React 18** (UI/Durum Yönetimi için), **Lucide-React** (İkonlar için)
* **Stil:** **Tailwind CSS** (Anlık, fayda tabanlı stil için)
* **Çalışma Zamanı:** **Babel Standalone** (Tarayıcıda JSX ve ES Modüllerini çalıştırmak için)

---

## 🏁 Kurulum ve Çalıştırma

Bu proje, tek bir HTML dosyası olduğu için herhangi bir sunucu veya derleme adımı gerektirmez.

### 1. Dosyayı Kaydetme

1.  Yukarıdaki kodu `index.html` olarak kaydedin.
2.  İsteğe bağlı olarak, başlıkta belirtilen favicon için aynı dizine bir `icon.png` dosyası ekleyin.

### 2. Çalıştırma

Dosyayı çalıştırmak için:

* `index.html` dosyasını tarayıcınızda çift tıklayarak doğrudan açın.

### ⚠️ Önemli Not

Uygulama, kullanıcı verilerini (kısayollar, temalar, kullanıcı adı/şifre testleri) depolamak için tarayıcının **LocalStorage** özelliğini kullanır. Bu, herhangi bir sunucu bağlantısı olmadığı anlamına gelir.

---

## 🛠️ Kullanım

Uygulama ilk açıldığında, sizden bir hesap oluşturmanız veya giriş yapmanız istenecektir:

1.  **Kayıt:** Bir e-posta adresi ve şifre (test için en az 6 karakter) girin ve **Register** butonuna tıklayın.
2.  **Giriş:** Kayıtlı bir e-posta ve şifre ile **Login** olun.
3.  Giriş yaptıktan sonra, sayfa başlığındaki navigasyon çubuğunu kullanarak dört ana sekme arasında geçiş yapabilirsiniz:
    * **Info & Shortcuts:** Metin kısayollarını yönetin.
    * **Website Shortcuts:** Web sitesi bağlantılarını ve simgelerini yönetin.
    * **Reminders:** Hatırlatıcıları ekleyin ve tamamlayın.
    * **Counter & Clock:** Dijital saat, Pomodoro Zamanlayıcısı ve Kronometreyi kullanın.
4.  Sağ üstteki **Settings** (Dişli İkonu) ile temayı değiştirebilir ve oturumu kapatabilirsiniz.

---

## 📝 Gelecek Geliştirmeler

Bu projenin ileride geliştirilebilecek potansiyel özellikleri şunlardır:

* **Gerçek Backend:** LocalStorage yerine veritabanı tabanlı kalıcı oturum yönetimi.
* **Gelişmiş Widget'lar:** Özelleştirilebilir RSS beslemeleri veya borsa takibi eklenmesi.
* **Mobil Uyumluluk:** Daha iyi bir mobil görüntüleme deneyimi için responsive tasarım iyileştirmeleri.
* **Özelleştirme Seçenekleri:** Kullanıcının panel düzenini (layout) sürükle-bırak ile değiştirebilmesi.

---

## 🤝 Katkıda Bulunma

Bu projeye katkıda bulunmaktan çekinmeyin.

1.  (Fork) Çatallayın
2.  (`git checkout -b feature/AmazingFeature`) Yeni bir dal oluşturun
3.  Değişikliklerinizi yapın
4.  (`git commit -m 'Add some AmazingFeature'`) Değişikliklerinizi taahhüt edin
5.  (`git push origin feature/AmazingFeature`) Dalı gönderin
6.  (Pull Request) Çekme İsteği açın

---

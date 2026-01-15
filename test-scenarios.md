# Test Senaryoları — Simple Notes (Android)

## TS-01: Uygulamanın Açılışı ve İlk Durum (Smoke Test)

- Uygulamanın hatasız şekilde açıldığını doğrula.
- Ana sayfanın başarıyla yüklendiğini doğrula.
- Hiç not yokken empty state mesajının görüntülendiğini doğrula.
- Empty state mesajının kullanıcıyı yönlendirici ve anlaşılır olduğunu doğrula.

---

## TS-02: Alt Menü (Bottom Navigation) Kontrolleri

- Ana Sayfa, Hepsi, Geçmiş ve Ayarlar sekmeleri arasında geçiş yapılabildiğini doğrula.
- Aktif sekmenin görsel olarak vurgulandığını doğrula.
- Sekmeler arası geçişte uygulama durumunun (state) korunduğunu doğrula.
- Orta alandaki “+” butonunun tüm sekmelerde erişilebilir olduğunu doğrula.

---

## TS-03: Yeni Not Oluşturma Giriş Noktaları

- “Yeni not” butonuna tıklandığında not oluşturma ekranının açıldığını doğrula.
- “+” butonuna tıklandığında not oluşturma ekranının açıldığını doğrula.
- Her iki butonun aynı davranışı sergilediğini doğrula.
- Geri butonuna basıldığında ana ekrana sorunsuz dönüldüğünü doğrula.

---

## TS-04: Empty State (Boş Durum) Davranışları

- Ana Sayfa ekranında not yokken empty state mesajının görüntülendiğini doğrula.
- Hepsi ekranında arama sonucu bulunamadığında uygun mesajın gösterildiğini doğrula.
- Geçmiş ekranında hiç not yokken empty state mesajının gösterildiğini doğrula.

---

## TS-05: Not Sıralama Seçenekleri

- “Şuna göre sırala” penceresinin açıldığını doğrula.
- “Manual” sıralama seçeneğinin çalıştığını doğrula.
- “Alfabetik” sıralama seçeneğinin çalıştığını doğrula.
- Seçilen sıralama türünün listeye doğru yansıtıldığını doğrula.
- Sayfa değiştirildiğinde sıralama seçiminin korunduğunu doğrula.

---

## TS-06: Sekme (Tab) Yönetimi

- Yeni bir sekme eklenebildiğini doğrula.
- Sekme adının değiştirilebildiğini doğrula.
- Sekmenin çoğaltılabildiğini doğrula.
- Sekme arka plan renginin değiştirilebildiğini doğrula.
- Seçili notların silinebildiğini doğrula.
- Tüm notların silinebildiğini doğrula.
- Sekmenin silinebildiğini doğrula.

---

## TS-07: Not Arama Fonksiyonu

- Hepsi ekranında arama alanının görüntülendiğini doğrula.
- Mevcut bir not başlığı ile arama yapıldığında doğru sonuçların listelendiğini doğrula.
- Var olmayan bir kelime ile arama yapıldığında “Not bulunamadı” mesajının gösterildiğini doğrula.

---

## TS-08: Geçmiş (History) Ekranı

- Son güncellenen notların listelendiğini doğrula.
- Hiç not yokken geçmiş ekranının doğru mesajı gösterdiğini doğrula.
- Notların güncellenme zamanına göre doğru sıralandığını doğrula.

---

## TS-09: Ayarlar Ekranı Fonksiyonları

- Ayarlar ekranının sorunsuz açıldığını doğrula.
- Dil seçeneğinin değiştirilebildiğini doğrula.
- Tema ayarının (açık/koyu/otomatik) çalıştığını doğrula.
- Bildirim ayarlarının açılıp kapatılabildiğini doğrula.
- Biyometrik doğrulama ayarının açılıp kapatılabildiğini doğrula.
- “Uyanık Tut” seçeneğinin çalıştığını doğrula.
- Uygulama sürüm bilgisinin görüntülendiğini doğrula.
- “Verileri Başlat” işleminin kullanıcıyı bilgilendirerek çalıştığını doğrula.

---

## TS-10: Kullanılabilirlik (Usability) ve UX Kontrolleri

- Metinlerin okunabilir olduğunu doğrula.
- Buton boyutlarının ve dokunma alanlarının yeterli olduğunu doğrula.
- İkon ve metinlerin tutarlı kullanıldığını doğrula.
- Kritik işlemler öncesinde kullanıcıya yeterli geri bildirim verildiğini doğrula.

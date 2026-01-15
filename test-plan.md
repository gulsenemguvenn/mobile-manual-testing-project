# Mobil Uygulama Manuel Test Planı

## 1. Amaç (Test Objective)
Bu test planının amacı, Android tabanlı bir not alma uygulamasının
manuel test yöntemleri kullanılarak fonksiyonel doğruluğunu,
kullanılabilirliğini ve temel kullanıcı akışlarını doğrulamaktır.

---

## 2. Kapsam (Scope)

### Test Kapsamına Dahil Olanlar
- Uygulama açılış ve ana ekran kontrolleri
- Not oluşturma, görüntüleme ve silme işlemleri
- Arama fonksiyonu
- Sıralama (Manual / Alfabetik)
- Sekme (Tab) yönetimi
- Ayarlar ekranı kontrolleri
- Negatif senaryolar (boş not vb.)
- Edge-case senaryolar (uzun metin, özel karakterler)

### Test Kapsamı Dışında Kalanlar
- Otomasyon testleri
- Performans testleri
- Güvenlik testleri
- Backend / API testleri

---

## 3. Test Yaklaşımı (Test Approach)
Testler manuel olarak gerçekleştirilmiştir.
Test senaryoları ve test case’ler önceden hazırlanmış,
test execution sırasında Actual Result ve Status alanları doldurulmuştur.
Test verileri Test_Data dokümanı üzerinden yönetilmiştir.

---

## 4. Test Ortamı (Test Environment)
- Platform: Android
- Cihaz: Fiziksel Android cihaz
- OS Versiyonu: Android 13
- Test Türü: Manuel Mobil Test

---

## 5. Test Türleri
- Fonksiyonel Test
- Negatif Test
- Kullanılabilirlik (Usability) Testi
- Edge-case Testleri

---

## 6. Giriş ve Çıkış Kriterleri (Entry / Exit Criteria)

### Giriş Kriterleri
- Uygulama cihaza başarıyla kurulmuş olmalıdır
- Test senaryoları ve test case’ler hazırlanmış olmalıdır

### Çıkış Kriterleri
- Tüm test case’ler çalıştırılmış olmalıdır
- Kritik veya yüksek öncelikli bug bulunmamalıdır
- Test sonuçları raporlanmış olmalıdır

---

## 7. Riskler ve Varsayımlar
- Testler tek cihaz üzerinde gerçekleştirilmiştir
- Farklı cihaz ve OS versiyonlarında farklı davranışlar gözlemlenebilir

---

## 8. Test Çıktıları (Test Deliverables)
- Test Plan dokümanı
- Test Senaryoları
- Test Case’ler
- Test Data
- Test Execution sonuçları
- Bug / İyileştirme kayıtları

---

## 9. Onay
Bu test planı, manuel mobil test sürecini tanımlamak amacıyla
QA çalışması kapsamında hazırlanmıştır.

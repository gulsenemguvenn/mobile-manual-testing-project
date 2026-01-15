# 📱 Mobil Manuel Test Projesi

Bu repository, Android tabanlı bir not alma uygulaması üzerinde gerçekleştirilen
uçtan uca **manuel mobil test çalışmasını** içermektedir.

Proje; test planlamasından test yürütmeye, test verisi yönetiminden hata raporlamaya
kadar manuel test sürecinin tüm adımlarını kapsamaktadır.

---

##  Proje Kapsamı

Bu projede aşağıdaki manuel test aktiviteleri gerçekleştirilmiştir:

- Test planı hazırlanması  
- Test senaryolarının oluşturulması  
- Detaylı test case yazımı  
- Test verilerinin tanımlanması  
- Manuel testlerin yürütülmesi  
- Hata ve iyileştirme raporlaması  

Amaç, manuel mobil test süreçlerine hakimiyeti ve dokümantasyon yetkinliğini
göstermektir.

---

##  Test Edilen Uygulama (AUT)

- **Platform:** Android  
- **Uygulama Türü:** Not alma uygulaması  
- **Uygulama Adı:** Simple Notes  

---

## 📂 Repository Yapısı

mobile-manual-testing-project/
│
├── README.md                  # Proje açıklaması ve özet
├── test-plan.md               # Test stratejisi ve kapsam
├── test-scenarios.md          # Yüksek seviyeli test senaryoları
├── device-info.md             # Cihaz ve test ortamı bilgileri
│
├── test-artifacts/
│   ├── Mobile_Manual_Testing.xlsx   # Tüm test çıktılarının Excel versiyonu
│   ├── test-cases.md                # Test case’lerin Markdown hali
│   └── test-data.md                 # Test data’ların Markdown hali
│
├── bug-reports/
│   ├── BR-001-no-defect-found.md     # Bug bulunmaması durumu
│   └── BR-002-ux-improvement.md      # UX iyileştirme önerisi


---

##  Test Artefaktları

###  Test Senaryoları
Uygulamanın temel fonksiyonlarını kapsayan yüksek seviyeli test senaryoları
aşağıdaki dosyada yer almaktadır:

- `test-scenarios.md`

---

###  Test Caseler
Tüm detaylı test caseler Excel formatında hazırlanmıştır ve aşağıdaki alanları içerir:

- Ön koşullar (Preconditions)  
- Test adımları (Test Steps)  
- Test verisi referansları  
- Beklenen sonuçlar  
- Gerçekleşen sonuçlar  
- Test durumu ve öncelik  

📎 Dosya:  
`test-artifacts/Mobile_Manual_Testing.xlsx`  
(Sayfa: **Test_Cases**)

---

###  Test Verileri
Test senaryolarında kullanılan tüm veriler ayrı bir test data tablosu olarak
tanımlanmıştır. Bu yapı, testlerin tekrar edilebilirliğini sağlamaktadır.

Örnek test verileri:
- Geçerli / geçersiz not içerikleri  
- Arama için uygun / uygun olmayan ifadeler  
- Sekme isimleri  
- Alfabetik sıralama verileri  

📎 Dosya:  
`test-artifacts/Mobile_Manual_Testing.xlsx`  
(Sayfa: **Test_Data**)

---

##  Test Çalıştırma Özeti

| Metrik | Değer |
|------|------|
| Toplam Test Case | 14 |
| Çalıştırılan Test Case | 14 |
| Başarılı (Pass) | 14 |
| Başarısız (Fail) | 0 |
| Bloklu (Blocked) | 0 |

Tanımlanan tüm test caseler başarıyla çalıştırılmıştır.  
Test edilen kapsam dahilinde **fonksiyonel bir hata tespit edilmemiştir**.

---

##  Hata / İyileştirme Özeti

Test süreci boyunca kritik veya yüksek öncelikli bir fonksiyonel hata
bulunmamıştır. Ancak kullanıcı deneyimi açısından bir iyileştirme alanı
tespit edilmiştir.

###  Kayıt Altına Alınan Bulgular

- **BR-001 – Hata Bulunamadı (No Defect Found)**
  - Test edilen kapsam dahilinde fonksiyonel bir hata tespit edilmemiştir.
  - Uygulamanın stabil çalıştığı gözlemlenmiştir.

- **BR-002 – UX İyileştirme Önerisi**
  - “Hepsi” sekmesinde sıralama seçeneğinin bulunmaması,
    kullanıcı deneyimi açısından iyileştirme alanı olarak değerlendirilmiştir.
  - Bu durum fonksiyonel bir hata değil, UX geliştirme önerisi olarak raporlanmıştır.

📎 Detaylar:
- Excel: `test-artifacts/Mobile_Manual_Testing.xlsx` (Sayfa: **Bug_Reports**)  
- Markdown raporu: `bug-reports/BR-002-ux-improvement.md`  
- Ekran görüntüsü: `screenshots/ux-sorting-hepsi.png`

---

##  Test Ortamı

Testlerin gerçekleştirildiği cihaz ve ortam bilgileri aşağıdaki dosyada yer almaktadır:

- `device-info.md`

---

##  Sonuç

Bu proje, manuel mobil test süreçlerinin nasıl yürütüldüğünü
gösteren bir çalışmadır.

Test planlama, senaryo oluşturma, test yürütme ve raporlama adımları
profesyonel bir şekilde ele alınmıştır.



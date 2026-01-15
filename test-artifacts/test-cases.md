#  Test Caseler – Simple Notes (Android)

Bu doküman, Simple Notes Android uygulaması için hazırlanan
tüm manuel test caseleri içermektedir.

---

## TC-001 – Uygulamanın Başarılı Açılması
- **Test Senaryosu:** TS-01
- **Ön Koşul:** Uygulama cihazda yüklü olmalı
- **Adımlar:**
  1. Uygulamaya dokun
  2. Açılış ekranını gözlemle
- **Beklenen Sonuç:** Ana sayfa hatasız şekilde açılır
- **Durum:** Passed
- **Öncelik:** High

---

## TC-002 – Yeni Not Oluşturulabilmeli
- **Test Senaryosu:** TS-02
- **Ön Koşul:** Uygulama açık olmalı
- **Adımlar:**
  1. “+” butonuna dokun
  2. Not oluşturma ekranını gözlemle
- **Beklenen Sonuç:** Yeni not ekranı açılır
- **Durum:** Passed
- **Öncelik:** High

---

## TC-003 – Not İçeriği Girilerek Kaydedilmeli
- **Test Senaryosu:** TS-02
- **Test Data:** DATA-001
- **Ön Koşul:** Yeni not ekranı açık olmalı
- **Adımlar:**
  1. Metin alanına not yaz
  2. Geri tuşuna bas
- **Beklenen Sonuç:** Not kaydedilir ve listede görüntülenir
- **Durum:** Passed
- **Öncelik:** High

---

## TC-004 – Boş Not Kaydedilmemeli
- **Test Senaryosu:** TS-10
- **Test Data:** DATA-002
- **Ön Koşul:** Yeni not ekranı açık olmalı
- **Adımlar:**
  1. Metin alanını boş bırak
  2. Geri tuşuna bas
- **Beklenen Sonuç:** Boş not kaydedilmez
- **Durum:** Passed
- **Öncelik:** Medium

---

## TC-005 – Arama Alanı Görünür Olmalı
- **Test Senaryosu:** TS-07
- **Ön Koşul:** Uygulama açık olmalı
- **Adımlar:**
  1. “Hepsi” sekmesine git
  2. Arama alanını gözlemle
- **Beklenen Sonuç:** Arama alanı görünür ve aktif olmalı
- **Durum:** Passed
- **Öncelik:** Medium

---

## TC-006 – Var Olan Not Aranarak Bulunabilmeli
- **Test Senaryosu:** TS-07
- **Test Data:** DATA-003
- **Ön Koşul:** Listede en az 2 not bulunmalı
- **Adımlar:**
  1. Arama alanına metin gir
  2. Sonuç listesini gözlemle
- **Beklenen Sonuç:** İlgili notlar listelenir
- **Durum:** Passed
- **Öncelik:** High

---

## TC-007 – Sonuç Yoksa Bilgilendirici Mesaj Gösterilmeli
- **Test Senaryosu:** TS-07
- **Test Data:** DATA-004
- **Ön Koşul:** Aranan ifadeyi içeren not olmamalı
- **Adımlar:**
  1. Arama alanına geçersiz ifade gir
- **Beklenen Sonuç:** “Sonuç bulunamadı” mesajı gösterilir
- **Durum:** Passed
- **Öncelik:** Medium

---

## TC-008 – Sıralama Menüsü Açılmalı
- **Test Senaryosu:** TS-06
- **Ön Koşul:** Uygulama açık olmalı
- **Adımlar:**
  1. Sıralama ikonuna dokun
- **Beklenen Sonuç:** Manuel ve Alfabetik seçenekleri görüntülenir
- **Durum:** Passed
- **Öncelik:** High

---

## TC-009 – Alfabetik Sıralama Çalışmalı
- **Test Senaryosu:** TS-06
- **Test Data:** DATA-007
- **Ön Koşul:** En az 3 not bulunmalı
- **Adımlar:**
  1. Alfabetik sıralamayı seç
- **Beklenen Sonuç:** Notlar A–Z sıralanır
- **Durum:** Passed
- **Öncelik:** High

---

## TC-010 – Manuel Sıralama Modu Aktif Olmalı
- **Test Senaryosu:** TS-06
- **Ön Koşul:** En az 2 not bulunmalı
- **Adımlar:**
  1. Manuel sıralamayı seç
- **Beklenen Sonuç:** Notlar sürüklenebilir hale gelir
- **Durum:** Passed
- **Öncelik:** Medium

---

## TC-011 – Yeni Sekme Eklenebilmeli
- **Test Senaryosu:** TS-05
- **Test Data:** DATA-005
- **Ön Koşul:** Uygulama açık olmalı
- **Adımlar:**
  1. Yeni sekme ekle
- **Beklenen Sonuç:** Sekme oluşturulur ve listede görünür
- **Durum:** Passed
- **Öncelik:** High

---

## TC-012 – Sekme Adı Değiştirilebilmeli
- **Test Senaryosu:** TS-05
- **Test Data:** DATA-006
- **Ön Koşul:** En az 1 sekme bulunmalı
- **Adımlar:**
  1. Sekme adını düzenle
- **Beklenen Sonuç:** Sekme adı güncellenir
- **Durum:** Passed
- **Öncelik:** Medium

---

## TC-013 – Ayarlarda Dil ve Tema Görüntülenmeli
- **Test Senaryosu:** TS-08
- **Ön Koşul:** Uygulama açık olmalı
- **Adımlar:**
  1. Ayarlara gir
- **Beklenen Sonuç:** Dil ve tema seçenekleri görüntülenir
- **Durum:** Passed
- **Öncelik:** Low

---

## TC-014 – Verileri Başlat İşlemi Onay Gerektirmeli
- **Test Senaryosu:** TS-08
- **Ön Koşul:** Ayarlar ekranı açık olmalı
- **Adımlar:**
  1. “Verileri başlat” butonuna dokun
- **Beklenen Sonuç:** Onay / iptal mesajı gösterilir
- **Durum:** Passed
- **Öncelik:** High

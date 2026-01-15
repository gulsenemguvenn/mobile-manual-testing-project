#  Test Data – Simple Notes (Android)

Bu doküman, manuel testlerde kullanılan tüm test verilerini içermektedir.

| Data ID  | Açıklama                          | Input     | Beklenen Çıktı |
|---------|-----------------------------------|-----------|----------------|
| DATA-001 | Geçerli not başlığı / içeriği     | Test notu | Not kaydedilir ve listede görünür |
| DATA-002 | Boş not içeriği                   | (boş)     | Not kaydedilmez, ana ekrana dönülür |
| DATA-003 | Arama için mevcut not içeriği     | Test      | “Test” içeren notlar listelenir |
| DATA-004 | Arama için geçersiz ifade         | xyz123    | “Sonuç bulunamadı” mesajı gösterilir |
| DATA-005 | Sekme adı örneği                  | Work      | Yeni sekme oluşturulur |
| DATA-006 | Sekme adı güncelleme              | Study     | Sekme adı güncellenir |
| DATA-007 | Alfabetik sıralama için notlar    | A, B, C   | Notlar A–Z sıralanır |

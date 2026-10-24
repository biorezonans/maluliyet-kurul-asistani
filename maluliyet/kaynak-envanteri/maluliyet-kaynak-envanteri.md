# Maluliyet kaynak envanteri — PDF külliyatı

**Envanter tarihi:** 24 Ekim 2026  
**Kaynak klasörü:** `C:\Users\TAMER\OneDrive\Belgeler\maluliyet`  
**Kapsam:** Klasördeki 6 PDF, toplam 465 sayfa. Her PDF için sayfa sıralı metin dökümü `maluliyet-kaynak-metni/` altındadır.  
**Amaç:** Kural çıkarımı ve mevzuata dayalı değerlendirmeler için izlenebilir kaynak kayıtları oluşturmak. Bu envanter hukuki yürürlük/doğruluk onayı veya otomatik karar kuralı değildir.

## Kaynak kayıtları

| ID | Kaynak dosya | Belge başlığı / ilk sayfadan tanımlama | Sayfa | Metin dökümü | İçerik edinme | SHA-256 (kaynak PDF) |
|---|---|---|---:|---|---|---|
| PDF-001 | `5510 sayılı SSK kanunu.pdf` | Sosyal Sigortalar ve Genel Sağlık Sigortası Kanunu, Kanun No. 5510; kabul 31.05.2006; Resmî Gazete 16.06.2006, Sayı 26200 | 203 | [Tam sayfa dökümü](maluliyet-kaynak-metni/5510%20say%C4%B1l%C4%B1%20SSK%20kanunu.txt) | PDF metin katmanı; her sayfada metin bulundu | `264e27c0b17f1cc1c975bfe50bbd174f12c3251ff161db116cd58d755b0be29f` |
| PDF-002 | `maluliyet_islemleri_ek_1.pdf` | “Ek-1 Hastalık Listesi”; çalışma gücü kaybına neden olan hastalık grupları ve düzey koşulları | 40 | [Tam sayfa dökümü](maluliyet-kaynak-metni/maluliyet_islemleri_ek_1.txt) | PDF metin katmanı; her sayfada metin bulundu | `0525b9e37abd05878aca26565b34b9da47c3eb40fc9e71c9d29b9ef307da9f6d` |
| PDF-003 | `saglik-raporlari-yonetmeligi-19052026pdf.pdf` | Sağlık Raporları Yönetmeliği; 19.05.2026 Resmî Gazete, Sayı 33258; Karar No. 11361; karar tarihi 18.05.2026 | 35 | [OCR sayfa dökümü](maluliyet-kaynak-metni/saglik-raporlari-yonetmeligi-19052026pdf.txt) | Görüntü tabanlı PDF; Türkçe OCR; ortalama sayfa güveni %94,9; en düşük sayfa güveni %94,0 | `05c15cc61ac3e1f234be459fe8616c2b4305d2374ecb8dceef19a9180a2e6e55` |
| PDF-004 | `Sosyal Sigorta İşlemleri Yönetmeliği.pdf` | Sosyal Sigorta İşlemleri Yönetmeliği | 102 | [Tam sayfa dökümü](maluliyet-kaynak-metni/Sosyal%20Sigorta%20%C4%B0%C5%9Flemleri%20Y%C3%B6netmeli%C4%9Fi.txt) | PDF metin katmanı; her sayfada metin bulundu | `6af724db4c1259d38a089cd769a9c14fded2dd9add268a1165eb72bdaeee35a8` |
| PDF-005 | `yonetmelik_eki.pdf` | “Ek Hastalık Listesi”; 5510 uygulamasına ilişkin/aynı liste olma ihtimali var; kaynağa bağlayan kapak ve resmî sürüm bilgisi ayrıca doğrulanmalı | 40 | [OCR sayfa dökümü](maluliyet-kaynak-metni/yonetmelik_eki.txt) | Görüntü tabanlı PDF; Türkçe OCR; ortalama sayfa güveni %88,5; en düşük sayfa güveni %80,0 | `73039dd4def6d2804ef647f2063a344a0a7b6086b08485f62ebe527c6d2adff1` |
| PDF-006 | `yönetmelik.pdf` | Maluliyet ve Çalışma Gücü Kaybı Tespiti İşlemleri Yönetmeliği; 28.09.2021 Resmî Gazete, Sayı 31612 | 45 | [Tam sayfa dökümü](maluliyet-kaynak-metni/yönetmelik.txt) | PDF metin katmanı; her sayfada metin bulundu | `0ab93ed4fd6ef443bdf8baaafa12102d6bf0514086cc19ea28065aa7d0cf0bc3` |

## Okunabilirlik ve eksiksizlik kontrolü

- Altı PDF’nin tamamı yerel kaynak klasöründen açıldı; PDF başlıkları, sayfa sayıları, dosya boyutları ve kaynak dosyaların SHA-256 özetleri kaydedildi.
- PDF-001, PDF-002, PDF-004 ve PDF-006’dan sayfa başına metin çıkarıldı. Bu dört belgede metin içermeyen sayfa saptanmadı.
- PDF-003 ve PDF-005 görüntü tabanlı olduğundan 75 sayfanın tamamı 180 DPI görüntüye dönüştürülerek Türkçe OCR’dan geçirildi. Her sayfada OCR metni oluştu. Güven puanı OCR motorunun tahminidir; doğruluk yüzdesi veya insan denetimi anlamına gelmez.
- Her döküm sayfa sınırlarıyla tutulmuştur. OCR dökümlerinde sayfa başlığında OCR güven puanı da bulunur. Bu metin dosyaları aranabilir çalışma kopyalarıdır; imzalı/doğrulanmış resmi nüsha yerine geçmez.
- Dört metin katmanlı PDF’de kelimeler çıkarılmıştır; PDF’den metin alma işlemi başlık, altbilgi, sütun ve tablo görsel yerleşimini her zaman aslı gibi korumaz. OCR’da özellikle madde numarası, tablo hücresi, noktalama, Türkçe karakter, dipnot ve sütun sırası için kaynak sayfa görüntüsüyle karşılaştırma gerekir.

## Kaynakları kullanırken dikkat edilecekler

1. `5510 sayılı SSK kanunu.pdf` başlığı yanıltıcıdır: belgenin kendi başlığı 5510 sayılı **Sosyal Sigortalar ve Genel Sağlık Sigortası Kanunu**dur. Dosyanın 2022’de üretildiği PDF metaverisinde görünür; bu, güncel konsolide kanun olduğunu kanıtlamaz.
2. 2021 Yönetmeliği PDF’si, aynı adlı yönetmeliğin 28.09.2021 tarihli Resmî Gazete metnini içeriyor. Daha sonraki değişikliklerin tamamı bu nüshada bulunmayabilir.
3. 2026 tarihli Sağlık Raporları Yönetmeliği dosyası ilk sayfada 19.05.2026 tarihini, 33258 sayısını ve 11361 karar numarasını gösteriyor. Kural kullanımından önce resmî yayımla ve yürürlük/değişiklik kayıtlarıyla teyit edilmelidir.
4. İki Hastalık Listesi dosyası benzer başlık ve yapıda olsa da kaynak/yayımlanma ilişkisi, sürüm farkı ve hangi nüshanın normatif olduğu doğrulanmadan birleştirilmemelidir. PDF-005 OCR ile okunduğu için birincil kural kaynağı olarak tek başına kullanıma uygun kabul edilmemiştir.
5. Bu dosyaların hiçbiri sırf klasörde bulunuyor diye güncel/yürürlükte veya hukuken bağlayıcı kabul edilmez. Her uygulanabilir kural için kaynak ID, madde/ek/sayfa, birebir alıntı, yürürlük durumu, koşullar, istisnalar ve uzman doğrulaması kaydedilmelidir.

## Metin döküm dosyaları

`maluliyet-kaynak-metni/` içindeki altı UTF-8 `.txt` dosyası, her kaynak PDF’nin sayfa sıralı çıkarılmış/OCR edilmiş metnini içerir. Dosyalar üretim sırasında kaynak PDF’ye göre sıralanmış, sayfa ayraçları eklenmiş ve kaynak SHA-256 değerleri yukarıya yazılmıştır. İçerik bir yazılım kural motoruna aktarılmadan önce OCR’lı sayfaların orijinal görüntüden gözden geçirilmesi, özellikle klinik eşik ve madde numaralarının iki kişi tarafından doğrulanması gerekir.

## Bu teslimde yapılmayan doğrulamalar

- Tüm hükümlerin güncel mevzuat ve Resmî Gazete arşiviyle karşılaştırılması.
- Eklerin hangi yönetmelik sürümüne ait olduğunun kesinleştirilmesi.
- OCR metninin her karakterinin iki insan tarafından kaynak görüntüye karşı düzeltilmesi.
- Klinik ölçütlerin ya da maluliyet sonucuna götüren karar kurallarının uzmanlarca onaylanması.

Dolayısıyla **kaynaklara erişim ve döküm alma tamamlandı; “kelimesi kelimesine insan denetimli doğruluk” ve hukuki içerik doğrulaması tamamlandı denemez.**

## Makinece okunabilir kayıt

[CSV kaynak kaydı](maluliyet-kaynak-kaydi.csv) kimlik, başlık, tarih notu, sayfa sayısı, edinme yöntemi, OCR puanı, kaynak özeti ve döküm yolunu içerir.


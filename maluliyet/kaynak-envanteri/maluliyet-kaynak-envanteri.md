# Maluliyet kaynak envanteri — PDF külliyatı

**Envanter tarihi:** 24 Ekim 2026  
**Kaynak klasörü:** `C:\Users\TAMER\OneDrive\Belgeler\maluliyet`  
**Kapsam:** `maluliyet` klasöründe 5 etkin PDF, toplam 425 sayfa vardır. İptal edilen eski ek yalnızca önceki envanterden kalan tarihsel kayıt olarak belirtilir; PDF ve OCR dökümü artık GitHub’da bulunmuyor. Beş etkin PDF’nin metin dökümleri bu envanterle aynı `kaynak-envanteri` klasöründedir.  
**Amaç:** Kural çıkarımı ve mevzuata dayalı değerlendirmeler için izlenebilir kaynak kayıtları oluşturmak. Bu envanter hukuki yürürlük/doğruluk onayı veya otomatik karar kuralı değildir.

## Kaynak kayıtları

| ID | Kaynak dosya | Belge başlığı / ilk sayfadan tanımlama | Sayfa | Metin dökümü | İçerik edinme | SHA-256 (kaynak PDF) |
|---|---|---|---:|---|---|---|
| PDF-001 | `5510 sayılı SSK kanunu.pdf` | Sosyal Sigortalar ve Genel Sağlık Sigortası Kanunu, Kanun No. 5510; kabul 31.05.2006; Resmî Gazete 16.06.2006, Sayı 26200 | 203 | [Tam sayfa dökümü](5510%20say%C4%B1l%C4%B1%20SSK%20kanunu.txt) | PDF metin katmanı; her sayfada metin bulundu | `264e27c0b17f1cc1c975bfe50bbd174f12c3251ff161db116cd58d755b0be29f` |
| PDF-002 | `maluliyet_islemleri_ek_1.pdf` | “Ek-1 Hastalık Listesi”; çalışma gücü kaybına neden olan hastalık grupları ve düzey koşulları | 40 | [Tam sayfa dökümü](maluliyet_islemleri_ek_1.txt) | PDF metin katmanı; her sayfada metin bulundu | `0525b9e37abd05878aca26565b34b9da47c3eb40fc9e71c9d29b9ef307da9f6d` |
| PDF-003 | `saglik-raporlari-yonetmeligi-19052026pdf.pdf` | Sağlık Raporları Yönetmeliği; 19.05.2026 Resmî Gazete, Sayı 33258; Karar No. 11361; karar tarihi 18.05.2026 | 35 | [OCR sayfa dökümü](saglik-raporlari-yonetmeligi-19052026pdf.txt) | Görüntü tabanlı PDF; Türkçe OCR; ortalama sayfa güveni %94,9; en düşük sayfa güveni %94,0 | `05c15cc61ac3e1f234be459fe8616c2b4305d2374ecb8dceef19a9180a2e6e55` |
| PDF-004 | `Sosyal Sigorta İşlemleri Yönetmeliği.pdf` | Sosyal Sigorta İşlemleri Yönetmeliği | 102 | [Tam sayfa dökümü](Sosyal%20Sigorta%20%C4%B0%C5%9Flemleri%20Y%C3%B6netmeli%C4%9Fi.txt) | PDF metin katmanı; her sayfada metin bulundu | `6af724db4c1259d38a089cd769a9c14fded2dd9add268a1165eb72bdaeee35a8` |
| PDF-005 | `yonetmelik_eki.pdf` (iptal; GitHub’dan kaldırıldı) | **İPTAL — kural kaynağı olarak kullanılmayacak.** Kullanıcının teyidine göre esas Hastalık Listesi eki PDF-002’dir. Bu tarihsel kaydın PDF’si ve OCR dökümü artık depoda yoktur. | 40 (önceki kopya) | Depoda yok | Önceki envanterde görüntü tabanlı OCR kaydı; etkin kural kaynağı değil | `73039dd4def6d2804ef647f2063a344a0a7b6086b08485f62ebe527c6d2adff1` |
| PDF-006 | `yönetmelik.pdf` | Maluliyet ve Çalışma Gücü Kaybı Tespiti İşlemleri Yönetmeliği; 28.09.2021 Resmî Gazete, Sayı 31612 | 45 | [Tam sayfa dökümü](yönetmelik.txt) | PDF metin katmanı; her sayfada metin bulundu | `0ab93ed4fd6ef443bdf8baaafa12102d6bf0514086cc19ea28065aa7d0cf0bc3` |

## Okunabilirlik ve eksiksizlik kontrolü

- Envanter ilk oluşturulurken altı PDF açılmış ve sayfa sayıları/hash değerleri kaydedilmişti. Kullanıcının iptal ettiği PDF-005 sonradan GitHub’dan kaldırıldı; mevcut depoda 5 etkin PDF (425 sayfa) ve bunlara ait 5 metin dökümü bulunuyor.
- PDF-001, PDF-002, PDF-004 ve PDF-006’dan sayfa başına metin çıkarıldı. Bu dört belgede metin içermeyen sayfa saptanmadı.
- PDF-003 görüntü tabanlıdır; 35 sayfanın tamamı 180 DPI Türkçe OCR’dan geçirilmiştir. Kullanıcı ilgili maddeleri, tabloları, eşikleri ve istisnaları sayfa görüntülerinden kontrol etmiştir. PDF-005’in önceki OCR kaydı iptal edilen kaynakla birlikte etkin kullanım dışındadır ve dökümü GitHub’da tutulmuyor.
- Her döküm sayfa sınırlarıyla tutulmuştur. OCR dökümlerinde sayfa başlığında OCR güven puanı da bulunur. Bu metin dosyaları aranabilir çalışma kopyalarıdır; imzalı/doğrulanmış resmi nüsha yerine geçmez.
- Dört metin katmanlı PDF’de kelimeler çıkarılmıştır; PDF’den metin alma işlemi başlık, altbilgi, sütun ve tablo görsel yerleşimini her zaman aslı gibi korumaz. OCR’da özellikle madde numarası, tablo hücresi, noktalama, Türkçe karakter, dipnot ve sütun sırası için kaynak sayfa görüntüsüyle karşılaştırma gerekir.

## Kullanıcı tarafından teyit edilen kaynak durumu (24 Ekim 2026)

- PDF-001 (5510 sayılı Kanun) ve PDF-006 (2021 Yönetmeliği) güncel konsolide metin olarak kullanıcı tarafından doğrulanmıştır; kural çıkarımında etkin kaynak kabul edilir.
- PDF-003 (19.05.2026 Sağlık Raporları Yönetmeliği) içindeki ilgili madde numaraları, tablolar, eşikler ve istisnalar kullanıcı tarafından sayfa görüntülerinden kontrol edilmiştir. Metin dökümü aranabilir yardımcı kopyadır; ihtilaf halinde kaynak PDF görüntüsü esas alınır.
- PDF-002 (`maluliyet_islemleri_ek_1.pdf`) okunabilir ve esas Hastalık Listesi eki olarak kullanıcı tarafından teyit edilmiştir; etkin kaynak kabul edilir.
- PDF-005 (`yonetmelik_eki.pdf`) kullanıcı tarafından iptal edilip GitHub’dan kaldırılmıştır. Yalnızca tarihsel envanter kaydı ve daha önce hesaplanmış SHA-256 değeri tutulur; PDF/OCR metni depoda yoktur. Kural çıkarımında kullanılmamalı ve PDF-002 ile birleştirilmemelidir.
- PDF-004 Sosyal Sigorta İşlemleri Yönetmeliği, ilgili olduğu kurallar için yardımcı kaynaktır; bu sohbette güncelliği ayrıca teyit edilmemiştir.
- Bu doğrulama durumları kullanıcı beyanına dayanır; metin dökümleri dosya metinlerini bulmayı kolaylaştırır, resmî nüshanın yerine geçmez.
- Her kural kaydında kaynak ID, madde/ek/sayfa, kapsam, koşullar, istisnalar, otomatik kontrol verisi ve doğrulama durumu saklanmalıdır.

## Metin döküm dosyaları

`` içindeki altı UTF-8 `.txt` dosyası, her kaynak PDF’nin sayfa sıralı çıkarılmış/OCR edilmiş metnini içerir. Dosyalar üretim sırasında kaynak PDF’ye göre sıralanmış, sayfa ayraçları eklenmiş ve kaynak SHA-256 değerleri yukarıya yazılmıştır. İçerik bir yazılım kural motoruna aktarılmadan önce OCR’lı sayfaların orijinal görüntüden gözden geçirilmesi, özellikle klinik eşik ve madde numaralarının iki kişi tarafından doğrulanması gerekir.

## Kural tablosuna geçmeden önce kalan sınırlar

- PDF-004’ün güncel sürümünün kullanılıp kullanılmayacağı, ona dayanan bir kural çıkarılacağı zaman ayrıca teyit edilmelidir.
- OCR metni aranabilir yardımcı dökümdür. Hukuki alıntı ve kritik eşikler kaynak PDF görüntüsüyle birlikte doğrulanmalıdır.
- Bu envanter hukuki yorum veya klinik kural onayı değildir. Türetilen her kural ayrıca uzman/kurul incelemesine sunulmalıdır.

## Makinece okunabilir kayıt

[CSV kaynak kaydı](maluliyet-kaynak-kaydi.csv) kimlik, başlık, tarih notu, sayfa sayısı, edinme yöntemi, OCR puanı, kaynak özeti ve döküm yolunu içerir.


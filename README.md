# Maluliyet ve Çalışma Gücü Kaybı Kurul Kararları Asistanı — İlk Prototip

## Bu sürümde neler var?
- Mobil uyumlu arayüz
- Android tarayıcısında arka kamera erişimi (uygun güvenli bağlantıda)
- Kameradan birden fazla belge görüntüsü alma ve görüntüleri kaldırma
- PDF ve görüntü dosyası seçme (dosyalar sunucuya gönderilmez; yalnızca tarayıcı ekranında listelenir)
- Uydurma örnek dosya verileri
- Düzenlenebilir karar taslağı
- Metni kopyalama
- Word uyumlu `.doc` indirme
- Yazdırma / PDF olarak kaydetme

## Önemli sınırlar
- OCR (belgeden otomatik metin okuma) henüz yok.
- Otomatik mevzuat değerlendirmesi veya kurul kararı verme özelliği yok.
- Veritabanı, kullanıcı girişi, bulut kaydı ve yetkilendirme yok.
- Gerçek hasta/kurum verisi girmeyin. Prototip yalnızca uydurma verilerle test edilmelidir.
- Kamera erişimi tarayıcıda genellikle HTTPS veya localhost gerektirir. Dosyayı telefonda doğrudan açmak kamera erişimini engelleyebilir.
- Kurumsal kullanımdan önce kurumun bilgi güvenliği, kişisel veri koruma, erişim kontrolü ve denetim kaydı şartları karşılanmalıdır.

## Nasıl deneyebilirsiniz?
1. `index.html` dosyasını bilgisayarda Chrome veya Edge ile açın.
2. `Örnek verileri yükle` düğmesine basın.
3. Karar metnini düzenleyin.
4. `Word uyumlu indir` veya `Yazdır / PDF kaydet` düğmesini deneyin.
5. Kamera özelliği için sayfayı HTTPS üzerinden güvenli bir web adresinde açmak gerekir. Bu dosyayı doğrudan telefon dosya yöneticisinden açmak kamerayı çalıştırmayabilir.

## Sonraki geliştirme aşamaları
1. PDF sayfa önizlemesi ve OCR
2. OCR sonuçlarını kullanıcıya doğrulatma
3. Resmî mevzuat sürümü ve kaynak bağlantısı alanları
4. Kurul bileşimi kontrol listesi (yürürlük tarihine göre)
5. Güvenli yerel/kurumsal saklama ve yetkilendirme tasarımı
6. Word çıktısının kurumsal şablona uyarlanması

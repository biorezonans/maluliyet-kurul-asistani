# Maluliyet ve Çalışma Gücü Kaybı Kurul Kararları Asistanı — OCR Prototipi

## Bu sürümde
- Android/masaüstü tarayıcıda kamera ile görüntü alma
- Görüntü dosyası ve PDF yükleme
- Tesseract.js ile Türkçe + İngilizce OCR
- PDF sayfalarını görüntüleyip OCR yapma (ilk 20 sayfa)
- OCR metnini düzenleme ve dosya özeti alanına aktarma
- Taslak karar metni oluşturma, kopyalama, Word uyumlu dosya indirme ve yazdırma

## Kullanım
1. `index.html` dosyasını GitHub deposunun ana dizinine yükleyin/var olan dosyanın yerine koyun.
2. GitHub Pages dağıtımının tamamlanmasını bekleyin.
3. HTTPS site adresini Chrome'da açın.
4. Kamera ile fotoğraf çekin veya bir PDF/görüntü dosyası seçin.
5. **Fotoğraf/PDF’yi OCR ile metne dönüştür** düğmesine basın.
6. Tanınan metni asıl belgeyle karşılaştırın, hataları düzeltin ve isterseniz **OCR metnini dosya özetine aktar** düğmesini kullanın.

## Teknik notlar
- OCR, tarayıcıda Tesseract.js kullanılarak çalışır; uygulama belge dosyalarını kendi sunucusuna yüklemez.
- Tesseract.js, PDF.js ve Türkçe/İngilizce dil modeli ilk kullanımda CDN üzerinden indirilir; internet gerekir.
- Büyük PDF'ler telefonda yavaş çalışabilir. Bu sürüm PDF başına en fazla 20 sayfayı OCR eder.
- OCR hatalı/eksik sonuç verebilir; her metin asıl belgeyle karşılaştırılmalıdır.
- Bu prototip mevzuat değerlendirmesi yapmaz ve otomatik tıbbi/idari karar vermez.
- Gerçek hasta verisi veya kurum içi belgeyle kullanmayın. Kurumsal kullanımdan önce bilgi güvenliği, veri koruma, yetkilendirme ve denetim gereksinimleri karşılanmalıdır.

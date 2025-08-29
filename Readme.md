# Araç Hasar Skoru (Vehicle Damage Score)

Bu proje, bir aracın görselindeki hasarları değerlendirip kullanıcılara basit, anlaşılır bir "hasar skoru" sunmayı amaçlayan statik bir web uygulamasıdır. Görsel öğeler ve temel hesaplama mantığı HTML/CSS ve SVG ile sağlanır; kullanıcı arayüzü basit ve hızlıdır.

## Özet

- Amaç: Araç üzerindeki hasarın görsel olarak gösterilmesi ve kısa bir skorlama ile özetlenmesi.
- Hedef kitle: Araç ekspertiz uzmanları, sigorta çalışanları veya araç sahipleri.

## Özellikler

- Hasarlı bölge vurgulama (SVG ile grafiksel gösterim).
- Basit sayısal "hasar skoru" hesaplama — hızlı karşılaştırma ve ön değerlendirme sağlar.
- Tek dosyalık (statik) kurulum: `index.html`, görseller (ör. `car.svg`) ve gerekli kaynaklar.

## Teknoloji

- HTML, CSS, (isteğe bağlı) JavaScript
- Vektörel grafikler için SVG

## Girdi / Çıktı (Kısa Sözleşme)

- Girdi: Kullanıcının seçtiği/işaretlediği araç bölgesi veya sisteme sağlanan görsel bilgiler.
- Çıktı: 0-100 aralığında özetlenen bir "hasar skoru" ve görsel vurgulama.
- Hata durumları: Eksik görsel, desteklenmeyen tarayıcı veya bozuk SVG dosyası; kullanıcıya açıklayıcı uyarı gösterilir.

## Nasıl çalıştırılır

1. Proje statik bir web sayfasıdır; doğrudan `index.html` dosyasını tarayıcıda açabilirsiniz.
2. Yerel bir sunucuda çalıştırmak isterseniz (ör. XAMPP), proje klasörünü `htdocs` altına koymuşsunuz: tarayıcıda `http://localhost/vehicle-damage-score/` adresini açın.

## Önemli dosyalar

- `index.html` — Uygulamanın ana sayfası.
- `car.svg` — Araç grafiği; üzerine hasar bölgesi işaretlemeleri yerleştirilebilir.
- `Readme.md` — Proje açıklaması (bu dosya).

## Varsayımlar

1. Proje statik ve küçük ölçekli; sunucu tarafı işlem gerekmiyor.
2. Hasar skoru basit heuristikler veya ön tanımlı kurallarla hesaplanır (ML yok).
3. Modern tarayıcılar (Chrome, Firefox, Edge, Safari) destekleniyor.

Eğer bu varsayımlardan farklı bir gereksiniminiz varsa (ör. sunucu tarafı analiz, ML modeli, API entegrasyonu), bunu belirtin; gerekli tasarım değişikliklerini yaparım.

## Geliştirme ve İleri Adımlar

- Hasar tespiti için görüntü işleme veya makine öğrenmesi entegrasyonu.
- İnteraktif araç: kullanıcıların bölge seçimi, açıklama ekleme ve çoklu fotoğraf desteği.
- Testler: küçük birim testleri ve tarayıcı uyumluluk kontrolleri.


# Smart Headline Pro

<p align="center">
  <img src="https://img.shields.io/github/v/release/AppsTRDesign/Smart-Headline-Pro">
  <img src="https://img.shields.io/github/downloads/AppsTRDesign/Smart-Headline-Pro/total">
  <img src="https://img.shields.io/badge/WordPress-6.0%2B-21759b?logo=wordpress" alt="WordPress 6.0+">
  <img src="https://img.shields.io/badge/PHP-7.4%2B-777bb4?logo=php&amp;logoColor=white" alt="PHP 7.4+">
  <img src="https://img.shields.io/badge/license-GPLv2%2B-16a34a" alt="GPLv2 or later">
</p>

<p align="center">
  <a href="https://wplugins.shop/eklenti/smart-fields-pro.zip"><b>⬇ İndir</b></a> ·
  <a href="README.md">🇬🇧 English</a>
</p>

13 duyarlı tasarım, gelişmiş yazı sorguları, bağlama duyarlı son yazılar, otomatik yerleşim kuralları ve modal tabanlı AJAX yönetim paneli sunan WordPress manşet slider eklentisi.

**Geliştirici:** AppsTRDesign · [wplugins.shop](https://wplugins.shop) · **Sürüm:** 2.4.2

## Özellikler

- 13 tasarım: Tam ekran, Bölünmüş, Klasik, Minimal, Kartlar, Sinematik, Dergi, Akış şeridi, Haber odası, Editoryal, Kategori Grupları, Kategori Slaytı ve Benzer Yazılar. Seçili tasarıma tekrar tıklayarak seçimi kaldırabilirsiniz.
- Son yazılar, seçili çoklu kategoriler/etiketler, arama terimi, içerik ID listesi veya benzer yazılarla sorgu oluşturma.
- Bağlama duyarlı **Son yazılar**: kategori, etiket ve taksonomi arşivlerinde yalnızca o terimin son yazıları, arama sayfalarında yalnızca arama metniyle eşleşen yazılar gösterilir; tekil yazıda geçerli yazı hariç tutulur.
- Kategori Grupları ve Kategori Slaytı için "en fazla kategori sayısı" ayarı yalnızca hiç kategori seçilmediğinde aktiftir; kategori seçildiğinde otomatik pasif olur.
- Kategori Slaytı sekme konumu (sol, üst, sağ): kaynak türü *Kategori seçimi* olduğunda kullanılabilir; tablet ve telefonda sekmeler her zaman üsttedir.
- Gerçek ön yüz koduyla oluşturulan, 13 tasarım için de çalışan gerçekçi canlı önizleme; masaüstü/tablet/mobil genişlikleri ve açık/koyu zemin.
- Yazı/sayfa türü, sonuç adedi ve sıralama ölçütü/yönü seçimi.
- Başlık, kategori, kısa özet, HTML'den arındırılmış içerik, tarih, yazar, yorum sayısı, okuma süresi ve bağlantı bileşenlerini ayrı ayrı yönetme.
- Başlık ve gövde boyutu/rengi; 10 Google Fonts seçeneği ve özel Google Font adı dahil tipografi ayarları; dolu, çerçeveli veya minimal oklar.
- Ana sayfa, tekil içerik, kategori/etiket arşivi ve arama sonuçları için içerikten önce/sonra otomatik yerleşim; iç içe içerik filtresi çağrılarına karşı koruma.
- Tema görünümlerine dayanıklı: grid/liste/mini geçişi olan temalarda ve 765px altında manşet kaybolmaz; tema kapsayıcıyı gizlese bile görünür alana taşınır.
- AJAX ile slider ekleme/düzenleme/silme; düzenleme, onay ve bildirimler modal pencerelerle yönetilir; ayarlar JSON olarak içe/dışa aktarılabilir.
- Gutenberg bloğu, `[smart_headline id="slider-id"]` kısa kodu ve tema dosyaları için PHP fonksiyonu.
- Modüler PHP sınıfları ve eklentiye özel CSS/JavaScript dosyaları.

## Kurulum

1. Eklentiyi kurup etkinleştirin.
2. **Smart Headline Pro** panelinden slider oluşturup kaynak sorgusunu ve bileşenlerini ayarlayın.
3. Kısa kodu kopyalayın, Gutenberg bloğunda sliderı seçin veya otomatik yerleşimi etkinleştirin.

## Kısa kod

```text
[smart_headline id="slider-id"]
```

Tema şablonunda `smart_headline('slider-id')`, HTML çıktısını döndürmek için `smart_headline_render('slider-id')` kullanın.

## Gereksinimler

- WordPress 6.0 veya üzeri
- PHP 7.4 veya üzeri

## Lisans

GPL-2.0-or-later. Lisans bildirimini eklenti paketinde bulabilirsiniz.

# 12'li LED Saat

RTC (gerçek zamanlı saat) modülünden alınan zaman bilgisini 12 ayrı LED üzerinden gösteren gömülü sistem projesi.

> **Durum:** Geliştirme aşamasında

## Proje hakkında

Bu proje; zaman bilgisinin bir RTC modülünden okunması, 12 saatlik formata dönüştürülmesi ve ilgili saati temsil eden LED'in yakılması üzerine kuruludur. Temel amaç, mikrodenetleyici, RTC modülü ve LED çıkışlarını birlikte kullanarak tekrar kurulabilir ve anlaşılır bir elektronik saat geliştirmektir.

## Çalışma mantığı

1. RTC modülünden güncel saat bilgisi okunur.
2. Saat bilgisi 12 saatlik gösterime dönüştürülür.
3. Saati temsil eden LED belirlenir.
4. İlgili LED yakılır ve gösterim düzenli aralıklarla güncellenir.
5. RTC sayesinde elektrik kesintilerinden sonra zaman bilgisi korunur.

## Kullanılan teknolojiler

- Mikrodenetleyici tabanlı gömülü sistem geliştirme
- RTC (gerçek zamanlı saat) modülü
- LED çıkış kontrolü
- C/C++ tabanlı mikrodenetleyici programlama

Kullanılan kart ve RTC modelinin kesin bilgileri proje tamamlandığında bu bölüme eklenecektir.

## Yol haritası

- [ ] Kullanılan bileşenleri ve teknik özelliklerini belgelemek
- [ ] Devre bağlantı şemasını eklemek
- [ ] Mikrodenetleyici kaynak kodunu yayımlamak
- [ ] Kurulum ve yükleme adımlarını hazırlamak
- [ ] Prototip fotoğraflarını eklemek
- [ ] Kısa çalışma videosu hazırlamak
- [ ] Karşılaşılan sorunları ve çözümlerini belgelemek
- [ ] Lisans eklemek

## Planlanan depo yapısı

```text
12li-led-saat/
├── src/          # Mikrodenetleyici kaynak kodu
├── docs/         # Devre şeması ve teknik dokümantasyon
├── images/       # Prototip fotoğrafları
└── README.md      # Proje açıklaması
```

## Geliştirme hedefleri

- Saat bilgisini güvenilir biçimde okumak
- LED gösterimini doğru ve kararlı şekilde güncellemek
- Elektrik kesintilerinden sonra saat bilgisini korumak
- Devreyi başka kullanıcıların da kurabileceği şekilde belgelemek

## Katkı

Proje geliştirme aşamasındadır. Öneriler ve iyileştirmeler GitHub Issues üzerinden paylaşılabilir.

## Lisans

Henüz bir lisans seçilmemiştir. Lisans bilgisi proje tamamlanırken eklenecektir.

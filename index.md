---
title: TRIARC Gizlilik Politikası (sürüm 0.3.2, Ekim 2026)
---

# TRIARC Gizlilik Politikası (sürüm 0.3.2, Ekim 2026)


TRIARC, Winter Arc kişisel takip uygulamasıdır. Verilerin yalnız TRIARC'ın kendi sunucusunda tutulur;
satılmaz, reklam ya da analiz için kullanılmaz, üçüncü kişilerle paylaşılmaz.

## Ne toplanır
- Hesap: Google ile girişte ad ve e-posta; Telegram ile girişte Telegram kimliği ve adı.
- Senin girdiğin kayıtlar: namaz ve manevi pratik, öğünler, kilo ve vücut ölçüleri, antrenmanlar, adımlar, okuma,
  görevler ve plan, geri bildirim mesajların.
- Konum (isteğe bağlı): "Konumumu kullan"a bastığında telefonun yaklaşık konumu bir kez okunur. Sunucu bunu ~1 km'ye
  yuvarlar, yalnız şehir adını, yuvarlanmış koordinatı ve saat dilimini saklar (namaz vakitleri ve hava için).
  Arka planda konum alınmaz; tam konum saklanmaz ve kayda geçmez.
- Adımlar (isteğe bağlı, Health Connect): yalnız adım kayıtları okunur, yalnız uygulama açıkken (açılışta,
  uygulamaya dönünce, "Şimdi güncelle" ile). Kayıtlar telefonda cihaz cihaz (telefon, saat) toplanır ki aynı yürüyüş
  iki kez sayılmasın; kayıtlar telefondan çıkmaz. Başka sağlık verisi okunmaz, Health Connect'e hiçbir şey yazılmaz.
  Sunucuya yalnız günün toplamı gider, o günün adımı olarak (skor, beslenme hedefi, haftalık rapor).
- Bildirim adresi: telefona bildirim gönderebilmek için Firebase Cloud Messaging kaydı. Bildirim metinlerinde
  sağlık ayrıntısı yer almaz.

## Health Connect verisinin kullanımı
Health Connect'ten alınan veri (adımlar; sunucuya yalnız günlük toplam) yalnız uygulamanın gösterdiği işlev için kullanılır:
günlük adım hedefi, Spor skoru ve beslenme hesabı. Reklam, profil çıkarma, satış ya da başka bir amaçla
kullanılmaz ve paylaşılmaz. Kullanım Health Connect izinleri politikasına uyar.

## Nasıl kapatılır ve silinir
- Adımlar: Ayarlar › Bu cihaz › Adım kaynağı › Elle, ya da Health Connect › Uygulama izinleri › TRIARC.
- Konum: Android ayarlarından TRIARC'ın konum izni kaldırılır; şehir arama kutusuyla da seçilebilir.
- Bütün veriler: Ayarlar › Hesap ve veri › dışa aktar (JSON/CSV) ve SİL (geri alınamaz; adımlar ve konum dahil).

## Hesap silme {#hesap-silme}
TRIARC hesabını ve bütün verilerini iki yoldan silebilirsin:
1. Uygulamada: Ayarlar › Hesap ve veri › SİL. Onaylayınca hesap hemen silinir (geri alınamaz).
2. Uygulama telefonunda değilse: hesabının e-posta adresinden (ya da Telegram ile girdiysen Telegram kullanıcı adınla)
   faisoftware.support@gmail.com adresine "TRIARC hesabımı sil" yaz. İstek en geç 30 gün içinde yerine getirilir
   ve sana yanıtla bildirilir.

Silinenler: hesap ve giriş kimlikleri (Google, Telegram), oturumlar, bildirim kaydı, bütün Winter Arc kayıtları
(namaz, öğünler, kilo ve ölçüler, antrenmanlar, adımlar, okuma, görevler, plan, konum ve şehir, geri bildirim mesajları).
Saklanan bir şey kalmaz; sunucu yedeklerindeki kopyalar en geç 30 gün içinde kendiliğinden silinir.

*Account deletion (EN): in the app, Settings › Account and data › DELETE; or email faisoftware.support@gmail.com from
your account's address with "Delete my TRIARC account". All account data and records are deleted; backup copies
expire within 30 days.*

## Güvenlik
Uygulama ile sunucu arasındaki her bağlantı şifrelidir (HTTPS). Oturum anahtarı telefonda güvenli depoda tutulur.

## Tıbbi tavsiye
TRIARC tıbbi tavsiye vermez; program ve beslenme hesapları kural tabanlıdır.

İletişim: faisoftware.support@gmail.com

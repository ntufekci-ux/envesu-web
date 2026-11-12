# ENVESU Web Sitesi — Yeniden Tasarım Prototipi (2026)

Envesu Çevre Enerji İnş. ve Müş. A.Ş. kurumsal web sitesinin, 2026 Şirket Profili ve Kurumsal Kimlik Kılavuzu esas alınarak hazırlanan Türkçe tasarım prototipi.

- Canlı önizleme: https://ntufekci-ux.github.io/envesu-web/
- Tek sayfa uygulama: `index.html` + `img/` (harici bağımlılık yalnızca Google Fonts).
- Sayfalar `#ad` bağlantılarıyla açılır: `#hizmetler`, `#hizmet-fizibilite`, `#referanslar`, `#proje-iaosb`, `#yaklasim`, `#makaleler`, `#makale-<id>`, `#hakkimizda`, `#baskanin-mesaji`, `#iletisim`.
- Prototip aşamasında arama motoru indekslemesi kapalıdır (`noindex`). Formlar bir gönderim servisine bağlı değildir.

## Yönetim Kurulu Başkanı fotoğrafı
Başkanın Mesajı bölümlerindeki portre `img/fikret-azili.jpg` dosyasıdır ("NKN Çekimi_Fotoğraf_02" fotoğrafından 4:5 kırpıldı, 1200×1500). Değiştirmek için aynı adla yeni bir dikey fotoğraf koymanız yeterli; dosya yoksa "FA" monogramı gösterilir.

## Yeni makale ekleme
`index.html` içinde `var MAKALELER=[` dizisine yeni bir öğe ekleyin (dosyanın başındaki açıklamada alanlar anlatılıyor). Kapak görselini `img/` klasörüne koyup `gorsel` alanına dosya adını (uzantısız, .jpg) yazın. Henüz onaylanmamış bir makaleye `taslak:true` yazarsanız kartta ve metin sonunda "Taslak" ibaresi görünür; onaylananlarda `taslak:false` kalmalı.

## Kurum logoları (Hakkımızda › İşverenler)

`index.html` içindeki `FINANSORLAR` ve `ISVERENLER` listeleri bu sayfayı oluşturur. Logo dosyaları `img/logo/` klasöründedir (PNG). Yeni logo eklemek için dosyayı bu klasöre koyup ilgili satırın `logo` alanına dosya adını (uzantısız) yazın; alan boşsa kurum adı yazıyla gösterilir.
Logolar Wikimedia Commons'tan ve kurumların resmi sitelerinden indirildi; kaynak listesi: `Web sitesi\Logo arşivi\_kaynaklar.tsv`. HEKTAŞ logosu şirket profilinden alındı (düşük çözünürlük).

## Kalite belgeleri (Yaklaşım › Kalite)

`SERTIFIKALAR` ve `SERTIFIKA_BILGI` listeleri sayfayı oluşturur. Belge görselleri `img/cert/`, PDF'ler `doc/` klasöründedir (BBS Belgelendirme, ilk belge 13.01.2026, geçerlilik 12.01.2029). Belgeler yenilendiğinde aynı adla dosyaları değiştirip tarihleri güncelleyin. Kaynak: SharePoint › 02 TEKLİF ve GELİŞTİRME › 03_Envesu › 01.envesu profil › envesu ISO › ISO 2026-2029.

## Ekip fotoğrafı

`img/ekip-toplu.jpg` ("Envesu toplu foto" dosyasından, 2200 px genişlik).

## Sözleşme bedelleri

`index.html` içindeki `BEDELLER` listesi proje kartlarında ve proje sayfalarında gösterilir: `"proje-id":["bedel","açıklama"]`. Değerler şirket profilindeki proje kartlarının "Sözleşme Bedeli" kutularından alındı. Bir projenin bedelini gizlemek için satırını silin.

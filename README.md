# ENVESU Web Sitesi — Yeniden Tasarım Prototipi (2026)

Envesu Çevre Enerji İnş. ve Müş. A.Ş. kurumsal web sitesinin, 2026 Şirket Profili ve Kurumsal Kimlik Kılavuzu esas alınarak hazırlanan Türkçe tasarım prototipi.

- Canlı önizleme: https://ntufekci-ux.github.io/envesu-web/
- Tek sayfa uygulama: `index.html` + `img/` (harici bağımlılık yalnızca Google Fonts).
- Sayfalar `#ad` bağlantılarıyla açılır: `#hizmetler`, `#hizmet-fizibilite`, `#referanslar`, `#proje-iaosb`, `#yaklasim`, `#makaleler`, `#makale-<id>`, `#hakkimizda`, `#baskanin-mesaji`, `#iletisim`.
- Prototip aşamasında arama motoru indekslemesi kapalıdır (`noindex`). Formlar bir gönderim servisine bağlı değildir.

## Yönetim Kurulu Başkanı fotoğrafı
Başkanın Mesajı bölümlerindeki portre `img/fikret-azili.jpg` dosyasıdır ("Fikret Azılı-Office" fotoğrafından 4:5 kırpıldı, 960×1200). Değiştirmek için aynı adla yeni bir dikey fotoğraf koymanız yeterli; dosya yoksa "FA" monogramı gösterilir.

## Yeni makale ekleme
`index.html` içinde `var MAKALELER=[` dizisine yeni bir öğe ekleyin (dosyanın başındaki açıklamada alanlar anlatılıyor). Kapak görselini `img/` klasörüne koyup `gorsel` alanına dosya adını (uzantısız, .jpg) yazın. Henüz onaylanmamış bir makaleye `taslak:true` yazarsanız kartta ve metin sonunda "Taslak" ibaresi görünür; onaylananlarda `taslak:false` kalmalı.

## Kurum logoları (Hakkımızda › İşverenler)

`index.html` içindeki `FINANSORLAR` ve `ISVERENLER` listeleri bu sayfayı oluşturur. Logo dosyaları `img/logo/` klasöründedir (PNG). Yeni logo eklemek için dosyayı bu klasöre koyup ilgili satırın `logo` alanına dosya adını (uzantısız) yazın; alan boşsa kurum adı yazıyla gösterilir.
Logolar Wikimedia Commons'tan ve kurumların resmi sitelerinden indirildi; kaynak listesi: `Web sitesi\Logo arşivi\_kaynaklar.tsv`. HEKTAŞ logosu şirket profilinden alındı (düşük çözünürlük). Sağlık Bakanlığı, KASKİ ve GOSB logoları bulunamadı.

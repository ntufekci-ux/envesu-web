# ENVESU Web Sitesi — Yeniden Tasarım Prototipi (2026)

Envesu Çevre Enerji İnş. ve Müş. A.Ş. kurumsal web sitesinin, 2026 Şirket Profili ve Kurumsal Kimlik Kılavuzu esas alınarak hazırlanan Türkçe tasarım prototipi.

- Canlı önizleme: https://ntufekci-ux.github.io/envesu-web/
- Tek sayfa uygulama: `index.html` + `img/` (harici bağımlılık yalnızca Google Fonts).
- Sayfalar `#ad` bağlantılarıyla açılır: `#hizmetler`, `#hizmet-fizibilite`, `#referanslar`, `#proje-iaosb`, `#yaklasim`, `#makaleler`, `#makale-<id>`, `#hakkimizda`, `#baskanin-mesaji`, `#iletisim`.
- Prototip aşamasında arama motoru indekslemesi kapalıdır (`noindex`). Formlar bir gönderim servisine bağlı değildir.

## Yönetim Kurulu Başkanı fotoğrafı
`img/fikret-azili.jpg` adıyla dikey (yaklaşık 4:5) bir fotoğraf eklendiğinde Başkanın Mesajı bölümlerinde otomatik görünür. Dosya yokken "FA" monogramı gösterilir.

## Yeni makale ekleme
`index.html` içinde `var MAKALELER=[` dizisine yeni bir öğe ekleyin (dosyanın başındaki açıklamada alanlar anlatılıyor). Kapak görselini `img/` klasörüne koyup `gorsel` alanına dosya adını (uzantısız, .jpg) yazın. Yayıma hazır makalelerde `taslak:true` satırını silin.

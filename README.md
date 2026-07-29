# Anne Pazarı

Annelerin çocuk kıyafeti, ayakkabı, oyuncak ve eşyalarını 2. el olarak alıp sattığı pazaryeri sitesi (tasarım prototipi).

## Bu depoyu nasıl kullanırsın

1. Bu depoyu GitHub'a yükle (zaten yüklüyorsan bu adımı geç).
2. Netlify'da "Add new site" → "Import an existing project" → GitHub'ı seç → bu depoyu seç.
3. Build ayarları: Build command boş bırakılabilir, Publish directory: `/` (kök dizin).
4. Deploy sonrası annepazari.com domain'ini Netlify site ayarlarından bağla.

## Notlar

- `index.html` şu an tek dosyalık bir tasarım prototipidir (HTML + CSS + JS bir arada).
- İlanlar ve giriş/kayıt işlemleri tarayıcı belleğinde (in-memory) tutulur; sayfa yenilenince sıfırlanır. Gerçek kullanıcı verisi ve ödeme için bir backend (ör. Firebase) eklenmesi gerekir.

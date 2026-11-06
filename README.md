# TTK App güncellemeleri

Bu depo **TTK App** masaüstü uygulamasının (Mac ve Windows) güncelleme kaynağıdır.

Uygulama, **Ayarlar → Güncellemeler** bölümünden ya da açılışta bu depodaki `latest.json` dosyasına bakar.
Yeni sürüm varsa `paketler/` klasöründeki arayüz paketini indirir, doğrular ve yeniden başlayınca kullanır.

- `latest.json`: son sürümün numarası, notları ve paketin doğrulama özeti (SHA-256)
- `paketler/ttk-icerik-<sürüm>.pak`: uygulamanın arayüz dosyaları

Telefon rehberi ve kişisel kayıtlar bu depoda **yoktur**; yalnızca kullanıcının bilgisayarında durur.

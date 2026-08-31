# haberportal — sabit demo adresi

Bu depo TEK İŞ yapar: geliştirme makinesindeki demo sunucusunun güncel
cloudflare tünel adresini tutar ve `index.html` ziyaretçiyi oraya yönlendirir.

- **Sabit adres:** https://xawiar.github.io/haberportal-adres/
- Adres `adres.json`'da durur; sayfa onu `raw.githubusercontent`ten anlık okur
  (GitHub Pages yayını ~1 dk geciktiği için doğrudan HTML'e gömülmez).
- Güncelleyen: `haberportal/scripts/baslat_servis.sh` (launchd ile açılışta çalışır).

Burada site kodu, veri ya da anahtar YOKTUR.

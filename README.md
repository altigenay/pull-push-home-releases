# Pull&Push Home — sürümler

Android TV ana ekranı Pull&Push Home'un hazır APK'ları ve güncelleme dosyası (`latest.json`).
Kaynak kodu özel depoda tutulur; burada yalnızca imzalı APK yayınlanır.

- Uygulama kendi güncellemesini `releases/latest/download/latest.json` adresinden denetler.
  APK, kurulmadan önce SHA-256 özeti ve imza anahtarıyla doğrulanır.
- App Pull&Push, TV'ye "Pull&Push Home'u kur" düğmesiyle buradan kurar.

## Lisanslar

Pull&Push Home, [kavunOS](https://github.com/batuhankul61-hub/kavunOS) ve
CleanYourTV (Gathin) üzerine kuruludur (MIT).
Lisans metinleri: `LICENSE-kavunOS-cleanyourtv.txt`; Inter yazı tipi SIL OFL 1.1: `INTER-LICENSE-OFL.txt`.

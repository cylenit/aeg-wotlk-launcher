# AEG WotLK Launcher

AEG WotLK 3.3.5a (12340) için launcher ve imzalı içerik güncellemeleri.

## İndir

[**AEG WotLK Launcher ZIP dosyasını indir**](https://github.com/cylenit/aeg-wotlk-launcher/releases/latest/download/AEG-WotLK-Launcher.zip)

[Sürüm sayfası ve güncelleme notları](https://github.com/cylenit/aeg-wotlk-launcher/releases/latest)

## Kurulum

1. ZIP dosyasını indir ve tamamını bir klasöre çıkar.
2. `AEG WotLK Launcher.exe` dosyasını aç.
3. **Klasör seç** ile WoW 3.3.5a klasöründeki `Wow.exe` dosyasını seç.
4. Radmin VPN'de **WotLK-AEG** ağına bağlan. Ağ parolasını sunucu sahibinden al.
5. **Güncelle / Onar**, ardından **OYNA** düğmesine bas.

Sunucu kendi bilgisayarında çalışıyorsa ilgili kutuyu işaretle. Arkadaşlar bu kutuyu boş bırakmalı. Sunucu sahibinin bilgisayarı ve oyun sunucusu açık olmalıdır.

## Özellikler

- GitHub üzerinden güncelleme kontrolü ve dosya onarma.
- İmzalı güncelleme listesi, paket ve dosya doğrulaması.
- Yarım kalan kurulumda önceki dosyaları geri yükleme.
- Sunucu bağlantısını kontrol etme ve oyunu açma.
- İlk içerik: Details! Damage Meter. Oyun içinde `/details show` ile açılır.

Windows 10/11 ve .NET Framework 4.8 gerekir. Oyun açıkken güncelleme yapılmaz.

WoW oyun istemcisi bu pakette bulunmaz. Oyun hesabının kullanıcı adı ve şifresi yalnızca oyunun giriş ekranına yazılır. Özel araba/binek bu sürümde yoktur.

## Güncelleme adresi

Launcher'da hazır olarak tanımlıdır:

```text
https://github.com/cylenit/aeg-wotlk-launcher/releases/latest/download/
```

Release dosyalarındaki `manifest.json`, `manifest.sig` ve `aeg-content-*.zip`, launcher tarafından kullanılır; oyuncular yalnızca launcher ZIP dosyasını indirmelidir. GitHub'ın otomatik oluşturduğu Source code arşivleri oyuncu paketi değildir.

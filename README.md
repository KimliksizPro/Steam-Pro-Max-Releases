# Steam Pro Max — Releases

Bu depo **dağıtım** içindir: kaynak kod barındırmaz, yalnızca derlenmiş
Windows sürümleri burada *Release* olarak yayınlanır.

Kaynak kod: `KimliksizPro/Steam-Pro-Max`

## Sürüm şeması

| Tag | GitHub'da görünümü |
|---|---|
| `vX.Y.Z-beta` | **Pre-release** — kararlı değildir, geri bildirim bekler |
| `vX.Y.Z` | Normal release — kararlı sürüm |

## Nasıl kurulur / çalıştırılır

1. Release'den `SteamProMax-win-x64-<tag>.zip` dosyasını indir
2. **Klasör olarak** çıkar (exe'yi tek başına çalıştırma)
3. `SteamProMax\sos.exe` dosyasını çift tıkla → tarayıcıda arayüz açılır

> `_internal` klasörü exe'nin yanında **olmak zorundadır**. Zip'i düz çalıştırma,
> çıkardığın klasörün tamamı gerekir.

Uygulama penceresizdir: konsol açılmaz, Steam kurulu ve oturum açık olmalıdır.
İlk açılışta arayüz şifresi sorulur (varsayılan `semih123`); değiştirmek için:

```bat
sos.exe ui --password <yeni>
```

## İçerik notları

- Hedef: **Windows 10/11** (x64)
- Her sürüm build sonrası otomatik doğrulanır: PE alt sistemi `WINDOWS_GUI`
  (konsol açılmaz) ve `RT_ICON` kayıt sayısı (ikon gömülü)
- Sürüm notları Release sayfasındadır
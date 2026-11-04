# Kasenti downloads

Installers for [Kasenti](https://kasenti.com), point of sale for shops. This
repository holds only the installer files, no code.

**To get Kasenti, go to [kasenti.com/download](https://kasenti.com/download).**
That page has the right file for your device and a short setup guide.

| Device | How to get it |
| --- | --- |
| Windows till or PC (Windows 10 or 11, 64-bit) | Download the installer from the [latest release](https://github.com/Mukela12/kasenti-downloads/releases/latest) |
| Android tablet (Android 7 or later) | Download the app (APK) from the [Android release](https://github.com/Mukela12/kasenti-downloads/releases/tag/v0.18.0-beta.2-android). It sells with no internet. |
| iPad, Mac or Chromebook | No download: open [app.kasenti.com](https://app.kasenti.com) and install it from the browser |

## Check your download

Each release lists the SHA-256 fingerprint of its installer, and so does
kasenti.com/download. On Windows, in PowerShell:

```
Get-FileHash .\Kasenti-Setup-0.18.0-beta.1.exe
```

The result must match the fingerprint exactly. If it doesn't, don't run the file,
and tell us at hello@kasenti.com.

## Help

WhatsApp +260 77 169 9187 or email hello@kasenti.com.

Kasenti is provided by Fluxium Tech Business, Lusaka, Zambia.

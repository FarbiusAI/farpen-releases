# FarPen for Windows

Draw, highlight and point over any app on your screen. FarPen is a Farbius product.

**Website:** https://www.farpen.farbius.com/en/pc · **Türkçe:** [aşağıda](#türkçe)

## Download

| Your PC | File |
| --- | --- |
| Most Windows PCs (Intel or AMD, 64-bit) | [FarPen-win-x64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x64.exe) |
| Windows on ARM (Snapdragon, Surface Pro X) | [FarPen-win-arm64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-arm64.exe) |
| Older 32-bit Windows | [FarPen-win-x86.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x86.exe) |

Not sure? Choose **x64**. All files of a version are on the [Releases](https://github.com/FarbiusAI/farpen-releases/releases) page.

**Requirements:** Windows 10 version 1809 or later, or Windows 11. No administrator rights are needed.

## Install

1. Run the downloaded file. FarPen installs itself for your Windows user only (in `%LOCALAPPDATA%\Programs\Farbius\FarPen`) and adds a Start menu shortcut.
2. Press **Ctrl + Alt + P** to draw on your screen.

**Windows SmartScreen:** The file is not code-signed yet, so Windows may show "Windows protected your PC". Only if you downloaded the file from this page and its checksum matches (see below), click **More info** and then **Run anyway**.

**Updates:** FarPen checks this page once a day and shows a notification when a new version is out. It downloads nothing by itself.

**Uninstall:** Windows Settings › Apps › Installed apps › FarPen › Uninstall.

## Check the file (recommended)

Every release lists the SHA-256 checksum of each file in `SHA256SUMS.txt`, and releases cannot be changed after they are published. In PowerShell:

```powershell
Get-FileHash .\FarPen-win-x64.exe -Algorithm SHA256
```

The value must match the line for the same file in `SHA256SUMS.txt`. If it does not, delete the file and do not run it.

## Security

Found a security problem? Please read [SECURITY.md](SECURITY.md) and report it privately.

## Legal

FarPen is free to use under the [Terms of Use](https://www.farpen.farbius.com/en/terms) and the [LICENSE](LICENSE) in this repository. How data is handled: [Privacy Policy](https://www.farpen.farbius.com/en/privacy). Open-source components: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md). This repository holds release files only; the source code is not published.

© 2026 Farbius. All rights reserved.

---

## Türkçe

Ekranında her uygulamanın üzerine çiz, vurgula ve işaret et. FarPen bir Farbius ürünüdür.

**Web sitesi:** https://www.farpen.farbius.com/pc

### İndir

| Bilgisayarın | Dosya |
| --- | --- |
| Çoğu Windows bilgisayar (Intel veya AMD, 64 bit) | [FarPen-win-x64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x64.exe) |
| ARM işlemcili Windows (Snapdragon, Surface Pro X) | [FarPen-win-arm64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-arm64.exe) |
| Eski 32 bit Windows | [FarPen-win-x86.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x86.exe) |

Emin değilsen **x64**'ü seç.

**Gereksinimler:** Windows 10 sürüm 1809 veya sonrası ya da Windows 11. Yönetici izni gerekmez.

### Kurulum

1. İndirdiğin dosyayı çalıştır. FarPen yalnızca senin Windows kullanıcın için kurulur (`%LOCALAPPDATA%\Programs\Farbius\FarPen`) ve Başlat menüsüne kısayol ekler.
2. Ekrana çizmek için **Ctrl + Alt + P** tuşlarına bas.

**Windows SmartScreen:** Dosya henüz kod imzalı değil, bu yüzden Windows "Windows bilgisayarınızı korudu" uyarısı gösterebilir. Dosyayı bu sayfadan indirdiysen ve sağlama değeri eşleşiyorsa (aşağıya bak) **Ek bilgi**'ye, ardından **Yine de çalıştır**'a tıkla.

**Güncellemeler:** FarPen günde bir kez bu sayfayı kontrol eder ve yeni sürüm çıktığında bildirim gösterir. Kendi kendine bir şey indirmez.

**Kaldırma:** Windows Ayarlar › Uygulamalar › Yüklü uygulamalar › FarPen › Kaldır.

### Dosyayı doğrula (önerilir)

Her sürümde dosyaların SHA-256 değerleri `SHA256SUMS.txt` içinde yer alır ve yayınlanan sürümler sonradan değiştirilemez. PowerShell'de:

```powershell
Get-FileHash .\FarPen-win-x64.exe -Algorithm SHA256
```

Çıkan değer, `SHA256SUMS.txt` içindeki aynı dosyanın satırıyla aynı olmalı. Değilse dosyayı sil ve çalıştırma.

### Hukuki

FarPen, [Kullanım Koşulları](https://www.farpen.farbius.com/terms) ve bu depodaki [LICENSE](LICENSE) kapsamında ücretsiz kullanılır. Kişisel veriler: [Gizlilik Politikası](https://www.farpen.farbius.com/privacy) ve [KVKK Aydınlatma Metni](https://www.farpen.farbius.com/kvkk). Güvenlik bildirimi: [SECURITY.md](SECURITY.md).

© 2026 Farbius. Tüm hakları saklıdır.

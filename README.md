# FarPen for Windows and Linux

Draw, highlight and point over any app on your screen. Pair your phone and it becomes a drawing tablet, a touchpad or a remote. FarPen is a Farbius product.

**[Windows](#windows)** · **[Linux](#linux)** · **[Check the file](#check-the-file)** · **[Türkçe](#türkçe)** · Website: https://www.farpen.farbius.com/en/pc

## Windows

**Recommended:** [Get FarPen from the Microsoft Store](https://apps.microsoft.com/detail/9nwn186vxtn1). It installs without warnings and updates itself. Or download the EXE:

| Your PC | Download |
| --- | --- |
| Most Windows PCs (Intel or AMD, 64-bit) | [FarPen-win-x64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x64.exe) |
| Windows on ARM (Snapdragon, Surface Pro X) | [FarPen-win-arm64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-arm64.exe) |
| Older 32-bit Windows | [FarPen-win-x86.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x86.exe) |

Not sure? Choose **x64**. Windows 10 (1809 or later) or Windows 11. No administrator rights needed.

1. Run the file. FarPen installs for your Windows user (`%LOCALAPPDATA%\Programs\Farbius\FarPen`) and adds a Start menu shortcut.
2. Press **Ctrl + Alt + P** to draw.

**SmartScreen:** the file is not code-signed yet, so Windows may say "Windows protected your PC". Only if you downloaded it from this page and its checksum matches, click **More info**, then **Run anyway**.

**Update:** Settings › Updates › Download and install. **Uninstall:** Windows Settings › Apps › Installed apps › FarPen.

## Linux

| Your system | Download |
| --- | --- |
| Debian, Ubuntu, Linux Mint, Pardus, Pardus ETAP | [FarPen-linux-amd64.deb](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-amd64.deb) |
| Fedora, openSUSE, RHEL family | [FarPen-linux-x86_64.rpm](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-x86_64.rpm) |
| Any distribution, no install | [FarPen-linux-x86_64.AppImage](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-x86_64.AppImage) |
| ARM 64-bit | [.deb](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-arm64.deb) · [.rpm](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-aarch64.rpm) · [AppImage](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-aarch64.AppImage) |

```sh
sudo apt install ./FarPen-linux-amd64.deb        # Debian, Ubuntu, Pardus
sudo dnf install ./FarPen-linux-x86_64.rpm       # Fedora
chmod +x FarPen-linux-x86_64.AppImage && ./FarPen-linux-x86_64.AppImage
```

Works on X11 desktops, and on Wayland desktops through XWayland. The AppImage needs no FUSE library. Phone tablet and touchpad modes need the .deb or .rpm, which add a udev rule for the signed-in user.

**Pardus ETAP smart boards:** an administrator (`etapadmin`) installs the .deb once; every teacher account can then use FarPen without a password. Touch draws by default.

**Update:** Settings › Updates. **Uninstall:** Settings › Uninstall FarPen, or `sudo apt purge farpen` / `sudo dnf remove farpen`.

## Check the file

Each release lists the SHA-256 of every file in `SHA256SUMS.txt`, and published releases cannot be changed. FarPen's in-app updater checks the same file before it installs anything.

```powershell
Get-FileHash .\FarPen-win-x64.exe -Algorithm SHA256      # Windows (PowerShell)
```

```sh
sha256sum --ignore-missing -c SHA256SUMS.txt               # Linux, in the download folder
```

If the value does not match the line for the same file, delete the file and do not run it.

## Security and legal

Found a security problem? Read [SECURITY.md](SECURITY.md) and report it privately.

FarPen is free to use under the [Terms of Use](https://www.farpen.farbius.com/en/terms) and the [LICENSE](LICENSE). Data: [Privacy Policy](https://www.farpen.farbius.com/en/privacy). Open-source components: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md). This repository holds release files only; the source code is not published.

© 2026 Farbius. All rights reserved.

---

## Türkçe

Ekranında her uygulamanın üzerine çiz, vurgula ve işaret et. Telefonunu eşle; çizim tableti, dokunmatik yüzey ya da kumanda olsun. FarPen bir Farbius ürünüdür.

**Web sitesi:** https://www.farpen.farbius.com/pc

### Windows

**Önerilen:** [FarPen'i Microsoft Store'dan al](https://apps.microsoft.com/detail/9nwn186vxtn1). Uyarısız kurulur, kendiliğinden güncellenir. Ya da EXE'yi indir:

| Bilgisayarın | İndir |
| --- | --- |
| Çoğu Windows bilgisayar (Intel veya AMD, 64 bit) | [FarPen-win-x64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x64.exe) |
| ARM işlemcili Windows (Snapdragon, Surface Pro X) | [FarPen-win-arm64.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-arm64.exe) |
| Eski 32 bit Windows | [FarPen-win-x86.exe](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-win-x86.exe) |

Emin değilsen **x64**'ü seç. Windows 10 (1809 veya sonrası) ya da Windows 11. Yönetici izni gerekmez.

1. Dosyayı çalıştır. FarPen yalnızca senin Windows kullanıcın için kurulur ve Başlat menüsüne kısayol ekler.
2. Çizmek için **Ctrl + Alt + P**.

**SmartScreen:** Dosya henüz kod imzalı değil; Windows "Windows bilgisayarınızı korudu" diyebilir. Dosyayı bu sayfadan indirdiysen ve sağlama değeri eşleşiyorsa **Ek bilgi**, ardından **Yine de çalıştır**.

**Güncelleme:** Ayarlar › Güncellemeler › İndir ve kur. **Kaldırma:** Windows Ayarlar › Uygulamalar › Yüklü uygulamalar › FarPen.

### Linux

| Sistemin | İndir |
| --- | --- |
| Debian, Ubuntu, Linux Mint, Pardus, Pardus ETAP | [FarPen-linux-amd64.deb](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-amd64.deb) |
| Fedora, openSUSE, RHEL ailesi | [FarPen-linux-x86_64.rpm](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-x86_64.rpm) |
| Her dağıtım, kurulumsuz | [FarPen-linux-x86_64.AppImage](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-x86_64.AppImage) |
| ARM 64 bit | [.deb](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-arm64.deb) · [.rpm](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-aarch64.rpm) · [AppImage](https://github.com/FarbiusAI/farpen-releases/releases/latest/download/FarPen-linux-aarch64.AppImage) |

```sh
sudo apt install ./FarPen-linux-amd64.deb        # Debian, Ubuntu, Pardus
sudo dnf install ./FarPen-linux-x86_64.rpm       # Fedora
chmod +x FarPen-linux-x86_64.AppImage && ./FarPen-linux-x86_64.AppImage
```

X11 masaüstlerinde ve XWayland üzerinden Wayland masaüstlerinde çalışır. AppImage FUSE kütüphanesi istemez. Telefonla tablet ve dokunmatik yüzey modları için .deb ya da .rpm gerekir.

**Pardus ETAP etkileşimli tahtalar:** Yönetici (`etapadmin`) .deb dosyasını bir kez kurar; ardından her öğretmen hesabı FarPen'i şifresiz kullanır. Dokunarak çizim varsayılan olarak açıktır.

**Güncelleme:** Ayarlar › Güncellemeler. **Kaldırma:** Ayarlar › FarPen'i kaldır ya da `sudo apt purge farpen`.

### Dosyayı doğrula

Her sürümdeki dosyaların SHA-256 değerleri `SHA256SUMS.txt` içindedir ve yayınlanan sürümler sonradan değiştirilemez. Windows'ta `Get-FileHash .\FarPen-win-x64.exe -Algorithm SHA256`, Linux'ta indirme klasöründe `sha256sum --ignore-missing -c SHA256SUMS.txt`. Değer eşleşmiyorsa dosyayı sil ve çalıştırma.

### Güvenlik ve hukuki

Güvenlik bildirimi: [SECURITY.md](SECURITY.md). FarPen, [Kullanım Koşulları](https://www.farpen.farbius.com/terms) ve [LICENSE](LICENSE) kapsamında ücretsiz kullanılır. Kişisel veriler: [Gizlilik Politikası](https://www.farpen.farbius.com/privacy) ve [KVKK Aydınlatma Metni](https://www.farpen.farbius.com/kvkk).

© 2026 Farbius. Tüm hakları saklıdır.

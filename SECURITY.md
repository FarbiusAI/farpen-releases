# Security

## Reporting a vulnerability

Please report security problems in FarPen (Windows, Android, FarPen Link or the website) privately:

- **GitHub:** use **Report a vulnerability** on the [Security tab](https://github.com/FarbiusAI/farpen-releases/security/advisories/new) of this repository, or
- **Email:** info@farbius.com with the subject "FarPen security".

Please include the FarPen version, your Windows or Android version and the steps to reproduce. Do not open a public issue and do not share the details publicly until a fix is out.

We aim to reply within 5 working days and to keep you updated until the problem is fixed. We credit reporters in the release notes if they wish.

Please do not access other people's data or devices, disrupt the service, or run tests that could harm other users.

## Supported versions

Only the latest release receives security fixes. FarPen shows a notification when a newer version is available.

## Verifying downloads

- Download FarPen only from this repository, www.farpen.farbius.com or the Microsoft Store.
- Each release includes `SHA256SUMS.txt`. Compare it with `Get-FileHash <file> -Algorithm SHA256` before running the file.
- Releases in this repository are immutable: once published, their files and tag cannot be changed.
- FarPen runs without administrator rights and does not install drivers or services.

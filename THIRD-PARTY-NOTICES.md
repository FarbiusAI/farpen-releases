# Third-party notices

FarPen for Windows and FarPen for Linux are built with the open-source components below. Each is used under its own license; these licenses are not limited by the FarPen [LICENSE](LICENSE).

| Component | Used for | License |
| --- | --- | --- |
| .NET runtime (Microsoft.NETCore.App) | Runs the app; bundled in the self-contained EXE | MIT |
| Windows Desktop runtime (WPF, Windows Forms) | Windows user interface | MIT |
| [QRCoder](https://github.com/codebude/QRCoder) 1.6.0 | The QR code for pairing a phone with FarPen Link | MIT |
| [Avalonia](https://github.com/AvaloniaUI/Avalonia) 12.1.6 (Linux) | Linux user interface | MIT |
| [SkiaSharp](https://github.com/mono/SkiaSharp) and [Skia](https://skia.org) (Linux) | Drawing and text rendering | MIT (SkiaSharp), BSD-3-Clause (Skia) |
| [HarfBuzzSharp](https://github.com/mono/SkiaSharp) and [HarfBuzz](https://github.com/harfbuzz/harfbuzz) (Linux) | Text shaping | MIT, Old MIT (HarfBuzz) |
| [Tmds.DBus.Protocol](https://github.com/tmds/Tmds.DBus) 0.94.1 (Linux) | Desktop notifications, shortcuts and the keyring over D-Bus | MIT |
| [Inter](https://rsms.me/inter/) (Linux) | The FarPen typeface, embedded in the app | SIL Open Font License 1.1 ([full text](licenses/OFL-Inter.txt)) |

The .NET runtime itself contains further third-party code. Its notices are in [licenses/dotnet-runtime-THIRD-PARTY-NOTICES.txt](licenses/dotnet-runtime-THIRD-PARTY-NOTICES.txt).

## .NET runtime, WPF and Windows Forms

```
The MIT License (MIT)

Copyright (c) .NET Foundation and Contributors

All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## QRCoder

```
The MIT License (MIT)

Copyright (c) 2013-2018 Raffael Herrmann

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Linux components

The MIT-licensed Linux components use the same MIT License text shown for QRCoder above, with these copyright notices:

- Avalonia: Copyright (c) The AvaloniaUI Project.
- SkiaSharp and HarfBuzzSharp: Copyright (c) 2015-2016 Xamarin, Inc.; Copyright (c) 2017-2018 Microsoft Corporation.
- HarfBuzz: Copyright © 2010-2022 Google, Inc. and the HarfBuzz contributors (Old MIT license).
- Tmds.DBus.Protocol: Copyright (c) 2017 Tom Deseyn.

The Linux packages also list every component in `/usr/share/doc/farpen/copyright`.

### Skia (BSD-3-Clause)

```
Copyright (c) 2011 Google Inc. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

  * Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

  * Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in
    the documentation and/or other materials provided with the
    distribution.

  * Neither the name of the copyright holder nor the names of its
    contributors may be used to endorse or promote products derived
    from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

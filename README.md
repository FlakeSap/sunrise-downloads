# Sunrise IDE: downloads

Downloads for **Sunrise IDE**, a code editor for Windows from [Sunovo Labs](https://sunovo-laboratories.onrender.com/). It works with **Sunshine**, our coding bot, and one click adds **Claude** next to it.

This repository holds the downloads only. There is no source code here.

## Get it

| | |
|---|---|
| **Installer (recommended)** | [SunriseIDE-Setup.exe](https://github.com/FlakeSap/sunrise-downloads/releases/latest/download/SunriseIDE-Setup.exe) |
| **Portable .zip** | [SunriseIDE-win32-x64.zip](https://github.com/FlakeSap/sunrise-downloads/releases/latest/download/SunriseIDE-win32-x64.zip) |

Windows 10 or 11, 64-bit. The installer installs for your account only (no administrator rights) and can be removed from Settings, Apps.
All versions are on the [Releases](https://github.com/FlakeSap/sunrise-downloads/releases) page.

## Before you run it

* **Windows may warn you.** The installer is not code-signed yet, so Windows can say "Windows protected your PC". Choose **More info**, then **Run anyway**.
* **Check the download** (optional). Version 0.1.0:

  ```
  c1c1b17d147d88bac599b509fce2a751e1e77f55f357da3d8971b52339af7a58  SunriseIDE-Setup.exe
  b01816c83fc5133b72a5b5cf39b78a79d3ef65141f622dfeb9cc41c591ce86ad  SunriseIDE-win32-x64.zip
  ```

  In PowerShell: `Get-FileHash .\SunriseIDE-Setup.exe -Algorithm SHA256`

## What you should know

* **Sunshine** is Sunovo Labs' coding bot. Open it from the sun icon on the left and sign in with Google (the same account as Sunset).
* **Add Claude** is the button at the bottom of the window. It installs Anthropic's official Claude Code extension from Open VSX. The editor first asks whether you trust the publisher, Anthropic; choose **Trust Publisher & Install**. Then Claude asks you to sign in with your own Claude account. Sunrise IDE never handles that login.
* Extensions come from Open VSX, not Microsoft's marketplace, so a few Microsoft-only extensions (such as Pylance) are not available.
* There is no automatic update yet: download the new version and install it over the old one. Your settings and extensions are kept.
* Telemetry is switched off.

## Licences

Sunrise IDE is built on [VSCodium](https://vscodium.com/) and Code - OSS (MIT licence). It is not made or endorsed by Microsoft or the VSCodium project. The licence texts are in the install folder (`resources\app\LICENSE.txt`, `ThirdPartyNotices.txt`, `LICENSES.chromium.html`). Claude is a product of Anthropic and is not part of this download.

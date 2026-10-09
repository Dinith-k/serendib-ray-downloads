# Serendib Ray downloads

Serendib Ray by **Aplogon**: a simple V2Ray/Xray client with live ping, speed tests, a country picker and SNI override.
This repository only holds the downloads; the apps need an activation key to work.

**[Download the latest version](https://github.com/Dinith-k/serendib-ray-downloads/releases/latest)**

## Windows (10 and 11, 64-bit)

[Serendib-Ray-Setup-0.4.0.exe](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/Serendib-Ray-Setup-0.4.0.exe)

1. Run the downloaded file and follow the steps. It installs for you, with no administrator rights needed.
2. If Windows says it protected your PC, choose **More info**, then **Run anyway**. The installer is not code-signed yet, so Windows does not know the publisher.
3. On the last page, leave **Run on startup and connect automatically** ticked if you want it to start by itself when you sign in (you can turn it off later in Settings).
4. Enter your activation key.

## macOS

| Your Mac | Download |
|---|---|
| Apple silicon (M1, M2, M3, M4) | [Serendib-Ray-0.4.0-mac-arm64.dmg](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/Serendib-Ray-0.4.0-mac-arm64.dmg) |
| Intel | [Serendib-Ray-0.4.0-mac-x64.dmg](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/Serendib-Ray-0.4.0-mac-x64.dmg) |

Not sure which? Apple menu > About This Mac: "Chip: Apple M..." is Apple silicon, "Processor: Intel..." is Intel.

1. Open the downloaded `.dmg` and drag **Serendib Ray** into **Applications**.
2. The first time, open it with **right-click > Open** (then **Open** again). The app is not yet notarized by Apple, so a double-click shows a warning.
3. Enter your activation key.

**Early build:** the macOS version has passed its automated tests on a Mac, but it is new. If macOS asks for your password when connecting, that is it changing the network proxy settings.

## Android: Serendib Ray Pro

[Serendib-Ray-Pro-1.0.0.apk](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/Serendib-Ray-Pro-1.0.0.apk)

The ad-free Android version, with the same look as Serendib Ray. It uses the same activation key as the Windows and Mac apps, shows your plan and time left, ranks servers fastest first with their latest speed test, and has an **Only servers on port 443** option (off by default). It installs next to the free Serendib Ray app and does not replace it. It is not on Google Play, so it is installed from this file.

1. Open this page on your phone and download the `.apk`.
2. Open the downloaded file. Android will ask you to allow installing apps from this source (your browser or Files app): allow it, then go back and tap **Install**.
3. Open **Serendib Ray Pro** and enter your activation key.
4. Tap the power button. Android asks once for permission to set up the VPN connection: choose **OK**.

Android 7.0 or newer. Each key works on one phone; to move it to another phone, ask for it to be reset.

## Checking your download

Checksums are in [SHA256SUMS.txt](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/SHA256SUMS.txt). On Windows: `certutil -hashfile Serendib-Ray-Setup-0.4.0.exe SHA256`. On macOS: `shasum -a 256 <file>`. On Android, a file-manager app that shows checksums can do the same. The result should match the line for your file.

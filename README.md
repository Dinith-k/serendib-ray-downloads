# Serendib Ray downloads

Serendib Ray by **Aplogon**: a simple V2Ray/Xray client with live ping, speed tests, a country picker and SNI override.
This repository only holds the downloads; the app needs an activation key to work.

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

## Checking your download

Checksums are in [SHA256SUMS.txt](https://github.com/Dinith-k/serendib-ray-downloads/releases/download/v0.4.0/SHA256SUMS.txt). On Windows: `certutil -hashfile Serendib-Ray-Setup-0.4.0.exe SHA256`. On macOS: `shasum -a 256 <file>`. The result should match the line for your file.

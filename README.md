# Warehouse – offline inventory movement accounting

Simple, free accounting of inventory movements between departments: receipts from suppliers, issues to consumers, returns, write-offs, and the balances of every department at any moment. Works fully offline on **Windows, macOS, Linux and Android**. No account, no advertising, your data stays on your device.

🌐 **Website (5 languages): [olegomela.github.io](https://olegomela.github.io)**

## Download

| System | File | Requirements | Download |
|---|---|---|---|
| Windows | `.msi` | Windows 10 or newer | [Latest version](https://github.com/olegomela/warehouse-releases-windows/releases/latest) |
| macOS | `.dmg` | A recent version of macOS | [Latest version](https://github.com/olegomela/warehouse-releases-macos/releases/latest) |
| Linux | `.deb` | Debian, Ubuntu, Linux Mint and other Debian-based systems | [Latest version](https://github.com/olegomela/warehouse-releases-linux/releases/latest) |
| Android | `.apk` | Android 8 or newer, phones and tablets | [Latest version](https://github.com/olegomela/warehouse-releases-android/releases/latest) |

Current version: **1.4.4**. Each release lists the SHA-256 checksums of its files; earlier versions are on the Releases page.

## Features

- **Transfers**: every movement of products and materials between departments. Each transfer keeps the balances it leaves behind.
- **Balances at any moment**: at the beginning or end of a period or on any date, with or without cost.
- **Accounting periods**: close a period to fix its transfers, look back at closed periods, reopen the last one.
- **Export** of any table to PDF, Excel, Word or OpenDocument (Android also CSV).
- **Barcode and QR scanning on Android**: add the code to a product's name, or find the product when recording a transfer.
- **Computer and phone**: move databases between the desktop and Android versions as ZIP files. Before replacing a database, the app warns if changes would be lost.
- **Several databases, backups with restore**, undo of the last deletion, and a sample database to try everything right away.
- **Five languages**: English, Ukrainian, German, French, Spanish; light and dark theme.

## Installation

The installers are free and not signed with paid publisher certificates, so Windows, macOS and Android show a warning the first time. Download only from the links above.

**Windows.** Run the `.msi` file. If "Windows protected your PC" appears, click "More info", then "Run anyway".

**macOS.** Open the `.dmg` and drag Warehouse into Applications. On the first start macOS blocks the app because it is not notarized by Apple: open System Settings › Privacy & Security, scroll down, click "Open Anyway" and confirm.

**Linux.** In a terminal, from the folder with the downloaded file:

```bash
sudo apt install ./warehouse_*.deb
```

**Android.** Open the downloaded `.apk`. If Android asks, allow your browser or file manager to install unknown apps. Updates install over the previous version and keep your data.

> ⚠️ Uninstalling the Android app deletes its databases. Before uninstalling, save every database you need with "Export for desktop (ZIP)".

**How the desktop version opens.** It opens in its own window of Google Chrome, Microsoft Edge or Brave, so one of these browsers should be installed (on Linux: Chrome, Chromium or Brave). Without them it opens in Firefox on Windows or in Safari on macOS. The app itself runs only on your computer.

### Checking a download (SHA-256)

Compare the result with the checksum listed in the release:

- Windows (PowerShell): `Get-FileHash .\file.msi`
- macOS: `shasum -a 256 file.dmg`
- Linux: `sha256sum file.deb`

## Privacy

Warehouse works fully offline. There is no account and no advertising, and the app does not collect or send your data: your databases are stored only on your device. On Android, barcode scanning uses Google's scanner from Google Play services where it is available.

## Contact

Questions and suggestions: [mksmpl@ukr.net](mailto:mksmpl@ukr.net)

---

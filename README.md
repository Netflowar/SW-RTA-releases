# SW RTA Companion — Releases

Public release binaries for the **SW RTA Companion** desktop app.

## Download

Check the [latest release](https://github.com/Netflowar/SW-RTA-releases/releases/latest) for the newest `.dmg` (macOS) / `.exe` (Windows).

**macOS** — two flavors:
- `...-macOS-arm64.dmg` — Apple Silicon (M1/M2/M3/M4)
- `...-macOS-x64.dmg` — Intel

The app is currently **unsigned**, so macOS warns on first launch:

- **macOS 15 (Sequoia) or newer** — open the app once and dismiss the warning, then go to **System Settings → Privacy & Security** and click **"Open Anyway"**. (Terminal alternative: `xattr -cr "/Applications/SW RTA Companion.app"`.)
- **Older macOS** — **right-click the app → Open**, then click "Open" in the dialog.

Either way it's one-time; subsequent launches are normal.

**Windows** — the newest Windows installer is [v0.17.8](https://github.com/Netflowar/SW-RTA-releases/releases/tag/v0.17.8) (`SW-RTA-Companion-0.17.8-Windows-Setup.exe`); newer releases are macOS-only for now. The installer is also unsigned, so SmartScreen warns on first run (**More info → Run anyway**).

## About

SW RTA Companion is an offline-first draft & planning tool for *Summoners War* Real-Time Arena — pick/ban assistant, GW planner, box builder, and AI coach.

The app is free while in beta. When subscriptions launch it will be **€3/month with the first 30 days free**.

The source code lives in a private repo. This repo hosts the release binaries and serves as the app's update-check endpoint.

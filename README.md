# Sentinel Security — downloads

Security review gate for Git: secrets, insecure patterns and an AI security review run before
every `git push`, a deterministic policy decides, and every decision is reported and audited.

| Platform | Installer | Portable |
|---|---|---|
| macOS 11+ (Apple Silicon + Intel) | [Sentinel-macos.pkg](https://github.com/Softiv/sentinel-releases/releases/latest/download/Sentinel-macos.pkg) | [Sentinel-macos.zip](https://github.com/Softiv/sentinel-releases/releases/latest/download/Sentinel-macos.zip) |
| Windows 10/11 x64 | [Sentinel-windows-setup.exe](https://github.com/Softiv/sentinel-releases/releases/latest/download/Sentinel-windows-setup.exe) | [Sentinel-windows.zip](https://github.com/Softiv/sentinel-releases/releases/latest/download/Sentinel-windows.zip) |

After installing, in any repository:

```sh
sentinel install
sentinel doctor
```

The app checks `latest.json` in this repository for updates and verifies each installer's SHA-256
before running it. Builds are not notarized / Authenticode-signed yet: macOS may ask to
**Open Anyway** (System Settings → Privacy & Security); Windows SmartScreen may ask
**More info → Run anyway**.

This repository only hosts release files; the source code is private.

# Custodian downloads

Installers for the Custodian desktop app. Download the latest build from
[Releases](https://github.com/hgbobia-zoe/custodian-releases/releases/latest).

| Computer | File |
|---|---|
| Windows | `Custodian-<version> Setup.exe` |
| Mac with Apple Silicon (M1 or later) | `Custodian-<version>-arm64.dmg` |
| Mac with Intel | `Custodian-<version>-x64.dmg` |

These are early builds and are not code-signed yet:

- **Windows:** if SmartScreen says "Windows protected your PC", click
  **More info → Run anyway**.
- **Mac:** open the DMG, drag Custodian to Applications, then run this once in
  Terminal (macOS blocks unsigned apps downloaded from the internet):
  ```
  xattr -cr /Applications/Custodian.app
  ```

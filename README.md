<div align="center">
  <img src="app-icon.svg" width="112" alt="zeronotch logo" />
  <h1>zeronotch</h1>
  <p>A focused notch workspace for Windows.</p>

  <p>
    <a href="https://github.com/fadilismee/zeronotch/releases/latest"><strong>Download the latest release</strong></a>
    ·
    <a href="https://cebanmatters.com/zeronotch">Support zeronotch</a>
  </p>

  <p>
    <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-26A7E8?style=flat-square" />
    <img alt="64-bit" src="https://img.shields.io/badge/platform-x64-5AD7C1?style=flat-square" />
    <img alt="License GPL-3.0" src="https://img.shields.io/badge/license-GPL--3.0-D8C4A8?style=flat-square" />
  </p>
</div>

zeronotch turns the area around your Windows notch into a compact workspace.
Switch between **Work** and **Study** so the interface only shows the tools that
matter in the current context.

![zeronotch Study overview](docs/img/overview-study.png)

## Highlights

- **Two focused modes** — keep work utilities and university tools separate.
- **Study workspace** — tasks, UT calendar, focus timer, study streak, notes,
  module search/download, and the interactive Kuma companion.
- **Everyday utilities** — File Shelf, scrollable clipboard history, calculator,
  mirror, and configurable app shortcuts.
- **Media controls** — compact playback controls with an optional dedicated
  lyrics view.
- **Optional AI** — connect an OpenAI-compatible endpoint using your own
  configuration.

<table>
  <tr>
    <td><img src="docs/img/music.png" alt="zeronotch music controls" /></td>
    <td><img src="docs/img/clipboard.png" alt="zeronotch clipboard cards" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Compact media controls</sub></td>
    <td align="center"><sub>Scrollable clipboard cards</sub></td>
  </tr>
</table>

## Install

1. Open [Releases](https://github.com/fadilismee/zeronotch/releases/latest).
2. Download the newest `zeronotch-Setup-vX.Y.Z.exe` asset.
3. Run the installer, then launch zeronotch from the Start menu.

The installer is currently unsigned. Windows SmartScreen may therefore identify
it as an unrecognized app. Release notes include the SHA-256 checksum so you can
verify the downloaded file.

## Requirements

- Windows 10 or Windows 11, 64-bit
- Python 3 only when using the module downloader
- Camera permission only when opening Mirror
- Internet access only for features you connect, such as UT, module downloads,
  lyrics, or an AI endpoint

## Privacy

zeronotch keeps workspace state on the device. Camera preview is local and is
not recorded by the app. Account, AI, and network-backed features are used only
after you configure or open them.

## Current limitations

- The Windows installer is not code-signed yet.
- UT sign-in and calendar synchronization depend on the university service and
  should be validated with your own account.
- Module downloads currently require Python 3.
- zeronotch uses Electron, so Windows may show several helper processes in Task
  Manager even though they belong to one application.

## Support the project

zeronotch is developed independently. If it helps your day, you can support its
continued development at [cebanmatters.com/zeronotch](https://cebanmatters.com/zeronotch).

## License

zeronotch is distributed under the GNU General Public License v3.0.


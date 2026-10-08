# Teal VPN for Linux

Teal VPN is a private VPN that is built to connect on networks that block VPNs. Teal Free gives you a daily data
allowance with no card and no ads. Teal Pro is unlimited and opens every location.

This page hosts the **direct download** of Teal VPN for Ubuntu, Debian and other Debian-based Linux (a `.deb`
package). This repository holds no source code, only the releases.

## Download

- **Intel / AMD (most PCs):** [teal-vpn_amd64.deb](https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_amd64.deb)
- **ARM (Raspberry Pi 4/5, ARM laptops):** [teal-vpn_arm64.deb](https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_arm64.deb)

Every version is on the [Releases](https://github.com/tealvpn/linux/releases) page.

## Install

```
sudo apt install ./teal-vpn_amd64.deb
```

Then open **Teal VPN** from your applications menu, sign in and press **Connect**.

## Check the file (SHA-256)

Each release lists the files' SHA-256 and carries a `.sha256` file for each package:

```
sha256sum -c teal-vpn_amd64.deb.sha256
```

The app updates itself and checks a signed manifest and the SHA-256 before installing an update.

## Official links

- Website: https://tealvpn.com
- Linux: https://tealvpn.com/linux
- Your account: https://account.tealvpn.com
- Help: support@tealvpn.com

Download Teal VPN only from tealvpn.com or this page.

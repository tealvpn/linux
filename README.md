<p align="center">
  <img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/banner.png" alt="Teal VPN" width="100%">
</p>

<h1 align="center">Teal VPN for Linux</h1>
<p align="center">Ubuntu, Debian and other Debian-based Linux, Intel / AMD and ARM.</p>

<p align="center">
  <a href="https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_amd64.deb"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-linux.png" alt="Download for Linux" height="56"></a>
  <a href="https://github.com/tealvpn/linux/releases/latest/download/teal-vpn_arm64.deb"><img src="https://raw.githubusercontent.com/tealvpn/.github/main/profile/btn-linux-arm.png" alt="Linux on ARM" height="56"></a>
</p>
<p align="center"><sub>Most PCs: the first button. Raspberry Pi 4/5 and ARM laptops: Linux on ARM.</sub></p>

<p align="center">
  <img src="screenshots/connect.webp" alt="Connected" width="420">
  <img src="screenshots/locations.webp" alt="Locations" width="420">
  <img src="screenshots/protection.webp" alt="Protection" width="420">
</p>

## Install

```
sudo apt install ./teal-vpn_amd64.deb
```

Then open **Teal VPN** from your applications menu, sign in and click **Connect**.

## Check the file

Each release lists the SHA-256 of each package and carries a `.sha256` file:

```
sha256sum -c teal-vpn_amd64.deb.sha256
```

## Updates

The app updates itself and checks a signed list and the SHA-256 before installing an update.

## Official links

[tealvpn.com](https://tealvpn.com/linux) · [Your account](https://account.tealvpn.com) · [All Teal VPN downloads](https://github.com/tealvpn) · support@tealvpn.com

Download Teal VPN only from tealvpn.com, Google Play or this GitHub organization. This repository holds no source code, only the releases.

<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PairDrop untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/pairdrop.svg)](https://ci-apps.yunohost.org/ci/apps/pairdrop/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/pairdrop.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/pairdrop.maintain.svg)

[![Pasang PairDrop dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pairdrop)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PairDrop secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

PairDrop is a sublime alternative to AirDrop that works on all platforms.

### Features

- File Sharing on your local network
	- Send images, documents or text via peer to peer connection to devices on the same local network.
- Internet Transfers
	- Join temporary public rooms to transfer files easily over the internet!
- Web-Application
	- As it is web based, it runs on all devices.


**Versi terkirim:** 1.10.7~ynh3

**Demo:** <https://pairdrop.net/>

## Tangkapan Layar

![Tangkapan Layar pada PairDrop](./doc/screenshots/pairdrop_screenshot_desktop.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://pairdrop.net/>
- Dokumentasi admin resmi: <https://github.com/babstar99/PairDrop/blob/master/docs/host-your-own.md>
- Depot kode aplikasi hulu: <https://github.com/babstar99/PairDrop>
- Gudang YunoHost: <https://apps.yunohost.org/app/pairdrop>
- Laporkan bug: <https://github.com/YunoHost-Apps/pairdrop_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
atau
sudo yunohost app upgrade pairdrop -u https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>

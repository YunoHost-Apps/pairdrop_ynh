<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PairDrop YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/pairdrop.svg)](https://dash.yunohost.org/appci/app/pairdrop) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/pairdrop.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/pairdrop.maintain.svg)

[![Instalatu PairDrop YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pairdrop)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PairDrop YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

PairDrop is a sublime alternative to AirDrop that works on all platforms.

### Features

- File Sharing on your local network
	- Send images, documents or text via peer to peer connection to devices on the same local network.
- Internet Transfers
	- Join temporary public rooms to transfer files easily over the internet!
- Web-Application
	- As it is web based, it runs on all devices.


**Paketatutako bertsioa:** 1.10.7~ynh2

**Demoa:** <https://pairdrop.net/>

## Pantaila-argazkiak

![PairDrop(r)en pantaila-argazkia](./doc/screenshots/pairdrop_screenshot_desktop.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://pairdrop.net/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/babstar99/PairDrop/blob/master/docs/host-your-own.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/babstar99/PairDrop>
- YunoHost Denda: <https://apps.yunohost.org/app/pairdrop>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/pairdrop_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
edo
sudo yunohost app upgrade pairdrop -u https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

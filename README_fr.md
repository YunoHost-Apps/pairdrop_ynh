<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# PairDrop pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/pairdrop.svg)](https://ci-apps.yunohost.org/ci/apps/pairdrop/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/pairdrop.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/pairdrop.maintain.svg)

[![Installer PairDrop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pairdrop)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer PairDrop rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

PairDrop est une sublime alternative à AirDrop qui fonctionne sur toutes les plateformes.

### Caractéristiques

- Partage de fichiers sur votre réseau local
	- Envoyez des images, des documents ou du texte via une connexion peer to peer vers des appareils sur le même réseau local.
- Transferts Internet
	- Rejoignez des salles publiques temporaires pour transférer facilement des fichiers sur Internet !
- Application Web
	- Comme il est basé sur le Web, il fonctionne sur tous les appareils.

**Version incluse :** 1.10.7~ynh3

**Démo :** <https://pairdrop.net/>

## Captures d’écran

![Capture d’écran de PairDrop](./doc/screenshots/pairdrop_screenshot_desktop.png)

## Documentations et ressources

- Site officiel de l’app : <https://pairdrop.net/>
- Documentation officielle de l’admin : <https://github.com/babstar99/PairDrop/blob/master/docs/host-your-own.md>
- Dépôt de code officiel de l’app : <https://github.com/babstar99/PairDrop>
- YunoHost Store : <https://apps.yunohost.org/app/pairdrop>
- Signaler un bug : <https://github.com/YunoHost-Apps/pairdrop_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pairdrop -u https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# PairDrop для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/pairdrop.svg)](https://ci-apps.yunohost.org/ci/apps/pairdrop/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/pairdrop.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/pairdrop.maintain.svg)

[![Установите PairDrop с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pairdrop)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить PairDrop быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

PairDrop is a sublime alternative to AirDrop that works on all platforms.

### Features

- File Sharing on your local network
	- Send images, documents or text via peer to peer connection to devices on the same local network.
- Internet Transfers
	- Join temporary public rooms to transfer files easily over the internet!
- Web-Application
	- As it is web based, it runs on all devices.


**Поставляемая версия:** 1.10.7~ynh2

**Демо-версия:** <https://pairdrop.net/>

## Снимки экрана

![Снимок экрана PairDrop](./doc/screenshots/pairdrop_screenshot_desktop.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://pairdrop.net/>
- Официальная документация администратора: <https://github.com/babstar99/PairDrop/blob/master/docs/host-your-own.md>
- Репозиторий кода главной ветки приложения: <https://github.com/babstar99/PairDrop>
- Магазин YunoHost: <https://apps.yunohost.org/app/pairdrop>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/pairdrop_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
или
sudo yunohost app upgrade pairdrop -u https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>

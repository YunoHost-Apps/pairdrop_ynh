<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 PairDrop

[![集成程度](https://dash.yunohost.org/integration/pairdrop.svg)](https://dash.yunohost.org/appci/app/pairdrop) ![工作状态](https://ci-apps.yunohost.org/ci/badges/pairdrop.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/pairdrop.maintain.svg)

[![使用 YunoHost 安装 PairDrop](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pairdrop)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 PairDrop。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

PairDrop is a sublime alternative to AirDrop that works on all platforms.

### Features

- File Sharing on your local network
	- Send images, documents or text via peer to peer connection to devices on the same local network.
- Internet Transfers
	- Join temporary public rooms to transfer files easily over the internet!
- Web-Application
	- As it is web based, it runs on all devices.


**分发版本：** 1.10.7~ynh2

**演示：** <https://pairdrop.net/>

## 截图

![PairDrop 的截图](./doc/screenshots/pairdrop_screenshot_desktop.png)

## 文档与资源

- 官方应用网站： <https://pairdrop.net/>
- 官方管理文档： <https://github.com/babstar99/PairDrop/blob/master/docs/host-your-own.md>
- 上游应用代码库： <https://github.com/babstar99/PairDrop>
- YunoHost 商店： <https://apps.yunohost.org/app/pairdrop>
- 报告 bug： <https://github.com/YunoHost-Apps/pairdrop_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
或
sudo yunohost app upgrade pairdrop -u https://github.com/YunoHost-Apps/pairdrop_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>

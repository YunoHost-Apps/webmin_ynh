<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 的 Webmin

[![集成程度](https://dash.yunohost.org/integration/webmin.svg)](https://dash.yunohost.org/appci/app/webmin) ![工作状态](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)

[![使用 YunoHost 安装 Webmin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Webmin。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like `/etc/passwd`, and lets you manage a system from the console or remotely.

**分发版本：** 2.111~ynh1

## 截图

![Webmin 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <http://www.webmin.com>
- 上游应用代码库： <https://github.com/webmin/webmin>
- YunoHost 商店： <https://apps.yunohost.org/app/webmin>
- 报告 bug： <https://github.com/YunoHost-Apps/webmin_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
或
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>

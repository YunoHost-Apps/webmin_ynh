<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Webmin for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/webmin)](https://ci-apps.yunohost.org/ci/apps/webmin/)
![Working status](https://apps.yunohost.org/badge/state/webmin)
![Maintenance status](https://apps.yunohost.org/badge/maintained/webmin)

[![Install Webmin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Webmin quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like `/etc/passwd`, and lets you manage a system from the console or remotely.

**Shipped version:** 2.303~ynh1

## Screenshots

![Screenshot of Webmin](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <http://www.webmin.com>
- Upstream app code repository: <https://github.com/webmin/webmin>
- YunoHost Store: <https://apps.yunohost.org/app/webmin>
- Report a bug: <https://github.com/YunoHost-Apps/webmin_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
or
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>

# WebMin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/webmin.svg)](https://dash.yunohost.org/appci/app/webmin) ![](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)  
[![Install WebMin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=webmin)

> *This package allows you to install WebMin quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

**Note:** This app has **root** access which can change core things in the system, thus **breaking the YunoHost**. Use it carefully and read the [documents](https://doxfer.webmin.com/Webmin/Main_Page) two times before changing values.

## Overview
[WebMin](http://www.webmin.com/index.html) is a **web-based** interface for system **administration** for Unix. Using any modern web browser, you can setup user **accounts**, **DNS**, **file sharing** and much more. Webmin removes the need to manually **edit Unix configuration** files like **/etc/passwd**, and lets you manage a system from the **console or remotely**. 

**Shipped version:** 1.953

## Important points

- Only **root** (system user) can connect 
- Webmin will **update itself** when system updates are run. So no need to **run upgrade script** once installed.
- Only **user** given permission at time of the installation can **access** the Webmin 
- Installation can only be done on **root path**. e.g. webmin.domain.tld 
- No **multi-instance** for webmin as it is a system integrated app 

## Links

 * Report a bug: https://github.com/YunoHost-Apps/webmin_ynh/issues
 * App website: http://www.webmin.com/
 * Upstream app repository: https://github.com/webmin/webmin
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
or
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Webmin YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/webmin.svg)](https://ci-apps.yunohost.org/ci/apps/webmin/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)

[![Instalatu Webmin YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Webmin YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like `/etc/passwd`, and lets you manage a system from the console or remotely.

**Paketatutako bertsioa:** 2.202~ynh1

## Pantaila-argazkiak

![Webmin(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://www.webmin.com>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/webmin/webmin>
- YunoHost Denda: <https://apps.yunohost.org/app/webmin>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/webmin_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
edo
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

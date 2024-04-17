<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Webmin pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/webmin.svg)](https://dash.yunohost.org/appci/app/webmin) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)

[![Installer Webmin avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Webmin rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Webmin est une interface Web pour l'administration système pour Unix. À l'aide de n'importe quel navigateur Web moderne, vous pouvez configurer des comptes d'utilisateurs, Apache, DNS, le partage de fichiers et bien plus encore. Webmin supprime le besoin de modifier manuellement les fichiers de configuration Unix comme « /etc/passwd » et vous permet de gérer un système depuis la console ou à distance.

**Version incluse :** 2.111~ynh1

## Captures d’écran

![Capture d’écran de Webmin](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <http://www.webmin.com>
- Dépôt de code officiel de l’app : <https://github.com/webmin/webmin>
- YunoHost Store : <https://apps.yunohost.org/app/webmin>
- Signaler un bug : <https://github.com/YunoHost-Apps/webmin_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

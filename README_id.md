<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Webmin untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/webmin.svg)](https://ci-apps.yunohost.org/ci/apps/webmin/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/webmin.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/webmin.maintain.svg)

[![Pasang Webmin dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=webmin)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Webmin secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Webmin is a web-based interface for system administration for Unix. Using any modern web browser, you can setup user accounts, Apache, DNS, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like `/etc/passwd`, and lets you manage a system from the console or remotely.

**Versi terkirim:** 2.202~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Webmin](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <http://www.webmin.com>
- Depot kode aplikasi hulu: <https://github.com/webmin/webmin>
- Gudang YunoHost: <https://apps.yunohost.org/app/webmin>
- Laporkan bug: <https://github.com/YunoHost-Apps/webmin_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/webmin_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
atau
sudo yunohost app upgrade webmin -u https://github.com/YunoHost-Apps/webmin_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>

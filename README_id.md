<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# GitList untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/gitlist.svg)](https://ci-apps.yunohost.org/ci/apps/gitlist/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Pasang GitList dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang GitList secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Versi terkirim:** 2.0.0~ynh5

## Tangkapan Layar

![Tangkapan Layar pada GitList](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://gitlist.org/>
- Dokumentasi admin resmi: <https://github.com/klaussilveira/gitlist/wiki>
- Depot kode aplikasi hulu: <https://github.com/klaussilveira/gitlist>
- Gudang YunoHost: <https://apps.yunohost.org/app/gitlist>
- Laporkan bug: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
atau
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>

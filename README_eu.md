<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# GitList YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/gitlist.svg)](https://ci-apps.yunohost.org/ci/apps/gitlist/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Instalatu GitList YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek GitList YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Paketatutako bertsioa:** 2.0.0~ynh6

## Pantaila-argazkiak

![GitList(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://gitlist.org/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/klaussilveira/gitlist/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/klaussilveira/gitlist>
- YunoHost Denda: <https://apps.yunohost.org/app/gitlist>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
edo
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

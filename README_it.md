<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# GitList per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/gitlist.svg)](https://dash.yunohost.org/appci/app/gitlist) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Installa GitList con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare GitList su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Versione pubblicata:** 2.0.0~ynh4

## Screenshot

![Screenshot di GitList](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://gitlist.org/>
- Documentazione ufficiale per gli amministratori: <https://github.com/klaussilveira/gitlist/wiki>
- Repository upstream del codice dell’app: <https://github.com/klaussilveira/gitlist>
- Store di YunoHost: <https://apps.yunohost.org/app/gitlist>
- Segnala un problema: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
o
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>

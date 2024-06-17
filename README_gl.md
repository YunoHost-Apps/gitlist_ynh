<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# GitList para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/gitlist.svg)](https://dash.yunohost.org/appci/app/gitlist) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Instalar GitList con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar GitList de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Versión proporcionada:** 2.0.0~ynh4

## Capturas de pantalla

![Captura de pantalla de GitList](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://gitlist.org/>
- Documentación oficial para admin: <https://github.com/klaussilveira/gitlist/wiki>
- Repositorio de orixe do código: <https://github.com/klaussilveira/gitlist>
- Tenda YunoHost: <https://apps.yunohost.org/app/gitlist>
- Informar dun problema: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>

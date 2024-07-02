<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# GitList para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/gitlist.svg)](https://ci-apps.yunohost.org/ci/apps/gitlist/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Instalar GitList con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarGitList rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Versión actual:** 2.0.0~ynh5

## Capturas

![Captura de GitList](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://gitlist.org/>
- Documentación administrador oficial: <https://github.com/klaussilveira/gitlist/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/klaussilveira/gitlist>
- Catálogo YunoHost: <https://apps.yunohost.org/app/gitlist>
- Reportar un error: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
o
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>

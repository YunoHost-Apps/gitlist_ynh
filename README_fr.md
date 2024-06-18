<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# GitList pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/gitlist.svg)](https://dash.yunohost.org/appci/app/gitlist) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Installer GitList avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer GitList rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

GitList est une interface Web élégante et moderne permettant d'interagir avec plusieurs référentiels git. Il vous permet de parcourir les référentiels à l'aide de votre navigateur préféré, d'afficher les fichiers sous différentes révisions, l'historique des validations, les différences. Il génère également des flux RSS/Atom pour chaque référentiel, vous permettant de rester au courant des dernières modifications à tout moment et en tout lieu.

### Caractéristiques

- Prise en charge de plusieurs référentiels
- Prise en charge de plusieurs succursales
- Prise en charge de plusieurs balises
- Commit historique, blâme, différence
- Flux RSS/Atom
- Mise en évidence de la syntaxe via CodeMirror ou Ace
- Statistiques du référentiel

**Version incluse :** 2.0.0~ynh5

## Captures d’écran

![Capture d’écran de GitList](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://gitlist.org/>
- Documentation officielle de l’admin : <https://github.com/klaussilveira/gitlist/wiki>
- Dépôt de code officiel de l’app : <https://github.com/klaussilveira/gitlist>
- YunoHost Store : <https://apps.yunohost.org/app/gitlist>
- Signaler un bug : <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
ou
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

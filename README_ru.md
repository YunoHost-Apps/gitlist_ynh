<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# GitList для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/gitlist.svg)](https://ci-apps.yunohost.org/ci/apps/gitlist/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![Установите GitList с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить GitList быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**Поставляемая версия:** 2.0.0~ynh5

## Снимки экрана

![Снимок экрана GitList](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://gitlist.org/>
- Официальная документация администратора: <https://github.com/klaussilveira/gitlist/wiki>
- Репозиторий кода главной ветки приложения: <https://github.com/klaussilveira/gitlist>
- Магазин YunoHost: <https://apps.yunohost.org/app/gitlist>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
или
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>

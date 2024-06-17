<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 GitList

[![集成程度](https://dash.yunohost.org/integration/gitlist.svg)](https://dash.yunohost.org/appci/app/gitlist) ![工作状态](https://ci-apps.yunohost.org/ci/badges/gitlist.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/gitlist.maintain.svg)

[![使用 YunoHost 安装 GitList](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gitlist)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 GitList。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

GitList is an elegant and modern web interface for interacting with multiple git repositories. It allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history, diffs. It also generates RSS/Atom feeds for each repository, allowing you to stay up-to-date with the latest changes anytime, anywhere.

### Features

- Multiple repository support
- Multiple branch support
- Multiple tag support
- Commit history, blame, diff
- RSS/Atom feeds
- Syntax highlighting via CodeMirror or Ace
- Repository statistics


**分发版本：** 2.0.0~ynh4

## 截图

![GitList 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://gitlist.org/>
- 官方管理文档： <https://github.com/klaussilveira/gitlist/wiki>
- 上游应用代码库： <https://github.com/klaussilveira/gitlist>
- YunoHost 商店： <https://apps.yunohost.org/app/gitlist>
- 报告 bug： <https://github.com/YunoHost-Apps/gitlist_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
或
sudo yunohost app upgrade gitlist -u https://github.com/YunoHost-Apps/gitlist_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>

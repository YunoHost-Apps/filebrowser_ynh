<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Filebrowser

[![集成程度](https://dash.yunohost.org/integration/filebrowser.svg)](https://ci-apps.yunohost.org/ci/apps/filebrowser/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/filebrowser.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/filebrowser.maintain.svg)

[![使用 YunoHost 安装 Filebrowser](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filebrowser)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Filebrowser。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

FileBrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.


**分发版本：** 2.31.0~ynh1

## 截图

![Filebrowser 的截图](./doc/screenshots/screenshot.PNG)

## 文档与资源

- 官方应用网站： <https://filebrowser.org>
- 官方管理文档： <https://filebrowser.org/>
- 上游应用代码库： <https://github.com/filebrowser/filebrowser>
- YunoHost 商店： <https://apps.yunohost.org/app/filebrowser>
- 报告 bug： <https://github.com/YunoHost-Apps/filebrowser_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
或
sudo yunohost app upgrade filebrowser -u https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>

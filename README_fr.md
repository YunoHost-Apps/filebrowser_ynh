# Filebrowser pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/filebrowser.svg)](https://dash.yunohost.org/appci/app/filebrowser) ![](https://ci-apps.yunohost.org/ci/badges/filebrowser.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/filebrowser.maintain.svg)  
[![Installer Filebrowser avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filebrowser)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Filebrowser rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.


**Version incluse :** 2.21.1~ynh2



## Captures d'écran

![](./doc/screenshots/spaces_-M8KDxOujDoPpJyJJ5_i_uploads_git-blob-9390768b0cbb83b1e7da55c0ae13ecd2d8fcb114_2.PNG)

## Avertissements / informations importantes

### Default credentials

```
username: admin
password: admin
```

You must change the password and, if you can, the username for the best security possible.

### Configuration

By default, the root path is set to `/home/yunohost.app/filebrowser`. You can choose a different root path in filebrowser configuration file: `/var/www/filebrowser/settings.json` and modify **root** entry as desired. (you may need to set the correct permissions for the new path).

## Documentations et ressources

* Site officiel de l'app : https://filebrowser.org
* Documentation officielle de l'admin : https://filebrowser.org/
* Dépôt de code officiel de l'app : https://github.com/filebrowser/filebrowser
* Documentation YunoHost pour cette app : https://yunohost.org/app_filebrowser
* Signaler un bug : https://github.com/YunoHost-Apps/filebrowser_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
ou
sudo yunohost app upgrade filebrowser -u https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
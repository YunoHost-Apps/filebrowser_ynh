<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Filebrowser pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/filebrowser.svg)](https://ci-apps.yunohost.org/ci/apps/filebrowser/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/filebrowser.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/filebrowser.maintain.svg)

[![Installer Filebrowser avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=filebrowser)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Filebrowser rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

FileBrowser fournit une interface de gestion de fichiers dans un répertoire spécifié et peut être utilisé pour télécharger, supprimer, prévisualiser, renommer et modifier vos fichiers. Il permet la création de plusieurs utilisateurs et chaque utilisateur peut avoir son propre répertoire. Il peut être utilisé comme application autonome ou comme middleware.

**Version incluse :** 2.31.0~ynh1

## Captures d’écran

![Capture d’écran de Filebrowser](./doc/screenshots/screenshot.PNG)

## Documentations et ressources

- Site officiel de l’app : <https://filebrowser.org>
- Documentation officielle de l’admin : <https://filebrowser.org/>
- Dépôt de code officiel de l’app : <https://github.com/filebrowser/filebrowser>
- YunoHost Store : <https://apps.yunohost.org/app/filebrowser>
- Signaler un bug : <https://github.com/YunoHost-Apps/filebrowser_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
ou
sudo yunohost app upgrade filebrowser -u https://github.com/YunoHost-Apps/filebrowser_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

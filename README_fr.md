# Mautic pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mautic.svg)](https://dash.yunohost.org/appci/app/mautic) ![](https://ci-apps.yunohost.org/ci/badges/mautic.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mautic.maintain.svg)  
[![Installer Mautic avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mautic)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Mautic rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Logiciel d'automatisation marketing open source

**Version incluse :** 4.1.0~ynh1

**Démo :** https://www.mautic.org/demo

## Captures d'écran

![](./doc/screenshots/mautic-Screenshots.jpg)

## Avertissements / informations importantes

## Configuration

 * Après l'installation, vous recevrez un e-mail avec le mot de passe DB.
 * Pour se connecter à Mautic `https://example.com/mautic/s/login`.

## Documentations et ressources

* Site officiel de l'app : https://www.mautic.org/
* Documentation officielle de l'admin : https://docs.mautic.org/en
* Dépôt de code officiel de l'app : https://github.com/mautic/mautic
* Documentation YunoHost pour cette app : https://yunohost.org/app_mautic
* Signaler un bug : https://github.com/YunoHost-Apps/mautic_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mautic_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mautic -u https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
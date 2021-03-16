# Mautic pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mautic.svg)](https://dash.yunohost.org/appci/app/mautic) ![](https://ci-apps.yunohost.org/ci/badges/mautic.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mautic.maintain.svg)  
[![Installer mautic avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mautic)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Mautic rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

**Version incluse :** 3.3.1

## Captures d'écran

![](mautic-Screenshots.jpg)

## Démo

 * [Démo](https://www.mautic.org/demo)

## Configuration

 * Après l'installation, vous recevrez un e-mail avec le mot de passe DB.
 * Pour se connecter à Mautic `https://example.com/mautic/s/login`.

## Documentation

 * Documentation : https://docs.mautic.org/en
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mautic%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mautic/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mautic%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mautic/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/mautic_ynh/issues
 * Site de l'application : https://www.mautic.org/
 * Dépôt de l'application principale : https://github.com/mautic/mautic
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mautic_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mautic -u https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
```

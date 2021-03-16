# Castopod pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/castopod.svg)](https://dash.yunohost.org/appci/app/castopod) ![](https://ci-apps.yunohost.org/ci/badges/castopod.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/castopod.maintain.svg)  
[![Installer Castopod avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=castopod)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Castopod rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Castopod Server est une plate-forme d'hébergement open source conçue pour les podcasteurs qui souhaitent s'engager et interagir avec leur public. Veuillez noter que Castopod est toujours en développement: il n'est peut-être pas stable à 100% et certaines fonctionnalités sont encore en développement.

**Version incluse :** 3.2.2

## Captures d'écran

![](mautic-Screenshots.jpg)

## Démo

 * [Démo]()

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

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/castopod%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/castopod/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/castopod%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/castopod/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/castopod_ynh/issues
 * Site de l'application : https://podlibre.org/
 * Dépôt de l'application principale : https://code.podlibre.org/podlibre/castopod
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/castopod_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/castopod_ynh/tree/testing --debug
ou
sudo yunohost app upgrade castopod -u https://github.com/YunoHost-Apps/castopod_ynh/tree/testing --debug
```

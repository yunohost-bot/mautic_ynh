# Mautic for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mautic.svg)](https://dash.yunohost.org/appci/app/mautic) ![](https://ci-apps.yunohost.org/ci/badges/mautic.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mautic.maintain.svg)  
[![Install Mautic with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mautic)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mautic quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

**Shipped version:** 3.3.2

## Screenshots

![](mautic-Screenshots.jpg)

## Demo

 * [Demo](https://www.mautic.org/demo)

## Configuration

 * After installation you will receive an email with the DB password.
 * To login to Mautic `https://example.com/mautic/s/login`.

## Documentation

 * Documentation: https://docs.mautic.org/en
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported?
 * Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mautic%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mautic/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mautic%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mautic/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/mautic_ynh/issues
 * App website: https://www.mautic.org/
 * Upstream app repository: https://github.com/mautic/mautic
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mautic_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
or
sudo yunohost app upgrade mautic -u https://github.com/YunoHost-Apps/mautic_ynh/tree/testing --debug
```

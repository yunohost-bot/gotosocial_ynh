<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# GoToSocial for YunoHost

[![Integration level](https://dash.yunohost.org/integration/gotosocial.svg)](https://dash.yunohost.org/appci/app/gotosocial) ![](https://ci-apps.yunohost.org/ci/badges/gotosocial.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/gotosocial.maintain.svg)  
[![Install GoToSocial with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=gotosocial)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install GoToSocial quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

GoToSocial is an [ActivityPub](https://activitypub.rocks/) social network server, written in Golang.

With GoToSocial, you can keep in touch with your friends, post, read, and share images and articles. All without being tracked or advertised to!

![](./doc/logo_sloth.png)

Documentation is at [docs.gotosocial.org](https://docs.gotosocial.org). You can skip straight to the API documentation [here](https://docs.gotosocial.org/en/latest/api/swagger/).


**Shipped version:** 0.2.1~ynh1



## Screenshots

![](./doc/screenshots/screenshot.jpg)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
  * GoToSocial require a dedicated root domain, eg. gotosocial.domain.tld
  * This package is not-working single-sign on or LDAP integration
  * This package is currently set to single-instance that means you can run a single GoToSocial instance on a single server.

## Documentation and resources

* Official app website: https://docs.gotosocial.org/
* Official user documentation: https://docs.gotosocial.org/en/latest/
* Official admin documentation: https://docs.gotosocial.org/en/latest/
* Upstream app code repository: https://github.com/superseriousbusiness/gotosocial
* YunoHost documentation for this app: https://yunohost.org/app_gotosocial
* Report a bug: https://github.com/YunoHost-Apps/gotosocial_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing --debug
or
sudo yunohost app upgrade gotosocial -u https://github.com/YunoHost-Apps/gotosocial_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
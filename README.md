# Dendrite for YunoHost

[![Integration level](https://dash.yunohost.org/integration/dendrite.svg)](https://dash.yunohost.org/appci/app/dendrite) ![](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)  
[![Install Dendrite with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

<!-- *[Lire ce readme en français.](./README_fr.md)* -->

> *This package allows you to install Dendrite quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse.

**Shipped version:** 0.3.3

:warning: The upstream app is still in beta. Tread carefully.

## Configuration

How to configure this app: from its configuration file.

## Documentation

 * Official documentation: https://github.com/matrix-org/dendrite/tree/master/docs
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? Not yet.
Can the app be used by multiple users? Yes.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/dendrite%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/dendrite/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/dendrite%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/dendrite/)

## Limitations

* Upstream app still in beta.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/dendrite_ynh/issues
 * App website: https://matrix.org/docs/projects/server/dendrite
 * Upstream app repository: https://github.com/matrix-org/dendrite
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
or
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Dendrite for YunoHost

[![Integration level](https://dash.yunohost.org/integration/dendrite.svg)](https://dash.yunohost.org/appci/app/dendrite) ![Working status](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![Install Dendrite with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Dendrite quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Shipped version:** 0.13.1~ynh2
## :red_circle: Antifeatures

- **Beta software**: May contain changing or unstable features, bugs, and security vulnerability.

## Documentation and resources

* Official app website: <https://matrix.org/>
* Official admin documentation: <https://github.com/matrix-org/dendrite/tree/master/docs>
* Upstream app code repository: <https://github.com/matrix-org/dendrite>
* YunoHost documentation for this app: <https://yunohost.org/app_dendrite>
* Report a bug: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
or
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>

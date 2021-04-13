# Whitebophir for YunoHost

[![Integration level](https://dash.yunohost.org/integration/whitebophir.svg)](https://dash.yunohost.org/appci/app/whitebophir) ![](https://ci-apps.yunohost.org/ci/badges/whitebophir.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/whitebophir.maintain.svg)  
[![Install Whitebophir with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=whitebophir)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install whitebophir quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## License

This package is available under the license [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.html)

## Overview
This application implements a collaborative whiteboard. It is possible to create and use multiple whiteboards and share them with a simple link

**Shipped version:** 1.10.0

## Screenshots

![](https://user-images.githubusercontent.com/552629/59885574-06e02b80-93bc-11e9-9150-0670a1c5d4f3.png)

## Demo

* [Official demo](wbo.ophir.dev)

## Documentation

 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features
#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/whitebophir%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/whitebophir/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/whitebophir%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/whitebophir/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/whitebophir_ynh/issues
 * App website: https://wbo.ophir.dev/
 * Upstream app repository: https://github.com/lovasoa/whitebophir
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/whitebophir_ynh/tree/dev).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/whitebophir_ynh/tree/dev --debug
or
sudo yunohost app upgrade whitebophir -u https://github.com/YunoHost-Apps/whitebophir_ynh/tree/dev --debug
```

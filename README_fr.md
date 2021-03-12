# Whiteboard pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/whitebophir.svg)](https://dash.yunohost.org/appci/app/whitebophir) ![](https://ci-apps.yunohost.org/ci/badges/whitebophir.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/whitebophir.maintain.svg)  
[![Installer Whitebophir avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=whitebophir)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Whitebophir rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Cette application implémente un whiteboard collaboratif. Elle permet de créer et de partager un whiteboard en un seul lien 

**Version incluse :** 1.6.4

## Captures d'écran

![](https://user-images.githubusercontent.com/552629/59885574-06e02b80-93bc-11e9-9150-0670a1c5d4f3.png)

## Démo

* [Démo officielle](wbo.bophir.dev)

## Documentation

 * Documentation officielle : https://github.com/lovasoa/whitebophir/tree/prod

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/whitebophir%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/whitebophir/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/whitebophir%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/whitebophir/)

## Limitations

* Ne s'installe que à la racine d'un domaine
* Pas de support multi-instance

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/whitebophir_ynh/issues
 * Site de l'application : https://wbo.ophir.dev/
 * Dépôt de l'application principale : https://github.com/lovasoa/whitebophir
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/whitebophir_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/whitebophir_ynh/tree/testing --debug
ou
sudo yunohost app upgrade whitebophir -u https://github.com/YunoHost-Apps/whitebophir_ynh/tree/testing --debug
```

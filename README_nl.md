<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Dendrite voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/dendrite)](https://ci-apps.yunohost.org/ci/apps/dendrite/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/dendrite)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/dendrite)

[![Dendrite met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Dendrite snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Geleverde versie:** 0.14.1~ynh2
## :red_circle: Anti-eigenschappen

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Documentatie en bronnen

- Officiele website van de app: <https://matrix.org/>
- Officiele beheerdersdocumentatie: <https://github.com/element-hq/dendrite/tree/master/docs>
- Upstream app codedepot: <https://github.com/element-hq/dendrite>
- YunoHost-store: <https://apps.yunohost.org/app/dendrite>
- Meld een bug: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
of
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>

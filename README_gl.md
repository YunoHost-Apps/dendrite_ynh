<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Dendrite para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/dendrite.svg)](https://dash.yunohost.org/appci/app/dendrite) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![Instalar Dendrite con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Dendrite de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Versión proporcionada:** 0.13.7~ynh1
## :red_circle: Caraterísticas cuestionables

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Documentación e recursos

- Web oficial da app: <https://matrix.org/>
- Documentación oficial para admin: <https://github.com/matrix-org/dendrite/tree/master/docs>
- Repositorio de orixe do código: <https://github.com/matrix-org/dendrite>
- Tenda YunoHost: <https://apps.yunohost.org/app/dendrite>
- Informar dun problema: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>

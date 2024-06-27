<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Dendrite para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/dendrite.svg)](https://ci-apps.yunohost.org/ci/apps/dendrite/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![Instalar Dendrite con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDendrite rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Versión actual:** 0.13.7~ynh1
## :red_circle: Características no deseables

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Documentaciones y recursos

- Sitio web oficial: <https://matrix.org/>
- Documentación administrador oficial: <https://github.com/matrix-org/dendrite/tree/master/docs>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/matrix-org/dendrite>
- Catálogo YunoHost: <https://apps.yunohost.org/app/dendrite>
- Reportar un error: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
o
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>

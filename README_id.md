<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Dendrite untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/dendrite.svg)](https://ci-apps.yunohost.org/ci/apps/dendrite/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![Pasang Dendrite dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Dendrite secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Versi terkirim:** 0.13.8~ynh1
## :red_circle: Antifitur

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://matrix.org/>
- Dokumentasi admin resmi: <https://github.com/matrix-org/dendrite/tree/master/docs>
- Depot kode aplikasi hulu: <https://github.com/matrix-org/dendrite>
- Gudang YunoHost: <https://apps.yunohost.org/app/dendrite>
- Laporkan bug: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>

<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Dendrite dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/dendrite)](https://ci-apps.yunohost.org/ci/apps/dendrite/)
![Status działania](https://apps.yunohost.org/badge/state/dendrite)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/dendrite)

[![Zainstaluj Dendrite z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Dendrite na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Dostarczona wersja:** 0.14.1~ynh1
## :red_circle: Niepożądane funkcje

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://matrix.org/>
- Oficjalna dokumentacja dla administratora: <https://github.com/element-hq/dendrite/tree/master/docs>
- Repozytorium z kodem źródłowym: <https://github.com/element-hq/dendrite>
- Sklep YunoHost: <https://apps.yunohost.org/app/dendrite>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
lub
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>

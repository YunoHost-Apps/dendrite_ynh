<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Dendrite per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/dendrite.svg)](https://dash.yunohost.org/appci/app/dendrite) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![Installa Dendrite con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Dendrite su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Versione pubblicata:** 0.13.6~ynh2
## :red_circle: Anti-funzionalità

- **Software in versione alpha**: Questo software è all’inizio della sua fase di sviluppo. Potrebbe dunque essere instabile, contenere bug e vulnerabilità di sicurezza.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://matrix.org/>
- Documentazione ufficiale per gli amministratori: <https://github.com/matrix-org/dendrite/tree/master/docs>
- Repository upstream del codice dell’app: <https://github.com/matrix-org/dendrite>
- Store di YunoHost: <https://apps.yunohost.org/app/dendrite>
- Segnala un problema: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
o
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>

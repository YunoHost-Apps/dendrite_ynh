<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Dendrite pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/dendrite)](https://ci-apps.yunohost.org/ci/apps/dendrite/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/dendrite)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/dendrite)

[![Installer Dendrite avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Dendrite rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Dendrite est un serveur domestique Matrix de deuxième génération écrit en Go. Il entend fournir une alternative efficace, fiable et évolutive à Synapse :

### Caractéristiques

- Efficace : une petite empreinte mémoire avec de meilleures performances de base qu'un Synapse prêt à l'emploi.
- Fiable : implémente la spécification Matrix telle qu'écrite, en utilisant la même suite de tests que Synapse ainsi qu'une toute nouvelle suite de tests Go.
- Évolutif : peut fonctionner sur plusieurs machines et éventuellement évoluer vers des déploiements massifs de serveurs domestiques.


**Version incluse :** 0.14.1~ynh1
## :red_circle: Anti-fonctionnalités

- **Logiciel en version alpha **: Le logiciel est au tout début de son développement. Il pourrait contenir des fonctionnalités changeantes ou instables, des bugs, et des failles de sécurité.

## Documentations et ressources

- Site officiel de l’app : <https://matrix.org/>
- Documentation officielle de l’admin : <https://github.com/element-hq/dendrite/tree/master/docs>
- Dépôt de code officiel de l’app : <https://github.com/element-hq/dendrite>
- YunoHost Store : <https://apps.yunohost.org/app/dendrite>
- Signaler un bug : <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

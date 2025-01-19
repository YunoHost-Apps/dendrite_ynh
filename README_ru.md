<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Dendrite для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/dendrite)](https://ci-apps.yunohost.org/ci/apps/dendrite/)
![Состояние работы](https://apps.yunohost.org/badge/state/dendrite)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/dendrite)

[![Установите Dendrite с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Dendrite быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**Поставляемая версия:** 0.14.1~ynh1
## :red_circle: Анти-функции

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://matrix.org/>
- Официальная документация администратора: <https://github.com/element-hq/dendrite/tree/master/docs>
- Репозиторий кода главной ветки приложения: <https://github.com/element-hq/dendrite>
- Магазин YunoHost: <https://apps.yunohost.org/app/dendrite>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
или
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>

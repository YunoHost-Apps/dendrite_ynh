<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Dendrite

[![集成程度](https://dash.yunohost.org/integration/dendrite.svg)](https://ci-apps.yunohost.org/ci/apps/dendrite/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/dendrite.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/dendrite.maintain.svg)

[![使用 YunoHost 安装 Dendrite](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dendrite)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Dendrite。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Dendrite is a second-generation Matrix homeserver written in Go. It intends to provide an efficient, reliable and scalable alternative to Synapse:

### Features

- Efficient: A small memory footprint with better baseline performance than an out-of-the-box Synapse.
- Reliable: Implements the Matrix specification as written, using the same test suite as Synapse as well as a brand new Go test suite.
- Scalable: can run on multiple machines and eventually scale to massive homeserver deployments.


**分发版本：** 0.13.7~ynh1
## :red_circle: 负面特征

- **Alpha software**: Early development stage. May contain changing or unstable features, bugs, and security vulnerability.

## 文档与资源

- 官方应用网站： <https://matrix.org/>
- 官方管理文档： <https://github.com/matrix-org/dendrite/tree/master/docs>
- 上游应用代码库： <https://github.com/matrix-org/dendrite>
- YunoHost 商店： <https://apps.yunohost.org/app/dendrite>
- 报告 bug： <https://github.com/YunoHost-Apps/dendrite_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
或
sudo yunohost app upgrade dendrite -u https://github.com/YunoHost-Apps/dendrite_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>

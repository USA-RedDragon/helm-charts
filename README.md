# Kubernetes Helm Charts

[![Release](https://github.com/USA-RedDragon/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/USA-RedDragon/helm-charts/actions/workflows/release.yaml)
[![Renovate](https://img.shields.io/badge/Renovate-enabled-brightgreen?logo=renovatebot&logoColor=1DDEDD)](https://renovatebot.com)

The code is provided as-is with no warranties.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add usa-reddragon https://charts.mcswain.dev
```

You can then run `helm search repo usa-reddragon` to see the charts.

## Chart Overview

| Chart | Description |
| ----- | ----------- |
| [Generic App ](charts/app/) | A Helm chart for a generic Docker app |
| [# mariadb ](charts/mariadb/) | MariaDB using bjw-s common chart |
| [Palworld Server <img src='https://tech.palworldgame.com/img/logo.jpg' alt='palworld icon' width='18px' align='right' loading='lazy'>](charts/palworld/) | Helm chart for the palworld-server Docker image, deploys a dedicated PalWorld server to your Kubernetes cluster! |
| [# valkey ](charts/valkey/) | Valkey is an open source (BSD) high-performance key/value datastore that supports a variety workloads such as caching, message queues, and can act as a primary database. |

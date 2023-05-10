# helm-chart-repository

[![Linter Yaml](https://github.com/santander-group-global-cto/helm-chart-repository/actions/workflows/quality.yml/badge.svg)](https://github.com/santander-group-global-cto/helm-chart-repository/actions/workflows/quality.yml)


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
  helm repo add helm-chart-repository https://santander-group-global-cto.github.io/helm-chart-repository
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo helm-chart-repository` to see
the charts.

To install the fastapi chart:

```bash
    helm install my-configmap santander-group-global-cto/configmap
```
To uninstall the chart:

```bash
    helm delete my-configmap
```

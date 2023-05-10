# helm-chart-repository

[![Linter Yaml](https://github.com/jbenaventem/charts/actions/workflows/quality.yml/badge.svg)](https://github.com/jbenaventem/charts/actions/workflows/quality.yml)


## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
  helm repo add helm-chart-repository https://jbenaventem.github.io/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo helm-chart-repository` to see
the charts.

To install the fastapi chart:

```bash
    helm install my-configmap jbenaventem/configmap
```
To uninstall the chart:

```bash
    helm delete my-configmap
```


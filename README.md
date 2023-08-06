[![Release Charts](https://github.com/linjan2/helm-charts/actions/workflows/release.yml/badge.svg)](https://github.com/linjan2/helm-charts/actions/workflows/release.yml)

Add the repo as follows:

```sh
helm repo add linjan2 https://linjan2.github.io/helm-charts
helm repo update
helm search repo linjan2
```

To install the `CHARTNAME` chart:

```sh
helm install RELEASENAME linjan2/CHARTNAME
```

To uninstall the chart:

```sh
helm delete RELEASENAME
```

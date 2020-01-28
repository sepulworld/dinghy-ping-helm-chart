# dinghy-ping-helm-chart
Helm chart to install Dinghy Ping

# Install repo

```helm repo add dinghy-ping https://sepulworld.github.io/dinghy-ping-helm-chart/```


## Build new chart version

```
vi helm-chart-sources/dinghy-ping/Chart.yaml
helm package helm-chart-sources/dinghy-ping/
helm repo index --url https://sepulworld.github.io/dinghy-ping-helm-chart/ .
```

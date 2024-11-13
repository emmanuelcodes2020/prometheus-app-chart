# prometheus-app-chart

This Helm chart deploys the Prometheus application on a EKS Cluster

Prerequisites:
1) EKS Cluster (AWS) : must be set up first 
2) Helm must be created with the "helm create repo"



## Installing the Chart

To install the chart with the release name : prometheus-app-release

```

helm install prometheus-app-release  ./prometheus-app-chart

```


## Upgrading your Chart

To upgrade the chart with the release name : prometheus-app-release

```

helm upgrade prometheus-app-release  ./prometheus-app-chart

```

## Installing the Chart with values.yaml

To install the chart with the release name : prometheus-app-release 

```

helm install prometheus-app-release ./prometheus-app-chart   --Values ./prometheus-app-chart/values.yaml

```



## Uninstalling the Chart

To uninstall the prometheus-app-release deployment:

```

helm uninstall prometheus-app-release   ./prometheus-app-chart

```


# Install

Add helm rpeo

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

Upate repo

```
helm repo update
```

Create namespace

```
kubectl create namespace monitoring
```

Deploy

```
helm install -n monitoring prometheus prometheus-community/kube-prometheus-stack -f values.yaml
```

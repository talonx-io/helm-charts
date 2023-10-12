# Longbow Kubernetes Agent helm charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up, add the repo using:

```
helm repo add longbow-helm https://talonx-io.github.io/helm-charts
```

To see the charts run:
```
helm search repo longbow-helm
```

And to install:
```
helm install release-name longbow-helm/longbow-kubernetes-agent
```

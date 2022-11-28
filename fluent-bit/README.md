## Installation

To add the ```fluent``` helm repo, run:
```sh
helm repo add fluent https://fluent.github.io/helm-charts
```

To install a release named ```fluent-bit```, run:

```sh
helm upgrade --install fluent-bit fluent/fluent-bit -f fluentbit-values.yaml
```

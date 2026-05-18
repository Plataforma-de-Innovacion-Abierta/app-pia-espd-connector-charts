# app-pia-espd-connector-charts

Este repositorio se utilizará para publicar los Helm Charts del conector, permitiendo que los participantes puedan desplegarlo en sus propias infraestructuras Kubernetes de forma autónoma, versionada y trazable.

## Uso

```bash
helm repo add pia https://plataforma-de-innovacion-abierta.github.io/app-pia-espd-connector-charts
helm repo update
helm pull pia/edc-ui-umbrella --version 0.5.4-patch.9
```

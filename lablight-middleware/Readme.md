# Installing lablight-middleware (middlware)

API Backend (Middleware) - image lablight-middleware
Project: https://github.com/nstarx/shi-api

## NStarX

```
helm install lablight-middleware . -f values_nstarx.yaml -n lablight-dev
helm upgrade lablight-middleware . -f values_nstarx.yaml -n lablight-dev
helm uninstall lablight-middleware -n lablight-dev
```

## SHI

```
helm install lablight-middleware . -f values_shi.yaml -n genai-cust-25178556
helm upgrade lablight-middleware . -f values_shi.yaml -n genai-cust-25178556
helm uninstall lablight-middleware -n genai-cust-25178556
```
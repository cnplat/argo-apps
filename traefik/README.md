# traefik

## Github

```
kubectl create ns traefik
kubectl apply -n traefik -f https://raw.githubusercontent.com/cnplat/yaml/main/traefik/traefik-crd.yaml
kubectl apply -n traefik -f https://raw.githubusercontent.com/cnplat/yaml/main/traefik/traefik-ingress-controller.yml
```

## Gitee

```shell
kubectl create ns traefik
kubectl apply -n traefik -f https://gitee.com/cnplat/yaml/raw/main/traefik/traefik-crd.yaml
kubectl apply -n traefik -f https://gitee.com/cnplat/yaml/raw/main/traefik/traefik-ingress-controller.yml
```
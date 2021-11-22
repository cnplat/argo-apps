# traefik

```shell
# 创建命名空间
kubuctl create namespace traefik
# 创建 argocd app
argocd app create traefik --repo https://github.com/cnplat/architect.git --path traefik --dest-server https://kubernetes.default.svc --dest-namespace traefik
```
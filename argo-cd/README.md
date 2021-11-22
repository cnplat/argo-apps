# argo-cd

## Github

```shell
kubectl create ns argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/application-crd.yaml
kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/appproject-crd.yaml
kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/install.yaml
# 获取argo-cd admin密码
~ kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
nbTjEbeMQQlzcoZv
# Visit UI: https://<your server ip>:30810/
```

## Gitee

```shell
kubectl create ns argocd
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/application-crd.yaml
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/appproject-crd.yaml
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/install.yaml
# 获取argo-cd admin密码
~ kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
nbTjEbeMQQlzcoZv
# Visit UI: https://<your server ip>:30810/
```

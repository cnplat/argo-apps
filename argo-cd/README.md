# argo-cd

## Github

```shell
kubectl create ns argocd
# 普通安装
kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/install.yaml
# 高可用安装
# kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/ha-application-crd.yaml
# kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/ha-appproject-crd.yaml
# kubectl apply -n argocd -f https://raw.githubusercontent.com/cnplat/yaml/main/argo-cd/ha-install.yaml
# 获取argo-cd admin密码
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
nbTjEbeMQQlzcoZv
# Visit UI: https://<your server ip>:30810/
```

## Gitee

```shell
kubectl create ns argocd
# 普通安装
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/install.yaml
# 高可用安装
# kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/ha-application-crd.yaml
# kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/ha-appproject-crd.yaml
# kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/argo-cd/ha-install.yaml
# 获取argo-cd admin密码
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
nbTjEbeMQQlzcoZv
# Visit UI: https://<your server ip>:30810/
```

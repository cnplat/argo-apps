# kubernetes-dashboard

## Github

```shell
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/kubernetes-dashboard/kubernetes-dashboard.yaml
kubectl apply -f https://raw.githubusercontent.com/cnplat/yaml/main/kubernetes-dashboard/dashboard-adminuser.yaml
# 获取登录token
kubectl describe secret admin-user --namespace=kube-system
# Visit: https://<your server ip>:30801/
```

## Gitee

```shell
kubectl create ns argocd
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/kubernetes-dashboard/kubernetes-dashboard.yaml
kubectl apply -n argocd -f https://gitee.com/cnplat/yaml/raw/main/kubernetes-dashboard/dashboard-adminuser.yaml
# 获取登录token
kubectl describe secret admin-user --namespace=kube-system
# Visit: https://<your server ip>:30801/
```
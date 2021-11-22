# kubernetes-dashboard

```shell
kubectl apply -f https://raw.githubusercontent.com/cnplat/argo-apps/main/kubernetes-dashboard/kubernetes-dashboard.yaml
kubectl apply -f https://raw.githubusercontent.com/cnplat/argo-apps/main/kubernetes-dashboard/dashboard-adminuser.yaml
# 获取登录token
kubectl describe secret admin-user --namespace=kube-system
# Visit: https://<your server ip>:30801/
```
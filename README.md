#yaml

## docker 私有库
```shell
kubectl create secret docker-registry docker_ccr_secret --docker-server=ccr.ccs.tencentyun.com --docker-username=11577870 --docker-password=liqiai88
```
yaml配置
```yaml
      imagePullSecrets:
        - name: docker-ccr-secret
      containers:
      ....
```
## Kubernetes1.13.1集群环境部署


### 文档目录
+ [kubernetes1.13.1+etcd3.3.10+flanneld0.10集群部署](https://github.com/minminmsn/k8s1.13/blob/master/kubernetes/kubernetes1.13.1%2Betcd3.3.10%2Bflanneld0.10%E9%9B%86%E7%BE%A4%E9%83%A8%E7%BD%B2.md)
+ [kubernetes1.13.1部署kuberneted-dashboard v1.10.1](https://github.com/minminmsn/k8s1.13/blob/master/kubernetes-dashboard-amd64/Kubernetes1.13.1%E9%83%A8%E7%BD%B2Kuberneted-dashboard%20v1.10.1.md)
+ [kubernetes1.13.1部署coredns](https://github.com/minminmsn/k8s1.13/blob/master/coredns/kubernetes1.13.1%E9%9B%86%E7%BE%A4%E9%83%A8%E7%BD%B2coredns.md)
+ [kubernetes1.13.1部署ingress-nginx并配置https转发dashboard]( https://github.com/minminmsn/k8s1.13/blob/master/ingress-nginx/kubernetes1.13.1%E9%83%A8%E7%BD%B2ingress-nginx%E5%B9%B6%E9%85%8D%E7%BD%AEhttps%E8%BD%AC%E5%8F%91dashboard.md)
+ [kubernetes1.13.1部署metrics-server0.3.1](https://github.com/minminmsn/k8s1.13/blob/master/metrics-server/kubernetes1.13.1%E9%83%A8%E7%BD%B2metrics-server0.3.1.md)
+ [kubernetes1.13.1集群使用ceph rbd存储块](https://github.com/minminmsn/k8s1.13/blob/master/volumes/rbd/k8s%E9%9B%86%E7%BE%A4%E4%BD%BF%E7%94%A8ceph%20rbd%E5%9D%97%E5%AD%98%E5%82%A8.md)
+ [kubernetes1.13.1集群结合ceph rbd部署最新版本jenkins](https://github.com/minminmsn/k8s1.13/blob/master/jenkins/k8s1.13.1%E9%9B%86%E7%BE%A4%E7%BB%93%E5%90%88ceph%20rbd%E9%83%A8%E7%BD%B2%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%ACjenkins.md)

### 演示效果如下
https://k8s.minminmsn.com

输入token

```
eyJhbGciOiJSUzI1NiIsImtpZCI6IiJ9.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJhZG1pbi10b2tlbi01ajJ2ZiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJhZG1pbiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjZiMGIwYzAwLTBiNDUtMTFlOS04NWZlLTUyNTQwMDg5YjJiNiIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTphZG1pbiJ9.TkpDjrLRiulxgOjm6AWGeiCIRDHTeCUR87lme6cY4YnLFFyC1MTiw2JWvTYeksYvGcaEIlope97Don-zk5oNn5q1HYgwZeY844KXRyYSQ3vVlC1lg1xMvIZSrfLuK7ek-jHB_pAxE1S2KGfjg1srfdDRHBHgBEaOIMB6DrkJvVMI-hVHxtL5ctwCpZ1iIo1XVyu83SgMUz2HnVE1TST8NL-s0KtR0rnz-Ve4YvJZ1_Jj9hKvMblS_APWetcqT0Trsf-VuZgfKxuRcOmOkFFRKV-ZSwU7i9umQabIWhD6xZ7dTsvogGCx4o0kgBOLwrwj-pUbgAyu7pmbbAbjOJ06cQ
```

> [![](https://i.loli.net/2019/01/02/5c2c7ce87af87.png)](https://i.loli.net/2019/01/02/5c2c7ce87af87.png)

### 随喜赞叹
> ![](https://github.com/minminmsn/k8s1.13/blob/master/minminmsn.jpg)
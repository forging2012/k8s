# k8s
Kubernetes images.

## v1.12.0 images

### 需要下载的镜像
```
k8s.gcr.io/kube-apiserver:v1.12.0
k8s.gcr.io/kube-scheduler:v1.12.0
k8s.gcr.io/kube-controller-manager:v1.12.0 
k8s.gcr.io/kube-proxy:v1.12.0
k8s.gcr.io/etcd:3.2.24 
k8s.gcr.io/pause:3.1
k8s.gcr.io/coredns:1.2.2
```

### 替换成加速镜像
```
docker pull forging2012/k8s:kube-apiserver-v1.12.0
docker pull forging2012/k8s:kube-scheduler-v1.12.0
docker pull forging2012/k8s:kube-controller-manager-v1.12.0 
docker pull forging2012/k8s:kube-proxy-v1.12.0
docker pull forging2012/k8s:etcd-3.2.24 
docker pull forging2012/k8s:pause-3.1
docker pull forging2012/k8s:coredns-1.2.2
```

```
docker pull forging2012/k8s:kube-apiserver-v1.12.0 \
&& docker tag forging2012/k8s:kube-apiserver-v1.12.0 k8s.gcr.io/kube-apiserver:v1.12.0 \
&& docker pull forging2012/k8s:kube-scheduler-v1.12.0 \
&& docker tag forging2012/k8s:kube-scheduler-v1.12.0 k8s.gcr.io/kube-scheduler:v1.12.0 \
&& docker pull forging2012/k8s:kube-controller-manager-v1.12.0 \
&& docker tag forging2012/k8s:kube-controller-manager-v1.12.0 k8s.gcr.io/kube-controller-manager:v1.12.0 \
&& docker pull forging2012/k8s:kube-proxy-v1.12.0 \
&& docker tag forging2012/k8s:kube-proxy-v1.12.0 k8s.gcr.io/kube-proxy:v1.12.0 \
&& docker pull forging2012/k8s:etcd-3.2.24 \
&& docker tag forging2012/k8s:etcd-3.2.24 k8s.gcr.io/etcd:3.2.24 \
&& docker pull forging2012/k8s:pause-3.1 \
&& docker tag forging2012/k8s:pause-3.1 k8s.gcr.io/pause:3.1 \
&& docker pull forging2012/k8s:coredns-1.2.2 \
&& docker tag forging2012/k8s:coredns-1.2.2 k8s.gcr.io/coredns:1.2.2
```

# END

# KIND 

```shell
kind create cluster \
    --config /home/project/k8s/config.yaml \
    --image registry.cn-hangzhou.aliyuncs.com/smartide/nestybox-kindestnode:v1.20.7


kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-mysql:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-nacos:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-redis:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-gateway:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-auth:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-modules-system:v1
kind load docker-image registry.cn-hangzhou.aliyuncs.com/boathouse/ruoyi-nginx:v1
```
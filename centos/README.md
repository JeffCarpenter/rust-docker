# rust-centos

基于`centos:centos7.2.1511`的基础进行构建`rust-1.39.0`的运行环境。

## 使用说明

### 下载镜像

```docker
docker pull wolfdeng/rust-centos:1.39.0
```

### 启动容器

```bash
docker run -it --rm -v ${pwd}:/source wolf.deng/rust-centos:1.39.0 bash
```

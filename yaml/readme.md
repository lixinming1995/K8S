# 各类配置文件展示

1. Pod：最基本的容器对象，一个Pod可以包含一个或多个容器。
2. Service：为一组Pod提供稳定的访问地址和负载均衡功能。
3. Deployment：管理Pod的副本数和版本，支持滚动升级和回滚等操作。
4. ConfigMap：存储配置数据的键值对，可以被Pod挂载为容器内部的环境变量或卷。
5. Secret：存储敏感数据的键值对，如密码、证书等，会被加密后存储。
6. Namespace：用于将资源划分为多个虚拟集群，可以实现资源隔离和访问控制。
7. ServiceAccount：为Pod提供访问Kubernetes API的身份认证信息。

## Docker-micro-services Tutorial

Docker 一个典型的应用就是在 Docker 容器上运行一个`OS, Software 或 APP`. 如下图所示：

但是对于一个大型的 Application，如一个大型的电商网站有下面的几个部分。维护，发布都比较麻烦。

一个新的趋势是使用微服务来做这个电商网站，那么我们的框架就是如下所示了。 


我们 website 单独运行在一个容器内，而其它每个服务都单独运行在一个容器中。每种服务可以用不同的语言来实现。


### Web-store Application

#### Product Service

我们先来用 python 来实现我们 Product service.


我们现在用 `docker-compse` 来管理我们的 docker 就十分方便了。在项目根目录下写一个 `docker-compose.yml` 文件。 配置如下:


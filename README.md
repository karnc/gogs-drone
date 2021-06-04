# gogs-drone
#### gogs drone docker-compose running
#### 说明
- 首先创建数据库gogs和drone，gogs和drone服务需要使用到
- 初始化安装gogs时，注意数据库主机、域名、SSH端口号和应用URL配置

#### 拷贝并命名配置文件（Windows系统请用`copy`命令），启动：
```
$ cd gogs-drone                                     # 进入项目目录
$ cp env.sample .env                                # 复制环境变量文件
$ cp docker-compose.sample.yml docker-compose.yml   # 复制 docker-compose 配置文件。
$ docker-compose up                                 # 启动
```

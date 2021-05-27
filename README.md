# gogs-drone
### gogs drone docker-compose running
## 说明
- 首先创建数据库gogs和drone，gogs和drone服务需要使用到
- 初始化安装gogs时，注意数据库主机、域名、SSH端口号和应用URL配置
- gogs域名和应用URL不要使用localhost，不然在drone自动部署时会出现clone不了gogs git仓库
- gogs域名和应用URL可使用公网IP或域名，本地windows docker搭建可查看docker hots域名使用
- 百度上很多搭建教程，可自行百度参考

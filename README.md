## 启动

进入目录，运行命令 `docker-compose up -d` 即可完成disconf服务启动。

## 停止
进入目录，运行命令 `docker-compose down` 停止服务。

## 目录说明
-  initdb.d：disconf所用到的数据库表定义语句（mysql）
-  web：disconf软件包
	- war： disconf服务的所有静态网页以及动态服务实现（通过源码编译生成）
	- nginx.conf: nginx代理服务配置
-  **docker-compose.yml**：disconf服务配置（核心配置文件）
- data：服务启用后生成
	- mysql：数据库文件夹（自动生成）
	- redis：redis缓存文件夹（自动生成）

# docker-lnmp

docker线下开发环境，包含 php+mysql,可配置ssl证书

## How to use?
- 1.多项目配置, 复制并修改./services/nginx/conf.d/api.qizuang.com.conf 中 root配置对应的项目位置
- 2.确保 ./services/php/extensions/install.sh 的换行方式 为 LF(UNIX)
- 3.命令行中输入 docker-compose up ,都成功即可

## 目录
- services:各个程序的配置文件和Dockerfile文件
- logs:日志文件目录
- www:项目文件目录
- .env:环境变量配置目录
- .docker-compose.yml 文件
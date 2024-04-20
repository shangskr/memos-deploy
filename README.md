# memos-deploy
在serv00等某些免费平台部署Memos

## Serv00部署教程（推荐版本）
新建并进入Memos的工作目录：
```
mkdir -p ~/domains/memos && cd ~/domains/memos
```
接着使用一键命令安装Memos：
```
wget -O memos-freebsd.sh https://raw.githubusercontent.com/SinzMise/memos-deploy/main/memos-serv00-0182.sh && sh memos-freebsd.sh
```
然后运行./memos --data ./db --mode prod --port （在Serv00放行的端口）即可使用

## Serv00部署教程（最新版本）
新建并进入Memos的工作目录：
```
mkdir -p ~/domains/memos && cd ~/domains/memos
```
接着使用一键命令安装Memos：
```
wget -O memos-freebsd.sh https://raw.githubusercontent.com/SinzMise/memos-deploy/main/memos-serv00.sh && sh memos-serv00.sh
```
然后运行./memos --data ./db --mode prod --port 在Serv00放行的端口  
即可使用

## 使用方法
cd ~/domains/memos
sh memos-freebsd.sh
./memos --data ./db --mode prod --port 19862（端口）
然后用pm2挂起

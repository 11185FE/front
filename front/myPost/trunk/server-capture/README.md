# 邮印象 nodejs 截图环境部署步骤

------------------

* 创建人：古雄洪      
* 创建时间： 2016/10/14

-------------------

[TOC]

## nodejs 环境安装
```bash
# 解压 nodejs 程序文件
$ tar xf node文件名 -C /usr/local/ 	
$ cd /usr/local/
$ mv node文件名/ nodejs
# 软连接 node、npm 执行程序
$ ln -s /usr/local/nodejs/bin/node /usr/local/bin    
$ ln -s /usr/local/nodejs/bin/npm /usr/local/bin
# 检查是否配置成功
$ node -v  # v4.6.0
$ npm -v  # 2.15.9
```

## nodejs 全局依赖安装
```bash
# 在 profile 末尾插入 nodejs 全局依赖包执行环境
$ vi /etc/profile
# 插入内容为：
export NODE_PATH=/usr/local/nodejs/bin
export PATH=${PATH}:${NODE_PATH}
echo "PATH=\${PATH}:${NODE_PATH}"

# source 一下 profile
$ source /etc/profile

# npm i xxx -g 安装全局依赖包，安装完毕后都可以使用  xxx -v 查看是否安装成功
$ npm i cpm -g  # 国内淘宝出品 npm 资源加载环境 cnpm 安装
$ npm i babel-cli -g # es6语法运行环境
$ npm i pm2 -g # nodejs 进程守护工具
$ npm i phantomjs -g # 虚拟webkit浏览器工具
```

## 字体安装
```bash
$ mkdir /usr/share/fonts/ipost
$ cd 字体文件目录
$ cp chinese.msyh.ttf  /usr/share/fonts/ipost
$ cd /usr/share/fonts/ipost
$ mkfontscale
$ mkfontdir
$ fc-cache

# 查看是否安装成功
$ fc-list :lang=zh
# ubuntu下安装正确返回
# /usr/share/fonts/ipost/chinese.msyh.ttf: Microsoft YaHei,微软雅黑:style=Regular,Normal,obyčejné,Standard,Κανονικά,Normaali,Normál,Normale,Standaard,Normalny,Обычный,Normálne,Navadno,Arrunta
```

## 截屏程序执行
```bash
$ cd 项目目录
# 安装项目依赖
$ cnpm i
# 使用 pm2 进程守护开启程序
$ pm2 start app.json
# 查看程序运行情况
$ pm2 log
```

> 该程序使用 pm2 进行进程守护，下面列一下 pm2 的基本使用方式

```bash
# pm2 启动程序
$ pm2 start xxx
# 查看 pm2 内运行的 node 程序
$ pm2 list
# 查看 log 内容
$ pm2 log
# 重启pm2所有node程序
$ pm2 restart all
# 重启对应项目
$ pm2 restart 程序pid # pid 可以在 pm2 list里面找
# 杀掉所有node程序运行进程
$ pm2 delete all
# 杀掉对应node进程
$ pm2 delete pid
```

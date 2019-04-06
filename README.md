# Aweekcouple
一周情侣报名网页系统



系统需要：Centos 7.x or 其他linux 发行版。
环境：Mongodb nodejs 


在原项目上改之：https://github.com/LuXuanqing/food-energy-activity-entry

学校社团的一个活动，用于该活动的网上报名。  
使用Node.js + Express + MongoDB搭建的网站。没有使用Pug模板，而是在客户端使用了Vue来渲染。
## Usage
```
在cetos 命令行下运行：
$yum -y install nodejs    
$yum -y install Mongodb  //安装数据库
$yum -y install wget    //如果服务器没有的话手动安装wget
$yum -y install unzip   //如果服务器没有的话手动安装unzip
$wget https://github.com/tokyohost/Aweekcouple/archive/master.zip
$unzip master.zip
$cd 解压目录
$ npm install
$ node app.js
```
默认运行在80端口  
通过http://localhost/food-energy/entry.html 进入报名页面，  
http://localhost/food-energy/1314admin.html 查看报名单。

## 后台：

[![capture_20190406230921791.bmp](https://i.loli.net/2019/04/06/5ca8c12f17a2b.bmp)](https://i.loli.net/2019/04/06/5ca8c12f17a2b.bmp)

## 填表：

[![capture_20190406230609407.bmp](https://i.loli.net/2019/04/06/5ca8c12f7bb5a.bmp)](https://i.loli.net/2019/04/06/5ca8c12f7bb5a.bmp)

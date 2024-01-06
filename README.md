# OPOJFE

分模块设计

1.导航栏：登录和注册
2.首页：公告显示
3.题库页
4.测评页
5.讨论页
6.题解页
7.排名页
8.管理员页

## 使用 Vue3 + Vite + ElementUI

## 文件结构

node_modules              # 通过 npm install 下载安装的项目依赖包
|-- public                # 存放静态资源公共资源
 |-- index.html           # 首页入口.html文件
|-- src                   # 项目开发主要文件
    |-- assest            # 静态文件
    |-- axios             # 存放axios配置，实现对后端发送请求
    |-- components        # 存放组件
    |-- pages             # 界面组件
    |-- router            # 存放路由配置，实现界面跳转
    |-- store             # 存放vuex配置
    |-- App.vue           # 根组件
    |-- main.js           # 入口文件
    |-- package.json      # 项目配置和包管理文件（项目依赖和技术）
    |-- vite.config.json  # 项目配置信息：跨域proxy代理

## nginx使用

配置文件：/etc/nginx/nginx.conf

nginx -t方法查看配置文件出错的地方。
systemctl reload nginx 修改配置文件后重启nginx
sudo service nginx stop 关闭 nginx 服务
sudo service nginx start 启动 nginx 服务
C:\Windows\System32\drivers\etc\hosts 文件中配置本地的ip和域名
测试：访问www.opoj.top

## windows搭建vue开发环境
1.安装node.js
2.安装vue-cli
3.创建vue项目 vue create OPOJFE
4.运行vue项目 cd vue-demo
             npm run serve
5.在浏览器中打开 http://localhost:8080/ 















    

    

    

    

    

    

    

    

    

    

    

    

    

    

    
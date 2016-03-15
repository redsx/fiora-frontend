# fiora-frontend

Fiora聊天室前端

## 技术栈

* 语言: JavaScript ES6, HTML5, CSS3
* 框架: Koa, React, Redux, React-Router
* 工具:   
    1. webpack
    2. babel
    3. amazeui-react
    4. antd
    5. html5-desktop-notifications
    6. koa-send
    7. koa-static
    8. moment
    9. sails.io.js
    
## 安装

本项目依赖[node.js](http://npm.taobao.org/mirrors/node) v5.4 以上环境, 请下载与您的系统相对应的版本安装.  

1. 克隆项目 `git clone https://github.com/yinxin630/fiora-frontend`
2. 进入项目目录 `cd fiora-frontend`
3. 安装依赖库 `npm install`
4. 修改配置, 编辑`config.js`, 设置端口`port`, 设置后端地址`server`
5. 使用webpack打包文件, 执行`./node_module/.bin/webpack` 
6. 运行项目 `node app.js`
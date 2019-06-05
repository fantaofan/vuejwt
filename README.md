## jwt(jsonwebtoken)认证

1. 创建文件夹 并在文件夹下面运行命令 npm init -y | npm 一键初始化
2. 下载需要使用的包 npm install express body-parser cors jsonwebtoken - 包的作用 body-parser 解析数据 cors cors 跨域 jsonwebtoken jwt 认证用的

## node 启动方式

1. Code Runner vscode 插件
2. 命令行 node + 文件名
3. nodemon npm install nodemon -g |nodemon + 文件名 node 文件有修改就会自动启动

## vue 结合 jwt

1. npm install iview --save
2. 请求的没完成之前有遮罩 请求完成之后隐藏
3. 每次都会传入一个 url 发请求时我们用队列存储这个 url 每次响应回来之后我们删除 url 一次 url 不在有了表示所有请求结束了

## 使用

npm install 运行 npm run serve 启动客户端 cd mock | node app.js 运行服务端

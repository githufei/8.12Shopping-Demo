
# 启动方式:
## sever启动方式:
本项目的server已经真实运行在阿里云服务器上。
如果遇到服务器出错不可用，可以启动本地的server,使用命令`node server.js`,同时要把客户端ajax请求的ip切换成`localhost:3333`;
在server下的database目录下,使用命令`node writeDataToDB.js`，可以把商品信息写入到MongoDB数据库。

## 客户端启动方式：
```
npm start 
```



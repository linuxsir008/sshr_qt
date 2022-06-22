## 本软件实现的功能，效果类似于 ssh -R 38080:localhost:8080
<br/>

## 测试环境 centos 7

<br/>

# 服务端设定
## 服务器启动  ./sshr_server_qt 65532 server_uuid
### 服务器端 目前没有配置文件 ，启动时指定端口 和 server_uuid(可以随便填)

<br/>

# 客户端设定
## 客户端启动 ./sshr_client_qt 121.17.6.33 65532 sshr.conf server_uuid
### 客户端启动时 指定服务器的ip 、端口、 配置文件、 server_uuid(和服务器程序保持一致)
### 客户端有配置文件 sshr.conf ， 可以有多行，示例：

38080 8080


<br/>
 
# 测试看看
## 客户端启动后，和服务器端建立连接后， 服务器就会监听 38080端口（客户端配置文件中有设定）
## 当访问服务器端的 38080端口，就会访问 到客户端电脑的8080端口。


<br/>
###　闲鱼源码购买
【闲鱼】https://m.tb.cn/h.fELHadj?tk=7BLd2MBJJ3C「我在闲鱼发布了【qt 内网穿透系统】」
点击链接直接打开

<br/>
### 需要源码请联系 , 另有java 内网穿透的　服务器和客户端源码
### weixin
![image](https://www.wujiatong.group/weixin.jpg)

<br/>

### qq
2377572461





 

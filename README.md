# Pi_OPQBot

###### 什么是OPQBot? 

跨平台 QQ机器人 框架 原生 高效 迸发 Lua Plugin 只有你想不到。



### 树莓派安装 OPQBot

1.⚠️ 授权登陆此网站换取Token [Gitter Developer](https://developer.gitter.im/apps)

2.下载二进制包，树莓派选择linux_arm.tar.gz包下载。[下载地址](https://gitter.im/OPQBOT/OPQ)。也可下载apk文件夹内压缩包，不过不保证保持最新。（3.0.8版本）

3.解压缩，**填写配置文件CoreConf.conf 配置Token**

~~~~
 #自定义监听服务端口
  Port = "0.0.0.0:8888"
  #工作线程 默认50
  WorkerThread = 50
  #IOTBOT版本
  IOTQQVer = "v3.0.0"
  #Gitter Token
  Token = ""
~~~~

4.进入解压缩之后文件夹内执行命令**`./IOTQQ` 默认开启8888端口作为WebSokcet/WebApi的服务端口**

###### 首次登陆会拉取部分脚本并有详细输出 当出现 Everything is ok! 说明服务就绪 获取登陆二维码 访问Url http://IP:PORT/v1/Login/GetQRcode 扫码登陆即可

![login](https://github.com/ZhangFaCai/Pi_OPQBot/blob/master/img/login.png)


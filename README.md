# ServerStatus-Hotaru
云探针、多服务器探针、云监控、多服务器云监控

基于ServerStatus-Toyo最新版本稍作修改，不太会脚本什么的，前端也垃圾。见谅

Test v0.021：头图来源：Pixiv：72725286

模板来自：<https://www.hostloc.com/thread-494384-1-1.html>

以及：<https://www.hostloc.com/thread-493783-1-1.html>

稍作修改，多了个Region调用区域旗帜。

##BlueSkyXN的微调版本
https://github.com/BlueSkyXN/ServerStatusProber

## 安装方法

请见：

服务端：

```bash
wget https://raw.githubusercontent.com/BlueSkyXN/ServerStatusProber/master/status.sh
bash status.sh s
```

客户端：

```
bash status.sh c
```

## 修改方法

如果你使用Toyo版本或原版本，请备份你的config文件并重新编译安装本版本服务端

配置文件：/usr/local/ServerStatus/server/config.json备份并自行添加Region

```json
{
   "username": "Name",
   "password": "Password",
   "name": "Your Servername",
   "type": "KVM",
   "host": "None",
   "location": "洛杉矶",
   "disabled": false ,
   "region": "US"
  },
```

替换配置文件，重启ServerStatus

## 效果演示（图源阿里图床，另也备份在本程序仓库的demo文件夹内）

![](https://ae01.alicdn.com/kf/H428b36c07f4748b1a9d6b3836238e176I.png)

![](https://ae01.alicdn.com/kf/H181c07c813ff4f5888856be2c45e47e95.png)

![](https://ae01.alicdn.com/kf/H0f85cc70f93d4caca4f6f3ae472eb9c2b.png)

![](https://ae01.alicdn.com/kf/Ha374a587b1a845f0b4826f9ff94245223.png)

![](https://ae01.alicdn.com/kf/H968f64e5b1914a30bcbe3477f144a0dcG.png)


当然前端可以自己自定义。

## 相关开源项目 ： 
* ServerStatus-Toyo：https://github.com/ToyoDAdoubiBackup/ServerStatus-Toyo
* ServerStatus：https://github.com/BotoX/ServerStatus
* mojeda's ServerStatus: https://github.com/mojeda/ServerStatus
* BlueVM's project: http://www.lowendtalk.com/discussion/comment/169690#Comment_169690

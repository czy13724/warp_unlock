# 【刷 WARP IP】 - 为 WARP 解锁流媒体而生
Born to make stream media unlock by WARP 

* * *

# 目录

- [更新信息和 TODO](README.md#更新信息和-todo)
- [脚本特点](README.md#脚本特点)
- [运行脚本](README.md#运行脚本)
- [鸣谢](README.md#鸣谢下列作者的文章和项目)

* * *

## 更新信息和 TODO
TODO:~1. Improve the architecture first, so that adding detection items in the future can be faster, more scalable and reusable; 2. Add other unlocking methods; 3. In addition to the original Netflix, add other unlocking support such as Disney+;~ 4. Check Unlock socks5 support for mainstream scripts ~5.Running log file~
   
待更新: ~1.先完善架构，以便日后增加检测项能更快捷，更具扩展性和复用性; 2.增加其他解锁方式; 3.除原有的 Netflix 外，增加 Disney+ 等其他解锁支持;~ 4.查解锁主流脚本的 socks5 支持(如作者支持就不做改了，直接引用) ~5.运行日志~

2022.1.29 1.02

2022.1.28 1.01 1. Add two ways to unlock; 2. Add running logs file 1. 增加两种解锁方式; 2. 加入运行日志
```
2022-01-29 10:44:12. IP:8.26.176.157
2022-01-29 10:44:20. Netflix: No
2022-01-29 10:44:26. Netflix: No
2022-01-29 10:44:33. Netflix: No
2022-01-29 10:44:39. Netflix: No
2022-01-29 10:44:46. Netflix: Yes
2022-01-29 10:44:47. Disney+: Yes
```

beta 2022.1.26 Media unlock daemon. Check it every 5 minutes. If unlocked, the scheduled task exits immediately. If it is not unlocked, it will be swiped successfully in the background. Advantages: Minimized use of system resources. ~Disadvantage: Can't see the results as intuitively as screen~

## 脚本特点
* 支持多种主流串流影视检测，可以单选或多选
* 多种方式解锁: 1.每 5 分钟检测一次状态; 2. screen 后台运行; 3. nohup & 后台运行 (已经是天花板，有本事来 [issue](https://github.com/fscarmen/warp_unlock/issues) 挑战)
* 支持 WARP Socks5 Proxy 检测和更换 IP 
* 日志输出

<img src="https://user-images.githubusercontent.com/62703343/151590856-7957f0fa-c6dd-4b83-9425-f6a2eb1ca53e.png" width="80%" />

## 运行脚本

```
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/warp_unlock/main/unlock.sh)
```

## 鸣谢下列作者的文章和项目

互联网永远不会忘记，但人们会。

技术文章和相关项目（排名不分先后）:
* luoxue-bot 的成熟作品: https://github.com/luoxue-bot/warp_auto_change_ip
* lmc999 的成熟作品: https://github.com/lmc999/RegionRestrictionCheck

服务提供（排名不分先后）:
* CloudFlare Warp(+): https://1.1.1.1/
* WGCF 项目原作者: https://github.com/ViRb3/wgcf/
* 获取公网 IP 及归属地查询: https://ip.gs/
* 统计PV网:https://hits.seeyoufarm.com/

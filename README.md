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

2022.1.30 1.03 1. Suppport pass parameter. You can run like this:``` [ bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/t.sh) -E -A us -4 -N nd -M 2]```; 2. Improve log details 1. 支持传参，你可以这样运行脚本:  ```[ bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/tools/main/t.sh) -E -A us -4 -N nd -M2]```

2022.1.29 1.02 1. Support Disney+ 1. 支持 Disney+

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

<img src="https://user-images.githubusercontent.com/62703343/151651669-92d5263e-bfa2-4c2c-9928-683b678d9956.png" width="70%" />

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

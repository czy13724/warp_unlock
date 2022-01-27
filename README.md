# 【刷 WARP IP】 - 为 WARP 解锁流媒体而生
Born to make stream media unlock by WARP 

* * *

# 目录

- [更新信息和 TODO](README.md#更新信息和-todo)
- [脚本特点](README.md#脚本特点)
- [运行脚本](README.md#运行脚本)

* * *

## 更新信息和 TODO
TODO:~1. Improve the architecture first, so that adding detection items in the future can be faster, more scalable and reusable;~ 2. Add other unlocking methods; 3. In addition to the original Netflix, add other unlocking support such as Disney+; 4. Check Unlock socks5 support for mainstream scripts
   
待更新: ~1.先完善架构，以便日后增加检测项能更快捷，更具扩展性和复用性;~ 2.增加其他解锁方式; 3.除原有的 Netflix 外，增加 Disney+ 等其他解锁支持; 4.查解锁主流脚本的 socks5 支持(如作者支持就不做改了，直接引用)

beta 2022.1.26 Media unlock daemon. Check it every 5 minutes. If unlocked, the scheduled task exits immediately. If it is not unlocked, it will be swiped successfully in the background. Advantages: Minimized use of system resources. Disadvantage: Can't see the results as intuitively as screen

流媒体解锁守护进程,定时5分钟检查一次,遇到不解锁时更换 WARP IP，直至刷成功。 优点: 占用系统资源最小化。 缺点: 不能像 screen 那么直观看到结果

## 脚本特点
作者很懒，还未写

## 运行脚本

```
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/warp_unlock/main/unlock.sh)
```

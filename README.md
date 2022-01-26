Born to make steam media unlock by WARP

为 WARP 解锁流媒体而生

1.0 2022.1.26 Media unlock daemon. Check it every 5 minutes. If unlocked, the scheduled task exits immediately. If it is not unlocked, it will be swiped successfully in the background. Advantages: Minimized use of system resources. Disadvantage: Can't see the results as intuitively as screen

流媒体解锁守护进程,定时5分钟检查一次,遇到不解锁时更换 WARP IP，直至刷成功。 优点: 占用系统资源最小化。 缺点: 不能像 screen 那么直观看到结果


TODO：先完善架构，以便日后增加检测项能更快捷，更具扩展性和复用性

运行脚本

```
bash <(curl -sSL https://raw.githubusercontent.com/fscarmen/warp_unlock/main/unlock.sh)
```

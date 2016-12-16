---
title: Mac OSX 关闭SIP
date: 2016-12-16 01:40:08
tags:
---

在全新的 OS X El Capitan 10.11 上已经使用了 Rootlees , 可以理解为一个更高等级的系统的内核保护.
系统默认将会锁定 /system /sbin /usr 这三个目录. 但是这个保护也是可以关闭的.

### 方法如下:
重启电脑开后按住 Command-R 进入恢复分区. 然后在 实用工具 栏找到 终端启动运行.
输入
``` bash
csrutil disable; reboot
```
你会看到系统保护被关闭的字样并且系统自动重启.


这样你就可以修改系统级别的文件了.

但是系统还有一个保护叫做 Gatekeeper , 这个是防止第三方应用访问你的隐私信息的. 如果你也想关掉在终端里输入
``` bash
sudo spctl --master-disable
```

即可
激活 GateKeeper的方法也很简单
输入
``` bash
sudo spctl --master-enable
```

还可以通过
``` bash
csrutil status
```

来查询 Rootless 保护的状态.

# QQGuild-cqhttp
go-cqhttp like QQGuild adapter(兼容OnebotV11)

配合一键脚本食用
https://github.com/Hoshinonyaruko/One-Click-Sanae

没有技术含量，是一个可以兼容早苗、云崽、trss、nonebot2（真寻）、koishi、茶会机器人的QQ频道适配器

本程序为qq频道的onebot实现端,文档地址:https://www.yuque.com/km57bt/hlhnxg
启动参数:sanae.exe [Onebot实现的反向ws地址] [频道机器人appid] [频道机器人token] *[强制频道兼容](0/1)(默认0=不强制兼容) *[百度云审核的api-token](可选)

启动参数实例

```
(测试用真寻地址)
sanae ws://zaomiao.com:25372 appid token 1
(测试用云崽地址)
sanae ws://zaomiao.com:25369 appid token 1
Trss(时雨)
sanae ws://127.0.0.1:2536/go-cqhttp appid token 1
Nonebot2
sanae ws://127.0.0.1:8080/onebot/v11/ws appid token 1
Koishi
sanae ws://127.0.0.1:5140/onebot appid token 1
Koishi(超时空猫猫)
sanae ws://127.0.0.1:11400/onebot appid token 1
(早苗,端口范围20004-20050,选一个，都用一个会卡)
sanae ws://zaomiao.com:20004 appid token 1
(灵梦,端口范围20050-20070,选一个，都用一个会卡)
sanae ws://zaomiao.com:20052 appid token 1
(灵梦,端口范围20071-20099,选一个，都用一个会卡)
sanae ws://zaomiao.com:20072 appid token 1
(茶会机器人澪)
sanae ws://zaomiao.com:25370 appid token 1
(茶会机器人浅羽)
sanae ws://zaomiao.com:25371 appid token 1
```

appid和token哪里来~
可以看这篇教程，
https://www.bilibili.com/read/cv20035105
结合脚本使用，脚本机器人选择、设置的引导，一步一步帮你设置。
https://github.com/Hoshinonyaruko/One-Click-Sanae
脚本使用，会更加简单

交流群749890922

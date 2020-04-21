# CobaltStrike Becon 上线提醒

## 0x01 起因:

因为最近在测试一些社工钓鱼方式的目标,每次等待Beacon回弹有点蛋疼!

就按照网上的一些方式,写了一个上线提醒的插件,通过微信Server酱提醒,效果测试后还可以! 

## 0x02 测试配置

<b> 1. 远程上线一下:</b>

![](https://loecho.oss-cn-beijing.aliyuncs.com/BlogImg20200421145137.png)

<b> 2. Beacon 回弹,server酱提醒!</b>

![](https://loecho.oss-cn-beijing.aliyuncs.com/BlogImg20200421145927.png)

<b>3.使用方法:</b>

因为是通过客户端提醒的,我们可以通过CobaltStrike 自带的agscript来运行这个插件,在服务段后台运行:

一 .填入你的Server酱的Key,链接如下::

http://sc.ftqq.com/3.version

**(1) 打开链接,登入Github账号,微信绑定公众号,在微信推送选项里就有.**

**(2) 打开cna文件,添加Key:**

![](https://loecho.oss-cn-beijing.aliyuncs.com/BlogImg20200421150846.png)

**(3) 后台运行cna插件:**

```
./agscript [host] [port] [user] [pass] 
```

- [host] 服务端IP
- [port] cs的端口号，默认50050
- [user] 用户名
- [pass] cs的密码
- [path] cna插件的路径

**(4) 配置成功后,你的Server酱会收到测试消息!**

**(5) 如果想通过其他webhook方式推送,自行修改!**









"# CobaltStrike_Script_Wechat_Push" 

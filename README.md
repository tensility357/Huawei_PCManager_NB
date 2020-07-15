# Huawei_PCManager_NB

[English](README_en.md)

由于公众号不方便发布零散消息，欢迎关注微博（[汉客儿](https://weibo.com/anhkgg)）获取最新消息。

在hw电脑管家`PCManager`基础上，让`PCManager`支持在非hw系电脑（以及美版hw电脑）运行，完美支持多屏协同功能。

**如果链接失效，请自行前往公众号汉客儿（回复hw2）获取最新链接。**

# 更新

### 2020-5-12

**功能简介**

1.  绕过hw对非hw电脑管家的限制，一键安装PCManager（不需要改bios）。
2.  提供一键一碰传NFC标签二维码生成功能。
3.  PCManager管理功能，启动、关闭、服务控制等。
4.  提供极客模式。
a)  喜欢折腾的朋友，可以通过该模式选择PCManager功能。
b)  在制作NFC标签时选择适合自己的SN选项，有系统SN、自定义SN、自动SN（同老版本功能）。

**更新日志：**

1.  增加自行可选安装包，兼容适配更新到10.1.2.33，若有更新版本自行测试
2.  去掉荣耀标志，电脑伪装为matebook x pro
3.  修复自动SN某些情况不能登陆的问题
4.  增加管家启动、退出
5.  增加极客模式，包括功能模块管理和不同种类sn配置。
6.  修复系统盘非C盘无法安装问题。
7.  增加升级功能、英文版。

[使用方法](http://www.anhkgg.xyz/help.pdf)

[GitHub下载](https://raw.githubusercontent.com/anhkgg/Huawei_PCManager_NB/master/PCManagerMgr1.1.zip)

[百度网盘](https://pan.baidu.com/s/1JL7Y-45hOHk7_BbzmJFZQA), 提取码: enh5

[蓝奏云](https://anhkgg.lanzous.com/b01becpva), 密码:avrw

### 2020年4月28日

增强版发布，支持一碰传。链接:https://pan.baidu.com/s/1Gjo1FjSOhE7j5sN9e5eYjw 提取码:9p8s 

### 2020年4月25日

完美支持10.1.1.99。未上传，自行前往获取。

### 2020年2月26日

支持美版hw电脑Huawei Share，一碰传。在公众号（汉客儿）后台回复：USA-HW 下载最新Util.dll替换即可。


# 使用方法

注意：hw原版PCManager仅支持Windows10 X64系统，电脑需有WIFI和蓝牙功能。

1. 安装`PCManager_Setup_10.0.2.59.exe`到`C:\Program Files\Huawei\PCManager`(默认路径)。
2. 打开`Windows`任务管理器-进程项，找到`MateBookService.exe`-`Huawei PCManger Widnows Service`，将其结束。
2. 复制`Util.dll`到`C:\Program Files\Huawei\PCManager`替换原始`Util.dll`。
3. 打开hw电脑管家，我的手机->立即连接->扫码连接，手机打开hw浏览器扫描确认连接。
4. 如果功能不正常（提示加载服务），需要重启一次电脑系统。

另：
电脑管家官网[下载地址](https://consumer-tkb.huawei.com/tkbapp/downloadWebsiteService?websiteId=1697397)

文件hash:

```
Huawei_PCManager_NB\PCManager_Setup_10.0.2.59.exe
MD5: 20AF7D3D82A9ACFA1ACDC82F45A34493
SHA1: F66F0A8E1F39C9165F5DFBF73D8BB9EBEF6750AD
Util.dll
MD5: 041AA7C4812BDD3CA17A8C238A818C6B
SHA1: 51A85CBCD079C8C2BFD4484F562632B1CCF3A535
```

如果下载速度慢，[百度网盘](https://pan.baidu.com/s/1YsPlMJ2IVW7y-7vJYV9iZw) 提取码:`tmm9`

**如果觉得作者给你提供了一点帮助，请他喝一杯咖啡吧**

![img](pay.png)
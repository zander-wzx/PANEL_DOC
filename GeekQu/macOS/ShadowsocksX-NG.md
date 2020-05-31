## 应用概述

ClashXR 是一个拥有 GUI 界面基于 Clash 可自定义规则的 macOS 代理应用。

支持 Shadowsocks 协议和其 simple-obfs 插件、v2ray-plugin 插件以及 VMess 协议和其 TCP、WebSocket 等传输方式。

## 应用下载

以下是各平台该应用的下载地址。

![](/getsoft?type=ShadowsocksX ':include :type=markdown')

!>如果提示被阻止运行，打开系统偏好设置，选择安全性与隐私，点击仍要打开

![](https://www.qbdyun.com/images/help/mac-01.png)
![](https://www.qbdyun.com/images/help/mac-02.png)
![](https://www.qbdyun.com/images/help/mac-03.png)
![](https://www.qbdyun.com/images/help/mac-04.png)
![](https://www.qbdyun.com/images/help/mac-05.png)

- 第一次运行需要输入密码

![mac2.png](https://www.qbdyun.com/images/help/mac-06.png)

>系统顶部菜单栏会出现“小飞机”图标，单击“小飞机”图标即可展开菜单界面。

## 将订阅链接导入客户端

点击系统右上角托盘处中的小飞机图标，在展开的菜单中，点击“`服务器`”→“`编辑订阅`”

![](https://www.qbdyun.com/images/help/mac-07.png)

弹出如下图所示的窗口，在窗口左下角点击`添加`按钮，然后将 **[获取订阅](#获取订阅)**拷贝至订阅地址，其它栏目留空，最后点击确定。如下图①②③所示。

![](https://www.qbdyun.com/images/help/mac-08.png)

>点击小飞机→服务器→勾选“打开时自动更新订阅”

![](https://www.qbdyun.com/images/help/mac-09.png)

>第一次导入订阅链接后，需要手动更新订阅。点击`小飞机图标-服务器-手动更新`订阅，即可完成订阅的操作。

![](https://www.qbdyun.com/images/help/mac-10.png)

## 获取订阅

此处将显示您的订阅链接，请注意为登录状态：

[cinwell website](/sublink?type=ssr ':include :type=markdown')

!> 这个 **订阅链接** 非常重要，你应当把它当做密码一样妥善保管。

## 连接节点

更新订阅后，在服务器列表中**勾选**合适的节点。

> 建议勾选“打开时自动更新订阅”，这样在SSR启动时会自动更新服务器信息。

![](https://www.qbdyun.com/images/help/mac-11.png)

- 最后，点击“打开Shdowsocks”开始连接，**建议勾选`自动连接`和`自动启动`两个选项（如下图所示），省心！

![](https://www.qbdyun.com/images/help/mac-12.png)

- 尝试一下能否打开[google.com](https://www.google.com)吧！

## 代理模式的选择

新手常用的两个模式分别为PAC模式、全局模式

**1. PAC模式：按照一定的规则进行分流，国内网站直连，被墙的网站走代理，点击小飞机→PAC自动模式**

![](https://www.qbdyun.com/images/help/mac-pac-01.png)

* 第一次使用需要更新GFWList，点击小飞机→代理设置→从GFWList更新PAC

![](https://www.qbdyun.com/images/help/mac-pac-02.png)

**2. 白名单模式:此模式代理所有国外网站，点击小飞机→白名单模式**

![](https://www.qbdyun.com/images/help/mac-bai-01.png)

* 第一次使用需要更新白名单，点击小飞机→代理设置→更新全部白名单

![](https://www.qbdyun.com/images/help/mac-bai-02.png)

**3. ALC模式：此模式代理所有国内网站,如果你是海外用户,想要翻回国内,请选择此模式.点击小飞机→ACL模式→代理大陆IP**

![](https://www.qbdyun.com/images/help/mac-da-01.png)

* 第一次使用需要设置并更新白名单，点击小飞机→高级设置

![](https://www.qbdyun.com/images/help/mac-da-02.png)

* 替换ACL Back China URL为下面的链接，关闭窗口。
> https://raw.githubusercontent.com/shadowsocks/shadowsocks-libev/master/acl/server_block_chn.acl

![](https://www.qbdyun.com/images/help/mac-da-03.png)

* 点击小飞机→代理设置→更新全部白名单

![](https://www.qbdyun.com/images/help/mac-da-04.png)

**4. 全局模式：全部流量走代理**

!> 一般情况下，建议新手使用PAC模式，可以将SSR常驻后台，既可以科学上网，也不影响国内网站。若遇到个别网站打不开的情况，可以尝试开启全局模式。

## 启用UDP转发

* 此步骤为选做，点击小飞机→高级设置。

![](https://www.qbdyun.com/images/help/mac-u-01.png)

* 勾选启用 Udp Relay，关闭窗口。

![](https://www.qbdyun.com/images/help/mac-u-02.png)

* 一般多用于游戏，应用APP等客户端的条件下转发。



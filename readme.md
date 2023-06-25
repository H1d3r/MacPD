# Parallels Desktop Crack

Crack for Parallels Desktop 18.2.0-53488 破解版  ✅ 已支持 Ventura 13.x

##### ✅ - Support Intel

##### ✅ - Support Apple Silicon (M1 & M2)

##### ✅ - Network

##### ✅ - USB

###### 🎉目前该项目由马克喵同步更新维护🎉

# 目前激活工具修复问题

*修复不能先破解后安装镜像的问题，

*修复运行虚拟系统prl_disp_service无法运行问题，

18.2.0官方修复此前破解方式，请等待后续更新破解！请回滚到18.1.1，安装破解


# 中文教程：

⚠️ 注意：安装证书的时候要赋予终端权限！否则显示“Operation not permitted”

打开 “完全磁盘访问” 权限.系统偏好设置 ▸ 隐私与安全性 ▸ 完整磁盘访问权限 ☑️勾选了终端 （如果之前勾选过-然后+）

![image](https://user-images.githubusercontent.com/39859514/199421247-b59a9092-a70a-4a70-a3ec-c3e73663f5f5.png)


1.去官网下载安装最新版18.1.1，并自己安装完需要的镜像文件

18.1.1官方安装包：https://download.parallels.com/desktop/v18/18.1.1-53328/ParallelsDesktop-18.1.1-53328.dmg

官方PD最新安装包：https://download.parallels.com/desktop/v18/18.2.0-53488/ParallelsDesktop-18.2.0-53488.dmg

2.更新安装完PD后打开一次！

自动安装完pd可能会出现“无法启动”提示，不要慌直接去启动台打开pd即可！

3.下载网站左侧激活工具，点击安装证书即可！打开PD查看吧！

4.一键屏蔽验证Pd联网工具即将发布！QQ群：342929996


![image](https://user-images.githubusercontent.com/39859514/207548077-7a2be77d-1137-47e2-bbbf-685abead8256.png)
![image](https://user-images.githubusercontent.com/39859514/207548105-9e2f704d-6a70-4881-bff3-45e1e92920e8.png)


# Usage

1. Install Parallels Desktop 18.1.1-53328.

   https://download.parallels.com/desktop/v18/18.1.1-53328/ParallelsDesktop-18.1.1-53328.dmg

2. Exit parallels account.

3. Download this repo file.

4. Extract and run Terminal in this directory.

5. `chmod +x ./install.sh && sudo ./install.sh`


# Manual

1. Exit Parallels Desktop

```
killall -9 prl_client_app
killall -9 prl_disp_service
```

2. Copy crack file

```
sudo cp -f prl_disp_service "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
sudo chown root:wheel "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
sudo chmod 755 "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
```

3. Copy licenses.json

```
sudo rm -f "/Library/Preferences/Parallels/licenses.json"
sudo cp licenses.json "/Library/Preferences/Parallels/licenses.json"
sudo chown root:wheel "/Library/Preferences/Parallels/licenses.json"
sudo chmod 444 "/Library/Preferences/Parallels/licenses.json"
```

4. Sign

```
sudo codesign -f -s - --timestamp=none --all-architectures --deep --entitlements ParallelsService.entitlements "/Applications/Parallels Desktop.app/Contents/MacOS/Parallels Service.app/Contents/MacOS/prl_disp_service"
```

# Notice

Parallels Desktop may upload client info or logs to server.

You can use a firewall block there domains.

Or use Hosts, AdGuardHome filter DNS resolve.

一键屏蔽验证Pd联网工具即将发布！QQ群：342929996
工具已发布：https://macmiao.lanzouy.com/iroRC0feprzc

PD正常用时可以不用该工具！该用具只限制PD打开跳试用的！


```
127.0.0.1 download.parallels.com
127.0.0.1 update.parallels.com
127.0.0.1 desktop.parallels.com
127.0.0.1 download.parallels.com.cdn.cloudflare.net
127.0.0.1 update.parallels.com.cdn.cloudflare.net
127.0.0.1 desktop.parallels.com.cdn.cloudflare.net
127.0.0.1 www.parallels.cn
127.0.0.1 www.parallels.com
127.0.0.1 www.parallels.de
127.0.0.1 www.parallels.es
127.0.0.1 www.parallels.fr
127.0.0.1 www.parallels.nl
127.0.0.1 www.parallels.pt
127.0.0.1 www.parallels.ru
127.0.0.1 www.parallelskorea.com
127.0.0.1 reportus.parallels.com
127.0.0.1 parallels.cn
127.0.0.1 parallels.com
127.0.0.1 parallels.de
127.0.0.1 parallels.es
127.0.0.1 parallels.fr
127.0.0.1 parallels.nl
127.0.0.1 parallels.pt
127.0.0.1 parallels.ru
127.0.0.1 parallelskorea.com
127.0.0.1 pax-manager.myparallels.com
127.0.0.1 myparallels.com
127.0.0.1 my.parallels.com
```
Parallels Desktop 将取消注释主机文件，可以使用此命令锁定您的主机文件：

```
sudo chflags uchg /etc/hosts
sudo chflags schg /etc/hosts
```
AdGuard 主页
将以下规则添加到您的Custom filtering rules：
```
||myparallels.com^$important
||parallels.cn^$important
||parallels.com^$important
||parallels.de^$important
||parallels.es^$important
||parallels.fr^$important
||parallels.nl^$important
||parallels.pt^$important
||parallels.ru^$important
||parallelskorea.com^$important
||parallels.com.cdn.cloudflare.net^$important
```
FAQ
为什么prl_disp_service文件这么大？
它是原始prl_disp_service文件的直接补丁文件。

这个破解安全吗？
它是开源的，你可以使用任何你喜欢的十六进制文件比较工具打开prl_disp_service来查看修改了什么。

我想自己破解。
检查看看prl_disp_service.md我是如何破解它的。

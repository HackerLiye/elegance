# 如何优雅地上网
## 服务器信息
因为之前在Vultr上搭的ss服务器实在太慢，让我产生了自己在拨号上网的错觉，所以又在Google Cloud上面建了一个新的SSR+BBR。

用了一下发现看YouTube上的4Ks60fps视频已经无压力，甚至膨胀到点开了8K60fps的，但是最终因为处理器性能不够作罢。

服务器链接凭据如下：
```
IP: 坏掉了 = =
Port: 8989
Password: 123456
Encryption: aes-256-cfb
```
搭建方法在这里，需要科学上网的环境还有一张信用卡
https://suiyuanjian.com/124.html
## 如果你使用Windows
1. 在[这里](https://github.com/shadowsocks/shadowsocks-windows/releases)下载最新的Shadowsocks版本
2. 下载完毕后解压，运行之后右下角会出现一个小飞机的图标，编辑服务器，将上面的服务器信息填入后保存
3. 选择PAC模式并启动Shadowsocks，再打开浏览器应该就能科学上网了
## 如果你是Mac用户
1. 在[这里](https://github.com/shadowsocks/ShadowsocksX-NG/releases/)下载最新的ShadowsocksX-NG
2. 下载完毕后打开，会看到新弹出的窗口中有个Shadowsocks的图标
3. 这里有最重要的一步，将这个软件复制到Application文件夹之后打开，否则会无效
4. 运行后上面任务栏会出现一个小飞机图标，同样编辑服务器将凭据填入，选择PAC模式并启动Shadowsocks，此时应该就能科学上网了

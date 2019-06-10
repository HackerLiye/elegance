# 如何优雅地上网
## 服务器信息
下面的服务器截至2019/6/10可用
### 来自Google Cloud的
台北滴服务器，在武汉大学速度很快
```
ssr://MzUuMTg5LjE3Mi4xOTQ6MTIyNjc6YXV0aF9jaGFpbl9hOmNoYWNoYTIwLWlldGY6dGxzMS4yX3RpY2tldF9hdXRoOk1USXpORFUyLz9vYmZzcGFyYW09JnByb3RvcGFyYW09JnJlbWFya3M9WjI5dloyeGxMWE56Y2cmZ3JvdXA9
```
> 地址：35.189.172.194:12267
> 
> 加密方法： chacha20-ietf
> 
> 密码： 123456
> 
> 协议： auth_chain_a
> 
> 混淆： tls1.2_ticket_auth

### 来自Vultr的
硅谷的服务器，速度一般
```
ssr://MTQ5LjI4LjIxMi4xNjc6MTA0MTk6YXV0aF9jaGFpbl9hOmNoYWNoYTIwLWlldGY6dGxzMS4yX3RpY2tldF9hdXRoOk1USXpORFUyLz9vYmZzcGFyYW09JnByb3RvcGFyYW09JnJlbWFya3M9ZG5Wc2RISXRjMmxzYVdOdmJpMTJZV3hzWlhrJmdyb3VwPQ
```
> 地址：149.28.212.167:10419
> 
> 加密方法： chacha20-ietf
> 
> 密码： 123456
> 
> 协议： auth_chain_a
> 
> 混淆： tls1.2_ticket_auth

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

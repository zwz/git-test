## 我的翻墙经验
---------
值此**Google**被封，作为一个谷粉、Google使用者，在怒骂一句
>
> **FUCK GFW**
>

之余，翻墙的技能又有提升，不敢私藏，与各位分享一下我的翻墙经验。

#### 首先，我最先使用的是自由门
> 自由门（Freegate）是动态网公司开发的一种破网软件，该软件一般用来突破中国大陆官方创建的防火长城以浏览海外敏感网站或邮件。由于防火长城不断加强封锁，所以该软件也不断升级以突破防火长城。除了中国大陆，在伊朗、叙利亚、阿联酋等国家也有很多用户使用其开发的软件访问那些被其官方屏蔽的网站。

所谓动态网，即轮子的网站，宣传法轮功的，这东西的政治意味太浓，最好不要用了，我也是就刚刚开始翻墙的时候才用过，后来就从来没用过了。

#### Goagent
 Goagent之名大凡翻墙之辈应该都听过了,我也是在前几天Google被全面封锁后才不得不放弃的，
 它的主页在 [Google Code][1] 上面,源码托管在 [GitHub][2] 。

> GoAgent 是使用跨平台语言 Python 开发的代理软件，利用 Google App Engine 的服务器充当代理，帮助用户浏览被封锁的内容 。该软件在中国大陆被广泛用于突破中国大陆官方创建的防火长城。
主要特点有
* 支持作为本地 DNS 服务器使用 。
* 支持代理自动配置 (PAC) 。
* 支持在数据传送过程中采用 HTTPS 加密链接 。
* 支持 Google App Engine，PHP 和 PaaS 三种模式 。
* 自 2.1.17 版本起支持在通信时加入混淆数据以避免数据包在传输时受到特征过滤 。
* 允许用户选择使用Google北京、香港或台湾数据中心的IP地址，或者Google的IPv6地址（Google App Engine位于美国的数据中心在中国大陆被GFW封锁）。
* GoAgent 自 3.0.6 版开始可选支持RC4加密选项。

Goagent是一种非常成熟的翻墙方案，除非中国政府像近期一样全面封锁Google（但应该不会太久，对各方面影响非常大），Goagent就可以使用。

#### shadowsocks
**Shadowsocks**来源于[V2EX][3]，是一种比较新的翻墙方案，是一个轻量级socks5代理，代码托管在[GitHub][4]。
**shadowsocks**没有**Google**作后台，所以这是一种基本需要收费的翻墙方案，你可能需要想他人购买**Shadowsocks**帐号来使用他人提供的**Shadowsocks**服务，或者干脆购买一台国外的VPS主机，自己架设Shadowsocks服务。

#### cow
> **COW** 是一个简化穿墙的 HTTP 代理服务器。它能自动检测被墙网站，仅对这些网站使用二级代理。用GO语言写成。
主要特点是
* 作为 HTTP 代理，可提供给移动设备使用；若部署在国内服务器上，可作为 APN 代理
* 支持 HTTP, SOCKS5, shadowsocks 和 cow 自身作为二级代理
* 可使用多个二级代理，支持简单的负载均衡
* 自动检测网站是否被墙，仅对被墙网站使用二级代理
* 自动生成包含直连网站的 PAC，访问这些网站时可绕过 COW
* 内置常见可直连网站，如国内社交、视频、银行、电商等网站（可手工添加）

**cow**对未知网站，先尝试直接连接，失败后使用二级代理重试请求，2 分钟后再尝试直接,会导致访问速度变慢。如果你只是想把socks代理转为HTTP代理，可能以下这两种更为合适。

####proxifier/proxychains
**proxifier/proxychains**的功能大同小异，只是一个在windows下工作，一个在linux下工作，我都把它们当作socks转HTTP软件使用。
> Proxifier是一款功能非常强大的socks5客户端，可以让不支持通过代理服务器工作的网络程序能通过HTTPS或SOCKS代理或代理链。支持 64位系统，支持Xp，Vista，Win7，MAC OS ,支持socks4，socks5，http代理协议，支持TCP，UDP协议，可以指定端口，指定IP，指定域名,指定程序等运行模式，兼容性非常好。有点类似SOCKSCAP。



 [1]: https://code.google.com/p/goagent/
 [2]: https://github.com/goagent/goagent/
 [3]: http://www.v2ex.com/t/32777
 [4]: https://github.com/clowwindy/shadowsocks
 [5]: 
 [6]:
 [7]:
 [8]: 

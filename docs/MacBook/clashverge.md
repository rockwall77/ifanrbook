**仔 细 阅 读 教 程 大部分问题 都 会 自 行 解 决!**

<table><tr><td bgcolor=cyan><font face="楷书"  size=4> 继续使用翻儿Cloud服务前，请务必查看是否满足以下条件。</font></td></tr></table>

 ✅浏览器访问 time.is 检查设备时间是否与北京时间同步    
 ✅ 我的 翻儿Cloud 会员没有过期     
 ✅设备中没有开启其他VPN类软件    
 ✅我的网络不是校园网或者公司内网      
<br>    

> ⚠️ 温馨提示     
> 再次确认你的设备环境是否满足以上条件，检查无误后继续查看使用教程。 
---
<br>
<br>
<br>

 - **macOS设备 Clash Verge客户端使用教学**

Clash-verge是一款用于 MacBook 装置的跨平台代理程式工具，可协助你在浏览网页时保护你的个人隐私以及绕过地区限制,  以下是Clash Verge forMacbook设备使用教程 的详细步骤。

![clashverge图标](https://doc.sev7en.blog/wp-content/uploads/2024/06/icon.png)

---
<br>

**相关链接**：<a href="https://github.com/clash-verge-rev/clash-verge-rev/releases" target="_blank">Github项目</a>  / 
  <a href="https://clash-verge-rev.github.io/faq/macos.html" target="_blank">Clash Verge Rev Docs</a>  

<br>
<br>
<br>



---

## **Clash verge for MacOS下载**
（以下链接提供 Clash.Verge_1.7.5 版本苹果电脑的安装包） <br>

  >intel芯片:x64.dmg    

 clash verge苹果电脑客户端大陆网络下载:
 <a href="https://wwv.lanzouh.com/i6omW24v1cri" target="_blank">**--->点击下载**</a>  
 <br> 
 
 > apple M芯片:aarch64.dmg     

 clash verge苹果电脑客户端大陆网络下载:
 <a href="https://www.miaofile.com/s/79GACE" target="_blank">**--->点击下载**</a>

 <br>
⚠️<strong><font color = red>「不支持 macos 10 操作系统，请升级 macos 到 11 或 更高版本。」</font></strong> 
 <strong>    

---
<br>


## **Clash verge安装**

下载完成后，双击安装包，将 Clash Verge 拖动到 Applications 文件夹中即可;     
如果提示已损坏无法安装，请打开终端（Terminal）输入下面的命令（如果提示密码，请输入开机密码）     

```
sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app
```

![clashverge安装](https://ifanr.org/file/823f1949b0d705c1a0940.png)
![终端命令](https://ifanr.org/file/a8000f5a7fbeea155f756.png)

---
<br>
<br>

## **Clash verge导入订阅**    

 >手动导入Clash订阅     

 1. 浏览器登录进入 <a href="https://zifanr.net/auth/register?code=freedom" target="_blank">**翻儿Cloud官网**</a> 
 「首页」 右下角点击  [手动复制ClashX订阅地址]

 如果您忘记了翻儿Cloud官网地址可前往地址发布页 <a href="https://ifanrvpn.github.io/" target="_blank">**点击前往**</a> 找到最新的官网地址。   

<br>

![打开翻儿Cloud官网](https://ifanr.org/file/7ce4f6dc2ef5507f4bd8c.png)

<br>


  2.返回Clashverge客户端页面;    
  鼠标右键图标打开面板进入 【订阅】 页面，点击【新建】 创建配置文件;

![导入订阅](https://ifanr.org/file/af252ce24130615403a8c.png)

<br>

 3.新建配置；类型选择 [Remote];     
 名称随意填写，比如[翻儿Cloud];     
 订阅链接框中请粘贴 从机场复制的ClashX订阅链接;     
更新间隔自行设置，使用系统代理更新；打开。最后点击【保存】     

![导入订阅](https://ifanr.org/file/56644cc0b78af5791595e.png)

---
<br>
<br>
<br>
<br>

## **开启代理**       

1,选择已导入的配置文件 “翻儿Cloud”; <br>
打开【代理】 页面根据需求自行设置代理策略组分流规则;

<br>


![选择配置文件](https://ifanr.org/file/29727af26e035cc0aa195.png)

![配置规则分流](https://ifanr.org/file/f2b4f5701d4ca015738da.png)

<br>

 2.进【设置】页面，把 [系统代理] 开启即可；<br>
 [代理] 页面自行选择模式;<br>

 - 全局模式（Global）：所有请求直接通过代理服务器。
 - 规则模式（Rule）：根据配置文件的规则进行分流，只有需要代理的网站才会经过代理服务器。
 - 直连模式（Direct）：所有请求直接发送到目的地

不出意外的话，你现在已经可以访问自由网络了。比如打开 <a href="https://google.com" target="_blank">GOOGLE.COM</a>


<br>

![开启代理](https://ifanr.org/file/a3d70b783cf0ddff4e80a.png)

---
<br>
<br>


### Tun模式(可选)
 - 代理程序会创建一张虚拟网卡，通过配置操作系统的路由将网络请求重定向到这张虚拟网卡，代理程序从虚拟网卡中读取并处理这些网络请求。
 - 开启TUN模式之前 先安装【服务模式】并开启。
 <br>

 ![安装服务模式](https://ifanr.org/file/2765e71ee1e5330570379.png)
 ![开启Tun模式](https://ifanr.org/file/4f671a5d439d327210be3.png)

 ---
 <br>
 <br>
 <br>
 <br>

## **更新订阅 & 更新版本**   

 - 更新订阅    
进入【订阅】页面，点击配置文件右上角半圆形箭头标识即是 [更新订阅]

<br>

![更新订阅](https://ifanr.org/file/e6e8865181edb849cceae.png)

<br>
<br>

 - 在线更新clashverge版本   <br>

客户端图标的左上角出现红色字体“NEW”，表示可升级直接在本地更新系统版本; <br>
点击“NEW”弹出提示页面，直接在此页面点击“更新” 即可。

<br>

![在线升级](https://ifanr.org/file/ff8cffd5be74532206f9a.png)

---
<br>
<br>
<br>
<br>


⚠️ **使用建议**

<table><tr><td bgcolor=violet><font face="楷书"  size=3> 订阅地址是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。
建议定期手动更新或者设置成启动时自动更新订阅，即可保持与服务器同步更新。</font></td></tr></table>

<br>

---

你可以观看以下 YouTube 视频了解更多信息：
(如果你在中国大陆地区访问 YouTube 受限，需要使用 VPN 或代理服务。)
<iframe width="560" height="315" src="https://www.youtube.com/embed/tNq4WQ3jvog" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
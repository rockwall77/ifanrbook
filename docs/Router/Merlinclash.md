
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
### **MerlinClash 使用教程** 
<br>


<table>
  <tr>
    <td bgcolor="#ADD8E6">
      <font face="楷书" size="3">
          <font color="black">
          	📛简介<br>
          	    <br>
          	 供用于asuswrt、asuswrt-merlin为基础的，带软件中心固件（≥384）路由器的科学上网功能。基于硬件限制，并非所有架构的路由器都能正常运行插件，请前往下面提供的文章链接查看自己路由器的软硬件版本是否支持。
            如何刷官改固件/梅改固件以及安装科学上网插件???       <br>有兴趣的小伙伴请访问
            <a href="https://doc.sev7en.blog/?p=606"> <strong>➡️ 梅林固件与MerlinClash ⬅️</strong></a>
            这篇文章。
          </font>
      </font>
    </td>
  </tr>
</table>


<table>
  <tr>
    <td bgcolor="FFB6C1"> <!-- 浅粉色 -->
      <font face="楷书" size="3">
          <font color="black">
          	⚠️说明 <br>
                    <br>
            本教程只适用于已成功安装 MerlinClash 插件的用户，不解答安装过程遇到的任何技术问题。本教程基于执行环境：KoolShare固件axhnd.675x平台机型386版本。本教程不具备全版本普适性，如果您的固件或插件不同于上述版本，可能实际运行状况及部分功能会有所不同，请参考MC项目文档。
          </font>
      </font>
    </td>
  </tr>
</table>


**相关链接 > [魔法MC文档](https://mcreadme.gitbook.io/mc) / [MC插件与安装](https://doc.sev7en.blog/?p=606)/ [油管教程](https://www.youtube.com/watch?v=w5UPoVnG120&t=177s)**   

---

<br>
<br>
<br>

### **导入订阅**    

1. **MerlinClash** 和 **科学上网** 插件不能同时启用，请确保配置和启动 **MerlinClash** 插件前彻底关闭原有的科学上网插件。

![科学上网插件](https://ifanr.org/file/d8542a9908fd578e829e7.png) 

---
<br>

  2.从路由器左下角的软件中心进来，打开Merlin Clash插件，切换到**『配置文件』**选项页，不要使用订阅助手和在线转换功能，直接使用下方的**Clash-Yaml配置下载**功能。
![MerlinClash插件页面](https://ifanr.org/file/1186c912eb89bd20596e1.png)
 

---

<br>

 3.浏览器登录进入 **[翻儿Cloud官网](https://zifanr.net/auth/register?code=freedom) 「首页」**右下角点击  **[手动复制ClashX订阅]**

 如果您忘记了翻儿Cloud官网地址可前往地址发布页 [点击前往](https://ifanrvpn.github.io/) 找到最新的官网地址。

![复制ClashX订阅](https://ifanr.org/file/7ce4f6dc2ef5507f4bd8c.png)

---
<br>


  4.在右方文本框粘贴上一步复制的ClashX订阅地址，重命名处填入配置文件名称（例如 ifanrCloud），然后点击右方Clash订阅按钮即可开始订阅。
![导入ClashX订阅](https://ifanr.org/file/bb1547f1eeee5b7674c08.png)


<br>


初次订阅的耗时时间可能比较长，请观察实时日志显示配置文件订阅成功!!! 订阅完成。

![订阅ClashX订阅](https://ifanr.org/file/1f8e66808dabaf85aa05b.png)

----
<br>
<br>
<br>


### **开启MerlinClash开关**

1 ，切换回到『首页功能』选项页，配置文件选择，选择上一步生成的配置文件 ifanrCLoud。

DNS方案，选择Fake-ip模式。开启定时重启功能，接着启动页面上方的『总开关』

最后点击页面最下方的『保持&启动』按钮。

![开启Merlinclash开关](https://ifanr.org/file/746e159c41a25db610a2c.png)

![配置MerlinClash](https://ifanr.org/file/19a66eeee31cfda6a4be4.png)

----
<br>


2 ，连通性检查板块显示百度搜索、GitHub、YouTube都连接正常。

表示**已成功**开启MerlinClash插件科学上网。

![MC插件状态](https://ifanr.org/file/e440446db53d8cad445b3.png)


----
<br>


3、成功启动插件后可以通过**Clash管理面板**进行管理。

根据自己的使用习惯，可以选择**RAZORD-Clash面板**或**YACD-Clash面板**，两者都可以完成代理模式切换和节点选择等基本操作，与所有其他Clash内核的客户端相通。

![Clash管理面板](https://ifanr.org/file/75d9b9b5abd42eb721184.png)
![Clash管理面板](https://ifanr.org/file/f6713f3c470a8ec14d760.png)

----
<br>
<br>
<br>


### **更新订阅**

 - 设置定时更新订阅 / 手动更新配置。
 ---

1 ， 切回 **『配置文件』**选项页开启定时订阅，可设定每隔/每天/每周/每月，定时更新订阅；

定时订阅后会自动重启插件，应用新配置，无需设置定时重启；

![开启定时订阅](https://doc.sev7en.blog/wp-content/uploads/2024/07/2024-07-04-10.12.59.jpg)


----
<br>

2 ， 下载|删除|更新配置文件：

选中命名的配置文件，按对应功能按钮即可。当前使用的配置文件，不允许删除；

![手动更新订阅](https://doc.sev7en.blog/wp-content/uploads/2024/07/2024-07-04-10.13.34.jpg)


----
<br>
<br>
<br>


### **其他功能设置**
开启sniffer域名嗅探：强烈建议**Netfilx TV**用户开启！！！

![sniffer域名嗅探](https://doc.sev7en.blog/wp-content/uploads/2024/07/2024-07-04-10.13.40.jpg)

**sniffer域名嗅探原理：**     
Netfilx TV与其他终端不同，APP内置了加密DNS，自行解析流媒体域名，导致Clash无法劫持DNS做有效域名分流，同时Netfilx使用了大量CDN服务器，导致IP不固定，也无法精确的IP分流。这就是你的Netfilx其他客户端都能完美解锁，只有TV版本提示代理的原因。sniffer通过读取握手包内的SNI字段，主动还原域名，帮助Clash进行域名分流，彻底杜绝上文提到的Netfilx TV版本的分流尴尬！

----
<br>
<br>
#### ⚠️ 使用建议

<table><tr><td bgcolor=violet><font face="楷书"  size=3> 订阅地址是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。
建议定期手动更新或者设置成启动时自动更新订阅，即可保持与服务器同步更新。</font></td></tr></table>

---
<br>
<br>
<br>
<br>

<strong><font color = Orange>你可以观看以下 YouTube 视频了解更多信息： (如果你在中国大陆地区访问 YouTube 受限，需要使用 VPN 或代理服务。)</font></strong><strong><font color = Orange>

 <iframe width="560" height="315" src="https://www.youtube.com/embed/w5UPoVnG120" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

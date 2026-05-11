# Stash 苹果手机/ipad使用教程   


 ✅ 我的 翻儿Cloud 会员没有过期     
 ✅设备中没有开启其他VPN类软件    
 ✅我的网络不是校园网或者公司内网 
<br>    
<br>

 ⚠️ 温馨提示   

> 再次确认你的设备环境是否满足以上条件，检查无误后继续查看使用教程。  


<br>    
<br>   

## **Stash客户端下载**

 1. Stash客户端在中国大陆地区AppStore商店未上架并且需要付费购买，你可以自行注册美区苹果账户或者购买现成的美区苹果ID账号。     
 （ <font face="楷书" color=red size=4> **推荐购买美区ID商城：**</font> [https://good.imfaner.com](https://good.imfaner.com)   ）  


 2. 打开 「App Store」 搜索 「Stash」 即可找到该应用。安装完成后务必退出美区ID共享账号，以免账号出现问题带来不必要的麻烦。

 3. 在登陆过程中，如有见任何 升级，Upgrade 等按钮，请不要点击，选择否定项按钮（不升级，Do not upgrade）以避免开启双重认证    

<br> 

<img src="https://cdn.jsdelivr.net/gh/ifanrBook/docs@main/blog-img/stash-download.gif" loop="true" autoplay="true"> 



 ---
 <br>
 <br>
 <br>
 <br>

## **导入Stash配置**

- 方式一 自动导入

---
 1. 使用浏览器登录进入 <a href=" https://zifanr.net/auth/register?code=freedom" target="_blank">**翻儿Cloud官网**</a> ，如果您忘记了 <strong> 翻儿Cloud</strong>  官网地址可前往地址发布页 <strong> <a href="https://ifanrvpn.github.io/" target="_blank">**点此前往发布页**</a> </strong>找到最新的官网地址。
 2. 点击 **「一键导入Stash配置文件」**按钮 后会自动提示跳转到 stash 客户端，
提示会弹出提示 在“Stash”中打开？ ，根据提示点击 打开 即可成功订阅节点。

 <br>

[![surfboard-into sub.gif](https://image.dooo.ng/c/2024/09/16/66e80cd9a0008.gif)](https://image.dooo.ng/c/2024/09/16/66e80cd9a0008.gif)

<br>
<br>

 - **左滑 配置文件 更新与重命名展示**<br>

[![surfboard-rename.gif](https://image.dooo.ng/c/2024/09/16/66e80cc783098.gif)](https://image.dooo.ng/c/2024/09/16/66e80cc783098.gif)


 ---
 <br>
 <br>
 <br>

- 方式二 手动复制Stash订阅导入

---
 1. 浏览器登录进入 <a href=" https://zifanr.net/auth/register?code=freedom" target="_blank">**翻儿Cloud官网**</a> ， **[首页]** 右下角 – **[复制Stash配置]**；
 2. 如果您忘记了 <strong> 翻儿Cloud</strong>  官网地址可前往地址发布页 <strong> <a href="https://ifanrvpn.github.io/" target="_blank">**点此前往发布页**</a> </strong>找到最新的官网地址。
 3. 打开Stash客户端 **设置－配置文件－可视化编辑 – 远程代理集－**（名称: 翻儿Cloud；URL 此处粘贴Stash配置 （Clash订阅地址链接）；更新间隔：1440）－点击右上角 存储 。

  4. 返回 首页 – 点击 启动Stash
 <br>
 <br>

  [![surfboard-intoSUB2.gif](https://image.dooo.ng/c/2024/09/16/66e80cdb983e6.gif)](https://image.dooo.ng/c/2024/09/16/66e80cdb983e6.gif)


 ---
 <br>
 <br>
 <br>
 <br>
 <br>

## **启动Stash开关**

 - **策略组** <br>
根据自己的需求自行配置Stash策略组分流规则，跟Clash分流规则同理~

 - **出站模式 **<br>
根据应用场景，可以自由更换规则、全局、直连等出站模式，在“规则”模式下，客户端将根据配置文件的内置规则自动智能判断分流
- Stash 首次启动会有提示允许VPN  <br> 开启的系统级弹窗提醒，需要确认，否则无法开启，按钮变绿后显示“断开”，此时确认 Stash 为开启状态。

 <br>

[![surfboard-start02.gif](https://image.dooo.ng/c/2024/09/16/66e80cd7d2f33.gif)](https://image.dooo.ng/c/2024/09/16/66e80cd7d2f33.gif)


 ---
 <br>
 <br>
 <br>
 <br>
 <br>


## **Stash启用MitM功能**

1. 如果想对 HTTPS 请求进行查看、改写、执行脚本，必须启用 MitM 功能；
2. 在启用 MitM 功能前，你的设备需要信任自行签发的 CA 证书，该 CA 证书可以由用户导入 Stash，或由 Stash 生成。

<br>

### **配置 CA 证书**
- 在 Stash 首页，找到 MitM ，选择 [CA 证书]；
- 点击 [Stash Generated CA] 生成新的证书；
- 点击 [安装 证书] 安装新证书；
- Stash 会自动跳转到 Safari 进行证书安装，点击 [允许] 安装新的证书；
- 出现 [已下载描述文件] ，则代表证书已成功安装；
 
 <br>
 <img src="https://cdn.jsdelivr.net/gh/ifanrBook/docs@main/blog-img/stash-MitM.gif" loop="true" autoplay="true"> 
 <br>
 <br>
<table>
  <tr>
    <td bgcolor="FFB6C1"> <!-- 浅粉色 -->
      <font face="楷书" size="4">
          <font color="black">
          	⚠️提示 <br>
除了基本的应用以外，Stash这款软件还有很多实用功能，VPN图标隐藏功能、流媒体线路解锁状态信息跟随网络环境切换自动开关代理、内置可下载规则集可以屏蔽广告或者突破付费墙的覆写功能等等             
          </font>
      </font>
    </td>
  </tr>
</table>

**相关链接>>  [Stash官方文档](https://stash.wiki/get-started)**

----
<br>
<br>

⚠️ **使用建议**

<table><tr><td bgcolor=violet><font face="楷书"  size=3> 订阅地址是你个人账号密码及节点的总集成，不能泄露给任何人及网络，以防止他人使用及知晓你的密码。
建议定期手动更新或者设置成启动时自动更新订阅，即可保持与服务器同步更新。</font></td></tr></table>
<br>
<br>

---
你可以观看以下 YouTube 视频了解更多信息：
(如果你在中国大陆地区访问 YouTube 受限，需要使用 VPN 或代理服务。)
<iframe width="560" height="315" src="https://www.youtube.com/embed/Y8yr6yd9apk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
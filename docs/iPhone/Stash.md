---
title: Stash for iOS 详细使用教程与配置指南
description: 2026年最新翻儿Cloud苹果手机端 Stash (iOS版Clash) 客户端美区ID下载、一键订阅配置、MitM证书安装及高级分流保姆级教程。
keywords: [苹果手机科学上网, Stash, Clash for iOS, iOS翻墙, 翻儿Cloud, 美区苹果ID, Stash配置, MitM证书]
---

# 🟣 Stash 苹果手机/iPad 使用指南 (2026 版)

!!! warning "开始前必读（防错检查）"
    为了确保您的苹果手机（iPhone / iPad）能够顺畅连通外网，在配置前请务必确认以下环境：

    - ✅ 浏览器访问 [time.is](https://time.is) 检查**手机本地时间**是否与北京时间完全同步。
    - ✅ 请确保您的 **翻儿Cloud** 会员套餐未过期且流量充足。
    - ✅ 请彻底关闭手机后台的**其他 VPN 或代理软件**（如 Shadowrocket 等），避免底层网络冲突。
    - ✅ 请确保您的网络环境**非严格限制的公司/校园内网**。

---

## 📥 1. 客户端下载与安装

Stash（完美兼容 Clash 规则）在中国大陆区 App Store 未上架且为付费软件。您必须使用**美区（或其他外区）的 Apple ID** 才能下载。

!!! tip "获取外区 Apple ID 途径"
    * 您可以自行通过网络教程注册免费的美区苹果账户。
    * **省心直购推荐：** 若不想折腾，可直接购买外区 ID 成品账号 👉 **[点击访问直购商城](https://good.imfaner.com)**

!!! danger "⚠️ 极度危险：千万不要在设置里登录！"
    **绝对不要**在手机系统的“设置 -> iCloud”中登录购买的共享美区 ID！一旦触发苹果风控机制，您的手机可能会被永久锁死成砖！**只能在 App Store 软件中登录！**

1. 打开手机的 **「App Store」**，点击右上角头像，滑到最底部 **退出您的国区账号**。
2. 登录美区 ID。若弹出「Apple ID 安全」升级提示，请务必点击 **「其他选项」 -> 「不升级」**（Do not upgrade），以避免开启双重认证。
3. 搜索 **「Stash」** 并下载安装。
4. ⚠️ **下载完成后，请务必退出美区 ID，换回您自己的国内账号！**

??? tip "▶️ 点击展开：App Store 登录与下载演示 (GIF)"
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/ifanrBook/docs@main/blog-img/stash-download.gif" alt="Stash下载演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

---

## 🔗 2. 导入 Stash 配置

=== "🚀 方式一：一键自动导入 (强烈推荐)"

    1. 使用手机 Safari 浏览器访问并登录 **[翻儿Cloud 官方控制台](https://zifanr.net/)**。
       *(💡 **防失联提示：** 若官网被墙无法访问，请前往永久发布页 **[https://ifanrvpn.github.io/](https://ifanrvpn.github.io/)** 获取最新可用入口。)*
    2. 在官网「首页」右下角，点击 **「一键导入 Stash 配置文件」** 按钮。
    3. 浏览器会弹窗提示“在 Stash 中打开？”，请点击 **「打开」**。
    4. 此时会自动跳转至 Stash 客户端，节点列表即刻加载完毕！
    
    ??? tip "▶️ 点击展开：一键导入演示 (GIF)"
        <div align="center">
          <img src="https://image.dooo.ng/c/2024/09/16/66e80cd9a0008.gif" alt="一键导入演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        </div>

=== "📝 方式二：手动复制导入"

    1. 登录进入 **[翻儿Cloud 官网](https://zifanr.net/)**，在「首页」右下角点击 **「复制 Stash 配置」**。
    2. 打开 Stash 客户端，依次点击：**「设置」 -> 「配置文件」 -> 「可视化编辑」 -> 「远程代理集」**。
    3. 点击右上角的加号，**名称**填写 `翻儿Cloud`，**URL** 粘贴刚才复制的链接，**更新间隔**填写 `1440`。
    4. 点击右上角的 **「存储」**。
    
    ??? tip "▶️ 点击展开：手动导入演示 (GIF)"
        <div align="center">
          <img src="https://image.dooo.ng/c/2024/09/16/66e80cdb983e6.gif" alt="手动导入演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        </div>

---

## 🚦 3. 启动 Stash 开关与模式选择

1. **出站模式：** 在首页点击「出站模式」，强烈建议选择 **「规则 (Rule)」** 模式。此模式下，客户端将根据配置文件的内置规则自动智能分流（国内直连、海外走代理）。
2. **策略组：** 点击首页的对应策略组板块，您可以根据需求自行手动选择指定国家/地区的节点。
3. **启动代理：** 点击首页最上方的 **「启动 (Start)」** 大按钮。
4. **授权 VPN：** 首次启动会弹出系统的 VPN 创建请求，请点击允许并验证锁屏密码。
5. **✅ 连接成功：** 按钮变绿后显示“断开”，且状态栏出现 VPN 图标，此时确认 Stash 已成功为您接管网络流量！

??? tip "▶️ 点击展开：启动代理操作演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e80cd7d2f33.gif" alt="启动代理演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

---

## ⚙️ 4. 进阶玩法：启用 MitM 功能 (解密 HTTPS)

如果想对 HTTPS 请求进行查看、改写、执行高级脚本（如去广告、流媒体解锁重定向等），必须启用 MitM 功能并安装 CA 证书。

### 安装与配置 CA 证书步骤：
1. 在 Stash 首页，找到 **「MitM」** 板块，点击进入选择 **「CA 证书」**。
2. 点击 **「Stash Generated CA」** 生成新的证书。
3. 点击 **「安装证书」**，Stash 会自动跳转到 Safari 浏览器。
4. 在弹出的提示中点击 **「允许」** 以下载配置描述文件。
5. 前往手机系统的 **「设置」 -> 「已下载描述文件」**，点击右上角进行安装。
6. 最后，前往系统的 **「设置」 -> 「通用」 -> 「关于本机」 -> 划到最底部「证书信任设置」**，将刚刚安装的 Stash 证书开关打开（变绿）。

??? tip "▶️ 点击展开：MitM 证书安装演示 (GIF)"
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/ifanrBook/docs@main/blog-img/stash-MitM.gif" alt="MitM安装演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

!!! info "Stash 强大功能提示"
    除了基本的科学上网，Stash 还有很多极客级实用功能：如 VPN 图标隐藏、跟随网络环境（WiFi/蜂窝）自动开关代理、内置可下载规则集（直接突破付费墙或屏蔽 App 开屏广告）等。详情可参考：[👉 Stash 官方文档](https://stash.wiki/get-started)。

---

## 📺 5. 完整视频教程

如果您在配置过程中遇到任何困难，可以观看下方为您准备的完整版视频教程：

!!! note "YouTube 完整版图文指南"
    <div align="center">
      <a href="https://www.youtube.com/watch?v=Y8yr6yd9apk" target="_blank">
        <img src="https://img.youtube.com/vi/Y8yr6yd9apk/0.jpg" alt="苹果 Stash 视频教程" width="70%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      </a>
      <br>
      <br>
      👉 <strong><a href="https://www.youtube.com/watch?v=Y8yr6yd9apk" target="_blank">点击观看：苹果 Stash 详细配置进阶视频教程</a></strong>
    </div>

---

## 🛡️ 6. 账号安全须知

!!! danger "关键隐私提示"
    您的**订阅链接**等同于您的账号密码总集成！请务必妥善保管，**切勿在任何公开平台（如贴吧、群聊、小红书等）截图或泄露**，以免造成流量被盗刷超标或账号被系统自动封禁。

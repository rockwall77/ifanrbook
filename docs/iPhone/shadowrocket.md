---
title: Shadowrocket for iOS 详细使用教程与配置指南
description: 2026年最新翻儿Cloud苹果手机端 Shadowrocket (小火箭) 客户端美区ID下载、一键订阅配置、代理开启及进阶懒人配置保姆级教程。
keywords: [苹果手机科学上网, Shadowrocket, 小火箭VPN, iOS翻墙, 翻儿Cloud, 美区苹果ID, 小火箭配置]
---

# 🚀 Shadowrocket For iOS 使用指南 (2026 版)

!!! warning "开始前必读（防错检查）"
    为了确保您的苹果手机（iPhone / iPad）能够顺畅连通外网，在配置前请务必确认以下环境：

    - ✅ 浏览器访问 [time.is](https://time.is) 检查**手机本地时间**是否与北京时间完全同步。
    - ✅ 请确保您的 **翻儿Cloud** 会员套餐未过期且流量充足。
    - ✅ 请彻底关闭手机后台的**其他 VPN 或代理软件**，避免底层网络冲突。
    - ✅ 请确保您的网络环境**非严格限制的公司/校园内网**。

---

## 📥 1. 客户端下载与安装

由于政策原因，Shadowrocket（俗称“小火箭”）在中国大陆区 App Store 已下架，且该软件为付费应用。您必须使用**美区（或其他外区）的 Apple ID** 才能下载。

!!! tip "获取外区 Apple ID 途径"
    * 您可以自行通过网络教程注册免费的美区苹果账户。
    * **省心直购推荐：** 若不想折腾，可直接购买外区 ID 成品账号 👉 **[点击访问小火箭直购商城](https://good.imfaner.com)**

### 第一步：退出国区 Apple ID
打开手机的 **「App Store」** 应用，点击右上角的 **「账户头像」**。将弹出的页面一直滑动到最底部，点击 **「退出登录」**。

??? tip "▶️ 点击展开：退出国区 ID 演示 (GIF)"
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/quit%20usID.gif" alt="退出国区ID" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

### 第二步：登录美区 ID 并下载软件
!!! danger "⚠️ 极度危险：千万不要在设置里登录！"
    **绝对不要**在手机系统的“设置 -> iCloud”中登录购买的共享美区 ID！一旦触发苹果风控机制，您的手机可能会被永久锁死成砖！**只能在 App Store 软件中登录！**

1. 在 App Store 登录界面输入美区 ID 账号和密码。
2. 若弹出「Apple ID 安全」升级提示，请务必点击 **「其他选项」 -> 「不升级」**。
3. 登录成功后，搜索 **「Shadowrocket」** 并下载安装。
4. ⚠️ **下载完成后，请务必重复第一步的操作，退出美区 ID，换回您自己的国内账号！**

??? tip "▶️ 点击展开：登录与下载演示 (GIF)"
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/sigin%20appstore.gif" alt="登录美区ID" width="48%" referrerpolicy="no-referrer" style="display:inline-block; border-radius: 8px;">
      <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/download%20shadow....gif" alt="下载Shadowrocket" width="48%" referrerpolicy="no-referrer" style="display:inline-block; border-radius: 8px;">
    </div>

---

## 🔗 2. 获取并导入订阅配置

=== "🚀 方式一：一键自动导入 (强烈推荐)"

    1. 使用手机 Safari 浏览器访问并登录 **[翻儿Cloud 官方控制台](https://zifanr.net/)**。
       *(💡 **防失联提示：** 若官网被墙无法访问，请前往永久发布页 **[https://ifanrvpn.github.io/](https://ifanrvpn.github.io/)** 获取最新可用入口。)*
    2. 在官网「首页」右下角，点击 **「一键导入 iOS 配置文件」** 按钮。
    3. 浏览器会弹窗提示“在 Shadowrocket 中打开？”，请点击 **「打开」**。
    4. 此时会自动跳转至小火箭客户端，节点列表即刻加载完毕！
    
    ??? tip "▶️ 点击展开：一键导入演示 (GIF)"
        <div align="center">
          <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/fastinto.gif" alt="一键导入演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        </div>

=== "📝 方式二：手动复制导入"

    1. 登录进入 **[翻儿Cloud 官网](https://zifanr.net/)**，在「首页」右下角点击 **「复制 v2ray 订阅链接」**。
    2. 打开 Shadowrocket 客户端，点击右上角的 **「➕ 加号」**。
    3. **类型 (Type)** 选择第三个 **「Subscribe (订阅)」**。
    4. **URL** 框内粘贴刚才复制的链接，**备注 (Remarks)** 填写 `翻儿Cloud`。
    5. 点击右上角的 **「完成 / 保存」**。
    
    ??? tip "▶️ 点击展开：手动导入演示 (GIF)"
        <div align="center">
          <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/coryssr.gif" alt="手动导入演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
        </div>

---

## 🚦 3. 开启系统代理

1. 返回 Shadowrocket 首页。
2. 将 **「全局路由 (Global Routing)」** 设置为 **「配置 (Config)」**。（推荐使用“配置”模式，实现国内外流量智能分流，不影响国内 App 速度）。
3. 在节点列表中，选中一个带有测速延迟的节点（选中后前方会出现小黄点）。
4. 点击最上方的 **“未连接”** 旁边的开关，将其打开。
5. **首次连接**会弹出“添加 VPN 配置”的安全提示，请点击 **「允许 (Allow)」**，并根据提示输入您的 iPhone 锁屏密码（或进行 Face ID 解锁）。
6. **✅ 连接成功：** 此时手机屏幕右上角（或下拉控制中心）会出现 `VPN` 图标，代表科学上网成功开启！

??? tip "▶️ 点击展开：启动代理演示 (GIF)"
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/start%20shdow.gif" alt="启动代理演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

!!! success "自动化维护小贴士"
    建议进入小火箭底部的 **「设置」 -> 「订阅」**，将 **“打开时更新”** 和 **“自动后台更新”** 全部开启。这样客户端就能智能保持与官方服务器的同步更新！

---

## 📺 4. 进阶玩法与完整视频教程

想学习如何配置更高级的策略组？如何根据延迟自动切换低延迟丝滑线路？如何指定固定地区访问特定域名？强烈建议观看下方的高阶视频教程！

!!! note "YouTube 完整版配置指南"
    <div align="center">
      <a href="https://www.youtube.com/watch?v=0hP9CrPZ8U4" target="_blank">
        <img src="https://img.youtube.com/vi/0hP9CrPZ8U4/0.jpg" alt="苹果 Shadowrocket 视频教程" width="70%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      </a>
      <br>
      <br>
      👉 <strong><a href="https://www.youtube.com/watch?v=0hP9CrPZ8U4" target="_blank">点击观看：苹果 Shadowrocket 进阶懒人分流配置视频教程</a></strong>
    </div>

---

## 🛡️ 5. 账号安全须知

!!! danger "关键隐私提示"
    您的**订阅链接**等同于您的账号密码总集成！请务必妥善保管，**切勿在任何公开平台（如贴吧、群聊、小红书等）截图或泄露**，以免造成流量被盗刷超标或账号失效。

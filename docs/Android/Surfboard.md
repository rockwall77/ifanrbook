---
title: Surfboard for Android 详细使用教程与配置指南
description: 2026年最新翻儿Cloud安卓手机端 Surfboard (冲浪板) 客户端下载、纯净模式拦截解决、订阅配置及高级分流保姆级教程。
keywords: [安卓科学上网, Surfboard, 冲浪板VPN, 安卓翻墙, 翻儿Cloud, Surfboard配置, 华为纯净模式]
---

# 🏄‍♂️ Surfboard For Android 使用指南 (2026 版)

!!! warning "开始前必读（防错检查）"
    为了确保您的安卓手机能够顺畅连通外网，在配置前请务必确认以下环境：

    - ✅ 浏览器访问 [time.is](https://time.is) 检查**手机本地时间**是否与北京时间完全同步。
    - ✅ 请确保您的 **翻儿Cloud** 会员套餐未过期且流量充足。
    - ✅ 请彻底关闭手机后台的**其他 VPN 或代理软件**（如 v2rayNG、Clash等），避免端口冲突。
    - ✅ 请确保您的网络环境**非严格限制的公司/校园内网**。

---

## 📥 1. 客户端下载与安装

Surfboard（俗称“冲浪板”）是安卓端极为优秀的一款代理软件，完美兼容 Surge 规则。请根据您的网络环境选择下载：

=== "⚡ 国内极速下载 (推荐)"

    适合无法访问外网的新用户。
    👉 **[点击下载 Surfboard 客户端 (国内镜像)](http://wwbie.appboz.com/b0187zb8bi)**
    *(备用全平台下载站：[点击访问](https://file.pmxu.xyz/))*

=== "🐙 官方 GitHub / 谷歌商店 下载"

    适合已经拥有外网环境的用户。
    👉 **[GitHub 发布页下载](https://github.com/getsurfboard/surfboard/releases/tag/2.24.3)**
    👉 **[Google Play 商店下载](https://play.google.com/store/apps/details?id=com.getsurfboard)**

!!! danger "⚠️ 华为/小米用户安装必读：纯净模式拦截"
    部分小米系统或**华为鸿蒙系统 (HarmonyOS)** 会因开启了“纯净模式”而拦截第三方应用的安装。
    * **解决办法：** 请在系统设置中搜索并**暂时关闭「纯净模式」**，或在安装风险提示时输入密码强制允许安装。

??? tip "▶️ 点击展开：下载与安装演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e839077ac19.gif" alt="安装教程演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

---

## 🔗 2. 获取并导入订阅配置

### 第一步：获取专属订阅链接
1. 使用手机浏览器访问并登录 **[翻儿Cloud 官方控制台](https://zifanr.net/)**。
   *(💡 **防失联提示：** 若官网被墙无法访问，请前往永久发布页 **[https://ifanrvpn.github.io/](https://ifanrvpn.github.io/)** 获取最新可用入口。)*
2. 在官网「首页」右下角，找到订阅地址栏目，点击 **「复制 Surfboard 订阅链接」** 按钮。

??? tip "▶️ 点击展开：复制订阅链接演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e8392942776.gif" alt="复制订阅演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

### 第二步：导入到 Surfboard
1. 打开 Surfboard 客户端，底部菜单点击进入 **「配置 (Profiles)」** 页面。
2. 点击右下角的 **「➕ 加号」** 按钮。
3. 选择 **「从 URL 导入 (Import from URL)」**，在弹出的窗口中粘贴刚才复制的订阅链接，点击导入。
4. 导入成功后，**请务必确认该配置文件前面的小圆点处于“选中状态”（蓝色）**，代表成功激活。

??? tip "▶️ 点击展开：导入配置文件演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e83915108f3.gif" alt="导入配置演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

---

## 🚦 3. 配置分流规则与开启代理

### 1. 配置规则与节点
1. 底部菜单点击进入 **「代理 (Proxy)」** 界面。
2. 推荐选择默认的 **「规则模式 (Rule)」**，这样系统会根据配置文件自动分流：国内网站直连，海外网站走代理。
3. 展开节点列表，选中一条您想要使用的国家/地区节点（右上角的工具栏可快速切换节点布局和排序方式）。

??? tip "▶️ 点击展开：选择节点与规则演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e8391bd1333.gif" alt="节点分流演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

### 2. 开启系统代理
1. 返回最左侧的 **「仪表盘 (Dashboard)」** 页面。
2. 点击右下方的 **播放 ▶️ 开关** 即可开启 Surfboard 系统代理。
3. 首次开启系统会弹出 VPN 授权请求，请点击允许。
4. **✅ 连接成功：** 成功启动后，仪表盘会出现实时的网络速度、流量图表及使用时间！

??? tip "▶️ 点击展开：启动代理演示 (GIF)"
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e8390d87cc4.gif" alt="启动代理演示" width="50%" referrerpolicy="no-referrer" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    </div>

---

## ⚙️ 4. 进阶神技：应用黑名单与开机自启

!!! success "应用分流（不让某些 App 走代理）"
    1. 进入 **「工具 (Tools)」** 页面，找到并点击 **「分流设置 (Bypass apps)」**。
    2. 在这里您可以勾选微信、支付宝、网银等纯国内应用。被勾选的应用将**直接走本地网络，完全绕过 Surfboard 流量转发**，有效避免国内 App 变慢或风控！
    
    <div align="center">
      <img src="https://image.dooo.ng/c/2024/09/16/66e839222672f.gif" alt="应用分流演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; margin-top: 10px;">
    </div>

!!! success "开机自动启动与静默更新"
    1. 进入 **「设置 (Settings)」** 页面，选择 **「VPN」**，开启 **“启动设备时启动 VPN”**。
    2. 返回上一层，选择 **「应用」**，开启 **“VPN连接后更新所有配置”**。
    3. 这样每次手机重启，Surfboard 都会自动连网并拉取最新节点，全程无感！
    
    <div align="center">
      <img src="https://cdn.jsdelivr.net/gh/ifanrBook/docs@main/blog-img/surfboard-enable.gif" alt="自动启动演示" width="60%" referrerpolicy="no-referrer" style="border-radius: 8px; margin-top: 10px;">
    </div>

---

## 📺 5. 完整视频教程

如果您在配置过程中遇到任何困难，可以观看下方为您准备的完整版视频教程：

!!! note "YouTube 完整版配置指南"
    <div align="center">
      <a href="https://www.youtube.com/watch?v=cPXuCDs8VSY" target="_blank">
        <img src="https://img.youtube.com/vi/cPXuCDs8VSY/0.jpg" alt="安卓 Surfboard 视频教程" width="70%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      </a>
      <br>
      <br>
      👉 <strong><a href="https://www.youtube.com/watch?v=cPXuCDs8VSY" target="_blank">点击观看：安卓 Surfboard 详细配置视频教程</a></strong>
    </div>

---

## 🛡️ 6. 账号安全须知

!!! danger "关键隐私提示"
    您的**订阅链接**等同于您的账号密码总集成！请务必妥善保管，**切勿在任何公开平台（如贴吧、群聊、抖音等）截图或泄露**，以免造成流量被盗刷超标或账号失效。

---
title: Clash Verge-Rev for Windows 详细使用教程与配置指南
description: 2026年最新翻儿Cloud Clash Verge-Rev 客户端下载、安装、一键订阅配置、代理设置及 TUN 模式开启的保姆级图文视频教程。
keywords: [Clash Verge, Clash Verge-Rev, Windows科学上网, 翻儿Cloud, TUN模式, 代理设置, 一键导入]
---

# 💻 Clash Verge-Rev For Windows 使用指南 (2026 版)

!!! warning "开始前必读（防错检查）"
    为了确保网络连接质量，在配置前请务必确认以下环境：

    - ✅ 浏览器访问 [time.is](https://time.is) 检查**设备本地时间**是否与北京时间完全同步。
    - ✅ 请卸载或彻底关闭系统内的**其他 VPN 或代理软件**，避免端口冲突。
    - ✅ 请确保您的网络环境**非严格限制的公司/校园内网**。

---

## 📥 1. 客户端下载

请根据您的网络环境，选择最适合的下载渠道：

=== "⚡ 国内极速下载 (推荐)"

    适合无法访问外网的新用户。
    👉 **[点击下载 Clash Verge-Rev (国内镜像)](https://file.pmxu.xyz/%E8%BD%AF%E4%BB%B6%E6%94%B6%E8%97%8F/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91/Clash-Verge)**

=== "🐙 官方 GitHub 下载"

    适合已经拥有外网环境，希望获取官方原版的用户。
    👉 **[点击访问最新 Release 版本下载](https://github.com/clash-verge-rev/clash-verge-rev/releases)**

---

## ⚙️ 2. 安装与启动

1. 将下载的安装包解压，或直接运行安装程序。
2. 安装完成后，**右键点击**图标选择 **「以管理员身份运行」**。
3. 首次启动时，程序可能需要安装虚拟网卡驱动，请点击「是」或「确认」以授予权限。

??? tip "▶️ 点击展开：安装与启动操作演示视频"
    <video width="100%" controls referrerpolicy="no-referrer" preload="metadata">
      <source src="https://itsmyimg.sev7.xyz/i26pic/clashv-install-client.mp4" type="video/mp4">
    </video>

---

## 🔗 3. 导入订阅配置

=== "🚀 方法一：一键自动导入 (强烈推荐)"

    1. 登录 **[翻儿Cloud 官网](https://zifanr.net/)**，在首页右下角点击 **「一键导入 Clash 配置文件」**。
    2. 浏览器会提示“是否跳转至 Clash Verge”，根据提示确认打开即可。
    3. 导入后，在客户端的 **「订阅」** 栏中选中对应的配置文件（选中后会有变色提示）。
    
    ??? tip "▶️ 点击展开：一键导入演示视频"
        <video width="100%" controls referrerpolicy="no-referrer" preload="metadata">
          <source src="https://itsmyimg.sev7.xyz/i26pic/clashv-subscribe-clinet.mp4" type="video/mp4">
        </video>

=== "📝 方法二：手动复制导入"

    1. 浏览器登录进入 **[翻儿Cloud 官网](https://zifanr.net/)**，在「首页」右下角点击 **「手动复制 ClashX 订阅地址」**。
       *(💡 若忘记官网地址，可前往发布页 [点击前往](https://ifanrvpn.github.io/) 寻找最新入口。)*
    2. 打开客户端，在 **「订阅」** 页面顶部的输入框中，粘贴您的 Clash 订阅链接地址。
    3. 点击右侧的 **「导入」** 按钮，拉取代理配置文件。
    
    ??? tip "▶️ 点击展开：手动导入演示视频"
        <video width="100%" controls referrerpolicy="no-referrer" preload="metadata">
          <source src="https://itsmyimg.sev7.xyz/i26pic/clashv-subscribe2-client.mp4" type="video/mp4">
        </video>

---

## 🚦 4. 开启系统代理与选择模式

1. 在 Verge 左侧菜单进入 **「设置」** 界面，找到“系统代理”开关，确保其处于开启状态。
2. 在 **「订阅」** 页面确认已选中刚导入的配置文件。
3. 在 **「代理」** 页面选择线路节点（💡 **强烈推荐选择“规则”模式**，以实现国内流量直连、国外流量走代理的智能自动分流）。

??? tip "▶️ 点击展开：开启系统代理与选择模式视频"
    <video width="100%" controls referrerpolicy="no-referrer" preload="metadata">
      <source src="https://itsmyimg.sev7.xyz/i26pic/clashv-start-client.mp4" type="video/mp4">
    </video>

---

## 🚀 5. 进阶： TUN 模式 (全流量接管)

若您需要实现终端命令、桌面端大型游戏等全系统流量代理，请开启更为强大的 TUN 模式。

!!! warning "TUN 模式注意事项"
    **TUN 模式与常规系统代理建议二选一即可。** 开启 TUN 模式前，请务必先点击“服务模式”旁边的“盾牌”图标安装虚拟网卡服务。

1. 点击 **「服务模式」** 旁边的盾牌图标，安装服务并确保其状态变为绿色的 **Running**。
2. 开启 **「TUN 模式」** 开关。
3. 开启后，系统将自动生成虚拟网卡，完美接管全系统所有流量。

??? tip "▶️ 点击展开：开启 TUN 模式演示视频"
    <video width="100%" controls referrerpolicy="no-referrer" preload="metadata">
      <source src="https://cdn.jsdelivr.net/gh/Dacui777/mypicgo@main/guide/start%20TUN.mp4" type="video/mp4">
    </video>

---

## 📺 6. 完整视频教程

如果您在配置过程中遇到任何困难，可以观看下方为您准备的完整版视频教程：

!!! note "YouTube 完整版配置指南"
    <div align="center" style="display: flex; justify-content: space-between; gap: 4%;">
      <div style="flex: 1;">
        <a href="https://www.youtube.com/watch?v=uVX7JZ-csr4" target="_blank">
          <img src="https://img.youtube.com/vi/uVX7JZ-csr4/0.jpg" alt="Clash Verge 基础配置教程" width="100%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </a>
        <br>
        <p style="margin-top: 10px;"><strong><a href="https://www.youtube.com/watch?v=uVX7JZ-csr4" target="_blank">👉 点击观看：基础配置教程</a></strong></p>
      </div>
      <div style="flex: 1;">
        <a href="https://www.youtube.com/watch?v=R-TLc04SOhU" target="_blank">
          <img src="https://img.youtube.com/vi/R-TLc04SOhU/0.jpg" alt="Clash Verge 更新与维护教程" width="100%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </a>
        <br>
        <p style="margin-top: 10px;"><strong><a href="https://www.youtube.com/watch?v=R-TLc04SOhU" target="_blank">👉 点击观看：更新与维护</a></strong></p>
      </div>
    </div>

---

## 🛡️ 7. 账号安全须知

!!! danger "关键隐私提示"
    您的**订阅链接**属于您的个人加密凭证！请务必妥善保管，**切勿在任何公开平台（如贴吧、群聊、论坛）截图或泄露**，以免造成流量超标或账号失效。

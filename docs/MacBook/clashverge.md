---
title: Clash Verge-Rev for macOS 详细使用教程与配置指南
description: 2026年最新翻儿Cloud苹果电脑 MacBook M芯片/Intel芯片 Clash Verge 客户端下载、安装报错修复、订阅配置及 TUN 模式教程。
keywords: [MacBook科学上网, Clash Verge macOS, 翻儿Cloud, 苹果电脑翻墙, xattr修复, 代理设置]
---

# 🍏 Clash Verge-Rev For macOS 使用指南 (2026 版)

!!! warning "开始前必读（防错检查）"
    为了确保您的 Mac 设备能够顺畅科学上网，在配置前请务必确认以下环境：

    - ✅ 浏览器访问 [time.is](https://time.is) 检查**设备本地时间**是否与北京时间完全同步。
    - ✅ 请卸载或彻底关闭 Mac 上的**其他 VPN 或代理软件**（如 Shadowrocket、V2rayU），避免端口冲突。
    - ✅ 请确保您的网络环境**非严格限制的公司/校园内网**。

---

## 📥 1. 客户端下载

Clash Verge 针对苹果不同的处理器芯片提供了不同的安装包，请先点击屏幕左上角  -> **关于本机**，查看您的芯片类型，并选择对应版本下载：

!!! info "芯片版本选择指南"
    * **Apple M 系列芯片 (M1/M2/M3/M4 等)：** 请下载带有 `aarch64` 或 `arm64` 字样的 `.dmg` 文件。
    * **Intel 芯片：** 请下载带有 `x64`字样的 `.dmg` 文件。
    * ⚠️ *系统要求：不支持 macOS 10 及以下操作系统，请升级 macOS 到 11 或更高版本。*

=== "⚡ 国内极速下载 (推荐)"

    适合无法访问外网的新用户。
    👉 **[点击下载 macOS 版 Clash Verge (国内镜像)](http://wwbie.appboz.com/b018819u6f)**
    *(备用全平台下载站：[点击访问](https://file.pmxu.xyz))*

=== "🐙 官方 GitHub 下载"

    适合已经拥有外网环境，希望获取官方原版的用户。
    👉 **[点击访问官方 Releases 最新版本下载](https://github.com/clash-verge-rev/clash-verge-rev/releases)**

---

## ⚙️ 2. 安装与“已损坏”报错修复

1. 下载完成后，双击打开 `.dmg` 安装包。
2. 将 **Clash Verge** 图标拖动到右侧的 **Applications (应用程序)** 文件夹中。

!!! danger "⚠️ 常见报错修复：提示『已损坏，无法打开』"
    由于苹果 macOS 的系统安全机制（Gatekeeper），非 App Store 下载的软件常会报错。**请按以下步骤一键修复：**
    
    1. 按下键盘 `Command + 空格`，搜索并打开 **「终端 (Terminal)」**。
    2. 复制并粘贴以下命令到终端中，然后按回车：
       ```bash
       sudo xattr -r -d com.apple.quarantine /Applications/Clash\ Verge.app
       ```
    3. 终端会提示输入 `Password:`，**请直接输入您的 Mac 开机密码**（注意：输入密码时屏幕不会显示任何字符，输入完直接按回车即可）。
    4. 修复完成后，前往“启动台”重新打开软件即可。

<div align="center">
  <img src="https://ifanr.org/file/823f1949b0d705c1a0940.png" alt="clashverge安装" width="48%" style="display:inline-block;">
  <img src="https://ifanr.org/file/a8000f5a7fbeea155f756.png" alt="终端命令修复" width="48%" style="display:inline-block;">
</div>

---

## 🔗 3. 导入订阅配置

=== "🚀 方法一：一键自动导入 (强烈推荐)"

    1. 登录 **[翻儿Cloud 官网](https://zifanr.net/)**，在首页右下角点击 **「一键导入 Clash 配置文件」**。*(💡 若忘记官网地址，可前往发布页 [点击前往](https://ifanrvpn.github.io/) 寻找最新入口。)*
    2. 浏览器会提示“是否允许打开 Clash Verge”，点击允许。
    3. 导入后，在客户端的 **「订阅」** 栏中选中对应的配置文件（选中后背景会变色）。

=== "📝 方法二：手动复制导入"

    1. 浏览器登录进入 **[翻儿Cloud 官网](https://zifanr.net/)**，在「首页」右下角点击 **「手动复制 ClashX 订阅地址」**。
       *(💡 若忘记官网地址，可前往发布页 [点击前往](https://ifanrvpn.github.io/) 寻找最新入口。)*
    2. 打开 Mac 上的 Clash Verge，进入左侧 **「订阅 (Profiles)」** 页面。
    3. 点击右上角的 **「新建 (New)」**。
    4. 类型选择 **Remote**，名称填写 `翻儿Cloud`，在订阅链接框中粘贴刚才复制的地址。
    5. 开启“使用系统代理更新”，点击 **「保存 (Save)」**。

<div align="center">
  <img src="https://ifanr.org/file/7ce4f6dc2ef5507f4bd8c.png" alt="复制订阅链接" width="80%">
  <br><br>
  <img src="https://ifanr.org/file/56644cc0b78af5791595e.png" alt="导入订阅保存" width="80%">
</div>

---

## 🚦 4. 开启代理与模式选择

1. 在左侧菜单进入 **「订阅」** 页面，**单击选中** 刚导入的 `翻儿Cloud` 配置文件。
2. 进入 **「代理」** 页面，选择一条延迟较低的国家/地区节点。
3. 进入 **「设置」** 页面，将 **「系统代理 (System Proxy)」** 开关打开。
   *(💡 **强烈建议将代理模式设为“规则 (Rule)”**，实现国内网站直连、海外网站走代理的智能分流！)*

<div align="center">
  <img src="https://ifanr.org/file/29727af26e035cc0aa195.png" alt="选择配置文件" width="80%">
  <br><br>
  <img src="https://ifanr.org/file/f2b4f5701d4ca015738da.png" alt="配置规则分流" width="80%">
</div>

**✅ 验证成功：** 现在您可以尝试在浏览器中打开 [google.com](https://google.com)，若能正常访问，恭喜您已成功连通自由网络！

---

## 🚀 5. 进阶： TUN 模式 (全流量接管)

若需要让 Mac 上的终端命令 (Terminal)、桌面端软件或部分游戏也走代理，请开启强大的 TUN 模式。

!!! note "开启 TUN 模式步骤"
    1. 在 **「设置」** 页面中找到“服务模式 (Service Mode)”。
    2. 点击旁边的盾牌图标或安装按钮，输入 Mac 开机密码以授权安装底层虚拟网卡。
    3. 安装成功后，直接打开 **「TUN 模式」** 开关即可全盘接管流量。

<div align="center">
  <img src="https://ifanr.org/file/2765e71ee1e5330570379.png" alt="安装服务模式" width="48%" style="display:inline-block;">
  <img src="https://ifanr.org/file/4f671a5d439d327210be3.png" alt="开启Tun模式" width="48%" style="display:inline-block;">
</div>

---

## 📺 6. 完整视频教程

如果您在配置过程中遇到任何困难，可以观看下方为您准备的完整版视频教程：

!!! note "YouTube 完整版配置指南"
    <div align="center">
      <a href="https://www.youtube.com/watch?v=tNq4WQ3jvog" target="_blank">
        <img src="https://img.youtube.com/vi/tNq4WQ3jvog/0.jpg" alt="macOS Clash Verge 视频教程" width="70%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
      </a>
      <br>
      <br>
      👉 <strong><a href="https://www.youtube.com/watch?v=tNq4WQ3jvog" target="_blank">点击观看：macOS Clash Verge 详细配置视频教程</a></strong>
    </div>

---

## 🛡️ 7. 账号安全须知

!!! danger "关键隐私提示"
    您的**订阅链接**属于您的个人加密凭证！请务必妥善保管，**切勿在任何公开平台（如贴吧、群聊、论坛）截图或泄露**，以免造成流量超标或账号失效。

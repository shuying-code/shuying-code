### 👋 你好，我是 shuying-code

> 疏影横斜水清浅，暗香浮动月黄昏。以代码为笔，写自己的山水。

---

## 🖼️ 精选项目 · [wallpaper-rs](https://github.com/shuying-code/wallpaper-rs)

<p align="center">
  <a href="https://github.com/shuying-code/wallpaper-rs">
    <img src="https://raw.githubusercontent.com/shuying-code/wallpaper-rs/main/assets/screenshot-online.png?v=0.14.4" width="72%" alt="wallpaper-rs — 网上壁纸库">
  </a>
</p>

**跨平台桌面壁纸软件**（Windows / macOS / Linux），用 **Rust + egui/eframe** 编写 —— 一个界面搞定 **固定壁纸 / 定时轮播 / 动态壁纸**，**默认进入「网上壁纸库」**：

- 🌐 **网上壁纸库（默认首页）**：必应每日 4K · 彼岸图网 · MoeWalls · MotionBGs，支持搜索 / 分类 / 翻页 / 收藏；可下载**原图**与**动态壁纸 MP4**，一键设为桌面 / 锁屏 / 动态壁纸。
- 🖼 **本地壁纸库**：按相册分组、搜索，一键设为壁纸 / 锁屏；视频直接作为动态壁纸。
- 🎞 **动态壁纸（Windows / macOS / Linux-X11）**：桌面图标层之下自建宿主 + mpv 循环播放；**动态壁纸也能参与轮播**，进入前先铺首帧、切换不闪。
- 📦 **单文件 exe 约 5 MB**（mpv 按需下载，不内置）；纯本地运行，**无登录 / 无订阅 / 无遥测**。

<p align="center">
  <a href="https://github.com/shuying-code/wallpaper-rs/releases/latest"><img alt="Release" src="https://img.shields.io/github/v/release/shuying-code/wallpaper-rs?color=blue&label=%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88"></a>
  <a href="https://github.com/shuying-code/wallpaper-rs/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/shuying-code/wallpaper-rs?color=yellow"></a>
  <a href="https://github.com/shuying-code/wallpaper-rs/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

➡️ **[下载最新版](https://github.com/shuying-code/wallpaper-rs/releases/latest)**　·　**[查看源码](https://github.com/shuying-code/wallpaper-rs)**

---

## 📺 新项目 · [ysp-live](https://github.com/shuying-code/ysp-live)

<p align="center">
  <a href="https://github.com/shuying-code/ysp-live">
    <img src="https://raw.githubusercontent.com/shuying-code/ysp-live/main/ios/YspLive/Assets.xcassets/AppIcon.appiconset/AppIcon-1024.png" width="120" alt="YSP Live">
  </a>
</p>

**Android TV / Android 手机 / iPhone 直播客户端**，用 **Rust + Kotlin + Swift** 分层实现：

- 🔐 **隐藏 WebView 官方鉴权**：不伪造签名，让官方页面自己完成 `token` / `ysign` 等易变逻辑。
- ▶️ **原生播放 + 官方回退**：Android 使用 libmpv，iOS 使用 AVPlayer；已验证频道走原生，其余保留官方页内播放器。
- 📺 **电视与手机双体验**：D-pad 频道抽屉、当天 EPG、连续切台、后台播放；Android 提供可选 Kiosk 变体。
- 🧩 **多语言各司其职**：Rust 负责共享校验核心，Kotlin/Swift 负责平台能力，JavaScript 只做官方页面内桥接。

<p align="center">
  <a href="https://github.com/shuying-code/ysp-live/releases/latest"><img alt="Release" src="https://img.shields.io/github/v/release/shuying-code/ysp-live?color=blue&label=%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88"></a>
  <a href="https://github.com/shuying-code/ysp-live/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/shuying-code/ysp-live?color=yellow"></a>
  <img alt="Android" src="https://img.shields.io/badge/Android-6.0%2B-3DDC84?logo=android&logoColor=white">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-17.0%2B-000000?logo=apple&logoColor=white">
  <a href="https://github.com/shuying-code/ysp-live/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-MIT-green"></a>
</p>

➡️ **[下载最新版](https://github.com/shuying-code/ysp-live/releases/latest)**　·　**[查看源码](https://github.com/shuying-code/ysp-live)**　·　**[语言与模块选型](https://github.com/shuying-code/ysp-live/blob/main/docs/LANGUAGE_AND_MODULES.md)**

> 仅用于播放器技术验证，不提供内容授权；不支持 DRM / 付费 / 地区限制绕过。

---

## 🚀 其它项目

| 项目 | 简介 |
| --- | --- |
| [postman-rs](https://github.com/shuying-code/postman-rs) | 本地化、无账号、无付费的 Postman 风格 API 客户端（Rust CLI + egui GUI，兼容 Postman Collection v2.1） |
| [navicat-rs](https://github.com/shuying-code/navicat-rs) | 跨平台数据库管理客户端（Rust + egui）：多引擎、6 套主题、全部功能免费开放 |
| [rwms](https://github.com/shuying-code/rwms) | Rust 仓库管理系统（Axum + SeaORM + SQLite）：单二进制、内嵌数据库、跨平台 |
| [programming-knowledge-base](https://github.com/shuying-code/programming-knowledge-base) | 个人编程知识库：Java / Go / Rust 学习笔记与面试题整理（Markdown） |

---

<sub>🦀 Rust · 🤖 Kotlin · 🍎 Swift · 跨平台 · 无遥测</sub>

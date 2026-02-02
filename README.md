# 🖥️ Gemini Screen Vision

[English](#-english-version) | [中文说明](#-中文说明)

> **A lightweight, client-side screen mirroring tool designed for AI vision context.** > **一个轻量级的纯前端屏幕镜像工具，专为辅助 AI 获取视觉上下文而设计。**

---

## 🔗 Live Demo / 在线演示
👉 **[Click here to use / 点击直接使用](https://dustheart25.github.io/gemini-screen-vision/)**

---

## 📖 English Version

### Introduction
**Gemini Screen Vision** is a pure frontend web application that mirrors your screen, window, or browser tab into a clean webpage.

It is specifically designed to help AI models (like **Gemini in Chrome**) "see" other applications by using Picture-in-Picture (PiP) mode. By floating the mirror window, you can let the AI analyze your screen content in real-time without needing complex software.

### ✨ Key Features
* **📡 Screen Mirroring**: Capture your entire screen, a specific app window, or a browser tab.
* **📺 Picture-in-Picture (PiP)**: Pop the video out into a floating window that stays on top of other apps. Perfect for sharing context with AI sidebars.
* **🔒 Privacy First**: Runs entirely in your browser using standard Web APIs (`getDisplayMedia`). **No data is uploaded to any server.** Your screen content never leaves your device.
* **⚡ Zero Install**: Just open the webpage and run. No plugins or extensions required.
* **⛶ Full Screen & Stop Control**: Easily maximize for detail or stop capturing with one click.

### 🚀 How to Use
1.  Open the [Live Demo](https://dustheart25.github.io/gemini-screen-vision/).
2.  Click **"📡 Start Capture" (开始捕获)**.
3.  Select the screen or window you want to mirror.
4.  Click **"📺 PiP" (画中画)** to float the window.
5.  Now you can continue working while the AI (or you) watches the floating monitor.

---

## 🇨🇳 中文说明

### 项目简介
**Gemini Screen Vision** 是一个无需安装、纯前端运行的网页版屏幕镜像工具。

它的开发初衷是为了解决 **Gemini in Chrome** 等浏览器内嵌 AI 无法直接读取其他软件画面的问题。通过这个工具，你可以将任何软件的界面“镜像”到浏览器的一个网页中，或者使用“画中画”模式悬浮显示，从而让 AI 能够轻松读取并分析屏幕内容。

### ✨ 核心功能
* **📡 屏幕/窗口镜像**：支持录制整个屏幕、单个应用程序窗口或 Chrome 标签页。
* **📺 画中画悬浮 (PiP)**：将镜像画面以悬浮窗形式置顶显示，方便在与 AI 对话时作为视觉参考。
* **🔒 隐私安全**：基于浏览器原生 WebRTC 技术，所有视频流仅在本地内存中传输，**绝不上传服务器**，安全无忧。
* **⚡ 即开即用**：无需安装插件或客户端，打开网页即可使用。
* **⛶ 完整控制**：支持全屏查看细节，提供一键停止捕获按钮。

### 🚀 使用方法
1.  点击访问 [在线演示地址](https://dustheart25.github.io/gemini-screen-vision/)。
2.  点击 **“📡 开始捕获”** 按钮。
3.  在弹出的系统提示框中，选择你想要监视/镜像的窗口或屏幕。
4.  （推荐）点击 **“📺 画中画悬浮”**，将画面独立出来。
5.  现在你可以一边操作软件，一边让 AI 分析悬浮窗里的内容了。

---

### 🛠️ Tech Stack / 技术栈
* HTML5
* CSS3
* JavaScript (WebRTC / `navigator.mediaDevices.getDisplayMedia`)

### 📄 License
MIT License

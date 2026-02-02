# 🖥️ Gemini Screen Vision & Recorder

[English](#-english-version) | [中文说明](#-中文说明)

> **A smart, client-side screen mirroring & recording tool designed for AI vision context.**
> **一个轻量级的纯前端屏幕镜像与录制工具，专为辅助 AI 获取视觉上下文及会议记录而设计。**

---

## 🔗 Live Demo / 在线演示
👉 **[Click here to use / 点击直接使用](https://dustheart25.github.io/gemini-screen-vision/)**

---

## 📖 English Version

### Introduction
**Gemini Screen Vision** is a pure frontend web application. It not only mirrors your screen for AI analysis (via PiP) but also features a **powerful local screen recorder** with smart compression modes.

It helps you record meetings, demonstrate code, or share context with AI models like **Gemini**, all without installing any software.

### ✨ Key Features
* **📡 Screen Mirroring**: Real-time mirroring of screen, window, or tab.
* **🎥 Local Recording**: Record your screen with **System Audio**. No server involved, saves directly to your disk as `.webm`.
* **🧠 Smart Scenarios**: Choose from 3 recording modes to optimize file size:
    * **📝 Meeting Mode**: Ultra-small file size (approx. 200MB/hour), perfect for text/PPT.
    * **📺 Standard Mode**: Balanced quality for daily use.
    * **🎬 Cinema Mode**: High bitrate for video and games.
* **📺 Picture-in-Picture (PiP)**: Keep the screen floating on top for AI sidebars.
* **🔒 Privacy First**: Runs entirely in your browser. **No data uploaded.**

### 🚀 How to Use
1.  Open the [Live Demo](https://dustheart25.github.io/gemini-screen-vision/).
2.  Click **"📡 Start Capture"** and select the content.
    * *Tip: Check "Share system audio" if you want to record sound.*
3.  Click **"🔴 Start Recording"**.
4.  Select a **Scene Mode** (e.g., Meeting Mode) from the popup menu.
5.  Click **"⏹️ Stop Recording"** to automatically save the video file.

---

## 🇨🇳 中文说明

### 项目简介
**Gemini Screen Vision** 是一款功能强大的纯前端屏幕工具。它不仅能将屏幕画面“镜像”给 AI 观看，还内置了**智能录屏功能**。

即使在没有安装 OBS 或会议录制权限的情况下，你也可以用它来录制长达数小时的高清会议、网课或操作演示，并根据场景自动压缩文件体积。

### ✨ 核心功能
* **📡 屏幕镜像 & 投屏**：支持全屏、窗口或标签页的实时预览。
* **🎥 本地视频录制**：支持录制**带系统声音**的视频，录制处理完全在本地内存完成，自动保存为 `.webm` 格式。
* **🧠 智能场景模式**：点击录制时可选择三种模式，解决文件过大的问题：
    * **📝 会议/文档模式**：极低码率，文字清晰，1小时视频仅约 200MB。
    * **📺 通用清晰模式**：画质与体积的完美平衡。
    * **🎬 影音/高动态模式**：原画级体验，适合录制游戏或视频。
* **📺 画中画悬浮 (PiP)**：让画面悬浮在浏览器顶层，方便与 AI 对话时实时参考。
* **🔒 隐私安全**：所有数据流仅在浏览器本地处理，**绝不上传任何服务器**。

### 🚀 使用方法
1.  访问 [在线演示地址](https://dustheart25.github.io/gemini-screen-vision/)。
2.  点击 **“📡 开始捕获”** 选择共享内容。
    * *注意：如需录制声音，请在系统弹窗左下角勾选“分享系统音频”。*
3.  点击 **“🔴 开始录制”**。
4.  在弹出的菜单中选择适合的模式（如：会议模式）。
5.  录制结束后点击 **“⏹️ 停止录制”**，视频将自动下载到本地。

---

### 🛠️ Tech Stack / 技术栈
* **Core**: HTML5, CSS3, JavaScript
* **APIs**: `getDisplayMedia` (Screen Capture), `MediaRecorder` (Recording), `Picture-in-Picture API`
* **Codec**: VP9 / WebM

### 📄 License
MIT License

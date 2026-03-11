# 🎯 HighRiskPortHunter

<p align="center">
  <img src="radar.ico" alt="HighRiskPortHunter Logo" width="128"/>
</p>

<p align="center">
  <strong>高性能内网资产边界测绘与安全审计引擎</strong><br>
  <em>High-Performance Intranet Asset Mapping & Security Auditing Engine</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-19C2FF.svg?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Engine-Asyncio-FF5C7A.svg" alt="Asyncio">
  <img src="https://img.shields.io/badge/Build-V24-success.svg" alt="Build">
  <img src="https://img.shields.io/badge/License-MIT-gray.svg" alt="License">
</p>

---

## 📖 简介 | Introduction

**[中文]**
**HighRiskPortHunter** 是一款专为红蓝对抗、企业内网测绘与资产漏洞治理打造的高性能图形化安全审计引擎。由安全从业者 **Lucius** 倾力开发，工具底层采用纯异步（`Asyncio`）发包架构，不仅拥有摧枯拉朽的并发探测能力，更首创了**“智能混合渲染机制”**——彻底解决了传统安全工具在面对海量扫描数据时引发的 UI 卡死痛点。配合全手工打磨的沉浸式暗黑控制台，为您带来丝滑、专业的极客安全体验。

**[English]**
**HighRiskPortHunter** is a high-performance, graphical security auditing engine built for Red/Blue teaming, enterprise intranet mapping, and asset vulnerability management. Developed by security practitioner **Lucius**, it utilizes a pure `asyncio` packet-sending architecture, delivering devastating concurrent scanning power. Its pioneered **"Smart Hybrid Rendering Mechanism"** completely eliminates the UI freezing issues typical of traditional security tools when handling massive scan data. Combined with a handcrafted immersive dark console, it provides a seamless, professional geek experience.

---

## ✨ 核心壁垒 | Core Highlights

* ⚡ **无感并发探测 (Stealth & Speed)**：基于底层协程，支持千级动态并发与滑动窗口速率限制。
* 🛡️ **深层协议鉴定 (Deep Fingerprinting)**：智能 Banner 抓取与深度握手交互验证，精准剔除防火墙误报。
* 🌌 **极客暗黑工作台 (Dark-Mode Console)**：定制无边框 UI，`<HighRisk>` 专属危险色高亮标识。
* 📦 **万级数据承载 (Massive Payload Ready)**：前 500 条数据实时上屏，超量自动平滑降级静默收集，支持导出 `.xlsx` / `.html`。

---

## 🚀 适用场景 | Scenarios

* **蓝队 / 桌面运维**：清点私自开放的违规高危端口（如 445, 3389, 6379, 7001 等）。
* **红队 / 渗透测试**：授权项目中的横向移动前置信息收集，极速锁定脆弱资产。

---

## 🛠️ 安装与运行 | Setup & Run

工具为独立免安装版本，完全离线运行，无需任何环境配置。
The tool is a portable standalone executable. It runs completely offline with no environment configuration required.

**[中文]**
1. 前往本仓库的 **[Releases 页面](../../releases)**。
2. 下载最新版本的压缩包（例如 `HighRiskPortHunter_V24_Windows.zip`）。
3. 解压压缩包后，双击运行 `HighRiskPortHunter.exe` 即可**开箱即用**。

**[English]**
1. Go to the **[Releases page](../../releases)** of this repository.
2. Download the latest ZIP file (e.g., `HighRiskPortHunter_V1.0.zip`).
3. Extract the archive and double-click `HighRiskPortHunter.exe` to run. **Ready to use out of the box.**

---

## 📸 猎测视角 | UI Preview

*(Place your screenshot here / 将运行截图命名为 `screenshot.png` 放置在项目根目录)*
![HighRiskPortHunter Console](screenshot.png)

---

## ⚠️ 免责声明 | Disclaimer

**[中文]**
本工具仅限用于**获取合法授权**的企业安全建设、合规性内网审计及安全教育研究用途。使用者应当严格遵守所在国家或地区的网络安全相关法律法规。下载、运行或分发本工具即表示您同意：**对于任何非法使用行为，开发者 (Lucius) 不承担任何直接、间接或连带的法律责任**。

**[English]**
This tool is strictly intended for **legally authorized** enterprise security auditing, compliance mapping, and educational research. Unauthorized illegal scanning or offensive attacks are strictly prohibited. By downloading, running, or distributing this tool, you agree that **the developer (Lucius) bears no direct, indirect, or joint legal responsibility for any illicit usage**.

---

## 📜 许可证 | License

Powered by Asyncio & Tkinter.
This project is licensed under the [MIT License](LICENSE). 
Designed & Developed with ⚔️ by **Lucius**.

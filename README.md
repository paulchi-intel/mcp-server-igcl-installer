# MCP Server for IGCL 安裝指南 / MCP Server for IGCL Installation Guide

> 本專案為 IGCL 概念驗證（Proof of Concept, PoC），僅實作部分功能，並基於 IGCL 0.95 版本開發。

<img src="mcp-server-igcl-icon.png" alt="MCP Server IGCL Icon" width="120" />

[繁中](#繁體中文) / [English](#english)

## 繁體中文

這份指南將引導您完成MCP Server的安裝和配置過程。這是一個概念驗證（PoC），並未完全實作IGCL的所有功能，且是使用IGCL 0.95版開發的。

### 演示影片

觀看[示範影片](demo_video_usage.mp4)以了解完整的安裝和使用流程。

## 系統需求

- 作業系統：Windows 10 或更新版本
- 必須安裝 Claude Desktop
- 網際網路連線

## 安裝步驟

1. 下載、安裝並登入 Claude Desktop [下載連結](https://claude.ai/download)
2. 將 "mcp_server_igcl" 資料夾複製到 C:\ (或其他位置)
3. 點擊Claude Desktop左上角的 漢堡選單 / 檔案 / 設定... / 開發者 / 編輯配置
4. 開啟並編輯 "claude_desktop_config.json"，將路徑更改為 "mcp_server_igcl" 所在位置。
5. 重啟設備並重新啟動 Claude Desktop。

## 常見問題

- **問題：MCP Server 無法啟動。**
  - 解決方案：檢查配置檔案中的路徑是否正確，並確認所有檔案已完整複製。

- **問題：無法下載 Claude Desktop。**
  - 解決方案：檢查您的網際網路連線，或嘗試使用其他網路。

## 聯絡我們

如有任何問題，請聯絡 paul.chi@intel.com。

## English

This guide will walk you through the installation and configuration of the MCP Server. This is a Proof of Concept (PoC) and does not fully implement all IGCL features. It was developed using IGCL version 0.95.

### Demo Video

Watch the [demonstration video](demo_video_usage.mp4) to understand the complete installation and usage process.

## System Requirements

- Operating System: Windows 10 or later
- Claude Desktop must be installed
- Internet connection

## Installation Steps

1. Download, install, and login to Claude Desktop [Download Link](https://claude.ai/download)
2. Copy the "mcp_server_igcl" folder to C:\ (or any other location)
3. At upper-left corner of Claude Desktop, click Hamburger Menu / File / Settings... / Developer / Edit Config
4. Open and edit "claude_desktop_config.json", change the path to where "mcp_server_igcl" is located.
5. Reboot the device and launch Claude Desktop again.

## FAQ

- **Issue: MCP Server cannot start.**
  - Solution: Check if the path in the configuration file is correct and ensure all files are completely copied.

- **Issue: Unable to download Claude Desktop.**
  - Solution: Check your internet connection or try using a different network.

## Contact Us

For any questions, please contact paul.chi@intel.com. 
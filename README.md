
# OpenShift-Practice

這個 Git 倉庫是用來記錄與實作 OpenShift 的各種操作與實戰練習，包含部署流程、升級策略、常見問題排解、以及自動化腳本等內容。目的是建立一個結構化的學習與實驗平台，幫助自己與他人更有效率地掌握 OpenShift 的使用與管理。

---

## 🖥️ 使用環境

Proxmox 目前配置：
- CPU1: E5 2699v4 22 Core
- CPU2: E5 2699v4 22 Core
- RAM: 128 GB
- SSD: 2 TB

本練習環境主要部署於 Proxmox 虛擬化平台，包含以下架構：

- 多台虛擬機作為 OpenShift 節點（Master / Worker）
- Master Node (4vCPU/16G) x3
- Worker Node (6vCPU/16G) x2
- (Feature) 搭配 Ansible Automation Platform 進行自動化設定與管理

docs/ 放置一些筆記或教學文件，例如：
- OpenShift 架構簡介
- 安裝流程紀錄
- 常見問題與Troubleshooting
- 升級策略

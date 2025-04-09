# OpenL 公益镜像项目

> 为开发者和科研用户打造的轻量级公益镜像系统，提供对 GitHub、HuggingFace 等网站的访问加速服务，并集成基础 DNS 解毒工具。

---

## ✨ 功能简介

- 📦 **GitHub 镜像访问**
  - 支持网页浏览、Release 下载、Git Clone 反代

- 🧠 **HuggingFace 镜像代理**
  - 支持模型 checkpoint 和 dataset 中转下载

- 🌐 **DNS 污染规避服务**
  - 提供 DoH 查询接口，辅助解决国内 DNS 劫持问题

- 🛠️ **用户工具**
  - 一键设置 hosts 文件、DNS 配置（Windows/Linux）

---

## 📦 快速部署

### 使用 Docker 一键启动

```bash
git clone https://github.com/yourname/openl.git
cd openl/deploy
docker-compose up --build

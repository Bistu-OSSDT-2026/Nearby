# Nearby — 校园二手物品交易平台

> 一个专为在校大学生设计的轻量级二手物品交易平台，让闲置流转更简单、更可信。

---

## 📖 项目简介

Nearby 是一个面向校园场景的开源二手交易网站。通过校园邮箱认证构建纯净的交易环境，帮助同学们便捷地发布和淘取教材、电子产品、生活用品等闲置物品，促进校园资源的循环利用。

---

## ✨ 核心功能

- 🔐 **校园邮箱认证**：使用学号和校园邮箱注册，保障身份真实可信
- 📦 **商品发布**：支持图文描述、分类标签、价格设定，一键上架
- 🔍 **智能筛选**：按分类（教材/数码/生活用品等）、价格区间快速定位目标商品
- 💬 **站内私信**：买家和卖家实时沟通，协商价格和面交地点
- 📋 **个人中心**：统一管理我的发布、我的私信、购买记录
- 🏷️ **商品状态**：交易完成后标记"已售出"，保持信息实效性

---

## 🛠️ 技术栈

| 模块 | 技术选型 |
|---|---|
| 前端 | HTML / CSS / JavaScript |
| 后端 | Node.js |
| 数据库 | JSON 文件存储（server/data.json） |

---

## 🚀 快速开始

### 环境要求

| 项目 | 要求 |
|---|---|
| Node.js | 18+ 版本 |
| npm | 随 Node.js 自带 |
| 操作系统 | Windows / Mac / Linux 均可 |
| 端口 | 3000（可修改） |
| 网络 | 校园网内网即可 |

> 📌 当前版本数据库使用 `server/data.json` 本地文件存储，无需额外安装数据库服务。

---

### 安装步骤

1. 克隆仓库
   ```bash
   git clone https://github.com/Bistu-OSSDT-2026/Nearby.git
   cd Nearby
2. 安装依赖
   ```bash
   cd server
   npm install
3. 配置环境变量（可选）
   ```js
   const PORT = process.env.PORT || 3000;  // 将 3000 改为其他端口号
4. 初始化数据库
   首次运行时会自动创建 server/data.json 数据文件，无需手动操作。
5. 启动项目
   ```bash
   npm start
6. 访问应用
   打开浏览器访问 http://localhost:3000 即可开始使用。

### 📁 项目结构

```Nearby/
├── server/
│   ├── server.js          # 后端入口文件
│   ├── data.json          # 数据库文件（首次运行自动生成）
│   └── package.json       # 后端依赖配置
├── frontend/              # 前端代码
├── README.md              # 项目说明
├── LICENSE                # 开源许可证
└── CONTRIBUTING.md        # 贡献指南
```

## 👥 贡献者

感谢以下同学对本项目的贡献：

- [@di1687](https://github.com/di1687) - 项目负责人 / 后端开发  
- [@di1687](https://github.com/di1687) - 前端开发  
- [@di1687](https://github.com/di1687) - 数据库设计 / 测试  
- [@kgualhy](https://github.com/kgualhy) - 测试
- [@ppwulang](https://github.com/ppwulang) - 测试
### 📄 开源协议
本项目采用 MIT License 开源协议。

### 📬 联系方式
项目地址：https://github.com/Bistu-OSSDT-2026/Nearby
问题反馈：请提交 Issue

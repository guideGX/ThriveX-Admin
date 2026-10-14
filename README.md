<p align="center">
    <a href="https://liuyuyang.net" target="_blank">
        <img width="120" src="https://bu.dusays.com/2024/11/17/6739adf188f64.png" alt="ThriveX logo" />
    </a>
</p>
<h1 align="center" style="margin: 20px 0; font-weight: 700; padding-bottom:10px;">ThriveX Admin</h1>


<p align="center">
    <a href="https://github.com/LiuYuYang01/ThriveX-Admin/blob/main/LICENSE" target="_blank">
        <img alt="License: AGPL-3.0" src="https://img.shields.io/badge/License-AGPL--3.0-blue.svg?style=flat-square&logo=gnu" />
    </a>
    <a href="https://github.com/LiuYuYang01/ThriveX-Admin/stargazers" target="_blank">
        <img alt="Stars" src="https://img.shields.io/github/stars/LiuYuYang01/ThriveX-Admin?style=flat-square&logo=github&color=gold" />
    </a>
    <a href="https://github.com/LiuYuYang01/ThriveX-Admin/network" target="_blank">
        <img alt="Forks" src="https://img.shields.io/github/forks/LiuYuYang01/ThriveX-Admin?style=flat-square&logo=github" />
    </a>
    <a href="https://github.com/guideGX/ThriveX-Admin/actions/workflows/ci.yml" target="_blank">
        <img alt="CI" src="https://github.com/guideGX/ThriveX-Admin/actions/workflows/ci.yml/badge.svg" />
    </a>
</p>

---

> ### 🍴 关于本仓库
>
> 本仓库是 [**LiuYuYang01/ThriveX-Admin**](https://github.com/LiuYuYang01/ThriveX-Admin) 的 **Fork**，用于个人学习与前端工程化实践，**并非上游官方仓库**。
> 上游作者：[刘宇阳](https://github.com/LiuYuYang01)，版权归原作者所有；原项目以 **AGPL-3.0** 开源，本仓库同步遵循同一协议。
>
> - 需要最新功能、官方文档与技术支持 → 请前往[上游仓库](https://github.com/LiuYuYang01/ThriveX-Admin)与[文档中心](https://docs.liuyuyang.net)
> - 想了解本 fork 增加了什么 → 见 [本 fork 的改动](#本-fork-的改动)

## 📖 项目简介

**ThriveX Admin** 是 ThriveX 博客系统的现代化管理后台，采用 Next.js 15 + React 19 + Ant Design 构建，提供全功能的内容管理、用户管理、系统配置等一站式解决方案。

作为 ThriveX 全栈解决方案的核心组成部分，Admin 控制端与前端博客（[ThriveX-Blog](https://github.com/LiuYuYang01/ThriveX-Blog)）和后端服务（[ThriveX-Server](https://github.com/LiuYuYang01/ThriveX-Server)）共同构成了一个完整的开源博客生态系统。



## ✨ 核心特性

- 🎨 **现代化 UI**：基于 Ant Design 6.x + Tailwind CSS 4.x，提供优雅的视觉体验
- 📝 **富文本编辑器**：集成 WangEditor + ByteMD，支持 Markdown/HTML 双模式
- 📊 **数据可视化**：ECharts 图表展示访问统计、文章分类、用户增长等关键指标
- 🎯 **权限管理**：细粒度的 RBAC 权限控制，支持角色分配与权限配置
- 📋 **操作日志**：管理端写操作自动留痕，支持筛选、详情、批量删除与清空
- 📁 **文件管理**：支持本地存储与多种 OSS 服务商（阿里云、腾讯云、七牛云等）
- 📧 **邮件系统**：内置 SMTP 邮件服务，支持评论回复、通知推送
- 📱 **响应式设计**：完美适配桌面端与平板设备
- 🌓 **暗色模式**：支持主题切换，保护用户视力
- ⚡ **性能优化**：代码分割、懒加载、缓存策略，确保极致性能



## 📸 界面预览

<div align="center">
    <img src="https://bu.dusays.com/2026/03/08/69ad27c95c51f.jpg" alt="ThriveX Admin Dashboard" style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.1)" />
</div>


## 🚀 快速开始

https://docs.liuyuyang.net/docs/项目部署/1Panel.html



## 📂 项目结构

```
ThriveX-Admin/
├── src/
│   ├── api/              # API 接口定义
│   ├── components/       # 公共组件
│   ├── hooks/            # 自定义 Hooks
│   ├── layout/           # 布局组件
│   ├── pages/            # 页面路由
│   │   ├── article/      # 文章管理
│   │   ├── cate/         # 分类管理
│   │   ├── comment/      # 评论管理
│   │   ├── config/       # 系统配置
│   │   ├── dashboard/    # 仪表盘
│   │   ├── file/         # 文件管理
│   │   ├── storage/      # 存储配置
│   │   └── user/         # 用户管理
│   ├── services/         # 服务层
│   ├── stores/           # 状态管理
│   ├── styles/           # 样式文件
│   ├── types/            # TypeScript 类型定义
│   └── utils/            # 工具函数
├── public/               # 静态资源
├── .env                  # 环境变量配置
├── package.json          # 项目配置
└── vite.config.js        # Vite 配置
```



## 🌐 项目链接

| 名称        | 链接                                                                                         | 说明         |
| ----------- | -------------------------------------------------------------------------------------------- | ------------ |
| 博客预览    | [https://liuyuyang.net](https://liuyuyang.net)                                               | 前端博客展示 |
| 官网地址    | [https://thrivex.liuyuyang.net](https://thrivex.liuyuyang.net)                               | 项目官网     |
| 文档中心    | [https://docs.liuyuyang.net](https://docs.liuyuyang.net)                                     | 使用文档     |
| GitHub 主页 | [https://github.com/LiuYuYang01/ThriveX-Admin](https://github.com/LiuYuYang01/ThriveX-Admin) | 源码仓库     |



## 本 fork 的改动

本 fork 与上游 `main` 保持同步，**不修改上游业务代码**，只在其之上补充工程化能力。

| 类别 | 内容 |
| --- | --- |
| 持续集成 | 新增 `.github/workflows/ci.yml`：ESLint 检查 → 生产构建 → 归档 `dist` 产物 |
| 持续部署 | 新增 `.github/workflows/deploy.yml`：手动触发，构建 Docker 镜像推送 GHCR，可 SSH 远程发布或发布到 Vercel |
| 文档 | 补充 Fork 说明与 CI/CD 使用文档 |

> 之所以不改上游代码，是为了后续能直接 `git fetch upstream && git merge upstream/main` 同步，避免冲突。



## ⚙️ CI/CD

### 持续集成 `.github/workflows/ci.yml`

| 触发事件 | 说明 |
| --- | --- |
| `push` → `main` | 推送到主分支时自动运行 |
| `pull_request` → `main` | 提交 PR 时自动校验 |
| `workflow_dispatch` | 在 Actions 页面手动触发 |

执行步骤：

1. **安装依赖** —— `npm ci`，严格按 `package-lock.json` 安装，保证与本地环境一致
2. **代码检查** —— `npm run lint`（ESLint 9 Flat Config）
3. **生产构建** —— `npm run build`（Vite 7）
4. **归档产物** —— 上传 `dist` 到 Actions Artifacts，保留 7 天

运行时 Node.js 固定为 **22**，满足 `package.json` 中 `engines` 的 `node >= 20` 要求；启用并发控制，同一分支只保留最新一次运行。

#### 可选：在 CI 中覆盖后端 API 地址

仓库内的 `.env` 只保存了占位地址。若希望 CI 构建出的产物指向真实后端，可在
**Settings → Secrets and variables → Actions → Variables** 中新增仓库变量：

| 变量名 | 示例值 |
| --- | --- |
| `VITE_PROJECT_API` | `https://api.example.com/api` |

未配置时，构建会直接使用仓库内 `.env` 的内容。



### 持续部署 `.github/workflows/deploy.yml`

该流水线**只在手动触发时执行**（`workflow_dispatch`），不会随 `push` 自动发布，因此未配置服务器时也不会在提交历史里留下失败记录。

在 **Actions → Deploy → Run workflow** 中选择部署目标：

| 目标 | 说明 |
| --- | --- |
| `docker` | 构建镜像并推送到 GitHub Container Registry（`ghcr.io`），再 SSH 到服务器拉取新镜像重启容器 |
| `vercel` | 通过 Vercel CLI 构建并发布到 Vercel |
| `both` | 同时执行以上两条 |

Docker 部署需要在服务器放置 `docker-compose.yml`（仓库内已提供模板），并把 `<OWNER>` 替换为你的 GitHub 用户名。

按下表配置 Secrets / Variables 后对应任务才会生效，未配置的任务会被自动跳过：

| 名称 | 类型 | 必填 | 说明 |
| --- | --- | --- | --- |
| `VITE_PROJECT_API` | Variable | 否 | 构建时注入的后端 API 地址 |
| `DEPLOY_HOST` | Variable | 是（SSH 部署） | 服务器 IP 或域名 |
| `DEPLOY_USER` | Variable | 是（SSH 部署） | SSH 登录用户名 |
| `DEPLOY_PATH` | Variable | 是（SSH 部署） | 服务器上存放 `docker-compose.yml` 的目录 |
| `DEPLOY_PORT` | Variable | 否 | SSH 端口，默认 22 |
| `DEPLOY_SSH_KEY` | Secret | 是（SSH 部署） | SSH 私钥，用于免密登录 |
| `VERCEL_TOKEN` / `VERCEL_ORG_ID` / `VERCEL_PROJECT_ID` | Secret | 是（Vercel 部署） | Vercel 项目凭据 |

#### 首次启用 Actions

Fork 仓库的 Actions 默认处于关闭状态。首次进入 **Actions** 标签页时，点击
**I understand my workflows, go ahead and enable them** 即可启用。



## 💻 本地开发

```bash
# 环境要求：Node.js >= 20、npm >= 10
npm ci            # 按锁定版本安装依赖
npm run dev       # 启动开发服务器，默认 http://localhost:9100
npm run lint      # 代码检查
npm run build     # 生产构建，产物输出到 dist/（内部先执行 eslint 再 vite build）
npm run preview   # 本地预览构建产物
```

构建前请确认 `.env` 中的 `VITE_PROJECT_API` 指向可用的后端服务地址。



## 📝 开源协议

本项目采用 **AGPL-3.0** 许可证。

**使用须知**：

- ✅ 允许商业使用、修改、分发
- ✅ 必须保留原始版权说明
- ✅ 修改后的版本必须开源
- ❌ 禁止任何闭源商业行为

在项目 Star 突破 2K 后，您可以自由选择保留或删除版权信息。



## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=LiuYuYang01/ThriveX-Admin&type=Date)](https://star-history.com/#LiuYuYang01/ThriveX-Admin&Date)



## 👨‍💻 作者信息

**刘宇阳**

- GitHub: [@LiuYuYang01](https://github.com/LiuYuYang01)
- 我的博客: [https://liuyuyang.net](https://liuyuyang.net)
- 关于我：[https://my.liuyuyang.net](https://my.liuyuyang.net)
- 邮箱: [liuyuyang1024@yeah.net](mailto:liuyuyang1024@yeah.net)



## 💬 交流群

欢迎加入 ThriveX 官方交流群，与开发者和其他用户交流：

<div align="center">
    <img src="https://bu.dusays.com/2025/06/03/683e96eb43ad8.jpg" alt="WeChat Group" style="width: 300px; border-radius: 8px;" />
</div>

**加群方式**：添加微信 `liuyuyang2023`，备注 "ThriveX"



## 🙏 鸣谢

感谢所有为 ThriveX 项目做出贡献的开发者和用户！

特别感谢以下项目提供的灵感与技术支持：

- [zw-blog](https://blog.zwying.com/)
- [blatr](https://www.blatr.cn/)
- [poetize](https://poetize.cn/)



## 🔒 免责声明

本项目仅供学习交流使用，不提供任何技术咨询或技术支持服务。使用者在使用本项目时应遵守当地法律法规，不得用于任何违法活动。

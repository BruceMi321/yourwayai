# YourWayAI 开源导航站

![VitePress](https://img.shields.io/badge/VitePress-1.6.4-blue?style=flat-square&logo=vitepress)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

发现并探索优质的免费开源软件，告别高昂订阅费，拥抱开源社区的力量。

## 🌟 项目特色

- **精选分类**：涵盖笔记、知识库、媒体影音、生产力工具等多个领域。
- **现代化设计**：基于 VitePress 构建，响应式布局，极速访问。
- **自动化收录**：内置自动化脚本，一键将 GitHub 仓库转为文档页面。
- **GitHub Pages 部署**：通过 GitHub Actions 实现自动化构建与发布。

## 🚀 快速开始

### 1. 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run docs:dev
```

### 2. 构建生产版本

```bash
npm run docs:build
```

## 🤖 自动化收录工具

本项目内置了一个强大的自动化脚本，可以从 GitHub 链接直接生成文档。

**运行方法：**

```bash
npm run add-tool -- https://github.com/用户名/仓库名
```

**该命令会自动执行：**
1. 抓取 GitHub 仓库元数据。
2. 生成对应的 Markdown 文档。
3. 自动更新侧边栏导航。
4. 提交并推送到远程仓库。

## 📂 目录结构

```text
yourwayAI/
├── docs/               # 文档源码
│   ├── .vitepress/    # VitePress 配置
│   ├── tools/         # 工具介绍页面
│   └── index.md       # 首页
├── scripts/            # 自动化脚本
└── package.json        # 项目配置
```

## 📄 开源协议

本项目基于 [MIT License](LICENSE) 开源。

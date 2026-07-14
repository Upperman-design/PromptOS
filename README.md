# PromptOS - AI 创作工作台

> AI Prompt 管理工具 —— 设计师的 AI 创作资产管理平台

一个单文件的 AI Prompt 管理原型，帮助设计师和创作者管理、分析、优化 AI 绘画 Prompt。

## ✨ 功能特性

- **AI 视觉解析** - 上传图片，AI 自动分析画面内容并生成结构化 Prompt
- **Prompt 构建器** - 积木式模块化编辑器，拖拽组合 Prompt 元素
- **智能标签筛选** - 按平台、标签、收藏夹多维度管理
- **AI 分析详情** - Chip 标签式展示主体/风格/色彩/构图等视觉分析
- **Ctrl+K 搜索** - 命令面板风格全局搜索
- **本地优先** - 所有数据存储在浏览器 localStorage，隐私安全
- **数据导入导出** - JSON 格式备份恢复

## 🚀 快速开始

### 在线体验

访问 **[GitHub Pages 演示地址](https://YOUR_USERNAME.github.io/PromptOS)** 直接在浏览器中使用。

### 本地使用

1. 下载  文件
2. 用浏览器直接打开即可使用
3. 首次使用请在右上角 ⚙️ 设置中配置 AI API

## ⚙️ AI API 配置

支持以下 OpenAI 兼容的视觉模型 API：

| 平台 | 推荐模型 | 备注 |
|------|---------|------|
| 通义千问 DashScope | qwen-vl-max | 浏览器 CORS 支持最好 |
| Moonshot (月之暗面) | moonshot-v1-32k-vision | |
| 智谱 AI | glm-4v | |
| OpenAI | gpt-4o | 可能需要代理 |

## 🛠️ 技术栈

- **React 18** (CDN)
- **Babel Standalone** (浏览器端 JSX 编译)
- **内联 SVG 图标** (stroke-based, 无外部依赖)
- **localStorage** (数据持久化)
- **单文件 HTML** (零构建, 零部署)

## 📄 开源协议

[MIT License](LICENSE) - 自由使用、修改和分发

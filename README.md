# AIDailySignal

> 每日 AI 领域要闻速递，关注 AI 编程与开发工具最新动态。

## 简介

AIDailySignal 每天自动收集 AI 领域（特别是 AI Coding 方向）的最新新闻，整理成结构化的中文日报，归档到本仓库。

## 运行方式

### 手动触发（Claude Code）

在本项目目录下打开 Claude Code，输入：

```
/daily-signal
```

Claude 会自动搜索最新 AI 新闻、生成日报、提交并推送到 GitHub。

### 自动运行（GitHub Actions）

每天北京时间 09:00 自动运行，也可以在 GitHub Actions 页面手动触发。

需要在仓库 Settings > Secrets > Actions 中添加 `ANTHROPIC_API_KEY`。

## 文件结构

日报按年月归档：

```
2026/
├── 01/
│   ├── 2026-01-01.md
│   └── ...
├── 02/
│   └── ...
└── 03/
    └── ...
```

## 日报内容

每期日报包含 8-15 条精选新闻，分为以下板块：

- **重要新闻** — 行业重大发布、融资、突破性进展
- **AI 编程与工具** — AI Coding 工具、IDE、代码助手更新
- **研究与技术** — 新论文、新模型、技术突破
- **行业动态** — 公司动态、产品发布、市场变化

## License

MIT

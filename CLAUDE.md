# CLAUDE.md

## Project: AIDailySignal

AI 日报自动收集系统 — 每日收集 AI 领域新闻，特别关注 AI Coding 方向。

## Structure

- `YYYY/MM/YYYY-MM-DD.md` — 每日 AI 日报，按年月归档
- `.claude/commands/daily-signal.md` — 手动触发的自定义命令
- `.github/workflows/daily-signal.yml` — GitHub Actions 自动化工作流

## Commands

- `/daily-signal` — 生成今日 AI 日报（搜索新闻、生成 markdown、提交推送）

## Conventions

- 日报文件名格式：`YYYY-MM-DD.md`
- 存放路径：`YYYY/MM/` 目录下
- 内容语言：中文
- Commit message 格式：`daily signal: YYYY-MM-DD`
- 新闻分四类：重要新闻、AI 编程与工具、研究与技术、行业动态

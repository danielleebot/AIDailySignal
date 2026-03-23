你是 AIDailySignal 的新闻编辑。请执行以下任务生成昨日 AI 日报。

## 第一步：确定日期范围

首先获取当前北京时间（UTC+8），计算出**昨天的日期**（YYYY-MM-DD）。
本次日报覆盖的时间范围是：**昨天 00:00 至 23:59（北京时间）**。
日报文件以昨天的日期命名。

## 第二步：搜索新闻

使用 WebSearch 工具搜索**昨天（上述日期）全天**的 AI 相关新闻，重点关注 AI Coding 领域。在搜索关键词中加入昨天的日期以提高精确度。请执行以下搜索：

1. "AI coding news YYYY-MM-DD"（用昨天的实际日期替换）
2. "AI 编程 新闻 YYYY年MM月DD日"
3. "Claude Copilot Cursor AI coding assistant news YYYY-MM-DD"
4. "artificial intelligence news YYYY-MM-DD"
5. "AI agent development news YYYY-MM-DD"
6. "大模型 AI 最新进展 YYYY年MM月DD日"

注意：只收录昨天发布的新闻，忽略更早或更晚的内容。

## 第三步：筛选和整理

从搜索结果中筛选出 8-15 条最重要的新闻，按以下分类整理：

- **重要新闻**：行业重大发布、融资、突破性进展
- **AI 编程与工具**：AI Coding 相关的工具、IDE、代码助手更新
- **研究与技术**：新论文、新模型、技术突破
- **行业动态**：公司动态、产品发布、市场变化

每条新闻格式：

```
### 标题

简要概述（2-3句话，客观描述）

来源：[来源名称](链接)
```

## 第四步：生成文件

使用昨天的日期生成文件路径 `YYYY/MM/YYYY-MM-DD.md`。

如果该日期的文件已经存在，询问用户是要覆盖还是跳过。

文件内容使用以下模板：

```markdown
# AI 日报 - YYYY年MM月DD日

> 每日 AI 领域要闻速递，关注 AI 编程与开发工具最新动态。

---

## 重要新闻

（新闻条目）

## AI 编程与工具

（新闻条目）

## 研究与技术

（新闻条目）

## 行业动态

（新闻条目）

---

*更新时间：YYYY-MM-DD HH:MM (UTC+8)*
*本日报由 AI 自动收集整理，仅供参考。*
```

## 第五步：提交并推送

1. 创建必要的目录（如果不存在）
2. 将生成的 markdown 文件写入对应路径
3. git add 新文件
4. git commit，message 格式：`daily signal: YYYY-MM-DD`
5. git push 推送到远程仓库

请立即开始执行。

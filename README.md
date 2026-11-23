# 👋 你好，我是 shenhui

**全栈开发者 · 求职中** · 专注 Web 全栈应用、AI Agent 记忆 / 知识工程与本地优先工具

我喜欢把想法做成"能跑的系统"：先立方法论，再用代码验证，最后沉淀成文档。

## 🛠 技术栈

| 方向 | 技术 |
|---|---|
| 后端 | Node.js · Express · Python · REST API · SSE |
| AI 应用 | LLM 应用开发 · MCP（Model Context Protocol）· 混合检索（FTS5 + 向量 / RRF）· 提示词工程 |
| 数据库 | SQLite（better-sqlite3 / WAL / FTS5 / sqlite-vec）· NetworkX |
| 前端 | Vue 3 · Vite · Element Plus · HTML / CSS / JavaScript |
| 工程 | Git · GitHub Actions · pytest · Vitest · node:test · Ruff · Pydantic · Typer |
| 兴趣 | Agent 记忆 · 个人知识管理 · 自动化管线 · 隐私与安全工程 |

## 🚀 代表项目

### 1. JVS · 时序-因果知识图谱（jvs-causal-graph）
[🔗 GitHub](https://github.com/shenhui-ui/jvs-causal-graph)

面向个人 AI Agent 的**本地优先时序-因果图谱 + 跨会话因果问答引擎**。

- **技术栈**：Python · SQLite FTS5 trigram · sqlite-vec · NetworkX · Pydantic · Typer · MCP ≥ 2.0
- **工程亮点**：强 / 弱 / 待定三级因果边 + 置信度闸门；双态双向 BFS（弱线索不阻断强因果链）；证据不足时自动优雅降级（`no_chain` / `low_confidence` / `weak_only`），避免编造因果；任何 LLM / 嵌入调用前先过 fail-closed 隐私闸门；同时提供 CLI、Python SDK、MCP Server（可接入 Claude Code / Cursor 等）；离线 pytest + GitHub Actions CI；MIT 许可

### 2. 文玺 · 单位台账管理系统（xinxi）
[🔗 GitHub](https://github.com/shenhui-ui/xinxi)

面向机关单位办公场景的**本地全栈台账系统**：7 大业务模块（任务 / 会议 / 文件收发 / 外出活动 / 用章 / 物资 / 统计驾驶舱）+ 附件管理 + AI 公文写作 + 公文 Word / 台账 Excel 导出 + UI 术语手册。

- **技术栈**：Node.js + Express + better-sqlite3（WAL）；Vue 3 + Vite + Element Plus
- **工程亮点**：通用 CRUD 构造器统一提供**乐观锁**（版本冲突返回 409）、软删除、分页、关键词搜索与级联清理；附件上传做 uuid 重命名与防路径遍历；公文 / 台账导出支持同步与异步双分支；含单元测试、1 万条数据压测与性能基准脚本；GitHub Actions CI（测试 + 构建）

### 3. QoderDaddy
[🔗 GitHub](https://github.com/shenhui-ui/QoderDaddy)

Qoder CN 官方 App Plugin 形态的**本地增强层**（WorkDaddy 的衍生作品，AGPL-3.0，pre-release）。

- **技术栈**：Node.js（CommonJS）· 宿主 pluginHost RPC · node:test · GitHub Actions
- **工程亮点**：白名单回传，零凭据外流；配置快照写盘前递归扫描疑似凭据键，命中即放弃写入；含 fsync 的原子写 + Windows rename 退避重试；配置的"缺失 / 解析失败 / 结构非法 / 为空"四种状态可区分；`PROVENANCE.md` 逐项记录代码来源

### 4. 自生长知识库（knowledge-base）
[🔗 GitHub](https://github.com/shenhui-ui/knowledge-base)

基于 **Karpathy LLM Wiki 方法论** 的本地知识库，用 Python 自动化管线实现"素材收件箱 → 结构化 Wiki 文章 → 可检索"的闭环。

- **规模**：176 篇 Wiki 文章 · 25 个 Python 模块 · 11 个 pytest 测试文件
- **每日定时管线**：01:00 自动生成日报 → 运行健康检查 → 失败自动重试
- **LLM 成本记账**：包含缓存命中统计，运行成本透明可审计

### 5. wiki-manager Skill（obsidian-skill-wiki-manager）
[🔗 GitHub](https://github.com/shenhui-ui/obsidian-skill-wiki-manager)

把知识库方法论**产品化打包**成可安装的 Claude Skill：SKILL.md + 3 个 Python 脚本，提供 **init / ingest / query / lint** 四种能力（搭建 9 分区骨架、收件箱提炼、自然语言检索、六类一致性体检），附万字使用 / 改造 / 排错教程。

## 💬 最近在做

- 为 JVS 完善中文文档、架构图与正式 Release
- 为各项目补齐 CI、界面截图与开源许可证
- 通过 good-first-issue 持续参与开源贡献

## 📈 GitHub 统计

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shenhui-ui&show_icons=true&hide=stars,contribs&theme=vue" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shenhui-ui&layout=compact&theme=vue" alt="Top Languages" />
</p>

## 📫 联系我

- 📧 邮箱：17602305106@163.com
- 💬 微信：SH13557573458
- 🎯 求职方向：全栈开发 / Web 后端 / AI 应用开发

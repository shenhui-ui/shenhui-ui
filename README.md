# 👋 你好，我是 shenhui

**全栈开发者 · 求职中** · 专注 Web 全栈应用与 AI 知识库工程化

我喜欢把想法做成"能跑的系统"：先立方法论，再用代码验证，最后沉淀成文档。目前每周投入 15h+ 持续构建和打磨自己的项目。

## 🛠 技术栈

| 方向 | 技术 |
|---|---|
| 后端 | Node.js · Express · Python · REST API |
| 数据库 | SQLite（better-sqlite3 / WAL） |
| 前端 | Vue 3 · Vite · Element Plus · HTML / CSS / JavaScript |
| 工程 | Git · npm · 单元测试 · 性能基准 · GitHub Actions |
| 兴趣 | LLM 应用 · 个人知识管理 · 自动化管线 |

## 🚀 代表项目

### 1. 文玺 · 单位台账管理系统（xinxi）
[🔗 GitHub](https://github.com/shenhui-ui/xinxi)

面向机关单位办公场景的**本地全栈台账系统**：7 大业务模块（任务 / 会议 / 文件收发 / 外出活动 / 用章 / 物资 / 统计驾驶舱）+ 附件管理 + AI 公文写作 + 公文 Word / 台账 Excel 导出 + UI 术语手册。

- **技术栈**：Node.js + Express + better-sqlite3（WAL）；Vue 3 + Vite + Element Plus
- **工程亮点**：通用 CRUD 构造器统一提供**乐观锁**（版本冲突返回 409）、软删除、分页、关键词搜索与级联清理；附件上传做 uuid 重命名与防路径遍历；公文 / 台账导出支持同步与异步双分支；含单元测试、1 万条数据压测与性能基准脚本

### 2. 自生长知识库（knowledge-base）
[🔗 GitHub](https://github.com/shenhui-ui/knowledge-base)

基于 **Karpathy LLM Wiki 方法论** 的本地知识库，用 Python 自动化管线实现"素材收件箱 → 结构化 Wiki 文章 → 可检索"的闭环。

- **每日定时管线**：01:00 自动生成日报 → 运行健康检查 → 失败自动重试
- **LLM 成本记账**：包含缓存命中统计，运行成本透明可审计

### 3. wiki-manager Skill（obsidian-skill-wiki-manager）
[🔗 GitHub](https://github.com/shenhui-ui/obsidian-skill-wiki-manager)

把知识库方法论**产品化打包**成可安装的 Claude Skill：SKILL.md + 3 个 Python 脚本，提供 **init / ingest / query / lint** 四种能力（搭建 9 分区骨架、收件箱提炼、自然语言检索、六类一致性体检），附万字使用 / 改造 / 排错教程。

## 💬 最近在做

- 为主项目补充 GitHub Actions CI、自动化测试与线上演示
- 通过 good-first-issue 持续参与开源贡献
- 深入打磨知识库管线，沉淀为系列技术文章

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

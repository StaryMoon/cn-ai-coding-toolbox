# AI 编程工具中文选型

> 按工作流整理 Codex、Claude Code、Gemini CLI、Cursor、Cline、Aider、Continue 等 AI 编程工具，帮助中文用户快速比较工具定位、适用场景和风险点。

<p align="left">
  <a href="https://github.com/StaryMoon/cn-ai-coding-toolbox"><img alt="stars" src="https://img.shields.io/github/stars/StaryMoon/cn-ai-coding-toolbox?style=flat&label=stars"></a>
  <img alt="category" src="https://img.shields.io/badge/AI%20%20%2F%20%20%E7%BC%96%E7%A8%8B-curated-blue">
  <img alt="language" src="https://img.shields.io/badge/language-中文-brightgreen">
</p>

![preview](assets/preview.png)

<sub>图片来源：公开入口预览图，[https://github.com/openai/codex](https://github.com/openai/codex)，截取/整理日期：2026-07-02。</sub>

## 定位

本仓库是一份面向中文用户的主题索引，重点整理常用、稳定、值得优先了解的工具入口，并补充适用场景、选型建议和风险边界。目标不是追求数量，而是降低第一次检索和筛选的成本。

- **主题**：AI / 编程
- **适合人群**：学生、研究生、开发者、开源维护者
- **首批重点**：OpenAI Codex CLI / Claude Code / Gemini CLI / Cursor / Cline
- **为什么值得整理**：AI coding 工具正在从补全走向 agent，中文资料常常只讲情绪不讲选型，这类页面很适合被搜索和收藏。

## 使用方式

1. 先看 [精选资源](#精选资源)，按自己的场景挑 2-3 个入口试用。
2. 再看 [选型建议](#选型建议)，避免一上来把同类工具全装一遍。
3. 如果用于课程、论文、开源项目或生产环境，务必看 [风险提醒](#风险提醒)。

## 收录口径

按实际编码位置分层：IDE、终端 agent、VS Code 插件、自托管补全。只收官方入口或活跃开源项目。

优先收录：

- 官方文档、官网、活跃 GitHub 仓库；
- 免费可试用或开源项目；
- 中文用户高频搜索、收藏、复用的工具；
- 入口稳定、说明清楚、维护状态可判断的资源。

暂不收录：

- 破解软件、灰色下载、账号代认证、返利推广；
- 长期不可访问或入口频繁变化的镜像；
- 只有营销话术、没有清晰文档的产品；
- 与本主题关系很弱的泛泛工具。

## 精选资源

| 名称 | 适合场景 | 入口 |
| --- | --- | --- |
| OpenAI Codex CLI | 终端 coding agent，适合本地仓库修改、测试、PR 小修。 | [访问](https://github.com/openai/codex) |
| Claude Code | Claude 生态 coding agent，适合长上下文和复杂任务拆解。 | [访问](https://docs.anthropic.com/en/docs/claude-code/overview) |
| Gemini CLI | Google Gemini 生态终端 agent，开源且热度高。 | [访问](https://github.com/google-gemini/gemini-cli) |
| Cursor | AI-first editor，适合需要完整 IDE 体验的用户。 | [访问](https://cursor.com/) |
| Cline | VS Code 内开源 autonomous coding agent。 | [访问](https://github.com/cline/cline) |
| Aider | Git/diff 驱动的经典终端 AI pair programmer。 | [访问](https://github.com/Aider-AI/aider) |
| Continue | 开源 AI coding assistant 平台，适合团队自定义。 | [访问](https://github.com/continuedev/continue) |
| Qwen Code | Qwen 生态终端 coding agent，中文用户值得关注。 | [访问](https://github.com/QwenLM/qwen-code) |
| OpenHands | 开源软件开发 agent，适合观察端到端任务执行。 | [访问](https://github.com/All-Hands-AI/OpenHands) |
| Tabby | 自托管代码补全和团队代码助手。 | [访问](https://github.com/TabbyML/tabby) |
| Windsurf | AI IDE，适合对比 Cursor 类产品体验。 | [访问](https://windsurf.com/) |
| Zed AI | 高速编辑器内置 AI 工作流。 | [访问](https://zed.dev/ai) |

## 选型建议

- 先选一种工作流：终端 agent、AI IDE、VS Code 插件。
- 小仓库试用：让工具读 README、修 bug、跑测试。
- 确认成本和权限后再交给它改大仓库。

## 风险提醒

- 避免向 agent 暴露生产密钥。
- 评估工具时同时关注编辑器适配、模型生态、权限边界和维护状态。

## 维护说明

- 本仓库会优先更新失效链接、官方入口变更和明显过时的描述。
- 新增资源请尽量给出官网、GitHub 仓库、文档页或可验证的公开说明。
- 推荐新资源时，请说明具体场景和选择理由，避免只写泛泛评价。

## 数据文件

结构化数据见 [`data/links.json`](data/links.json)，可用于脚本生成网页、表格或个人导航页。

## Contributing

欢迎提交 PR 修正链接、补充官方文档、更新截图或改进中文说明。请保持描述短、准、可验证。

## License

MIT。第三方商标、截图、网页内容和产品名称归各自权利方所有，本仓库只做索引和学习整理。

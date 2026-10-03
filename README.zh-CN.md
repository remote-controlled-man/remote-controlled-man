# Steven huang

**Agent 系统 · 智能体评测 · 多模态交互**

[English](./README.md) · **简体中文**

我目前在**香港大学**攻读计算机硕士，关注**自进化 Agent、Harness 与评测、实时多模态交互**。目前在**蚂蚁集团**实习，负责 AI 量化研究中从因子库到策略生成与回测反馈的完整链路，探索自进化 Loop 驱动的因子挖掘；此前在 **Cybopal / 细胞壁科技**实习，负责 Agent 评测、Harness 设计与全双工端到端多模态 Interaction Model 研究，也曾在**快手**从事多媒体评测与后端开发。我还在开发 [skillfit](https://github.com/remote-controlled-man/skillfit)，并参与 Agent 生态的开源贡献。

## 开源贡献

已向 **8 个上游项目提交 21 个已合并 PR**。下表精选代表性贡献，全部 21 个 PR 可在下方展开查看。

| 项目 · Star | 项目用途 | 我的已合并 PR | 贡献模块与代表改动 |
| :--- | :--- | :---: | :--- |
| [AgentField](https://github.com/Agent-Field/agentfield)<br>[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=social)](https://github.com/Agent-Field/agentfield/stargazers) | Agent 后端框架<br><sub>服务化 · 运行与扩展</sub> | **[4](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **SDK · Harness**<br>增加 TypeScript Provider 预检，避免 Python 限流抖动影响全局随机状态。 [#1069](https://github.com/Agent-Field/agentfield/pull/1069) · [#1078](https://github.com/Agent-Field/agentfield/pull/1078) |
| [AxonHub](https://github.com/looplj/axonhub)<br>[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=social)](https://github.com/looplj/axonhub/stargazers) | LLM API 网关<br><sub>多模型路由 · 协议兼容</sub> | **[9](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **API 适配 · 流式响应 · 工具调用**<br>修复工具限制传递、流式字段与引用信息的保留。 [#2519](https://github.com/looplj/axonhub/pull/2519) · [#2561](https://github.com/looplj/axonhub/pull/2561) · [#2572](https://github.com/looplj/axonhub/pull/2572) |
| [MCP-Use](https://github.com/mcp-use/mcp-use)<br>[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=social)](https://github.com/mcp-use/mcp-use/stargazers) | MCP 全栈框架<br><sub>MCP Apps · MCP Servers</sub> | **[1](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **Client · MCP App 渲染**<br>修复 HTML 资源的 UTF-8 解码，让中文和 Emoji 正确显示。 [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit)<br>[![CopilotKit stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=social)](https://github.com/CopilotKit/CopilotKit/stargazers) | Agent 前端框架<br><sub>应用内助手 · 生成式 UI</sub> | **[1](https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **Runtime · HTTP 路由**<br>修复 basePath 边界判定，避免端点误匹配。 [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher)<br>[![GPT Researcher stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)](https://github.com/assafelovic/gpt-researcher/stargazers) | 自主深度研究 Agent<br><sub>资料检索 · 深度研究</sub> | **[2](https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **研究上下文 · 检索器**<br>修复补充检索上下文合并与规范化后空结果的回退。 [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) · [#2105](https://github.com/assafelovic/gpt-researcher/pull/2105) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=social)](https://github.com/HKUDS/DeepTutor/stargazers) | 个性化 AI 学习助手<br><sub>个性化辅导 · 学习辅助</sub> | **[1](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **模型适配 · 视觉能力**<br>修复带资源前缀的 Gemini 模型的视觉能力识别。 [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) |
| [PR-Agent](https://github.com/The-PR-Agent/pr-agent)<br>[![PR-Agent stars](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=social)](https://github.com/The-PR-Agent/pr-agent/stargazers) | AI 代码审查工具<br><sub>代码审查 · PR 自动化</sub> | **[1](https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | **GitHub 集成 · Changelog**<br>发布更新日志时支持创建尚不存在的目标文件。 [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) |

<sub>PR 数量核实于 2026-10-03；Star 标记展示上游项目的 Star 数量，由 Shields.io 自动刷新。</sub>

<details>
<summary>展开全部 21 个已合并 PR · 8 个项目</summary>

**[AgentField](https://github.com/Agent-Field/agentfield) · 4 个 PR**

Agent 后端框架 · 贡献方向：SDK · Harness

- [#1082](https://github.com/Agent-Field/agentfield/pull/1082) — 统一 AGENTFIELD_ASYNC 布尔环境变量的解析规则。
- [#1078](https://github.com/Agent-Field/agentfield/pull/1078) — 避免限流器的随机抖动影响全局随机数状态。
- [#1072](https://github.com/Agent-Field/agentfield/pull/1072) — 在不使用 Schema 的 Harness 运行中跳过 Schema 输出目录。
- [#1069](https://github.com/Agent-Field/agentfield/pull/1069) — 为 TypeScript Agent Harness 增加运行前的 Provider 可用性检查。

**[AxonHub](https://github.com/looplj/axonhub) · 9 个 PR**

LLM API 网关 · 贡献方向：API 适配 · 流式响应 · 工具调用

- [#2572](https://github.com/looplj/axonhub/pull/2572) — 将聚合后的引用信息放入响应顶层字段，避免泄露内部转换元数据。
- [#2561](https://github.com/looplj/axonhub/pull/2561) — 聚合聊天流时保留拒绝回答、音频、logprobs 和推理字段。
- [#2519](https://github.com/looplj/axonhub/pull/2519) — 在 Chat Completions 请求转发中保留允许调用的工具范围。
- [#2517](https://github.com/looplj/axonhub/pull/2517) — 修复配置弹窗内模板浮层无法滚动的问题。
- [#2501](https://github.com/looplj/axonhub/pull/2501) — 保留上游服务要求的 User-Agent 请求头。
- [#2499](https://github.com/looplj/axonhub/pull/2499) — 应用 set_if_absent 请求体覆盖规则时使用原始入站请求体。
- [#2484](https://github.com/looplj/axonhub/pull/2484) — 修正内嵌测试数据的文件系统路径。
- [#2423](https://github.com/looplj/axonhub/pull/2423) — 在 Anthropic 请求处理中保留 DeepSeek 原生网页搜索工具。
- [#2370](https://github.com/looplj/axonhub/pull/2370) — 让透传模式下的图像编辑接口接受 application/json 请求。

**[MCP-Use](https://github.com/mcp-use/mcp-use) · 1 个 PR**

MCP 全栈框架 · 贡献方向：Client · MCP App 渲染

- [#2632](https://github.com/mcp-use/mcp-use/pull/2632) — 使用 UTF-8 解码 MCP App HTML，让中文和 Emoji 正确显示。

**[CopilotKit](https://github.com/CopilotKit/CopilotKit) · 1 个 PR**

Agent 前端框架 · 贡献方向：Runtime · HTTP 路由

- [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) — 修复单路由模式下仅路径前缀相同就被错误匹配的问题。

**[GPT Researcher](https://github.com/assafelovic/gpt-researcher) · 2 个 PR**

自主深度研究 Agent · 贡献方向：研究上下文 · 检索器

- [#2105](https://github.com/assafelovic/gpt-researcher/pull/2105) — 在检索内容规范化后为空时启用回退处理。
- [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) — 合并来源时保留补充网页检索上下文，避免文本被破坏。

**[DeepTutor](https://github.com/HKUDS/DeepTutor) · 1 个 PR**

个性化 AI 学习助手 · 贡献方向：模型适配 · 视觉能力

- [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) — 修复带 models/ 前缀的 Gemini 模型 ID 的视觉能力识别。

**[PR-Agent](https://github.com/The-PR-Agent/pr-agent) · 1 个 PR**

AI 代码审查工具 · 贡献方向：GitHub 集成 · Changelog

- [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) — 发布自动生成的更新日志时，支持创建尚不存在的目标文件。

**[Agent-For-Exam](https://github.com/1firecracker/Agent-For-Exam) · 2 个 PR**

多 Agent 备考助手 · 贡献方向：移动端 UI · 弹窗 · 触控

- [#15](https://github.com/1firecracker/Agent-For-Exam/pull/15) — 修复移动端 Teleport 弹窗的全局样式覆盖。
- [#14](https://github.com/1firecracker/Agent-For-Exam/pull/14) — 适配 Android 端的模型设置弹窗和 PPT 触控操作。

</details>

[在 GitHub 查看完整记录 →](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man+-user%3Aremote-controlled-man&type=pullrequests)

## 项目与分享

- **[skillfit](https://github.com/remote-controlled-man/skillfit)** — 用于检验 Skills、规则文件和 MCP 配置能否改善 Coding Agent 任务表现的命令行工具。通过配对实验和结果校验，对比质量、成本与不确定性。
- **[Agent Context & Memory Guide](https://github.com/remote-controlled-man/agent-context-memory-guide)** — 基于源码阅读，梳理六个 Agent 系统的上下文与记忆机制，提供中文学习笔记和配套学习站。

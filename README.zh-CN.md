# Steven huang

[English](./README.md) · **简体中文**

我在香港大学读计算机硕士，目前在蚂蚁集团实习，做 AI + 量化。我负责让 Agent 从已有因子生成策略、跑回测，最近也在研究让它根据回测反馈挖掘新的因子。之前在细胞壁（Cybopal）做 Agent 评测、Harness 和全双工多模态交互研究，也在快手实习过。

## 项目与笔记

### [skillfit](https://github.com/remote-controlled-man/skillfit)

我在开发的 Coding Agent 配置评测工具，用来检验 Skill、规则文件和 MCP 配置是否真的改善任务表现。通过相同任务的配对实验，比较结果质量、触发率与成本，并保留结果校验和不确定性信息。

[复现 MCP-Use 案例](https://github.com/remote-controlled-man/skillfit/blob/main/benches/contrib/oss-mcp-use-utf8/README.md) · [评测方法](https://github.com/remote-controlled-man/skillfit/blob/main/docs/metrics.md)

### [Agent Context & Memory Guide](https://github.com/remote-controlled-man/agent-context-memory-guide)

早期整理的源码阅读笔记，记录六个 Agent 系统当时的上下文与记忆机制。[在线阅读](https://remote-controlled-man.github.io/agent-context-memory-guide/)

## 开源贡献

**21 个已合并 PR，覆盖 8 个开源项目。** 以下为精选贡献，完整记录见下方折叠列表。

| 项目 | PR | 代表贡献 |
| :--- | :---: | :--- |
| [AxonHub](https://github.com/looplj/axonhub)&nbsp;[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=flat&label=%E2%98%85&color=555)](https://github.com/looplj/axonhub/stargazers)<br>LLM API 网关 | [9](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 修复 API 转换中的工具调用限制与流式字段丢失，完善协议兼容。 [#2561](https://github.com/looplj/axonhub/pull/2561) |
| [AgentField](https://github.com/Agent-Field/agentfield)&nbsp;[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&label=%E2%98%85&color=555)](https://github.com/Agent-Field/agentfield/stargazers)<br>Agent 后端框架 | [4](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 为 TypeScript Harness 增加 Provider 预检，修复 Python SDK 的配置解析与随机状态隔离问题。 [#1069](https://github.com/Agent-Field/agentfield/pull/1069) |
| [MCP-Use](https://github.com/mcp-use/mcp-use)&nbsp;[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&label=%E2%98%85&color=555)](https://github.com/mcp-use/mcp-use/stargazers)<br>MCP 应用框架 | [1](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 修复客户端 HTML 资源的 UTF-8 解码，让 MCP App 正确显示中文和 Emoji。 [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit)&nbsp;[![CopilotKit stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=flat&label=%E2%98%85&color=555)](https://github.com/CopilotKit/CopilotKit/stargazers)<br>Agent 前端框架 | [1](https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 修复 Runtime 的路由边界判断，避免路径前缀相似的请求被误匹配。 [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) |
| [GPT&nbsp;Researcher](https://github.com/assafelovic/gpt-researcher)&nbsp;[![GPT Researcher stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&label=%E2%98%85&color=555)](https://github.com/assafelovic/gpt-researcher/stargazers)<br>自主研究 Agent | [2](https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 修复研究上下文合并与空检索结果回退，保留补充检索内容。 [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)&nbsp;[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=flat&label=%E2%98%85&color=555)](https://github.com/HKUDS/DeepTutor/stargazers)<br>个性化 AI 学习助手 | [1](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 修复模型适配中的视觉能力识别，支持带资源前缀的 Gemini 模型 ID。 [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) |
| [PR-Agent](https://github.com/The-PR-Agent/pr-agent)&nbsp;[![PR-Agent stars](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat&label=%E2%98%85&color=555)](https://github.com/The-PR-Agent/pr-agent/stargazers)<br>AI 代码审查工具 | [1](https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | 完善 GitHub 更新日志发布，支持在目标文件缺失时自动创建。 [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) |

<details>
<summary>展开全部 21 个已合并 PR · 8 个项目</summary>

统计核实于 2026-10-03。上表 Star 为上游仓库的动态计数。

**[AgentField](https://github.com/Agent-Field/agentfield) · 4 个 PR**

- [#1082](https://github.com/Agent-Field/agentfield/pull/1082) — 统一 AGENTFIELD_ASYNC 布尔环境变量的解析规则。
- [#1078](https://github.com/Agent-Field/agentfield/pull/1078) — 避免限流器的随机抖动影响全局随机数状态。
- [#1072](https://github.com/Agent-Field/agentfield/pull/1072) — 在不使用 Schema 的 Harness 运行中跳过 Schema 输出目录。
- [#1069](https://github.com/Agent-Field/agentfield/pull/1069) — 为 TypeScript Agent Harness 增加运行前的 Provider 可用性检查。

**[AxonHub](https://github.com/looplj/axonhub) · 9 个 PR**

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

- [#2632](https://github.com/mcp-use/mcp-use/pull/2632) — 使用 UTF-8 解码 MCP App HTML，让中文和 Emoji 正确显示。

**[CopilotKit](https://github.com/CopilotKit/CopilotKit) · 1 个 PR**

- [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) — 修复单路由模式下仅路径前缀相同就被错误匹配的问题。

**[GPT Researcher](https://github.com/assafelovic/gpt-researcher) · 2 个 PR**

- [#2105](https://github.com/assafelovic/gpt-researcher/pull/2105) — 在检索内容规范化后为空时启用回退处理。
- [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) — 合并来源时保留补充网页检索上下文，避免文本被破坏。

**[DeepTutor](https://github.com/HKUDS/DeepTutor) · 1 个 PR**

- [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) — 修复带 models/ 前缀的 Gemini 模型 ID 的视觉能力识别。

**[PR-Agent](https://github.com/The-PR-Agent/pr-agent) · 1 个 PR**

- [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) — 发布自动生成的更新日志时，支持创建尚不存在的目标文件。

**[Agent-For-Exam](https://github.com/1firecracker/Agent-For-Exam) · 2 个 PR**

- [#15](https://github.com/1firecracker/Agent-For-Exam/pull/15) — 修复移动端 Teleport 弹窗的全局样式覆盖。
- [#14](https://github.com/1firecracker/Agent-For-Exam/pull/14) — 适配 Android 端的模型设置弹窗和 PPT 触控操作。

[在 GitHub 查看完整记录 →](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man+-user%3Aremote-controlled-man&type=pullrequests)

</details>

## 联系

[LinkedIn](https://www.linkedin.com/in/steven-sidi-huang/)

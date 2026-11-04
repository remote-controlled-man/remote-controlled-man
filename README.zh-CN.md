<picture><source media="(prefers-color-scheme: dark) and (max-width: 700px)" srcset="./assets/hero-zh-dark-mobile-v16.png"><source media="(max-width: 700px)" srcset="./assets/hero-zh-light-mobile-v16.png"><source media="(prefers-color-scheme: dark)" srcset="./assets/hero-zh-dark-v16.png"><img src="./assets/hero-zh-light-v16.png" width="100%" alt="Steven Huang — Agent Harness、评测与自进化"></picture>

<p align="center">
  <a href="#user-content-项目"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/key-projects-zh-dark-v16.svg"><img src="./assets/key-projects-zh-light-v16.svg" width="130" alt="项目"></picture></a>&nbsp; <a href="#user-content-开源贡献"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/key-opensource-zh-dark-v16.svg"><img src="./assets/key-opensource-zh-light-v16.svg" width="130" alt="开源贡献"></picture></a>&nbsp; <a href="https://www.linkedin.com/in/steven-sidi-huang/"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/key-linkedin-zh-dark-v16.svg"><img src="./assets/key-linkedin-zh-light-v16.svg" width="130" alt="LinkedIn"></picture></a>&nbsp; <a href="./README.md"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/key-language-zh-dark-v16.svg"><img src="./assets/key-language-zh-light-v16.svg" width="130" alt="English"></picture></a>
</p>

我在香港大学读计算机硕士，目前在[蚂蚁集团](https://www.antgroup.com/)实习，做 AI + 量化。我负责让 Agent 从已有因子生成策略、跑回测，最近也在研究让它根据回测反馈挖掘新的因子。之前在[细胞壁（Cybopal）](https://cybopal.com/)做 Agent 评测、Harness 和全双工多模态交互研究，也在[快手](https://www.kuaishou.com/)实习过。

## 项目

<table>
<tr><td width="100%">
<a href="https://github.com/remote-controlled-man/skillfit"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/project-skillfit-zh-dark-v17.svg"><img src="./assets/project-skillfit-zh-light-v17.svg" width="470" alt="skillfit"></picture></a>
<p>用配对 A/B 实验比较 Skill、规则文件与 MCP 配置的实际效果，记录任务质量、触发率和 Token 成本。支持预算控制与结果回放，可从 npm 安装。</p>
<p><a href="https://github.com/remote-controlled-man/skillfit/blob/main/benches/contrib/oss-mcp-use-utf8/README.md">复现案例</a>  ·  <a href="https://github.com/remote-controlled-man/skillfit/blob/main/docs/reference/metrics.md">评测方法</a></p>
</td></tr>
</table>

<table>
<tr><td width="100%">
<a href="https://github.com/remote-controlled-man/device-agent-arena"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/project-arena-zh-dark-v17.svg"><img src="./assets/project-arena-zh-light-v17.svg" width="470" alt="DeviceAgent Arena"></picture></a>
<p>中文多轮工具调用的实验环境：用模拟状态和故障注入构造任务，根据最终状态与完整轨迹评估 Agent，也探索小模型与 Planner 的协同执行。</p>
<p><a href="https://github.com/remote-controlled-man/device-agent-arena/blob/main/docs/V2_7_LAYERED_EXPERIMENT_REPORT.md">实验报告</a>  ·  <a href="https://github.com/remote-controlled-man/device-agent-arena/blob/main/docs/REPRODUCING_V2_7.md">复现指南</a></p>
</td></tr>
</table>

<p><strong>笔记</strong>  ·  <a href="https://github.com/remote-controlled-man/llm-paper-wiki">LLM Paper Wiki</a>  ·  <a href="https://remote-controlled-man.github.io/agent-context-memory-guide/">Agent Context &amp; Memory Guide</a> <sub>（早期阅读）</sub></p>

## 开源贡献

### 60 个已合并 PR · 15 个上游项目

<sub>截至 2026-11-04</sub>

| 项目 | PR | 代表贡献 |
| :--- | :---: | :--- |
| **[Agent Reach](https://github.com/Panniantong/Agent-Reach)**<br>[![Agent Reach stars](https://img.shields.io/github/stars/Panniantong/Agent-Reach?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/Panniantong/Agent-Reach/stargazers)<br><sub>Agent 联网工具</sub> | **[1](https://github.com/Panniantong/Agent-Reach/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复浏览器桥接不可用时被误记为空会话的问题。 [#879](https://github.com/Panniantong/Agent-Reach/pull/879) |
| **[DeepTutor](https://github.com/HKUDS/DeepTutor)**<br>[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/HKUDS/DeepTutor/stargazers)<br><sub>AI 学习与研究平台</sub> | **[2](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复会话读取最新消息时的全量分页。 [#2042](https://github.com/HKUDS/DeepTutor/pull/2042) |
| **[LLM](https://github.com/simonw/llm)**<br>[![LLM stars](https://img.shields.io/github/stars/simonw/llm?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/simonw/llm/stargazers)<br><sub>大模型命令行与 Python 工具</sub> | **[1](https://github.com/simonw/llm/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复添加端点时破坏流式 YAML 列表的问题。 [#1845](https://github.com/simonw/llm/pull/1845) |
| **[AxonHub](https://github.com/looplj/axonhub)**<br>[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/looplj/axonhub/stargazers)<br><sub>LLM API 网关</sub> | **[15](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 支持数组通配字段删除，修复 Gemini 多段推理内容与工具调用顺序。 [#2824](https://github.com/looplj/axonhub/pull/2824) [#2831](https://github.com/looplj/axonhub/pull/2831) [#2633](https://github.com/looplj/axonhub/pull/2633) |
| **[AgentField](https://github.com/Agent-Field/agentfield)**<br>[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/Agent-Field/agentfield/stargazers)<br><sub>Agent 后端框架</sub> | **[16](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 增加 Harness 预检，修复事件解析与记忆订阅重连。 [#1069](https://github.com/Agent-Field/agentfield/pull/1069) [#1148](https://github.com/Agent-Field/agentfield/pull/1148) [#1145](https://github.com/Agent-Field/agentfield/pull/1145) |
| **[Basic Memory](https://github.com/basicmachines-co/basic-memory)**<br>[![Basic Memory stars](https://img.shields.io/github/stars/basicmachines-co/basic-memory?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/basicmachines-co/basic-memory/stargazers)<br><sub>AI 记忆与知识库</sub> | **[2](https://github.com/basicmachines-co/basic-memory/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复关系解析后的向量索引同步与无效地址的错误处理。 [#1884](https://github.com/basicmachines-co/basic-memory/pull/1884) [#1885](https://github.com/basicmachines-co/basic-memory/pull/1885) |
| **[FastMCP](https://github.com/punkpeye/fastmcp)**<br>[![FastMCP stars](https://img.shields.io/github/stars/punkpeye/fastmcp?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/punkpeye/fastmcp/stargazers)<br><sub>TypeScript MCP 服务框架</sub> | **[7](https://github.com/punkpeye/fastmcp/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复资源模板批量注册及 JSON Schema 2019-09 验证。 [#478](https://github.com/punkpeye/fastmcp/pull/478) [#485](https://github.com/punkpeye/fastmcp/pull/485) |
| **[OpenLIT](https://github.com/openlit/openlit)**<br>[![OpenLIT stars](https://img.shields.io/github/stars/openlit/openlit?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/openlit/openlit/stargazers)<br><sub>Agent 可观测性与评测</sub> | **[1](https://github.com/openlit/openlit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 增加 OpenCode 集成，接入生命周期、Token 与成本遥测。 [#1591](https://github.com/openlit/openlit/pull/1591) |
| **[MCP-Use](https://github.com/mcp-use/mcp-use)**<br>[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/mcp-use/mcp-use/stargazers)<br><sub>MCP 应用框架</sub> | **[1](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复 MCP App HTML 的 UTF-8 解码，让中文和 Emoji 正确显示。 [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| **[Vibe-Trading](https://github.com/HKUDS/Vibe-Trading)**<br>[![Vibe-Trading stars](https://img.shields.io/github/stars/HKUDS/Vibe-Trading?style=flat&label=%E2%98%85&color=496e64&cacheSeconds=3600)](https://github.com/HKUDS/Vibe-Trading/stargazers)<br><sub>AI 交易 Agent</sub> | **[5](https://github.com/HKUDS/Vibe-Trading/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | 修复 Agent 最终回答重试、文档数值证据识别和期权波动率年化。 [#2136](https://github.com/HKUDS/Vibe-Trading/pull/2136) [#2135](https://github.com/HKUDS/Vibe-Trading/pull/2135) [#1753](https://github.com/HKUDS/Vibe-Trading/pull/1753) |

<details>
<summary>展开全部 60 个已合并 PR · 15 个项目</summary>
<p>统计核实于 2026-11-04。Star 为上游仓库的动态计数。</p>
<p><strong><a href="https://github.com/Panniantong/Agent-Reach">Agent Reach</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/Panniantong/Agent-Reach/pull/879">#879</a> — 避免浏览器桥接不可用时将失败的会话发现误记为空快照，并提供恢复提示。</li>
</ul>
<p><strong><a href="https://github.com/simonw/llm">LLM</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/simonw/llm/pull/1845">#1845</a> — 修复在流式 YAML 列表中添加端点时生成无效配置的问题。</li>
</ul>
<p><strong><a href="https://github.com/looplj/axonhub">AxonHub</a> · 15 个 PR</strong></p>
<ul>
<li><a href="https://github.com/looplj/axonhub/pull/2831">#2831</a> — 修复 Gemini 响应转换丢失多段推理摘要的问题。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2830">#2830</a> — 修复 GraphQL 生成时 Dashboard 辅助函数被移走导致的构建失败。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2824">#2824</a> — 支持在请求体数组中通过通配路径删除字段，包括嵌套数组。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2634">#2634</a> — 将消息中的音频识别为有效响应内容，避免误判为空响应并重复重试。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2633">#2633</a> — 转换 Responses API 输入时，将工具结果紧邻对应调用，避免上游拒绝消息顺序。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2572">#2572</a> — 将聚合后的引用信息放入响应顶层字段，避免泄露内部转换元数据。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2561">#2561</a> — 聚合聊天流时保留拒绝回答、音频、logprobs 和推理字段。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2519">#2519</a> — 在 Chat Completions 请求转发中保留允许调用的工具范围。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2517">#2517</a> — 修复配置弹窗内模板浮层无法滚动的问题。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2501">#2501</a> — 保留上游服务要求的 User-Agent 请求头。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2499">#2499</a> — 应用 set_if_absent 请求体覆盖规则时使用原始入站请求体。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2484">#2484</a> — 修正内嵌测试数据的文件系统路径。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2423">#2423</a> — 在 Anthropic 请求处理中保留 DeepSeek 原生网页搜索工具。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2414">#2414</a> — 将标准 reasoning_effort: none 正确映射为百炼的关闭思考选项。</li>
<li><a href="https://github.com/looplj/axonhub/pull/2370">#2370</a> — 让透传模式下的图像编辑接口接受 application/json 请求。</li>
</ul>
<p><strong><a href="https://github.com/Agent-Field/agentfield">AgentField</a> · 16 个 PR</strong></p>
<ul>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1148">#1148</a> — 修复 Harness JSONL 解析错误切分 Unicode 分隔符，避免有效事件丢失。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1145">#1145</a> — 让记忆事件客户端在自动重连时保留订阅过滤条件。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1142">#1142</a> — 停止记忆事件客户端关闭后的重连，并清理进行中的连接任务。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1141">#1141</a> — 修复 Go 格式化命令重复遍历文件的问题。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1140">#1140</a> — 在测试间等待已接受的 MCP 任务完成，避免共享并发状态互相影响。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1137">#1137</a> — 对记忆订阅过滤参数进行 URL 编码，保留特殊字符。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1129">#1129</a> — 将数值型 Retry-After 作为最短等待时间，避免过早重试。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1136">#1136</a> — 按字面匹配记忆订阅键，避免特殊字符被误读为正则。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1109">#1109</a> — 让 Python SDK 对不可恢复的状态回调错误停止重试。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1106">#1106</a> — 修复 memory.exists() 对缺失键的判断，同时正确识别已存储的空值、零等假值。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1105">#1105</a> — 将 Provider 确认的零成本正确记为已知费用，避免误报为成本未知。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1100">#1100</a> — 让无法识别的异步布尔环境变量回退到实际类默认值，兼容子类配置。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1082">#1082</a> — 统一 AGENTFIELD_ASYNC 布尔环境变量的解析规则。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1078">#1078</a> — 避免限流器的随机抖动影响全局随机数状态。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1072">#1072</a> — 在不使用 Schema 的 Harness 运行中跳过 Schema 输出目录。</li>
<li><a href="https://github.com/Agent-Field/agentfield/pull/1069">#1069</a> — 为 TypeScript Agent Harness 增加运行前的 Provider 可用性检查。</li>
</ul>
<p><strong><a href="https://github.com/punkpeye/fastmcp">FastMCP</a> · 7 个 PR</strong></p>
<ul>
<li><a href="https://github.com/punkpeye/fastmcp/pull/485">#485</a> — 修复 jsonSchemaAdapter 对 JSON Schema 2019-09 的验证。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/478">#478</a> — 修复批量注册重复资源模板时读取到旧内容的问题。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/477">#477</a> — 批量注册重复工具名时只保留最后一个定义，使工具列表与调用一致。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/476">#476</a> — 按 URI 替换重复资源，保持读取、嵌入与删除的一致性。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/442">#442</a> — 修复必填 JSON 请求体在未传属性时被省略的问题，正确发送空对象。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/434">#434</a> — 停止服务时关闭框架持有的 stdio 会话与传输，覆盖取消执行和初始化失败时的清理。</li>
<li><a href="https://github.com/punkpeye/fastmcp/pull/433">#433</a> — 为 OpenAPI 扁平对象路径参数增加 simple 风格的序列化支持。</li>
</ul>
<p><strong><a href="https://github.com/basicmachines-co/basic-memory">Basic Memory</a> · 2 个 PR</strong></p>
<ul>
<li><a href="https://github.com/basicmachines-co/basic-memory/pull/1884">#1884</a> — 修复关系前向引用解析后向量索引未同步的问题。</li>
<li><a href="https://github.com/basicmachines-co/basic-memory/pull/1885">#1885</a> — 将无效的记忆上下文地址返回为 400，避免误报服务端错误。</li>
</ul>
<p><strong><a href="https://github.com/openlit/openlit">OpenLIT</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/openlit/openlit/pull/1591">#1591</a> — 增加 OpenCode 集成，覆盖生命周期遥测、Token 与成本统计，以及有界非阻塞事件投递。</li>
</ul>
<p><strong><a href="https://github.com/mcp-use/mcp-use">MCP-Use</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/mcp-use/mcp-use/pull/2632">#2632</a> — 使用 UTF-8 解码 MCP App HTML，让中文和 Emoji 正确显示。</li>
</ul>
<p><strong><a href="https://github.com/HKUDS/Vibe-Trading">Vibe-Trading</a> · 5 个 PR</strong></p>
<ul>
<li><a href="https://github.com/HKUDS/Vibe-Trading/pull/2138">#2138</a> — 澄清 A 股数据源的安装方式和自动回退链。</li>
<li><a href="https://github.com/HKUDS/Vibe-Trading/pull/2136">#2136</a> — 为迭代上限处被拒绝的工具标记回答提供一次受限的纯文本重试。</li>
<li><a href="https://github.com/HKUDS/Vibe-Trading/pull/2135">#2135</a> — 保留文档整数的千位分隔标记，避免有来源的数值证据被漏判。</li>
<li><a href="https://github.com/HKUDS/Vibe-Trading/pull/1766">#1766</a> — 修正富途交易日志的格式识别，避免通用列名被误解析后将成交数量和金额静默归零。</li>
<li><a href="https://github.com/HKUDS/Vibe-Trading/pull/1753">#1753</a> — 按照回测实际 K 线频率年化期权定价波动率，统一定价与指标的时间口径。</li>
</ul>
<p><strong><a href="https://github.com/CopilotKit/CopilotKit">CopilotKit</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/CopilotKit/CopilotKit/pull/7341">#7341</a> — 修复单路由模式下仅路径前缀相同就被错误匹配的问题。</li>
</ul>
<p><strong><a href="https://github.com/assafelovic/gpt-researcher">GPT Researcher</a> · 2 个 PR</strong></p>
<ul>
<li><a href="https://github.com/assafelovic/gpt-researcher/pull/2105">#2105</a> — 在检索内容规范化后为空时启用回退处理。</li>
<li><a href="https://github.com/assafelovic/gpt-researcher/pull/2104">#2104</a> — 合并来源时保留补充网页检索上下文，避免文本被破坏。</li>
</ul>
<p><strong><a href="https://github.com/samanhappy/mcphub">MCPHub</a> · 3 个 PR</strong></p>
<ul>
<li><a href="https://github.com/samanhappy/mcphub/pull/1392">#1392</a> — 完整解析数值工具参数，避免前缀解析造成数值错误。</li>
<li><a href="https://github.com/samanhappy/mcphub/pull/1315">#1315</a> — 让 jose 的测试转换规则兼容 Windows 与 POSIX 路径，修复相关测试无法加载的问题。</li>
<li><a href="https://github.com/samanhappy/mcphub/pull/1314">#1314</a> — 修复 Windows 上 MCPB 安装的目录重命名失败，确保移动解压目录前目标路径不存在。</li>
</ul>
<p><strong><a href="https://github.com/HKUDS/DeepTutor">DeepTutor</a> · 2 个 PR</strong></p>
<ul>
<li><a href="https://github.com/HKUDS/DeepTutor/pull/2042">#2042</a> — 限制会话最新消息查询的读取范围，避免遍历整段历史。</li>
<li><a href="https://github.com/HKUDS/DeepTutor/pull/1588">#1588</a> — 修复带 models/ 前缀的 Gemini 模型 ID 的视觉能力识别。</li>
</ul>
<p><strong><a href="https://github.com/The-PR-Agent/pr-agent">PR-Agent</a> · 1 个 PR</strong></p>
<ul>
<li><a href="https://github.com/The-PR-Agent/pr-agent/pull/3639">#3639</a> — 发布自动生成的更新日志时，支持创建尚不存在的目标文件。</li>
</ul>
<p><strong><a href="https://github.com/1firecracker/Agent-For-Exam">Agent-For-Exam</a> · 2 个 PR</strong></p>
<ul>
<li><a href="https://github.com/1firecracker/Agent-For-Exam/pull/15">#15</a> — 修复移动端 Teleport 弹窗的全局样式覆盖。</li>
<li><a href="https://github.com/1firecracker/Agent-For-Exam/pull/14">#14</a> — 适配 Android 端的模型设置弹窗和 PPT 触控操作。</li>
</ul>
<p><a href="https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man+-user%3Aremote-controlled-man&amp;type=pullrequests">在 GitHub 查看完整记录 →</a></p>
</details>

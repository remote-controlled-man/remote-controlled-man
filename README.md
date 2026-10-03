# Steven huang

**Agent systems · Evaluation · Multimodal interaction**

**English** · [简体中文](./README.zh-CN.md)

I'm a Computer Science master's student at **The University of Hong Kong**. I work on self-improving agents for quantitative research, agent harnesses and evaluation, and real-time multimodal interaction.

I build [skillfit](https://github.com/remote-controlled-man/skillfit) and contribute fixes and features to open-source projects across the agent ecosystem.

## Experience

**Ant Group · Agent Optimization Algorithm Intern · 2026–present**

AI for quantitative research: own the workflow from a factor library to strategy generation, backtesting, and feedback, while researching self-improving agents for strategy optimization and factor discovery.

**Cybopal · Agent Algorithm Intern · 2026**

Agent evaluation and harness design, alongside research on full-duplex, end-to-end multimodal interaction models through deployment, reproduction, evaluation, and model design studies.

**Kuaishou · Backend Development Intern · 2024** — Multimedia evaluation and automated data processing.

## Open-source contributions

**21 merged PRs across 8 upstream projects.** Selected contributions are highlighted below; expand the full list for all 21 PRs.

| Project · Stars | My merged PRs | Selected contribution |
| :--- | :---: | :--- |
| [AgentField](https://github.com/Agent-Field/agentfield)<br>[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=social)](https://github.com/Agent-Field/agentfield/stargazers) | **[4](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Added provider availability checks and actionable errors to the TypeScript agent harness. [#1069](https://github.com/Agent-Field/agentfield/pull/1069) |
| [AxonHub](https://github.com/looplj/axonhub)<br>[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=social)](https://github.com/looplj/axonhub/stargazers) | **[9](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Preserved allowed-tool restrictions when forwarding Chat Completions requests. [#2519](https://github.com/looplj/axonhub/pull/2519) |
| [MCP-Use](https://github.com/mcp-use/mcp-use)<br>[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=social)](https://github.com/mcp-use/mcp-use/stargazers) | **[1](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Fixed UTF-8 decoding so MCP App HTML renders Chinese text and emoji correctly. [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit)<br>[![CopilotKit stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=social)](https://github.com/CopilotKit/CopilotKit/stargazers) | **[1](https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Fixed runtime routing that incorrectly accepted paths sharing only a text prefix. [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher)<br>[![GPT Researcher stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)](https://github.com/assafelovic/gpt-researcher/stargazers) | **[2](https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Fixed corrupted context when combining source URLs with complementary web research. [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=social)](https://github.com/HKUDS/DeepTutor/stargazers) | **[1](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Restored vision-capability detection for Gemini model IDs with a resource prefix. [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) |
| [PR-Agent](https://github.com/The-PR-Agent/pr-agent)<br>[![PR-Agent stars](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=social)](https://github.com/The-PR-Agent/pr-agent/stargazers) | **[1](https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)** | Fixed changelog publishing when the target file does not yet exist. [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) |

<sub>PR counts verified on 2026-10-03. Star badges show upstream repository stars and refresh via Shields.io.</sub>

<details>
<summary>View all 21 merged PRs across 8 projects</summary>

**[AgentField](https://github.com/Agent-Field/agentfield) · 4 merged**

- [#1082](https://github.com/Agent-Field/agentfield/pull/1082) — Aligned AGENTFIELD_ASYNC boolean parsing with the repository's environment-variable conventions.
- [#1078](https://github.com/Agent-Field/agentfield/pull/1078) — Prevented rate-limiter jitter from changing the global random state.
- [#1072](https://github.com/Agent-Field/agentfield/pull/1072) — Skipped schema output directories when harness runs do not use a schema.
- [#1069](https://github.com/Agent-Field/agentfield/pull/1069) — Added provider availability checks before TypeScript agent harness runs.

**[AxonHub](https://github.com/looplj/axonhub) · 9 merged**

- [#2572](https://github.com/looplj/axonhub/pull/2572) — Placed aggregated citations in the top-level response field without leaking transformer metadata.
- [#2561](https://github.com/looplj/axonhub/pull/2561) — Preserved refusal, audio, logprobs, and reasoning when aggregating chat streams.
- [#2519](https://github.com/looplj/axonhub/pull/2519) — Preserved allowed-tool restrictions across Chat Completions routes.
- [#2517](https://github.com/looplj/axonhub/pull/2517) — Kept the template popover scrollable inside the profiles dialog.
- [#2501](https://github.com/looplj/axonhub/pull/2501) — Preserved the User-Agent required by providers on outbound requests.
- [#2499](https://github.com/looplj/axonhub/pull/2499) — Used the inbound request body when applying set_if_absent overrides.
- [#2484](https://github.com/looplj/axonhub/pull/2484) — Corrected embedded fixture paths for the filesystem API.
- [#2423](https://github.com/looplj/axonhub/pull/2423) — Preserved DeepSeek native web-search tools in Anthropic request handling.
- [#2370](https://github.com/looplj/axonhub/pull/2370) — Accepted application/json for image-edit requests in passthrough mode.

**[MCP-Use](https://github.com/mcp-use/mcp-use) · 1 merged**

- [#2632](https://github.com/mcp-use/mcp-use/pull/2632) — Decoded MCP App HTML blobs as UTF-8 so Chinese text and emoji render correctly.

**[CopilotKit](https://github.com/CopilotKit/CopilotKit) · 1 merged**

- [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) — Enforced base-path segment boundaries in single-route runtime matching.

**[GPT Researcher](https://github.com/assafelovic/gpt-researcher) · 2 merged**

- [#2105](https://github.com/assafelovic/gpt-researcher/pull/2105) — Fell back when retriever content became blank after normalization.
- [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) — Preserved complementary web-research context when combining sources.

**[DeepTutor](https://github.com/HKUDS/DeepTutor) · 1 merged**

- [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) — Recognized vision support in Gemini model IDs with a models/ prefix.

**[PR-Agent](https://github.com/The-PR-Agent/pr-agent) · 1 merged**

- [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) — Created a missing changelog file when publishing generated updates.

**[Agent-For-Exam](https://github.com/1firecracker/Agent-For-Exam) · 2 merged**

- [#15](https://github.com/1firecracker/Agent-For-Exam/pull/15) — Applied global styles to teleported settings dialogs on mobile.
- [#14](https://github.com/1firecracker/Agent-For-Exam/pull/14) — Adapted the LLM settings dialog and PPT touch controls for Android.

</details>

[View the full history on GitHub →](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man+-user%3Aremote-controlled-man&type=pullrequests)

## Projects & writing

- **[skillfit](https://github.com/remote-controlled-man/skillfit)** — A CLI to test whether Skills, rules files, and MCP configurations improve a coding agent on your tasks. Uses paired experiments and verifiers to compare quality, cost, and uncertainty.
- **[Agent Context & Memory Guide](https://github.com/remote-controlled-man/agent-context-memory-guide)** — Chinese learning notes on context and memory in six agent systems, grounded in source code and accompanied by a learning site.

Also interested in context and memory, small-model post-training, and learning from agent failure traces.

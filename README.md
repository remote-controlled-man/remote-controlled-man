<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/header-mobile-dark.svg">
  <source media="(max-width: 600px)" srcset="./assets/header-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" width="100%" alt="Steven huang — remote-controlled-man">
</picture>

<p align="center">
  <strong>English</strong> &nbsp; / &nbsp; <a href="./README.zh-CN.md">简体中文</a>
  &nbsp; · &nbsp; <a href="#projects">Projects</a>
  &nbsp; · &nbsp; <a href="#open-source-contributions">Open source</a>
  &nbsp; · &nbsp; <a href="https://www.linkedin.com/in/steven-sidi-huang/">LinkedIn ↗</a>
</p>

I'm a master's student in Computer Science at the University of Hong Kong, currently interning at [Ant Group](https://www.antgroup.com/) on AI for quantitative research. I build agents that turn existing factors into trading strategies and backtest them, and I'm exploring how they can use backtesting feedback to discover new factors. Previously, I worked on agent evaluation, harnesses, and full-duplex multimodal interaction at [Cybopal](https://cybopal.com/), and interned at [Kuaishou](https://www.kuaishou.com/).

## Projects

<table width="100%">
<tr><td>
<p><sub>IN DEVELOPMENT</sub></p>
<h3><a href="https://github.com/remote-controlled-man/skillfit">skillfit ↗</a></h3>
<p><strong>Does changing your coding agent's setup actually help?</strong></p>
<p>A CLI I'm building to compare Skills, rules files, and MCP configurations through paired experiments on the same tasks. It measures quality, trigger behavior, and cost, keeping verification results and uncertainty visible.</p>
<p><a href="https://github.com/remote-controlled-man/skillfit/blob/main/benches/contrib/oss-mcp-use-utf8/README.md">Reproduce a case →</a> &nbsp; · &nbsp; <a href="https://github.com/remote-controlled-man/skillfit/blob/main/docs/metrics.md">Evaluation protocol</a></p>
</td></tr>
</table>

<sub>Earlier reading notes: <a href="https://remote-controlled-man.github.io/agent-context-memory-guide/">Agent Context &amp; Memory Guide ↗</a> · context and memory in six agent systems.</sub>

## Open-source contributions

**21 merged PRs · 8 upstream projects** &nbsp; <sub>As of 2026-10-03</sub>

| Project | What I worked on |
| :--- | :--- |
| [AxonHub](https://github.com/looplj/axonhub)<br>[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=flat&label=%E2%98%85&color=555)](https://github.com/looplj/axonhub/stargazers) | <sub>LLM API gateway · [9 merged PRs](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Fixed tool-call restrictions and dropped streaming fields across API conversions. [#2561](https://github.com/looplj/axonhub/pull/2561) |
| [AgentField](https://github.com/Agent-Field/agentfield)<br>[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&label=%E2%98%85&color=555)](https://github.com/Agent-Field/agentfield/stargazers) | <sub>Agent backend framework · [4 merged PRs](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Provider preflight checks for the TypeScript harness; configuration parsing and random-state isolation in the Python SDK. [#1069](https://github.com/Agent-Field/agentfield/pull/1069) |
| [MCP-Use](https://github.com/mcp-use/mcp-use)<br>[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&label=%E2%98%85&color=555)](https://github.com/mcp-use/mcp-use/stargazers) | <sub>MCP application framework · [1 merged PR](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>UTF-8 decoding of HTML resources, so MCP Apps render Chinese text and emoji correctly. [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit)<br>[![CopilotKit stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=flat&label=%E2%98%85&color=555)](https://github.com/CopilotKit/CopilotKit/stargazers) | <sub>Frontend framework for agents · [1 merged PR](https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Fixed route-boundary checks in the runtime to reject requests with similar path prefixes. [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) |
| [GPT&nbsp;Researcher](https://github.com/assafelovic/gpt-researcher)<br>[![GPT Researcher stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&label=%E2%98%85&color=555)](https://github.com/assafelovic/gpt-researcher/stargazers) | <sub>Autonomous research agent · [2 merged PRs](https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Fixed research-context merging and fallback for empty retrieval results, preserving complementary sources. [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)<br>[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=flat&label=%E2%98%85&color=555)](https://github.com/HKUDS/DeepTutor/stargazers) | <sub>Personalized AI tutor · [1 merged PR](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Fixed vision-capability detection for Gemini model IDs with a resource prefix. [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) |
| [PR-Agent](https://github.com/The-PR-Agent/pr-agent)<br>[![PR-Agent stars](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat&label=%E2%98%85&color=555)](https://github.com/The-PR-Agent/pr-agent/stargazers) | <sub>AI code review tool · [1 merged PR](https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man)</sub><br>Updated GitHub changelog publishing to create the target file when it does not exist. [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) |

<details>
<summary>View all 21 merged PRs across 8 projects</summary>

PR counts verified on 2026-10-03. Star badges show dynamically updated upstream repository stars.

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

[View the full history on GitHub →](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man+-user%3Aremote-controlled-man&type=pullrequests)

</details>

---

<p align="center"><a href="https://www.linkedin.com/in/steven-sidi-huang/">Find me on LinkedIn ↗</a></p>

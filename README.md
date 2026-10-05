<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 600px)" srcset="./assets/header-mobile-dark.svg">
  <source media="(max-width: 600px)" srcset="./assets/header-mobile-light.svg">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img src="./assets/header-light.svg" width="100%" alt="Steven huang — remote-controlled-man">
</picture>

<p align="center">
  <strong>English</strong> &nbsp; / &nbsp; <a href="./README.zh-CN.md">简体中文</a>
  <br>
  <a href="#user-content-projects">Projects</a>
  &nbsp; · &nbsp; <a href="#user-content-open-source-contributions">Open&nbsp;source</a>
  &nbsp; · &nbsp; <a href="https://www.linkedin.com/in/steven-sidi-huang/">LinkedIn&nbsp;↗</a>
</p>

I'm a master's student in Computer Science at the University of Hong Kong, currently interning at [Ant Group](https://www.antgroup.com/) on AI for quantitative research. I build agents that turn existing factors into trading strategies and backtest them, and I'm exploring how they can use backtesting feedback to discover new factors. Previously, I worked on agent evaluation, harnesses, and full-duplex multimodal interaction at [Cybopal](https://cybopal.com/), and interned at [Kuaishou](https://www.kuaishou.com/).

## Projects

<table width="100%">
<tr><td>
<p><sub>IN DEVELOPMENT</sub></p>
<h3><a href="https://github.com/remote-controlled-man/skillfit">skillfit ↗</a></h3>
<p><strong>Paired evaluations for coding agent configurations</strong></p>
<p>A CLI I'm building to compare Skills, rules files, and MCP configurations through paired experiments on the same tasks. It measures quality, trigger behavior, and cost, keeping verification results and uncertainty visible.</p>
<p><a href="https://github.com/remote-controlled-man/skillfit/blob/main/benches/contrib/oss-mcp-use-utf8/README.md">Reproduce a case →</a> &nbsp; · &nbsp; <a href="https://github.com/remote-controlled-man/skillfit/blob/main/docs/metrics.md">Evaluation protocol</a></p>
</td></tr>
</table>

<sub>Earlier reading notes: <a href="https://remote-controlled-man.github.io/agent-context-memory-guide/">Agent Context &amp; Memory Guide ↗</a> · context and memory in six agent systems.</sub>

## Open-source contributions

**21 merged PRs · 8 upstream projects** &nbsp; <sub>As of 2026-10-03</sub>

<table width="100%">
<tr><td>
<p><a href="https://github.com/looplj/axonhub"><strong>AxonHub</strong></a> &nbsp; <a href="https://github.com/looplj/axonhub/stargazers"><img src="https://img.shields.io/github/stars/looplj/axonhub?style=flat&amp;label=%E2%98%85&amp;color=555" alt="AxonHub stars"></a><br>
<sub>LLM API gateway · <a href="https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">9 merged PRs</a></sub></p>
<p>Fixed tool-call restrictions and dropped streaming fields across API conversions. <a href="https://github.com/looplj/axonhub/pull/2561">#2561</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/Agent-Field/agentfield"><strong>AgentField</strong></a> &nbsp; <a href="https://github.com/Agent-Field/agentfield/stargazers"><img src="https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&amp;label=%E2%98%85&amp;color=555" alt="AgentField stars"></a><br>
<sub>Agent backend framework · <a href="https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">4 merged PRs</a></sub></p>
<p>Provider preflight checks for the TypeScript harness; configuration parsing and random-state isolation in the Python SDK. <a href="https://github.com/Agent-Field/agentfield/pull/1069">#1069</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/mcp-use/mcp-use"><strong>MCP-Use</strong></a> &nbsp; <a href="https://github.com/mcp-use/mcp-use/stargazers"><img src="https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&amp;label=%E2%98%85&amp;color=555" alt="MCP-Use stars"></a><br>
<sub>MCP application framework · <a href="https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">1 merged PR</a></sub></p>
<p>UTF-8 decoding of HTML resources, so MCP Apps render Chinese text and emoji correctly. <a href="https://github.com/mcp-use/mcp-use/pull/2632">#2632</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/CopilotKit/CopilotKit"><strong>CopilotKit</strong></a> &nbsp; <a href="https://github.com/CopilotKit/CopilotKit/stargazers"><img src="https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=flat&amp;label=%E2%98%85&amp;color=555" alt="CopilotKit stars"></a><br>
<sub>Frontend framework for agents · <a href="https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">1 merged PR</a></sub></p>
<p>Fixed route-boundary checks in the runtime to reject requests with similar path prefixes. <a href="https://github.com/CopilotKit/CopilotKit/pull/7341">#7341</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/assafelovic/gpt-researcher"><strong>GPT&nbsp;Researcher</strong></a> &nbsp; <a href="https://github.com/assafelovic/gpt-researcher/stargazers"><img src="https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&amp;label=%E2%98%85&amp;color=555" alt="GPT Researcher stars"></a><br>
<sub>Autonomous research agent · <a href="https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">2 merged PRs</a></sub></p>
<p>Fixed research-context merging and fallback for empty retrieval results, preserving complementary sources. <a href="https://github.com/assafelovic/gpt-researcher/pull/2104">#2104</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/HKUDS/DeepTutor"><strong>DeepTutor</strong></a> &nbsp; <a href="https://github.com/HKUDS/DeepTutor/stargazers"><img src="https://img.shields.io/github/stars/HKUDS/DeepTutor?style=flat&amp;label=%E2%98%85&amp;color=555" alt="DeepTutor stars"></a><br>
<sub>Personalized AI tutor · <a href="https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">1 merged PR</a></sub></p>
<p>Fixed vision-capability detection for Gemini model IDs with a resource prefix. <a href="https://github.com/HKUDS/DeepTutor/pull/1588">#1588</a></p>
</td></tr>
<tr><td>
<p><a href="https://github.com/The-PR-Agent/pr-agent"><strong>PR-Agent</strong></a> &nbsp; <a href="https://github.com/The-PR-Agent/pr-agent/stargazers"><img src="https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat&amp;label=%E2%98%85&amp;color=555" alt="PR-Agent stars"></a><br>
<sub>AI code review tool · <a href="https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man">1 merged PR</a></sub></p>
<p>Updated GitHub changelog publishing to create the target file when it does not exist. <a href="https://github.com/The-PR-Agent/pr-agent/pull/3639">#3639</a></p>
</td></tr>
</table>

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

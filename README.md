# Steven huang

**English** · [简体中文](./README.zh-CN.md)

I'm pursuing a master's in Computer Science at the University of Hong Kong, with interests in self-improving agents, agent evaluation, and real-time multimodal interaction. As an intern at Ant Group, I own the AI quantitative research workflow from factor libraries to strategy generation and backtesting, while exploring self-improving factor discovery. My previous internships involved agent harnesses, evaluation, and full-duplex, end-to-end multimodal interaction models at Cybopal, and multimedia evaluation and backend development at Kuaishou.

## Projects & notes

### [skillfit](https://github.com/remote-controlled-man/skillfit)

A CLI I'm building to measure whether Skills, rules files, and MCP configurations actually improve a coding agent on your tasks. It runs paired experiments on the same tasks, comparing quality, trigger behavior, and cost while preserving verification results and uncertainty.

[Reproduce an MCP-Use case](https://github.com/remote-controlled-man/skillfit/blob/main/benches/contrib/oss-mcp-use-utf8/README.md) · [Evaluation protocol](https://github.com/remote-controlled-man/skillfit/blob/main/docs/metrics.md)

### [Agent Context & Memory Guide](https://github.com/remote-controlled-man/agent-context-memory-guide)

Earlier source-reading notes on context and memory in six agent systems, reflecting the versions studied at the time. [Read online](https://remote-controlled-man.github.io/agent-context-memory-guide/)

## Open-source contributions

**21 merged PRs across 8 upstream projects.** Selected contributions below; expand the full record for every PR.

| Project | PRs | Selected contributions |
| :--- | :---: | :--- |
| [AxonHub](https://github.com/looplj/axonhub)&nbsp;[![AxonHub stars](https://img.shields.io/github/stars/looplj/axonhub?style=flat&label=%E2%98%85&color=555)](https://github.com/looplj/axonhub/stargazers)<br>LLM API gateway | [9](https://github.com/looplj/axonhub/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Fixed tool-call restrictions and dropped streaming fields across API conversions. [#2561](https://github.com/looplj/axonhub/pull/2561) |
| [AgentField](https://github.com/Agent-Field/agentfield)&nbsp;[![AgentField stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&label=%E2%98%85&color=555)](https://github.com/Agent-Field/agentfield/stargazers)<br>Agent backend framework | [4](https://github.com/Agent-Field/agentfield/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Added provider preflight checks to the TypeScript harness; fixed configuration parsing and random-state isolation in the Python SDK. [#1069](https://github.com/Agent-Field/agentfield/pull/1069) |
| [MCP-Use](https://github.com/mcp-use/mcp-use)&nbsp;[![MCP-Use stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat&label=%E2%98%85&color=555)](https://github.com/mcp-use/mcp-use/stargazers)<br>MCP application framework | [1](https://github.com/mcp-use/mcp-use/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Fixed UTF-8 decoding of HTML resources in the client so MCP Apps render Chinese text and emoji correctly. [#2632](https://github.com/mcp-use/mcp-use/pull/2632) |
| [CopilotKit](https://github.com/CopilotKit/CopilotKit)&nbsp;[![CopilotKit stars](https://img.shields.io/github/stars/CopilotKit/CopilotKit?style=flat&label=%E2%98%85&color=555)](https://github.com/CopilotKit/CopilotKit/stargazers)<br>Frontend framework for agents | [1](https://github.com/CopilotKit/CopilotKit/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Fixed route-boundary checks in the runtime to reject requests with similar path prefixes. [#7341](https://github.com/CopilotKit/CopilotKit/pull/7341) |
| [GPT&nbsp;Researcher](https://github.com/assafelovic/gpt-researcher)&nbsp;[![GPT Researcher stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&label=%E2%98%85&color=555)](https://github.com/assafelovic/gpt-researcher/stargazers)<br>Autonomous research agent | [2](https://github.com/assafelovic/gpt-researcher/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Fixed research-context merging and fallback for empty retrieval results, preserving complementary sources. [#2104](https://github.com/assafelovic/gpt-researcher/pull/2104) |
| [DeepTutor](https://github.com/HKUDS/DeepTutor)&nbsp;[![DeepTutor stars](https://img.shields.io/github/stars/HKUDS/DeepTutor?style=flat&label=%E2%98%85&color=555)](https://github.com/HKUDS/DeepTutor/stargazers)<br>Personalized AI tutor | [1](https://github.com/HKUDS/DeepTutor/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Fixed vision-capability detection for Gemini model IDs with a resource prefix. [#1588](https://github.com/HKUDS/DeepTutor/pull/1588) |
| [PR-Agent](https://github.com/The-PR-Agent/pr-agent)&nbsp;[![PR-Agent stars](https://img.shields.io/github/stars/The-PR-Agent/pr-agent?style=flat&label=%E2%98%85&color=555)](https://github.com/The-PR-Agent/pr-agent/stargazers)<br>AI code review tool | [1](https://github.com/The-PR-Agent/pr-agent/pulls?q=is%3Apr+is%3Amerged+author%3Aremote-controlled-man) | Updated GitHub changelog publishing to create the target file when it does not exist. [#3639](https://github.com/The-PR-Agent/pr-agent/pull/3639) |

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

## Contact

[LinkedIn](https://www.linkedin.com/in/steven-sidi-huang/)

<p align="center">
  <img src="./assets/header.svg" alt="Build. Evaluate. Improve. — Steven Huang, Agent Systems" width="100%" />
</p>

<p align="center">
  <strong>English</strong> · <a href="./README.zh-CN.md">简体中文</a>
</p>

# Hi, I'm Steven Huang · 黄思迪

**Agent systems · Evaluation · LLM post-training**

I'm a Computer Science master's student at **The University of Hong Kong**. I build agents that use tools, learn from failures, and can be evaluated beyond a convincing demo.

My work spans agent harnesses, embodied tool execution, retrieval, and small-model post-training. I care about making execution observable, failures reproducible, and improvements measurable.

[GitHub](https://github.com/remote-controlled-man) · [Projects](#selected-work) · [Experience](#experience) · [中文介绍](./README.zh-CN.md)

## What I work on

- **Reliable execution** — tool contracts, context and memory, runtime tracing, and recovery when things go wrong.
- **Evidence-driven evaluation** — task environments, deterministic verifiers, failure analysis, and controlled comparisons.
- **Efficient adaptation** — SFT / QLoRA, training data from failure traces, and routing between small and larger models.

## Selected work

### [skillfit](https://github.com/remote-controlled-man/skillfit)

**Do agent configurations actually help? Measure them.**

An open-source CLI for evaluating Skills, rules files, and MCP configurations on a user's own tasks. It pairs baseline and treatment runs, checks outcomes with verifiers, and reports quality, cost, and uncertainty. It also measures whether an agent actually invokes an installed Skill.

`TypeScript` `Agent Evals` `MCP` `Paired Experiments`

### DeviceAgent Arena

**Train and evaluate tool use through multi-step tasks and failure recovery.**

A personal project combining a task environment, fault injection, and scoring against both final state and execution trace. I fine-tuned Qwen3-1.7B with QLoRA and built a routing pipeline using FunctionGemma-270M for well-defined steps, with Qwen handling validation failures.

On **36 held-out tasks excluded from training and repair**, strict success improved from **22/36 to 31/36**; Qwen calls fell **34.1%** and P95 latency fell **17.6%**. Safety-check passes remained **34/36**. These results describe this task set.

`Tool Use` `QLoRA` `Failure Analysis` `Model Routing`

### ExamPilot

**A course assistant whose answers lead back to the source page.**

A personal Agentic RAG project using LangGraph and LightRAG to orchestrate retrieval and tool use over course materials. It combines vector retrieval with a knowledge graph, maps evidence back to document pages, and streams retrieval and tool events for inspection and replay.

`LangGraph` `LightRAG` `Page-level Citations` `RAG`

### [Agent Context & Memory Guide](https://github.com/remote-controlled-man/agent-context-memory-guide)

**Understand how agents assemble context and retain memory.**

Chinese learning notes comparing six agent projects through source-code reading, with implementation references and an accompanying learning site. The focus is on how history, summarization, retrieval, and persistent memory fit together.

`Context Engineering` `Memory` `Source-code Reading`

## Experience

| Where | Role | Focus |
| :--- | :--- | :--- |
| **Ant Group** · Jul 2026–present | Agent Optimization Algorithm Intern | Strategy-generation and evaluation loops, verifiers, and reproducible agent experiments |
| **Cybopal / 细胞壁科技** · Mar–Jun 2026 | Agent Algorithm Intern | Embodied tool execution, robotic-arm MCP integration, voice-command agents, and recovery |
| **Kuaishou** · Aug–Nov 2024 | Backend Development Intern | Async data processing and automated multimedia evaluation workflows |

## Toolkit

**Engineering** — Python, TypeScript, Rust, Asyncio, FastAPI, Tokio, Docker, CI/CD  
**Agent systems** — MCP, tool calling, JSON Schema, tracing, context and memory  
**Models & retrieval** — SFT, LoRA / QLoRA, LangGraph, LightRAG

## Education

**The University of Hong Kong** — Master's studies in Computer Science  
**Beijing University of Technology** — Bachelor's degree in Software Engineering

---

I'm happy to exchange ideas about agent evaluation, tool use, and open-source developer tooling. [Explore my repositories →](https://github.com/remote-controlled-man?tab=repositories)

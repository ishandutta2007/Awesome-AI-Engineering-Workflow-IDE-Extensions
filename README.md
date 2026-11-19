# Awesome-AI-Engineering-Workflow-IDE-Extensions

## Top AI Engineering Workflow & IDE Extensions Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Compound Engineering Plugins, Agentic IDE Extensions, Plan-to-PR Software Workflows, Local LLM Copilots & Multi-Editor AI Tooling*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Engineering Workflow & IDE Extensions**. These tools embed structured engineering workflows—planning, architecture review, multi-file editing, automated testing, and pull-request verification—directly inside VS Code, JetBrains IDEs, Neovim, Zed, and terminal editors.



**Examples** include Cursor, GitHub Copilot Workspace, Windsurf (Codeium), Replit Ghostwriter / Agent, Tabnine Enterprise, Amazon Q Developer, Sourcegraph Cody, Continue.dev, JetBrains AI, and EveryInc/compound-engineering-plugin (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for compound engineering agent plugins, autonomous VS Code & JetBrains extensions (`Continue`, `Cline`, `Roo Code`, `Kilo Code`), open-source AI-native editors (`Void`, `Zed`), Neovim/Emacs agent workflows, and local LLM autocomplete engines — ideal for software engineers, tech leads, and open-source maintainers building reproducible AI engineering pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The AI developer tools and engineering workflow market is projected to reach approximately $7.0B to $9.5B by 2026, driven by enterprise shift from simple autocomplete to autonomous agentic workflows and multi-file code synthesis. The sector displays a concentrated core dominated by hyperscalers and key platform providers (such as Microsoft/GitHub, Amazon, and Anysphere/Cursor) capturing the majority of enterprise revenue, complemented by a moderately fragmented, fast-evolving ecosystem of specialized venture-backed startups and open-source tooling.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Tier Pricing | Free Tier Limits / Evaluation | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon Q Developer](https://amazon.com)** | ~$2.1T (Parent: Amazon Market Cap) / $19/user/mo Pro tier | $19.00 / user / month (Pro Tier) | **Perpetual Free Tier**: 50 agentic requests/mo, 1,000 lines of code transformation/mo, and 50 security scans/mo (AWS Builder ID required). | Cloud AI software development assistant providing IDE code generation, automated Java/Python runtime upgrades, security vulnerability scanning, and AWS infrastructure troubleshooting. |
| **[GitHub Copilot & Copilot Workspace](https://github.com)** | ~$3.1T (Parent: Microsoft Market Cap) / ~$2B+ Copilot ARR | $10.00 / month (Copilot Pro) | **Perpetual Free Tier**: 2,000 code completions/mo and 50 chat messages/mo with basic agent capabilities; 30-day trial for Pro. | End-to-end AI engineering platform spanning inline IDE autocomplete, multi-file Copilot Edits, issue-to-PR planning workspaces, and autonomous coding agent workflows. |
| **[Cursor](https://cursor.com)** | $60B (Acquired by SpaceX, Aug 2026; prev. $29.3B Series D) | $20.00 / month (Pro Tier) | **Perpetual Free Tier (Hobby)**: 2,000 Tab completions/mo and 50 slow premium requests/mo; 14-day Pro trial on signup. | AI-native code editor forked from VS Code featuring predictive Tab autocomplete, codebase-wide RAG indexing, Composer multi-file agents, and background cloud agents. |
| **[Replit Agent & Ghostwriter](https://replit.com)** | $9B (Series D, Mar 2026; prev. $3B valuation) | $25.00 / month (Replit Core) | **Perpetual Free Tier (Starter)**: 0.5 vCPU, 512MB RAM, limited basic autocomplete, and a restricted daily allowance for Replit Agent. | Cloud-based collaborative IDE and autonomous software engineering platform capable of planning, coding, debugging, and deploying full-stack applications from natural language. |
| **[Windsurf (formerly Codeium)](https://windsurf.com)** | $3B (Acquired via Google licensing & Cognition, 2025) | $15.00 / month (Codeium Pro) / $20.00 / month (Windsurf Pro) | **Perpetual Free Tier**: Unlimited standard code autocompletions/edits across IDEs, with a restricted light quota for Cascade Flow agent actions on mini models. | Agentic AI IDE and multi-editor extension suite powered by Cascade flows, deep contextual awareness, live terminal/preview synchronization, and low-latency Supercomplete. |
| **[Sourcegraph Cody](https://sourcegraph.com)** | $2.6B (Series D valuation) / ~$50M ARR | $19.00 / user / month (Enterprise Starter) | **Enterprise Trial**: No perpetual free individual tier; provides a customized 14-to-30 day Enterprise proof-of-concept (PoC) evaluation upon sales demo. | Enterprise AI engineering assistant leveraging Sourcegraph's code graph and multi-repository search to deliver context-aware chat, inline edits, and unit test synthesis. |
| **[Augment Code](https://augmentcode.com)** | $977M (Series B valuation) | $20.00 / user / month (Standard Plan) | **Free Evaluation**: No perpetual free tier; offers an initial 7-day free trial / trial credits upon workspace onboarding. | Enterprise AI software engineering platform engineered with real-time codebase context engines for massive monorepos and autonomous task execution. |
| **[JetBrains AI Assistant & Junie](https://jetbrains.com)** | ~$700M+ Annual Revenue (Privately held / bootstrapped) | $10.00 / month (AI Pro) | **Perpetual Free Tier (`AI Free`)**: Unlimited local model support, basic local completions, and 3 cloud AI credits/30 days; includes 30-day AI Pro trial. | Natively integrated AI coding assistant and autonomous engineering agent built directly into IntelliJ IDEA, PyCharm, WebStorm, GoLand, and Rider. |
| **[Tabnine Enterprise](https://tabnine.com)** | ~$100M (Acquired by Tricentis, Jul 2026) / ~$27M ARR | $39.00 / user / month (Code Assistant Plan) | **Free Trial**: 90-day free trial of Pro/Code Assistant features; perpetual free starter tier has been discontinued. | Enterprise-grade AI coding assistant emphasizing zero-data-retention privacy, VPC/air-gapped deployments, custom repository fine-tuning, and compliance-safe code generation. |
| **[Continue.dev Hub (Cloud)](https://continue.dev)** | $5.5M funding raised (Acquired by Cursor, Jun 2026) | $10.00 / developer / month (Team Hub) | **Perpetual Free Tier**: Full open-source client extension (Apache 2.0) with unlimited usage via local LLMs (Ollama) or Bring-Your-Own-Key (BYOK). | Cloud governance and configuration layer for the open-source Continue IDE extension enabling shared team engineering assistants, MCP tool setups, and model routing policies. |





## Open-Source GitHub Projects



- **[EveryInc/compound-engineering-plugin](https://github.com)**  

  Open-source (`MIT`) compound engineering workflow plugin for Claude Code, Cursor, OpenCode, and Codex providing structured `/workflows:plan`, `/workflows:work`, `/workflows:review`, and `/workflows:compound` loops with multi-agent review personas.



- **[Continue (`continuedev/continue`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) AI code assistant extension for VS Code and JetBrains enabling custom Tab autocomplete, inline edits, and agent workflows backed by any local or cloud LLM.



- **[Cline (`cline/cline`)](https://github.com)**  

  Popular open-source (`Apache-2.0`) autonomous engineering agent for VS Code capable of creating/editing files, running terminal commands, inspecting browsers, and connecting to MCP servers with human-in-the-loop approval.



- **[Roo Code (`RooCodeInc/Roo-Code`)](https://github.com)**  

  Feature-rich open-source (`Apache-2.0`) fork of Cline offering specialized engineering modes (`Architect`, `Code`, `Debug`, `Orchestrator`), Boomerang sub-tasks, and granular model routing.



- **[Kilo Code (`Kilo-Org/kilocode`)](https://github.com)**  

  Open-source (`Apache-2.0`) unified VS Code AI engineering extension combining the best capabilities of Cline, Roo Code, and Continue with built-in model routing and automated refactoring.



- **[Void (`voideditor/void`)](https://github.com)**  

  Open-source (`Apache-2.0`) alternative to Cursor built directly on VS Code providing inline diffs, local codebase indexing, agentic file editing, and direct BYOK/Ollama connections.



- **[Zed Editor (`zed-industries/zed`)](https://github.com)**  

  High-performance open-source (`GPL-3.0` / `Apache-2.0`) Rust code editor featuring native Agentic Editing, Edit Prediction (`Zeta` open model), and multi-buffer AI engineering workflows.



- **[Aider (`Aider-AI/aider`)](https://github.com)**  

  Pioneering open-source (`Apache-2.0`) terminal AI pair-programming tool that maps entire Git repositories, coordinates multi-file edits, runs linters/tests, and creates clean Git commits.



- **[OpenCode (`anomalyco/opencode`)](https://github.com)**  

  Modern open-source (`MIT`) terminal-native AI coding agent featuring a polished TUI, LSP diagnostics integration, client/server architecture, and multi-provider LLM support.



- **[Tabby (`TabbyML/tabby`)](https://github.com)**  

  Self-hosted open-source (`Apache-2.0`) AI coding assistant written in Rust offering repository-level RAG, FIM (Fill-in-the-Middle) autocomplete, and extensions for VS Code, Vim/Neovim, and IntelliJ.



- **[Twinny (`twinnydotdev/twinny`)](https://github.com)**  

  Privacy-first open-source (`MIT`) VS Code extension designed for local Ollama, llama.cpp, and LM Studio inference with zero telemetry, FIM autocomplete, and RAG chat.



- **[Avante.nvim (`yetone/avante.nvim`)](https://github.com)**  

  Open-source (`Apache-2.0`) Neovim plugin replicating the Cursor AI IDE experience inside Vim with side-by-side diff previews, agentic tool calling, and multi-model support.



- **[CodeCompanion.nvim (`olimorris/codecompanion.nvim`)](https://github.com)**  

  Extensible open-source (`MIT`) AI engineering plugin for Neovim supporting inline code transformations, agentic slash commands, MCP servers, and local/cloud adapters.



- **[Superpowers (`obra/superpowers`)](https://github.com)**  

  Popular open-source (`MIT`) structured software-engineering skill framework for Claude Code, Codex, and OpenCode enforcing brainstorming, TDD, subagent-driven development, and systematic debugging.



- **[OpenHands (`All-Hands-AI/OpenHands`)](https://github.com)**  

  Open-source (`MIT`) platform for autonomous software-engineering agents operating inside sandboxed Docker containers with full bash, code editor, and web browser capabilities.



- **[PR-Agent / Qodo Merge (`qodo-ai/pr-agent`)](https://github.com)**  

  Open-source (`Apache-2.0`) AI-powered pull request reviewer and engineering workflow tool providing automated code walkthroughs, bug detection, test generation, and `/improve` commands.



- **[Refact.ai (`smallcloudai/refact`)](https://github.com)**  

  Self-hostable open-source (`BSD-3-Clause`) AI coding engine supporting local fine-tuning, AST-aware code completion, and autonomous bug-fixing agents for VS Code and JetBrains.



### Additional Strong Open-Source Options



- **[Serena (`oraios/serena`)](https://github.com)** and **[Tree-sitter (`tree-sitter/tree-sitter`)](https://github.com)** for Language Server Protocol (LSP) MCP toolkits and incremental AST parsing giving IDE extensions symbol-level codebase intelligence.

- **[Spec-Kit (`github/spec-kit`)](https://github.com)** and **[BMAD-METHOD (`bmadcode/BMAD-METHOD`)](https://github.com)** for open-source spec-driven AI engineering workflows (`Specify -> Plan -> Tasks -> Implement`) across IDE agents.

- **[llama.vim (`ggml-org/llama.vim`)](https://github.com)** and **[minuet-ai.nvim (`milanglacier/minuet-ai.nvim`)](https://github.com)** for ultra-lightweight Vim/Neovim local FIM code completion.

- **[Ollama (`ollama/ollama`)](https://github.com)** and **[Qwen2.5-Coder / Qwen3-Coder (`QwenLM/Qwen2.5-Coder`)](https://github.com)** for running high-accuracy open-weight coding models locally behind IDE extensions.

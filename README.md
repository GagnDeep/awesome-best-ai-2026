---
title: "best-AI-2026"
description: "Best AI 2026 open source GitHub list featuring verified self-hosted AI tools, coding agents, workflows, and local model stacks for builders."
icon: 📋
category: awesome-list
---

# Best AI 2026: Open Source GitHub Tools

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@main/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Topics](https://img.shields.io/github/stars/GagnDeep/awesome-best-ai-2026?style=social)

> Best AI 2026 is a curated list of open source AI tools that live on public GitHub repositories and can be self-hosted, extended, or audited. This list focuses on practical tools for coding, local inference, workflow automation, search, media, and AI-powered product building without depending on proprietary SaaS lock-in.

## Table of Contents
- [TL;DR](#tldr)
- [Why This List](#why-this-list)
- [Open Source Tools](#open-source-tools)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## TL;DR
- `LocalAI`, `Tabby`, `Plandex`, `Onyx`, and `Activepieces` are the strongest starting points for a practical open source AI stack in 2026.
- If you want local inference and API compatibility, start with `LocalAI`.
- If you want AI coding help on your own infrastructure, compare `Tabby`, `gemini-cli`, `qwen-code`, and `aide`.
- If you want retrieval, internal search, or knowledge assistants, `Onyx`, `openakita`, and `ragrabbit` are the clearest fits.
- If you want automations and agent workflows, `activepieces`, `rowboat`, `bytebot`, and `self-hosted-ai-starter-kit` cover most use cases.

## Why This List
The best AI 2026 stack is increasingly open source because teams want control over data, deployment, licensing, and model choice. Public GitHub repositories make it easier to inspect the code, self-host the workload, fork missing features, and avoid building a workflow around tools that can disappear or change pricing without warning.

This repository only includes tools that resolve to a `github.com` project URL. When a category has sparse coverage in the supplied research data, that gap is documented instead of padded with weak or unverifiable entries.

## Open Source Tools

### Coding And Developer Assistants

#### [gemini-cli](https://github.com/google-gemini/gemini-cli)
> **Description:** Gemini CLI is positioned as an open source command-line AI assistant for developer workflows. The repository centers on terminal-native prompting, code generation, shell-oriented usage, and extensibility for engineering tasks that benefit from a fast interactive loop. In the supplied GitHub research, it appears as a very large TypeScript project under Apache License 2.0 with strong community adoption. `Last Commit` data was not included in the offline dataset used to build this list, so that field is intentionally marked as a metadata gap to avoid inventing freshness signals.

- **GitHub:** [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
- **Stars:** 99,506 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** coding, cli, developer-tools
- **Best for:** terminal-first AI coding assistance

---

#### [qwen-code](https://github.com/QwenLM/qwen-code)
> **Description:** Qwen Code is an open source coding-focused assistant built around developer productivity tasks in the terminal and codebase context. Its positioning makes it useful for prompt-driven coding, repository-aware execution, and AI-assisted development loops without locking the user into a closed hosted product. The supplied research identifies it as a TypeScript project released under Apache License 2.0 with a large star count. Because the offline dataset does not include repository activity timestamps, the `Last Commit` value is kept explicit about that limitation rather than pretending the date was verified live.

- **GitHub:** [github.com/QwenLM/qwen-code](https://github.com/QwenLM/qwen-code)
- **Stars:** 21,320 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** coding, cli, llm-tools
- **Best for:** open source code generation and repo-aware coding flows

---

#### [tabby](https://github.com/TabbyML/tabby)
> **Description:** Tabby is a well-known self-hosted AI coding assistant that targets code completion and developer workflows for teams that want local control. The project is built in Rust and is commonly used as an alternative to hosted code assistants where privacy, customization, or deployment flexibility matters. In the research supplied for this repository, Tabby stands out as one of the strongest self-hosted coding options by star count. Its GitHub license metadata is listed as `Other`, so the list preserves that exact value instead of normalizing it.

- **GitHub:** [github.com/TabbyML/tabby](https://github.com/TabbyML/tabby)
- **Stars:** 33,233 ⭐
- **Language:** Rust
- **License:** Other
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** coding, self-hosted, autocomplete
- **Best for:** teams that need self-hosted AI code completion

---

#### [aide](https://github.com/codestoryai/aide)
> **Description:** Aide is an open source coding assistant project focused on helping developers work faster inside a codebase. The repository is implemented in TypeScript and is licensed under AGPL-3.0, making it relevant for users who prioritize source availability and are comfortable with copyleft licensing obligations. Its positioning in the supplied research places it alongside newer generation AI development tools rather than general chat products. The repository has a moderate but meaningful GitHub following, and the activity date remains an explicit unknown in this offline build.

- **GitHub:** [github.com/codestoryai/aide](https://github.com/codestoryai/aide)
- **Stars:** 2,199 ⭐
- **Language:** TypeScript
- **License:** GNU Affero General Public License v3.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** coding, assistant, agpl
- **Best for:** open source IDE-style AI assistance

---

#### [plandex](https://github.com/plandex-ai/plandex)
> **Description:** Plandex is an AI coding and planning tool designed for larger engineering tasks that need more structure than a single prompt-response loop. The project is written in Go and distributed under the MIT License, which makes it comparatively easy to adopt in commercial or internal engineering environments. It is best thought of as a tool for orchestrating multi-step development work, code changes, and implementation plans. Based on the supplied research, it has strong adoption and sits in the top tier of open GitHub projects for agent-like coding workflows.

- **GitHub:** [github.com/plandex-ai/plandex](https://github.com/plandex-ai/plandex)
- **Stars:** 15,168 ⭐
- **Language:** Go
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** coding, planning, agents
- **Best for:** structured multi-step AI coding tasks

---

#### [onlook](https://github.com/onlook-dev/onlook)
> **Description:** Onlook is an open source AI-assisted design and frontend workflow tool built in TypeScript. The project is relevant for developers and product teams that want design-aware iteration directly connected to code, making it more practical than generic image-generation tools for UI work. In the supplied research data it appears as a large Apache-2.0 repository with strong momentum. While this list cannot confirm live activity dates without network access, the project clearly qualifies as a substantial public GitHub tool rather than a thin demo repository.

- **GitHub:** [github.com/onlook-dev/onlook](https://github.com/onlook-dev/onlook)
- **Stars:** 24,985 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** frontend, design, developer-tools
- **Best for:** AI-assisted frontend and product UI iteration

---

### Self-Hosted AI Platforms And Local Stacks

#### [LocalAI](https://github.com/mudler/LocalAI)
> **Description:** LocalAI is a flagship open source project for running AI models locally and exposing interfaces that fit into existing app stacks. The repository is written in Go and uses the MIT License, which makes it attractive for self-hosted deployments, edge environments, and teams migrating away from hosted inference dependencies. In practice, LocalAI is often used when builders want local model execution behind a familiar API layer. The supplied research places it among the most popular self-hosted AI repositories in this list by GitHub stars.

- **GitHub:** [github.com/mudler/LocalAI](https://github.com/mudler/LocalAI)
- **Stars:** 44,589 ⭐
- **Language:** Go
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** self-hosted, inference, local-models
- **Best for:** local AI inference and API-compatible self-hosting

---

#### [self-hosted-ai-starter-kit](https://github.com/n8n-io/self-hosted-ai-starter-kit)
> **Description:** The self-hosted AI starter kit from n8n is aimed at giving teams a practical base for deploying AI workflows on infrastructure they control. The repository appears in the supplied research as a highly starred Apache-2.0 project and is best understood as deployment scaffolding plus working patterns, rather than a single monolithic application. It is useful for operators who want to stand up AI automations quickly with open tooling and standard components. Because the offline input omitted commit timestamps, freshness must be rechecked before publication if exact activity dates matter.

- **GitHub:** [github.com/n8n-io/self-hosted-ai-starter-kit](https://github.com/n8n-io/self-hosted-ai-starter-kit)
- **Stars:** 14,494 ⭐
- **Language:** Not specified in supplied dataset
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** self-hosted, starter-kit, automation
- **Best for:** bootstrapping an open source AI deployment stack

---

#### [LocalAGI](https://github.com/mudler/LocalAGI)
> **Description:** LocalAGI extends the local-first AI idea into agent-style workflows that can run without handing all control to a remote SaaS platform. It is built in Go, published under the MIT License, and surfaced in the supplied research as a smaller but still credible companion project in the self-hosted AI ecosystem. The repository is most relevant for users experimenting with local agents, task execution, and chained AI workflows close to their own infrastructure. It is included here because it is public, clearly GitHub-native, and aligned with open deployment goals.

- **GitHub:** [github.com/mudler/LocalAGI](https://github.com/mudler/LocalAGI)
- **Stars:** 1,693 ⭐
- **Language:** Go
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** self-hosted, agents, local-models
- **Best for:** local agent experiments and private AI task execution

---

#### [waveterm](https://github.com/wavetermdev/waveterm)
> **Description:** Wave Terminal is an open source terminal workspace that has become relevant for AI-assisted development because it blends shell work, workspace organization, and interactive tooling in one place. The supplied research shows it as a large Go repository under Apache License 2.0 with strong adoption. Although it is not a model server, it is a real infrastructure layer for people building AI-driven CLI workflows and managing multiple developer tasks. It belongs in this list because the best open source AI environment is often a stack of tools, not only models and chat interfaces.

- **GitHub:** [github.com/wavetermdev/waveterm](https://github.com/wavetermdev/waveterm)
- **Stars:** 18,936 ⭐
- **Language:** Go
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** terminal, developer-experience, workspace
- **Best for:** AI-heavy terminal workflows and multi-task developer sessions

---

#### [onyx](https://github.com/onyx-dot-app/onyx)
> **Description:** Onyx is an open source AI assistant platform aimed at search, knowledge access, and organizational information workflows. The project is written in Python and appears in the supplied research with a very large star count, indicating strong traction for teams that want self-hosted internal AI experiences. The GitHub license field is listed as `Other`, so that value is preserved exactly here. Onyx is one of the clearest enterprise-oriented options in this repository when the goal is to search across content and provide grounded answers inside a private environment.

- **GitHub:** [github.com/onyx-dot-app/onyx](https://github.com/onyx-dot-app/onyx)
- **Stars:** 20,160 ⭐
- **Language:** Python
- **License:** Other
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** self-hosted, enterprise-search, rag
- **Best for:** internal knowledge assistants and enterprise search

---

#### [selfhostedAI](https://github.com/josStorer/selfhostedAI)
> **Description:** selfhostedAI is a public GitHub project focused on practical self-hosted AI deployment patterns. In the supplied dataset it appears as a Python repository under Apache License 2.0. Compared with larger platforms, it is more useful as an opinionated toolkit or guide rail for users who want to assemble their own private AI environment. It is included because the repository is public, license metadata is visible in the research, and it reinforces the core theme of this list: building with GitHub-first tools that can run under your control.

- **GitHub:** [github.com/josStorer/selfhostedAI](https://github.com/josStorer/selfhostedAI)
- **Stars:** 417 ⭐
- **Language:** Python
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** self-hosted, deployment, infrastructure
- **Best for:** assembling a custom private AI stack

---

### Workflow Automation And Agents

#### [activepieces](https://github.com/activepieces/activepieces)
> **Description:** Activepieces is an open workflow automation platform that has become increasingly relevant for AI orchestration, agent pipelines, and tool-connected automations. It is built in TypeScript and is listed in the supplied research as a high-star repository with GitHub license metadata marked `Other`. The repository is best suited to users who want visual or structured automation building blocks without centering their stack on a closed SaaS workflow engine. It earns a place here because modern open source AI work often depends on automations, triggers, and integrations as much as it depends on models.

- **GitHub:** [github.com/activepieces/activepieces](https://github.com/activepieces/activepieces)
- **Stars:** 21,482 ⭐
- **Language:** TypeScript
- **License:** Other
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** automation, workflows, integrations
- **Best for:** AI-enabled workflow automation on your own infrastructure

---

#### [rowboat](https://github.com/rowboatlabs/rowboat)
> **Description:** Rowboat is an open source AI automation and agent-oriented platform built in TypeScript and licensed under Apache License 2.0. Based on the supplied research, it has a strong GitHub footprint and is positioned as a modern option for users building AI workflows that connect tools, prompts, and operational tasks. It is especially relevant when the goal is not just chatting with a model, but wiring LLM behavior into repeatable application logic. The repository is public and clearly tool-like, which makes it appropriate for this curated list.

- **GitHub:** [github.com/rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat)
- **Stars:** 9,333 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** agents, automation, orchestration
- **Best for:** agentic workflow building and operational automations

---

#### [bytebot](https://github.com/bytebot-ai/bytebot)
> **Description:** Bytebot is a TypeScript-based Apache-2.0 project in the supplied research that fits the emerging category of AI-driven task automation. Its public GitHub presence and star count make it stronger than many smaller automation demos, and the repository appears positioned around machine-assisted execution instead of static low-code flows. That makes it relevant for teams exploring semi-autonomous process automation on infrastructure they can inspect and modify. The project is included because it broadens the list beyond coding and search into real operational workflow territory.

- **GitHub:** [github.com/bytebot-ai/bytebot](https://github.com/bytebot-ai/bytebot)
- **Stars:** 10,698 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** automation, task-execution, agents
- **Best for:** AI-assisted operational workflows and execution agents

---

#### [ottomator-agents](https://github.com/coleam00/ottomator-agents)
> **Description:** Ottomator Agents is a Python project under the MIT License focused on agent workflows and examples that help users assemble useful AI automations faster. In the supplied GitHub research it has meaningful adoption and reads as a practical repository rather than a purely experimental snippet collection. It is most useful for builders who want ready-made patterns for tool use, chaining, and agent-style execution. The repository is included here because open source AI in 2026 increasingly means reusable agent systems rather than only standalone applications.

- **GitHub:** [github.com/coleam00/ottomator-agents](https://github.com/coleam00/ottomator-agents)
- **Stars:** 5,478 ⭐
- **Language:** Python
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** agents, examples, automation
- **Best for:** reusable agent templates and experiment-driven automation

---

#### [mission-control](https://github.com/builderz-labs/mission-control)
> **Description:** Mission Control is a TypeScript repository licensed under MIT that appears in the supplied self-hosted AI research as a strong workflow-oriented project. The name and positioning suggest a coordination layer for AI operations and task routing, which is useful for teams managing multiple AI processes rather than isolated prompts. It is included because it clears the core validation bar for this repository: public GitHub URL, visible metadata, open licensing, and a practical AI workflow focus. Users comparing agent control planes should keep it on the shortlist.

- **GitHub:** [github.com/builderz-labs/mission-control](https://github.com/builderz-labs/mission-control)
- **Stars:** 3,587 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** orchestration, control-plane, workflows
- **Best for:** coordinating AI task pipelines and operational flows

---

#### [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot)
> **Description:** FinRobot is a finance-oriented open source AI repository that appears in the supplied research as a Jupyter Notebook project under Apache License 2.0. While narrower than general-purpose automation platforms, it is a useful example of domain-specific agent and workflow work built in public. The repository is relevant for teams exploring autonomous analysis, research assistants, or task pipelines in regulated and data-heavy financial settings. It belongs in this category because its practical value comes from AI workflow composition more than from being a single general UI product.

- **GitHub:** [github.com/AI4Finance-Foundation/FinRobot](https://github.com/AI4Finance-Foundation/FinRobot)
- **Stars:** 6,514 ⭐
- **Language:** Jupyter Notebook
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** finance, agents, domain-specific-ai
- **Best for:** finance research and domain-specific AI automation

---

#### [Tale](https://github.com/tale-project/tale)
> **Description:** Tale is a self-hosted team workspace connecting project tasks and shared knowledge with configured AI agents and versioned automations. Tasks are started explicitly, with reports and deliverables available for review; automation definitions are versioned and deployed separately. Community software is MIT-licensed, while hosting infrastructure and configured model usage have separate costs.

- **GitHub:** [github.com/tale-project/tale](https://github.com/tale-project/tale)
- **Stars:** 32 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** 2026-10-08 (verified 2026-10-08)
- **Category:** agents, workflows, self-hosted
- **Best for:** shared project context, reviewed agent tasks, and versioned AI automations

---

### Search, RAG, And Knowledge Tools

#### [openakita](https://github.com/openakita/openakita)
> **Description:** OpenAkita is a Python-based Apache-2.0 project that fits the open source AI knowledge and assistant category. In the supplied research data it appears as a public GitHub repository with enough adoption to qualify as a credible tool rather than a toy example. It is relevant for search, document-aware assistants, or knowledge-centric AI workflows where teams want source visibility and self-hosting options. The project is included because GitHub-first knowledge tools remain one of the highest-value AI categories for real organizations.

- **GitHub:** [github.com/openakita/openakita](https://github.com/openakita/openakita)
- **Stars:** 1,497 ⭐
- **Language:** Python
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** knowledge, assistants, python
- **Best for:** building open knowledge assistants with Python tooling

---

#### [ragrabbit](https://github.com/madarco/ragrabbit)
> **Description:** Ragrabbit is a TypeScript MIT-licensed project surfaced in the supplied self-hosted AI results. The repository name and category fit retrieval-augmented generation workflows, making it relevant for builders who need a slimmer RAG-focused codebase instead of a full enterprise knowledge platform. With a smaller star count, it is not positioned as a category leader, but it is still a verified public GitHub option that broadens the list with a more focused retrieval tool. It is best used by users who want to prototype or customize document-grounded answer systems.

- **GitHub:** [github.com/madarco/ragrabbit](https://github.com/madarco/ragrabbit)
- **Stars:** 132 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** rag, retrieval, typescript
- **Best for:** lightweight RAG prototypes and custom retrieval apps

---

#### [openreview](https://github.com/vercel-labs/openreview)
> **Description:** OpenReview is a TypeScript repository from Vercel Labs that appears in the self-hosted AI research as a public project for reviewing or evaluating AI outputs and workflows. Its GitHub license field is blank in the supplied dataset, so it is excluded from harder licensing comparisons but still worth watching as a public reference implementation. It belongs in the search and knowledge section because review, evaluation, and content feedback loops are tightly coupled to document and answer quality. Use it as a research-grade building block, not as a guaranteed production standard.

- **GitHub:** [github.com/vercel-labs/openreview](https://github.com/vercel-labs/openreview)
- **Stars:** 1,235 ⭐
- **Language:** TypeScript
- **License:** License not captured in supplied offline GitHub dataset
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** evaluation, review, experiments
- **Best for:** evaluating AI outputs and review-oriented workflows

---

#### [lmrouter](https://github.com/LMRouter/lmrouter)
> **Description:** LMRouter is a TypeScript project under the MIT License that fits the infrastructure layer for routing requests across models, providers, or AI endpoints. In the supplied research it appears in the AI API search results, but its practical role is broader than API examples because routing is a core capability for production AI applications. The repository is useful when teams want an open control point between applications and the models they call. It is included here because routing and grounding infrastructure often matter more than the model UI itself.

- **GitHub:** [github.com/LMRouter/lmrouter](https://github.com/LMRouter/lmrouter)
- **Stars:** 293 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** routing, infrastructure, api-layer
- **Best for:** model routing and open AI application infrastructure

---

#### [QueryGPT](https://github.com/MoonMao42/QueryGPT)
> **Description:** QueryGPT is a Python MIT-licensed repository from the supplied AI database search results that appears aimed at natural-language querying over structured data. That makes it relevant to one of the most practical knowledge tasks in AI: turning human questions into useful database interactions. The project is smaller than the headline repositories in this list, but it still qualifies as a public GitHub tool with visible language and license metadata. It is included to represent the database-querying corner of the open source AI ecosystem.

- **GitHub:** [github.com/MoonMao42/QueryGPT](https://github.com/MoonMao42/QueryGPT)
- **Stars:** 29 ⭐
- **Language:** Python
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** database, natural-language-query, python
- **Best for:** translating questions into database-oriented AI workflows

---

#### [brainy](https://github.com/soulcraftlabs/brainy)
> **Description:** Brainy is a small TypeScript MIT-licensed repository found in the AI database search set. It does not have the adoption of larger search and assistant projects, but it is still a valid public GitHub entry that helps cover the long tail of AI knowledge tooling. The project is included cautiously and should be treated as an experimental or emerging option rather than a mature standard. Its presence also highlights a real gap in the supplied research: database-focused open AI tools are materially less populated than coding, local inference, or workflow categories.

- **GitHub:** [github.com/soulcraftlabs/brainy](https://github.com/soulcraftlabs/brainy)
- **Stars:** 6 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** database, experimental, knowledge-tools
- **Best for:** experimenting with smaller AI knowledge-tool codebases

---

### Media, Content, And Presentation Tools

#### [upscayl](https://github.com/upscayl/upscayl)
> **Description:** Upscayl is one of the most visible open source AI media tools in this research set. It is a TypeScript project under AGPL-3.0 and is best known for image upscaling workflows that users can run without depending on proprietary image services. The repository has very strong GitHub adoption and represents a category where open source AI is already highly practical for everyday work. It is included because media creation and enhancement remain a major part of how people search for the best AI 2026 tools.

- **GitHub:** [github.com/upscayl/upscayl](https://github.com/upscayl/upscayl)
- **Stars:** 44,279 ⭐
- **Language:** TypeScript
- **License:** GNU Affero General Public License v3.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** image, media, desktop
- **Best for:** local image upscaling with an open source stack

---

#### [presenton](https://github.com/presenton/presenton)
> **Description:** Presenton is an open source TypeScript project under Apache License 2.0 aimed at AI-assisted presentation creation. The repository appears in the supplied research as a substantial public GitHub tool rather than a minor template, making it a strong option for users who want AI support for slide workflows while keeping the code inspectable. It is relevant for product teams, founders, and internal communications use cases where fast deck generation matters. Compared with hosted presentation products, it offers more room for customization and self-managed deployment.

- **GitHub:** [github.com/presenton/presenton](https://github.com/presenton/presenton)
- **Stars:** 4,508 ⭐
- **Language:** TypeScript
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** presentations, content, typescript
- **Best for:** open source AI slide generation workflows

---

#### [presentation-ai](https://github.com/allweonedev/presentation-ai)
> **Description:** Presentation AI is another public GitHub tool for AI-assisted deck and presentation workflows. In the supplied research it appears as a TypeScript repository under the MIT License with meaningful adoption. Its inclusion alongside Presenton makes this category more useful for comparison instead of relying on a single example. Teams evaluating presentation-focused AI tools can compare design assumptions, license posture, and implementation style by looking at both repositories. It is one of the more practical content-generation projects in the provided dataset.

- **GitHub:** [github.com/allweonedev/presentation-ai](https://github.com/allweonedev/presentation-ai)
- **Stars:** 2,696 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** presentations, generation, productivity
- **Best for:** AI-generated presentation drafts and deck building

---

#### [photoshot](https://github.com/premieroctet/photoshot)
> **Description:** Photoshot is a TypeScript MIT-licensed GitHub repository focused on AI image workflows. It is included here because it adds a more creator-oriented option alongside infrastructure-heavy tools, showing that open source AI can also serve design, asset generation, and visual experimentation. The repository has a healthy star count in the supplied research and appears to be more productized than many small image demos. Users looking for customizable image-generation-adjacent tooling on GitHub should keep it in the shortlist.

- **GitHub:** [github.com/premieroctet/photoshot](https://github.com/premieroctet/photoshot)
- **Stars:** 3,888 ⭐
- **Language:** TypeScript
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** image, creative-tools, productized
- **Best for:** open source AI photo and image workflow experiments

---

#### [Scriberr](https://github.com/rishikanthc/Scriberr)
> **Description:** Scriberr is a Go-based MIT-licensed public repository listed in the supplied self-hosted AI results. Its name and placement suggest a writing, transcription, or content-assistance workflow oriented around self-hosting. It is included here because not every useful AI content tool needs massive GitHub scale to be worth tracking, especially when the repository is cleanly public and openly licensed. For users exploring written or voice-adjacent content pipelines outside proprietary platforms, Scriberr is a reasonable project to evaluate.

- **GitHub:** [github.com/rishikanthc/Scriberr](https://github.com/rishikanthc/Scriberr)
- **Stars:** 2,530 ⭐
- **Language:** Go
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** writing, content, self-hosted
- **Best for:** self-hosted content and writing-oriented AI workflows

---

#### [AVA-AI-Voice-Agent-for-Asterisk](https://github.com/hkjarral/AVA-AI-Voice-Agent-for-Asterisk)
> **Description:** AVA AI Voice Agent for Asterisk is a Python MIT-licensed repository focused on voice automation around the Asterisk telephony ecosystem. It is a useful inclusion because voice remains a real AI deployment category, and open telephony integrations are still relatively uncommon compared with chat or image tools. The project appears in the supplied research with more than 1,000 stars, which is enough to make it a serious option for voice agent experimentation. It is best suited to teams building AI-assisted call flows or interactive voice systems on infrastructure they control.

- **GitHub:** [github.com/hkjarral/AVA-AI-Voice-Agent-for-Asterisk](https://github.com/hkjarral/AVA-AI-Voice-Agent-for-Asterisk)
- **Stars:** 1,023 ⭐
- **Language:** Python
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** voice, telephony, agents
- **Best for:** AI voice agents integrated with Asterisk systems

---

### APIs, Frameworks, And Integrations

#### [cortex.cpp](https://github.com/janhq/cortex.cpp)
> **Description:** Cortex.cpp is a C++ project under Apache License 2.0 that appears in the supplied AI API research. It belongs in this list because open source AI stacks often need a runtime or systems-oriented layer, not just user-facing apps. The repository is notable for combining lower-level implementation concerns with practical AI usage, making it attractive to builders who want more control over performance and deployment than JavaScript-first tools typically offer. It is one of the stronger native-code projects in the provided dataset.

- **GitHub:** [github.com/janhq/cortex.cpp](https://github.com/janhq/cortex.cpp)
- **Stars:** 2,763 ⭐
- **Language:** C++
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** runtime, c-plus-plus, infrastructure
- **Best for:** low-level AI runtime and systems integration work

---

#### [susi_api_wrapper](https://github.com/fossasia/susi_api_wrapper)
> **Description:** SUSI API Wrapper is a Python Apache-2.0 repository that represents the API and integration side of open AI development. Rather than being a full standalone product, it is useful as a bridge for developers who need reusable code to talk to AI services or assistant backends in an open source way. The project has a substantial star count in the supplied dataset and reflects a more integration-heavy layer of the ecosystem. It is best suited to developers assembling custom applications around existing open AI services.

- **GitHub:** [github.com/fossasia/susi_api_wrapper](https://github.com/fossasia/susi_api_wrapper)
- **Stars:** 1,487 ⭐
- **Language:** Python
- **License:** Apache License 2.0
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** api, wrapper, python
- **Best for:** integrating open AI assistant capabilities into custom apps

---

#### [stability-sdk](https://github.com/Stability-AI/stability-sdk)
> **Description:** Stability SDK is a MIT-licensed repository surfaced in the supplied AI API research as a common integration layer for image and generative workflows. Although it is not a full application, it is a practical open source dependency for developers building media-focused AI products. The repository has strong GitHub adoption relative to other API-layer entries and gives this list a credible framework-level option for media generation pipelines. It is useful when you need code, examples, and client-side access patterns instead of a desktop interface.

- **GitHub:** [github.com/Stability-AI/stability-sdk](https://github.com/Stability-AI/stability-sdk)
- **Stars:** 2,440 ⭐
- **Language:** Jupyter Notebook
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** sdk, media, api
- **Best for:** building image-generation products on open SDK foundations

---

#### [OpenAI-Api-Unreal](https://github.com/KellanM/OpenAI-Api-Unreal)
> **Description:** OpenAI API Unreal is a C++ MIT-licensed plugin-style repository that makes the API and integration category more useful for game and realtime developers. It is included because the best AI 2026 landscape is broader than web apps and terminals; game engines and interactive simulations also need open integration code on GitHub. The repository has a respectable star count in the supplied dataset and is more specific than a generic API wrapper, which helps diversify the list with a concrete platform use case.

- **GitHub:** [github.com/KellanM/OpenAI-Api-Unreal](https://github.com/KellanM/OpenAI-Api-Unreal)
- **Stars:** 769 ⭐
- **Language:** C++
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** unreal, integration, games
- **Best for:** integrating AI features into Unreal Engine projects

---

#### [OpenAi-Api-Unity](https://github.com/hexthedev/OpenAi-Api-Unity)
> **Description:** OpenAI API Unity is a C# MIT-licensed GitHub repository aimed at Unity developers who need AI integrations inside games, prototypes, or interactive applications. It complements the Unreal entry by covering the other major indie and cross-platform engine ecosystem. The project is included because public integration code matters for developers who do not want to start from raw HTTP requests or closed plugins. Within this list, it serves as a practical bridge between open AI APIs and production-facing interactive software.

- **GitHub:** [github.com/hexthedev/OpenAi-Api-Unity](https://github.com/hexthedev/OpenAi-Api-Unity)
- **Stars:** 341 ⭐
- **Language:** C#
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** unity, integration, games
- **Best for:** adding AI features to Unity apps and games

---

#### [ComfyUI-OllamaGemini](https://github.com/al-swaiti/ComfyUI-OllamaGemini)
> **Description:** ComfyUI Ollama Gemini is a Python MIT-licensed repository that connects model tooling into a ComfyUI-style workflow. It is a useful integration example for users who value visual pipelines and composable graph-based execution over hand-written scripts. The project has a smaller star count than the largest repositories here, but it is still a public GitHub tool with explicit metadata and a clear AI integration purpose. It helps round out the list by covering open composable tooling for advanced users and makers.

- **GitHub:** [github.com/al-swaiti/ComfyUI-OllamaGemini](https://github.com/al-swaiti/ComfyUI-OllamaGemini)
- **Stars:** 171 ⭐
- **Language:** Python
- **License:** MIT License
- **Last Commit:** Not captured in supplied offline GitHub dataset
- **Category:** comfyui, integrations, visual-workflows
- **Best for:** graph-based AI workflows with open integrations

---

### Gaps In The Supplied Research
- `AI databases` had fewer than 5 strong, clearly licensed, production-grade repositories in the supplied research after filtering for public GitHub URLs and usable metadata.
- `AI alternatives` had only a handful of candidates and several weak or unclear repositories, so it is underrepresented here by design.
- `AI workflow automation` had enough entries to include, but the long tail was much thinner than coding, self-hosted inference, or media tools.
- `Last Commit` dates were not present in the provided offline dataset. Refresh those fields from live GitHub metadata before publishing if exact recency is required.

## FAQ

### What are the best open source AI tools on GitHub in 2026?
The strongest options in this list for broad use are `LocalAI`, `Tabby`, `Onyx`, `Plandex`, `gemini-cli`, and `activepieces`. They cover the main workloads most teams care about: local inference, coding assistance, knowledge search, and workflow automation.

### What is the best self-hosted AI stack for 2026?
A practical self-hosted stack usually combines `LocalAI` for model serving, `Onyx` or `openakita` for retrieval and knowledge, and `activepieces` or `rowboat` for automation. If coding help is part of the stack, add `Tabby` or `Plandex`.

### Which open source AI coding assistants are worth using?
`Tabby`, `gemini-cli`, `qwen-code`, `aide`, and `Plandex` are the main coding-focused picks in this list. The right choice depends on whether you want self-hosted autocomplete, terminal-first workflows, or structured multi-step coding plans.

### Are these AI tools free to use commercially?
Some are, some are not. The list preserves GitHub license metadata exactly where it was provided, so check the license on each repository before adopting it in a product. MIT and Apache-2.0 are usually the easiest starting points for commercial use.

### Why are some licenses listed as `Other` or missing?
That is how the supplied GitHub research data represented them. This repository does not rewrite or guess license metadata. If licensing is a hard requirement, verify the repository directly before using it.

### Why are last commit dates missing from the entries?
The offline research data used for this build included stars, primary language, and license metadata, but not last commit dates. Instead of fabricating activity dates, the list flags that gap explicitly.

### How do I submit a new tool to this awesome list?
Open a pull request with a public `github.com` repository URL, a short description, stars, primary language, license, and last commit date. Non-GitHub links and proprietary SaaS products are out of scope for this repository.

## GitHub Search Queries Used

The supplied research referenced these query themes. Example CLI commands:

```bash
gh search repos "open source AI" --limit 50
gh search repos "self-hosted AI" --limit 50
gh search repos "AI API" --limit 50
gh search repos "AI database" --limit 50
gh search repos "AI alternative" --limit 50
gh search repos "AI workflow automation" --limit 50
```

## Contributing

Contributions are welcome. Every submission must include:

- A public `github.com/owner/repo` URL
- A short description of what the tool does
- GitHub stars, primary language, and license metadata
- A verified last commit date
- A category suggestion and a `Best for` line

Submissions will be rejected if they:

- Link to a proprietary SaaS instead of a GitHub repository
- Depend on a non-GitHub homepage as the canonical URL
- Omit license information or have unclear repository status
- Are duplicates, abandoned demos, or off-topic academic notes without a usable tool

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full process.

## License

MIT License. See [LICENSE](./LICENSE).

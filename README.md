# Awesome AI Agents Index

> 一份面向学习者与工程师的 **AI Agents 学习资源索引**：课程教程、框架 SDK、编码 CLI、实战项目、多智能体、浏览器/Computer Use、记忆与 RAG、评测基准、论文调研、工程实践与社区精选。

**Stars 数据抓取日期：2026-07-22**（按 GitHub stars 降序排列；同一资源不跨分类重复列出）

---

## 目录

1. [课程教程](#1-课程教程)
2. [Agent 框架与 SDK](#2-agent-框架与-sdk)
3. [编码 Agent / CLI 工具](#3-编码-agent--cli-工具)
4. [实战应用与自主 Agent](#4-实战应用与自主-agent)
5. [多智能体系统](#5-多智能体系统)
6. [浏览器与 Computer Use](#6-浏览器与-computer-use)
7. [记忆、RAG 与工具生态](#7-记忆rag-与工具生态)
8. [评测基准](#8-评测基准)
9. [论文与调研索引](#9-论文与调研索引)
10. [工程实践、可观测与 Awesome 社区](#10-工程实践可观测与-awesome-社区)

---

## 1. 课程教程

从入门到生产的系统化学习路径（官方课程、Cookbook、开源教程）。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 113345 | 微软 Generative AI 入门：21 课 |
| 2 | [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch) | 99538 | 从零实现 ChatGPT 类 LLM（PyTorch） |
| 3 | [mlabonne/llm-course](https://github.com/mlabonne/llm-course) | 81133 | LLM 学习路线图 + Colab 笔记本 |
| 4 | [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 76806 | Prompt / Context / RAG / Agents 指南 |
| 5 | [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | 74795 | OpenAI 官方 Cookbook |
| 6 | [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | 70050 | 微软 AI Agents 入门：18 课 |
| 7 | [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents) | 67802 | 《从零开始构建智能体》中文教程 |
| 8 | [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 52558 | 微软 AI for Beginners：12 周 24 课 |
| 9 | [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | 49282 | Anthropic Claude 官方 Cookbook |
| 10 | [patchy631/ai-engineering-hub](https://github.com/patchy631/ai-engineering-hub) | 36636 | LLM / RAG / Agent 实战工程教程 |
| 11 | [huggingface/agents-course](https://github.com/huggingface/agents-course) | 30311 | Hugging Face Agents Course |
| 12 | [NirDiamant/GenAI_Agents](https://github.com/NirDiamant/GenAI_Agents) | 23413 | 50+ GenAI Agent 技术教程与实现 |
| 13 | [anthropics/courses](https://github.com/anthropics/courses) | 22387 | Anthropic 官方教育课程 |
| 14 | [NirDiamant/agents-towards-production](https://github.com/NirDiamant/agents-towards-production) | 21150 | 生产级 Agent 端到端代码教程 |
| 15 | [google-gemini/cookbook](https://github.com/google-gemini/cookbook) | 17555 | Google Gemini API Cookbook |
| 16 | [huggingface/smol-course](https://github.com/huggingface/smol-course) | 6692 | Hugging Face smol models 对齐课程 |
| 17 | [coleam00/ai-agents-masterclass](https://github.com/coleam00/ai-agents-masterclass) | 3442 | YouTube AI Agents Masterclass 配套代码 |
| 18 | [pguso/agents-from-scratch](https://github.com/pguso/agents-from-scratch) | 907 | 无框架、从第一性原理构建 Agent |
| 19 | [martimfasantos/ai-agents-frameworks](https://github.com/martimfasantos/ai-agents-frameworks) | 613 | 主流开源 Agent 框架对比实验场 |
| 20 | [bryanyzhu/agentic-ai-system-course](https://github.com/bryanyzhu/agentic-ai-system-course) | 491 | 设计 / 构建 / 运维生产 Agent 课程骨架 |

---

## 2. Agent 框架与 SDK

构建 Agent 的核心库与工程平台。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | 152186 | 可视化构建与部署 AI Agent / Workflow |
| 2 | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 142292 | Agent 工程平台（LangChain） |
| 3 | [microsoft/autogen](https://github.com/microsoft/autogen) | 59885 | 微软 Agentic AI 编程框架 |
| 4 | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 55935 | 角色协作式多 Agent 编排框架 |
| 5 | [BerriAI/litellm](https://github.com/BerriAI/litellm) | 54299 | 统一 100+ LLM API 的轻量网关 |
| 6 | [run-llama/llama_index](https://github.com/run-llama/llama_index) | 50994 | Document Agent / RAG 领先框架 |
| 7 | [agno-agi/agno](https://github.com/agno-agi/agno) | 41335 | 构建、运行与管理 Agent 平台 |
| 8 | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 37808 | 构建有状态、可恢复的 Agent |
| 9 | [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) | 36296 | 用编程而非纯提示词编排 LM |
| 10 | [huggingface/smolagents](https://github.com/huggingface/smolagents) | 28483 | 以代码思考的极简 Agent 库 |
| 11 | [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | 28346 | 微软 Semantic Kernel |
| 12 | [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 28072 | OpenAI 多 Agent 工作流框架 |
| 13 | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) | 28136 | 可观测、可信的 Agent 构建运行时 |
| 14 | [vercel/ai](https://github.com/vercel/ai) | 25714 | Vercel AI SDK（TypeScript） |
| 15 | [google/adk-python](https://github.com/google/adk-python) | 20835 | Google Agent Development Kit |
| 16 | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | 18723 | Pydantic 风格的 Agent 框架 |
| 17 | [camel-ai/camel](https://github.com/camel-ai/camel) | 17462 | CAMEL：多智能体与 Scaling Law |
| 18 | [QwenLM/Qwen-Agent](https://github.com/QwenLM/Qwen-Agent) | 16826 | 基于 Qwen 的 Agent 框架与应用 |
| 19 | [VoltAgent/voltagent](https://github.com/VoltAgent/voltagent) | 10109 | TypeScript Agent 工程平台 |
| 20 | [strands-agents/harness-sdk](https://github.com/strands-agents/harness-sdk) | 6664 | 生产 Agent Harness SDK（Py/TS） |

---

## 3. 编码 Agent / CLI 工具

终端与 IDE 中的编码 Agent（含用户提到的 gemini-cli、hermes、opencode 等）。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 218515 | Hermes：与你一起成长的 Agent |
| 2 | [anomalyco/opencode](https://github.com/anomalyco/opencode) | 188400 | 开源编码 Agent |
| 3 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 138626 | Claude Code：终端 Agentic 编码工具 |
| 4 | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | 106114 | 把 Gemini 带进终端的开源 Agent |
| 5 | [openai/codex](https://github.com/openai/codex) | 100487 | OpenAI 轻量终端编码 Agent |
| 6 | [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) | 81624 | OpenHands：AI 驱动开发 |
| 7 | [earendil-works/pi](https://github.com/earendil-works/pi) | 74927 | Agent 工具包：LLM API + Agent Loop + TUI |
| 8 | [openinterpreter/openinterpreter](https://github.com/openinterpreter/openinterpreter) | 67085 | 面向开源模型的编码 Agent |
| 9 | [cline/cline](https://github.com/cline/cline) | 64915 | 自主编码 Agent（SDK / IDE / CLI） |
| 10 | [Aider-AI/aider](https://github.com/Aider-AI/aider) | 47602 | 终端 AI 结对编程 |
| 11 | [continuedev/continue](https://github.com/continuedev/continue) | 35023 | 开源编码 Agent |
| 12 | [cursor/cursor](https://github.com/cursor/cursor) | 33054 | Cursor IDE 相关开源仓库 |
| 13 | [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) | 19882 | 自动修复 GitHub Issue 的 Agent |
| 14 | [smol-ai/developer](https://github.com/smol-ai/developer) | 12185 | 可嵌入应用的 Developer Agent |
| 15 | [SWE-agent/mini-swe-agent](https://github.com/SWE-agent/mini-swe-agent) | 5951 | 约 100 行的高分 SWE-bench Agent |
| 16 | [smallcloudai/refact](https://github.com/smallcloudai/refact) | 3549 | 端到端工程任务 AI Agent |
| 17 | [AutoCodeRoverSG/auto-code-rover](https://github.com/AutoCodeRoverSG/auto-code-rover) | 3095 | 仓库结构感知的自主软件工程师 |
| 18 | [kenryu42/cc-safety-net](https://github.com/kenryu42/cc-safety-net) | 1452 | 编码 CLI 危险命令安全网 |
| 19 | [Dicklesworthstone/pi_agent_rust](https://github.com/Dicklesworthstone/pi_agent_rust) | 1375 | Rust 高性能编码 Agent CLI |
| 20 | [minmaxflow/mini-kode](https://github.com/minmaxflow/mini-kode) | 304 | 教学向 AI 编码 Agent CLI |

---

## 4. 实战应用与自主 Agent

可直接运行或二次开发的 Agent 产品与应用。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [n8n-io/n8n](https://github.com/n8n-io/n8n) | 197404 | 工作流自动化平台（原生 AI 能力） |
| 2 | [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 185649 | 自主 Agent 经典项目 AutoGPT |
| 3 | [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | 154148 | Agent 友好的网页抓取与搜索 API |
| 4 | [langgenius/dify](https://github.com/langgenius/dify) | 149704 | Agentic 工作流 / RAG 协作平台 |
| 5 | [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 77561 | 长程 SuperAgent harness |
| 6 | [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) | 63660 | 本地优先的完整 Agent 体验 |
| 7 | [pathwaycom/llm-app](https://github.com/pathwaycom/llm-app) | 59004 | RAG / AI Pipeline 云模板 |
| 8 | [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt) | 57358 | 私有化 RAG / Skills / MCP API 层 |
| 9 | [FoundationAgents/OpenManus](https://github.com/FoundationAgents/OpenManus) | 57539 | 开源通用 Agent（OpenManus） |
| 10 | [FlowiseAI/Flowise](https://github.com/FlowiseAI/Flowise) | 54819 | 可视化构建 AI Agents |
| 11 | [janhq/jan](https://github.com/janhq/jan) | 43667 | 离线运行的开源 ChatGPT 替代 |
| 12 | [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | 41095 | 增强版 ChatGPT：Agents / MCP / Skills |
| 13 | [reworkd/AgentGPT](https://github.com/reworkd/AgentGPT) | 36278 | 浏览器中组装部署自主 Agent |
| 14 | [khoj-ai/khoj](https://github.com/khoj-ai/khoj) | 35921 | 可自托管的 AI 第二大脑 / 自主 Agent |
| 15 | [stanford-oval/storm](https://github.com/stanford-oval/storm) | 30233 | LLM 知识策展与长文报告系统 |
| 16 | [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) | 28539 | 自主深度研究 Agent |
| 17 | [microsoft/JARVIS](https://github.com/microsoft/JARVIS) | 25076 | 连接 LLM 与 ML 社区的系统 |
| 18 | [dzhng/deep-research](https://github.com/dzhng/deep-research) | 19393 | 极简迭代式深度研究 Agent |
| 19 | [agent0ai/agent-zero](https://github.com/agent0ai/agent-zero) | 18486 | Agent Zero AI 框架 |
| 20 | [TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | 17632 | 开发者优先的自主 Agent 框架 |

---

## 5. 多智能体系统

角色分工、协作编排与 Agent 间协议（与「框架」分类互补，侧重协作形态与协议）。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 93999 | 多智能体金融交易框架 |
| 2 | [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 69465 | 多智能体「软件公司」框架 |
| 3 | [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | 33802 | LLM 驱动的多智能体协作开发 |
| 4 | [a2aproject/A2A](https://github.com/a2aproject/A2A) | 24938 | Agent2Agent 互操作开放协议 |
| 5 | [yoheinakajima/babyagi](https://github.com/yoheinakajima/babyagi) | 22336 | 经典任务驱动自主 Agent |
| 6 | [openai/swarm](https://github.com/openai/swarm) | 21853 | OpenAI 轻量多智能体编排（教育向） |
| 7 | [elizaOS/eliza](https://github.com/elizaOS/eliza) | 18790 | 开源 Agent 操作系统 |
| 8 | [OpenBMB/XAgent](https://github.com/OpenBMB/XAgent) | 8525 | 复杂任务自主 LLM Agent |
| 9 | [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) | 7598 | 多 harness 编排与策略沙箱 |
| 10 | [xlang-ai/OpenAgents](https://github.com/xlang-ai/OpenAgents) | 4849 | 野外语言 Agent 开放平台 |
| 11 | [LazyAGI/LazyLLM](https://github.com/LazyAGI/LazyLLM) | 3855 | 低门槛多智能体应用构建 |
| 12 | [Josh-XT/AGiXT](https://github.com/Josh-XT/AGiXT) | 3205 | 跨 Provider 的 Agent 自动化平台 |
| 13 | [InternLM/lagent](https://github.com/InternLM/lagent) | 2270 | 轻量 LLM Agent 构建框架 |
| 14 | [openonion/connectonion](https://github.com/openonion/connectonion) | 1174 | Agent 协作框架 |
| 15 | [victordibia/autogen-ui](https://github.com/victordibia/autogen-ui) | 999 | AutoGen Web UI |
| 16 | [framerslab/agentos](https://github.com/framerslab/agentos) | 601 | TS：认知记忆 + 多 Agent 编排 |
| 17 | [EthanXiang777/circuit-framework](https://github.com/EthanXiang777/circuit-framework) | 487 | 多智能体交易研究系统 |
| 18 | [Kohaku-Lab/KohakuTerrarium](https://github.com/Kohaku-Lab/KohakuTerrarium) | 442 | 组合式多智能体团队与工具运行时 |
| 19 | [evalops/cognitive-dissonance-dspy](https://github.com/evalops/cognitive-dissonance-dspy) | 282 | 认知失调检测与消解多智能体 |
| 20 | [DeepAuto-AI/automl-agent](https://github.com/DeepAuto-AI/automl-agent) | 149 | AutoML 全流程多智能体（ICML'25） |

---

## 6. 浏览器与 Computer Use

网页自动化、GUI / 桌面操作与 Computer-Using Agents。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 105984 | 让网站对 AI Agent 可用的浏览器自动化 |
| 2 | [bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | 38173 | 开源多模态 AI Agent 桌面栈 |
| 3 | [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) | 27049 | 网站转 CLI，供 Agent 使用已登录浏览器 |
| 4 | [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) | 22546 | AI 驱动的浏览器工作流自动化 |
| 5 | [browser-use/browser-harness](https://github.com/browser-use/browser-harness) | 16160 | 自愈式 Browser Harness |
| 6 | [web-infra-dev/midscene](https://github.com/web-infra-dev/midscene) | 14151 | 视觉驱动的跨平台 UI 自动化 |
| 7 | [microsoft/fara](https://github.com/microsoft/fara) | 6016 | Fara：前沿 Computer Use Agent 模型族 |
| 8 | [yuruotong1/autoMate](https://github.com/yuruotong1/autoMate) | 3936 | 自然语言驱动的本地电脑自动化 |
| 9 | [TurixAI/TuriX-CUA](https://github.com/TurixAI/TuriX-CUA) | 3124 | TuriX Computer-use Agent |
| 10 | [xlang-ai/OSWorld](https://github.com/xlang-ai/OSWorld) | 3030 | 真实电脑环境多模态 Agent 基准 |
| 11 | [showlab/ShowUI](https://github.com/showlab/ShowUI) | 1883 | GUI Agent / Computer Use 端到端模型 |
| 12 | [openai/openai-cua-sample-app](https://github.com/openai/openai-cua-sample-app) | 1751 | OpenAI CUA API 示例 |
| 13 | [web-arena-x/webarena](https://github.com/web-arena-x/webarena) | 1550 | 真实 Web 环境自主 Agent 基准 |
| 14 | [a-real-ai/pywinassistant](https://github.com/a-real-ai/pywinassistant) | 1344 | 纯自然语言操作 GUI 的开源 CUA |
| 15 | [ServiceNow/BrowserGym](https://github.com/ServiceNow/BrowserGym) | 1284 | Web 任务自动化 Gym 环境 |
| 16 | [OpenGVLab/ScaleCUA](https://github.com/OpenGVLab/ScaleCUA) | 1126 | 跨平台 Computer Use Agents |
| 17 | [OSU-NLP-Group/SeeAct](https://github.com/OSU-NLP-Group/SeeAct) | 851 | 通用 Web Agent（ICML'24） |
| 18 | [xlang-ai/OpenCUA](https://github.com/xlang-ai/OpenCUA) | 802 | Computer-Use Agents 开放基础 |
| 19 | [meituan/EvoCUA](https://github.com/meituan/EvoCUA) | 332 | 演化式 Computer Use Agent |
| 20 | [langchain-ai/langgraph-cua-py](https://github.com/langchain-ai/langgraph-cua-py) | 214 | LangGraph 实现的 CUA |

---

## 7. 记忆、RAG 与工具生态

Memory、检索增强、MCP、工具调用与沙箱。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | 88742 | Model Context Protocol 官方 Servers |
| 2 | [mem0ai/mem0](https://github.com/mem0ai/mem0) | 61418 | AI Agents 通用记忆层 |
| 3 | [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | 29317 | 1000+ 工具包与 Agent 执行工作台 |
| 4 | [NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques) | 28761 | 高级 RAG 技术 Notebook 合集 |
| 5 | [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | 27068 | Agent Memory / RAG / Skills 统一上下文库 |
| 6 | [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 25976 | 生产级编排：检索、路由、记忆、生成 |
| 7 | [chatchat-space/Langchain-Chatchat](https://github.com/chatchat-space/Langchain-Chatchat) | 38456 | 本地知识库 RAG + Agent 应用 |
| 8 | [guidance-ai/guidance](https://github.com/guidance-ai/guidance) | 21689 | 控制 LLM 输出的 Guidance 语言 |
| 9 | [dottxt-ai/outlines](https://github.com/dottxt-ai/outlines) | 14909 | Structured Outputs |
| 10 | [567-labs/instructor](https://github.com/567-labs/instructor) | 13596 | LLM 结构化输出 |
| 11 | [e2b-dev/E2B](https://github.com/e2b-dev/E2B) | 13067 | Agent 安全沙箱运行时 |
| 12 | [Portkey-AI/gateway](https://github.com/Portkey-AI/gateway) | 12502 | AI Gateway + Guardrails |
| 13 | [microsoft/TaskWeaver](https://github.com/microsoft/TaskWeaver) | 6176 | 代码优先的数据分析 Agent 框架 |
| 14 | [microsoft/promptflow](https://github.com/microsoft/promptflow) | 11187 | LLM App 从原型到生产 |
| 15 | [PrefectHQ/marvin](https://github.com/PrefectHQ/marvin) | 6180 | Ambient intelligence 库 |
| 16 | [BuilderIO/gpt-crawler](https://github.com/BuilderIO/gpt-crawler) | 22359 | 爬站生成自定义 GPT 知识文件 |
| 17 | [langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research) | 12299 | LangChain 开源深度研究 |
| 18 | [lastmile-ai/aiconfig](https://github.com/lastmile-ai/aiconfig) | 1087 | 配置驱动的生成式 AI 应用框架 |
| 19 | [heurist-network/heurist-agent-framework](https://github.com/heurist-network/heurist-agent-framework) | 818 | 推理 / 工具 / 记忆 / MCP / AaaS |
| 20 | [open-gitagent/gitagent](https://github.com/open-gitagent/gitagent) | 618 | Git-native：身份、规则、记忆皆版本化 |

---

## 8. 评测基准

衡量 Agent 能力的公开基准与评测工具。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 23480 | Prompt / Agent / RAG 测试与红队 |
| 2 | [confident-ai/deepeval](https://github.com/confident-ai/deepeval) | 17022 | LLM Evaluation Framework |
| 3 | [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) | 14947 | LLM / RAG 应用评估 |
| 4 | [AgentOps-AI/agentops](https://github.com/AgentOps-AI/agentops) | 5721 | Agent 监控、成本与基准 SDK |
| 5 | [SWE-bench/SWE-bench](https://github.com/SWE-bench/SWE-bench) | 5467 | 真实 GitHub Issue 修复基准 |
| 6 | [THUDM/AgentBench](https://github.com/THUDM/AgentBench) | 3588 | 将 LLM 作为 Agent 的综合基准 |
| 7 | [openai/SWELancer-Benchmark](https://github.com/openai/SWELancer-Benchmark) | 1436 | 自由职业软件工程收益基准 |
| 8 | [allenai/ai2thor](https://github.com/allenai/ai2thor) | 1772 | 视觉 AI 交互环境平台 |
| 9 | [augmentcode/augment-swebench-agent](https://github.com/augmentcode/augment-swebench-agent) | 876 | 开源 SWE-bench Verified 实现 |
| 10 | [Kodezi/Chronos](https://github.com/Kodezi/Chronos) | 4924 | 调试优先模型与 SWE-bench 相关结果 |
| 11 | [scaleapi/SWE-bench_Pro-os](https://github.com/scaleapi/SWE-bench_Pro-os) | 485 | 长程软件工程任务基准 |
| 12 | [Human-Agent-Society/CORAL](https://github.com/Human-Agent-Society/CORAL) | 832 | 多智能体自演化与评测基础设施 |
| 13 | [china-qijizhifeng/agentic-harness-engineering](https://github.com/china-qijizhifeng/agentic-harness-engineering) | 758 | Agentic Harness 自动演化与评测 |
| 14 | [xlang-ai/OSWorld-V2](https://github.com/xlang-ai/OSWorld-V2) | 198 | OSWorld 2.0：长程真实任务 |
| 15 | [aymeric-roucher/GAIA](https://github.com/aymeric-roucher/GAIA) | 153 | 用 Transformers Agents 冲击 GAIA |
| 16 | [Future-House/BixBench](https://github.com/Future-House/BixBench) | 132 | 计算生物学 LLM Agent 基准 |
| 17 | [Kaiwen0418/agent-benchmark](https://github.com/Kaiwen0418/agent-benchmark) | 101 | 工具使用 Agent 交互式评测平台 |
| 18 | [Hugging-Face-KREW/Ko-AgentBench](https://github.com/Hugging-Face-KREW/Ko-AgentBench) | 66 | 韩语 Agent 评测基准 |
| 19 | [eth-sri/agentbench](https://github.com/eth-sri/agentbench) | 60 | Agent 安全 / 评测相关研究实现 |
| 20 | [OWASP/www-project-agent-observability-standard](https://github.com/OWASP/www-project-agent-observability-standard) | 57 | Agent 可观测性标准（OWASP） |

---

## 9. 论文与调研索引

Survey、论文列表与代表性学术实现。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations) | 67203 | 60+ 深度学习论文旁注实现（含 Agent/RL 相关） |
| 2 | [WooooDyy/LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List) | 8166 | 《The Rise and Potential of LLM Agents》论文列表 |
| 3 | [zjunlp/LLMAgentPapers](https://github.com/zjunlp/LLMAgentPapers) | 3086 | LLM Agents 必读论文 |
| 4 | [Paitesanshi/LLM-Agent-Survey](https://github.com/Paitesanshi/LLM-Agent-Survey) | 2908 | LLM Agent Survey 资源 |
| 5 | [AGI-Edgerunners/LLM-Agents-Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers) | 2331 | LLM-based Agent 论文列表 |
| 6 | [hyp1231/awesome-llm-powered-agent](https://github.com/hyp1231/awesome-llm-powered-agent) | 2250 | LLM Agent：论文 / 仓库 / 博客 |
| 7 | [ysymyth/awesome-language-agents](https://github.com/ysymyth/awesome-language-agents) | 1246 | Cognitive Architectures for Language Agents |
| 8 | [google-deepmind/ai-safety-gridworlds](https://github.com/google-deepmind/ai-safety-gridworlds) | 636 | Agent 安全属性强化学习环境套件 |
| 9 | [xinzhel/LLM-Agent-Survey](https://github.com/xinzhel/LLM-Agent-Survey) | 514 | LLM Agents Survey（CoLing 2025） |
| 10 | [MobileLLM/Personal_LLM_Agents_Survey](https://github.com/MobileLLM/Personal_LLM_Agents_Survey) | 433 | Personal LLM Agents 论文列表 |
| 11 | [SunzeY/SEAgent](https://github.com/SunzeY/SEAgent) | 257 | ICML-2026：自演化 Computer Use Agent |
| 12 | [Xtra-Computing/CryptoTrade](https://github.com/Xtra-Computing/CryptoTrade) | 166 | EMNLP 2024：反思式交易 Agent |
| 13 | [WxxShirley/GNN4TaskPlan](https://github.com/WxxShirley/GNN4TaskPlan) | 154 | NeurIPS 2024：图学习改进 Agent 规划 |
| 14 | [langfengQ/DrMAS](https://github.com/langfengQ/DrMAS) | 143 | 多智能体 LLM RL 共训（论文框架） |
| 15 | [agiresearch/Formal-LLM](https://github.com/agiresearch/Formal-LLM) | 137 | Formal-LLM：可控 LLM Agent |
| 16 | [llm-platform-security/SecGPT](https://github.com/llm-platform-security/SecGPT) | 120 | LLM Agent 执行隔离架构 |
| 17 | [Wei-ZENG1020/Value-Alignment-Agentic-AI-Papers-Survey-Taxonomy](https://github.com/Wei-ZENG1020/Value-Alignment-Agentic-AI-Papers-Survey-Taxonomy) | 108 | Agentic AI 价值对齐调研 |
| 18 | [genglongling/SagaLLM](https://github.com/genglongling/SagaLLM) | 41 | 多智能体规划的上下文与事务保证 |
| 19 | [tmlr-group/ECON](https://github.com/tmlr-group/ECON) | 39 | ICML 2025：多智能体贝叶斯博弈推理 |
| 20 | [SAIFS-AIHub/Awesome-AI-Agents-Live](https://github.com/SAIFS-AIHub/Awesome-AI-Agents-Live) | 30 | 持续更新的 AI Agents 论文目录 |

---

## 10. 工程实践、可观测与 Awesome 社区

生产原则、可观测、社区 Awesome 与官方/社区精选合集。

| # | 项目 | Stars | 简介 |
|---:|------|------:|------|
| 1 | [f/prompts.chat](https://github.com/f/prompts.chat) | 166171 | Awesome ChatGPT Prompts 社区提示词 |
| 2 | [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | 125910 | 100+ AI Agents / Skills / RAG Apps |
| 3 | [lobehub/lobehub](https://github.com/lobehub/lobehub) | 80648 | Chief Agent Operator：编排 Agent 团队 |
| 4 | [langfuse/langfuse](https://github.com/langfuse/langfuse) | 31616 | 开源 LLM 可观测 / Eval / Prompt 管理 |
| 5 | [e2b-dev/awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) | 28998 | 自主 AI Agents 权威 Awesome 列表 |
| 6 | [Hannibal046/Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM) | 27177 | Awesome-LLM 精选列表 |
| 7 | [humanlayer/12-factor-agents](https://github.com/humanlayer/12-factor-agents) | 24624 | 生产级 LLM 软件的 12-Factor 原则 |
| 8 | [enescingoz/awesome-n8n-templates](https://github.com/enescingoz/awesome-n8n-templates) | 24051 | 280+ n8n AI Agent 自动化模板 |
| 9 | [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix) | 10664 | AI Observability & Evaluation |
| 10 | [traceloop/openllmetry](https://github.com/traceloop/openllmetry) | 7317 | 基于 OpenTelemetry 的 GenAI 可观测 |
| 11 | [jasontang-ai/Context-Engineering](https://github.com/jasontang-ai/Context-Engineering) | 9174 | Context Engineering 第一性原理手册 |
| 12 | [kyrolabs/awesome-agents](https://github.com/kyrolabs/awesome-agents) | 2646 | AI Agents Awesome 列表 |
| 13 | [slavakurilyak/awesome-ai-agents](https://github.com/slavakurilyak/awesome-ai-agents) | 1931 | 300+ Agentic AI 资源 |
| 14 | [jim-schwoebel/awesome_ai_agents](https://github.com/jim-schwoebel/awesome_ai_agents) | 1893 | 1500+ AI Agents 相关资源 |
| 15 | [disler/claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) | 1500 | Claude Code Hooks 多智能体可观测 |
| 16 | [caramaschiHG/awesome-ai-agents-2026](https://github.com/caramaschiHG/awesome-ai-agents-2026) | 1481 | 2026 Agents / Frameworks / Tools |
| 17 | [Jenqyang/Awesome-AI-Agents](https://github.com/Jenqyang/Awesome-AI-Agents) | 1189 | LLM 驱动自主 Agents 合集 |
| 18 | [AgenticHealthAI/Awesome-AI-Agents-for-Healthcare](https://github.com/AgenticHealthAI/Awesome-AI-Agents-for-Healthcare) | 1167 | 医疗 Agentic AI 进展 |
| 19 | [rohitg00/awesome-ai-apps](https://github.com/rohitg00/awesome-ai-apps) | 805 | 多技术栈 AI Agents / Apps 实战合集 |
| 20 | [Azure-Samples/python-ai-agent-frameworks-demos](https://github.com/Azure-Samples/python-ai-agent-frameworks-demos) | 335 | Azure / GitHub Models Agent 框架示例 |

---

## 推荐学习路径

```text
入门
  microsoft/ai-agents-for-beginners
  huggingface/agents-course
  datawhalechina/hello-agents
    ↓
框架动手
  openai/openai-agents-python 或 pydantic/pydantic-ai
  langchain-ai/langgraph
  huggingface/smolagents
    ↓
工具与生产
  modelcontextprotocol/servers
  mem0ai/mem0
  humanlayer/12-factor-agents
  NirDiamant/agents-towards-production
    ↓
专题深入
  编码 CLI：gemini-cli / hermes-agent / opencode / claude-code
  浏览器：browser-use / skyvern
  多智能体：MetaGPT / CrewAI / CAMEL
  论文：WooooDyy/LLM-Agent-Paper-List
```

---

## 贡献

欢迎 PR：

- 新增资源：归入合适分类，补充一句话简介，并尽量附带 stars 量级
- 纠错：失效链接、错误归类、过时描述
- 建议：新分类或学习路径改进

请保持「每个分类约 20 条、按 stars 优先」的索引风格，避免同质化堆砌。

---

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — 索引内容可自由使用。

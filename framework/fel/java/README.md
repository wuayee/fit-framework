FIT Expression for LLM (FEL) 项目旨在简化 AI 应用程序开发，避免不必要的复杂性。

该项目从 Python 领域的杰出项目如 LangChain 和 LlamaIndex 中汲取灵感，但 FEL 并非直接源自这些项目的移植版。该项目基于 FIT 插件化开发以及 WaterFlow 水流式流程引擎，使得下一代 AI 应用程序不仅仅局限于 Python 开发者，而是普遍存在于多种编程语言中。

FEL 提供了一系列抽象和标准原语，作为 AI 应用程序的基础组件，这些抽象具有多个插件实现，允许用户在零代码修改的情况下轻松替换组件。基于 AiFlow 的响应式开发语法，开发者就能够在流程中集成大模型、知识库、提示词等组件，快速构建 AI 应用，而不用关心复杂的流程调度。

FEL 提供以下特性：

- 支持主要的模型提供商：如 OpenAI、文心一言、千问等。
- 支持跨 AI 供应商的通用 API，屏蔽不同厂商之间的 API 差异，做到接口层面的统一调用。
- 支持 Hugging Face 的 34 个深度学习任务和上千个模型：包括文生图、图生图、音频转录、语音合成等。
- 支持工具调用：任意函数简单注册为工具，突破语言和物理机限制。
- 专为数据工程师设计的模块化 RAG 框架。
- 生态兼容：兼容 LangChain、LlamaIndex 中的工具以及知识库。
- 智能体：提供开箱即用的基于 OpenAI、React 的智能体，更多类型即将推出。
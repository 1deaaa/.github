# 1deaaa
大模型 Agent 应用开发工程师
实践AI全栈工程：两年 LLM / Agent 实践，独立交付 20+ 开源项目；覆盖模型后训练—推理—模型网关—上下文工程—Agent Harness—MCP / RAG —前后端交付，可独立打通 Model-Infra-Harness 全链路。

## 技术栈
AI Agent 全栈开发：LangChain / LangGraph 多 Agent 编排（记忆管理、Agent 委派协作、缓存优化）、MCP 开发、RAG（Agentic + Graph+Metadata RAG）、上下文工程、Prompt 工程。

前后端开发：Python（FastAPI / Django）、Java（Spring Boot 3 / MyBatis-Plus / Redis / Flyway / Sa-Token）、TypeScript（Vue3 / React / Next.js / Tauri）、数据库（PostgreSQL /PGVector / MySQL ）、C# / Unity

LLM后训练与推理：SFT（Unsloth / TRL / PEFT，INT8 LoRA）、合成数据审计与确定性评测；SGLang（RadixAttention、LoRA Serving、continuous batching）与 llama.cpp / GGUF 量化部署。

工程化与交付：Linux（Ubuntu / Debian）、Docker Compose、1Panel；GitHub / Gitea / GitLab CI。
个人概述# 代表项目

### SparkArc Studio · 多 Agent 自主创作平台
智能体集群驱动的创作 IDE：LangGraph 导演 Agent 自主拆解意图，分发给执笔、审稿、演出统筹等 6 类专家 Agent，实现无人值守管道与断点恢复。
- **多 Agent 编排**：导演-专家双层调度，任务分发 + 中断恢复 + 后台无人管道
- **上下文工程**：ARC 剧本文本格式较等效 JSON 省约三成 token（实测 37.4%）· 动态记忆池 + 判别工单 · Agentic + Graph RAG
- **成本优化**：缓存友好排布，DeepSeek V4 实测第二轮命中约 95%
- **交付形态**：公网 SaaS + 本地部署双形态，四语国际化；Tauri 桌面端 + Android

- [代码](https://github.com/1deaaa/spark-arc-studio) · [在线体验](https://arc.1dea.top)

### LUI-for-All · 零侵入 Agentic 自然语言接口
给任何传统后端加自然语言操作层：MCP 接入、源码只读、写操作隔离、5 级安全分级 + 人工审批。
- [代码](https://github.com/1deaaa/lui-for-all) · [在线体验](https://lui.1dea.top)
### Occuspec · 职业健康检查辅助判定系统

Agentic Metadata RAG，结论可溯源至 GBZT 条款原文；自编排 agent flow 和 RAG。
- Spring Boot 3.5 / Java 21 / MyBatis-Plus / Redis / PGVector；分布式锁降级、限流 / 幂等 / 审计切面

### Delta-Scope-MCP · 前端逐帧调试 MCP
让纯文本模型看懂前端动画与 DOM 动态：page_map + timeline + focus。
- [代码](https://github.com/1deaaa/delta-scope-mcp) · `npx delta-scope@latest`

## 联系

[博客 1dea.top](https://1dea.top) · 邮箱：aideaaa@outlook.com

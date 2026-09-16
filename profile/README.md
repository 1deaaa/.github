# 1deaaa
大模型 Agent 应用开发工程师
两年 LLM / Agent 全栈工程实践：多 Agent 编排、MCP 协议、RAG、模型后训练与量化部署、全链路交付。擅长把模糊需求拆成可落地系统，并单人保持团队级交付节奏。

## 技术栈

- **语言**：Python（FastAPI / Django）· TypeScript（Vue3 / Tauri）· Java（Spring Boot / MyBatis-Plus）· C#
- **Agent / LLM**：LangChain / LangGraph 多 Agent 编排 · MCP 协议开发（server / 网关 / 聚合代理）· RAG（Agentic + Graph）· Context Engineering · Prompt 工程
- **模型层**：SFT（Unsloth / TRL / PEFT，INT8 LoRA）· 合成数据生产与审计 · 确定性评测框架 · llama.cpp / GGUF 量化部署
- **工程化**：Docker · CI/CD（GitHub Actions / Gitea / GitLab）· Linux · 全栈交付

## 个人能力
- **技术负责人经验**：带 6~8 人团队交付 3 个全栈产品（教学智能体 / 文旅平台 / 外包商城）
- **AI 协作范式**：主导 AI 协作规范在多人团队落地；本人以架构+AI 辅助单人维持团队级交付节奏
- **开源社区运营**：SparkArc 维护 80 人反馈社群，处理 issue 与用户反馈闭环
- **跨栈迁移能力**：Python 主栈 + Java/TypeScript 双栈交付，能用任意栈把同一系统重做一遍（Occuspec 即 Python RAG 的 Java 重写）

## 代表项目
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
- 
### Occuspec · 职业健康检查辅助判定系统
Agentic Metadata RAG，结论可溯源至 GBZT 条款原文；自编排 agent flow 和 RAG。
- Spring Boot 3.5 / Java 21 / MyBatis-Plus / Redis / PGVector；分布式锁降级、限流 / 幂等 / 审计切面

### Delta-Scope-MCP · 前端逐帧调试 MCP
让纯文本模型看懂前端动画与 DOM 动态：page_map + timeline + focus。
- [代码](https://github.com/1deaaa/delta-scope-mcp) · `npx delta-scope@latest`

## 联系

[博客 1dea.top](https://1dea.top) · [Email](mailto:aideaaa@outlook.com) 

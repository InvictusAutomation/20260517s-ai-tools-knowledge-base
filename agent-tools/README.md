# 🤖 Agent 技术与工具

> 追踪 AI Agent、多 Agent 协作框架和最佳实践

---

## 目录

1. [Agent 框架对比](./frameworks/)
2. [多 Agent 协作](./multi-agent/)
3. [Agent 技能](./skills/)
4. [调研能力](./research-capability/)

---

## Agent 核心能力评估

### 1. 调研能力 (最重要)

| 能力 | 说明 | 评估标准 |
|------|------|----------|
| **实时信息** | 搜索最新信息 | 工具: Perplexity, Kimi, web search |
| **最佳实践** | 代码细节、高质量教程 | 搜索质量 |
| **学术搜索** | 论文、期刊 | arXiv, NeurIPS, ICML |
| **闭源信息** | 产品文档、API | 来源可信度 |

### 2. 自主执行

| 能力 | 说明 |
|------|------|
| **任务规划** | 拆解复杂任务 |
| **代码执行** | 运行、调试 |
| **工具使用** | API、CLI 调用 |
| **学习积累** | Context Hub |

### 3. 多 Agent 协作

| 模式 | 说明 |
|------|------|
| **导演模式** | 一个 Agent 协调多个 |
| **流水线** | 串行处理不同任务 |
| **辩论模式** | Agent 之间的讨论 |
| **角色扮演** | 不同专家协作 |

---

## 当前最佳 Agent 实践

### 调研工作流

```
1. Perplexity / Kimi → 搜索信息
2. 筛选可信来源
3. 深度阅读最佳实践
4. 总结并应用到代码
```

### 多 Agent 协作

```
Leader (capi) → 任务拆解
  ├─→ Researcher (nova) → 信息收集
  ├─→ Coder (bolt) → 代码生成
  ├─→ Analyst (iris) → 数据分析
  └─→ Writer (echo) → 文档撰写
```

---

## Agent 工具对比

| 工具 | 特点 | 适用场景 |
|------|------|----------|
| **OpenClaw** | 多通道集成 | 复杂任务自动化 |
| **Claude Code** | 深度理解 | 复杂代码项目 |
| **Cursor** | AI-first IDE | 日常编程 |
| **Windsurf** | Flow State | 持续开发 |
| **Bolt.new** | 全栈生成 | 快速原型 |
| **Context Hub** | 知识管理 | 学习积累 |
| **InsForge** | 开源后端平台 | 全栈应用开发 |
| **jcode** | Rust 编码 Agent | 高性能项目 |
| **iFlyAgent** | 字节跳动 Agent | 电商/生产场景 |

---

## 2026 年 06 月新出现工具 (GitHub Trending)

### Agent 性能优化

| 工具 | 描述 | 特点 |
|------|------|------|
| **harness** | Agent 性能优化系统 | Skills, instincts, memory, security |
| **headroom** | Token 压缩工具 | 60-95% 更少 token |
| **oh-my-pi** | 终端 AI 编码 Agent | hash-anchored edits |

### 记忆与知识

| 工具 | 描述 | 特点 |
|------|------|------|
| **supermemory** | 超快记忆引擎 | Memory API for AI |
| **fff** | 文件搜索工具 | 最快最准的 AI 文件搜索 |

### 浏览器与自动化

| 工具 | 描述 | 特点 |
|------|------|------|
| **Agent-Reach** | 互联网视觉 Agent | 读取 Twitter, Reddit, YouTube 等 |
| **CloakBrowser** | 反检测 Chromium | 30/30 测试通过 |

### 技能库

| 工具 | 描述 | 来源 |
|------|------|------|
| **last30days-skill** | 30天内研究技能 | Reddit, X, YouTube, HN |
| **taste-skill** | AI 品味提升 | 避免生成无聊内容 |
| **compound-engineering-plugin** | 复合工程插件 | Claude Code / Codex / Cursor |

### 视频与语音

| 工具 | 描述 | 特点 |
|------|------|------|
| **Open-LLM-VTuber** | 开源 VTuber | 免手语音交互 + Live2D |
| **MoneyPrinterTurbo** | 短视频生成 | 一键生成高清视频 |

### Agent 编排

| 工具 | 描述 | 特点 |
|------|------|------|
| **hermes-agent** | 成长型 Agent | NousResearch |
| **revfactory/harness** | 元技能设计 | 定义专业 Agent 团队 |

---

## 2026 年 05 月新出现工具

### Agent 编排框架

| 工具 | 描述 | GitHub 星标 |
|------|------|-------------|
| **ruflo** | 多 Agent 编排平台，支持 Claude Code/Codex | 新兴项目 |
| **TradingAgents** | 多 Agent 金融交易框架 | 新兴项目 |
| **local-deep-research** | 本地深度研究 (~95% SimpleQA) | 新兴项目 |
| **hermes-agent** | 可成长的 Agent 框架 | NousResearch |

### 编码 Agent

| 工具 | 描述 | 特点 |
|------|------|------|
| **jcode** | Rust 编码 Agent | 2,710 stars/week |
| **DeepSeek-TUI** | 终端 DeepSeek 客户端 | 终端应用 |
| **InsForge** | 开源后端平台 | 数据库/Auth/存储/计算 |
| **free-claude-code** | 免费 Claude Code 终端 | 开源替代 |

### 技能库 (重点更新)

| 工具 | 描述 | 来源 |
|------|------|------|
| **addyosmani/agent-skills** | 生产级工程技能 | Google Chrome 团队 |
| **mattpocock/skills** | 工程技能集合 | 独立开发者 |
| **ComposioHQ/awesome-codex-skills** | Codex 技能集 | 官方 |
| **zilliztech/claude-context** | 代码搜索 MCP | Milvus |
| **maigret** | 用户名 OSINT 工具 | 3000+ 站点 |

### 浏览器自动化

| 工具 | 描述 | 特点 |
|------|------|------|
| **CloakBrowser** | 反检测 Chromium | 30/30 测试通过 |
| **hyperframes** | HeyGen 视频生成框架 | Agent 专用 |

### 视频/媒体

| 工具 | 描述 | 特点 |
|------|------|------|
| **Pixelle-Video** | AI 全自动短视频引擎 | 全自动化 |
| **Open-Generative-AI** | 开源图像视频生成 | 200+ 模型 |

## 2026 年 05 月新兴工具 (Trending)

| 工具 | 描述 | 特点 |
|------|------|------|
| **codegraph** | Claude Code/Codex/Cursor 预索引代码知识图谱 | 减少 token 和工具调用，100%本地 |
| **CloakBrowser** | 反检测 Chromium (30/30 测试通过) | Playwright 替代品 |
| **agentmemory** | 编码 Agent 持久化内存 | 基于真实世界基准测试 |
| **awesome-codex-skills** | Codex 技能精选列表 | ComposioHQ 出品 |
| **sandcastle** | TypeScript 沙箱编码 Agent 编排 | mattpocock 出品 |
| **ViMax** | Agentic 视频生成 (导演+编剧+制片+生成) | HKUDS 出品 |
| **codex-free-router** | 连接多个免费 AI 提供商 | 40+ 提供商自动 fallback |

---

## 持续更新

- 最后更新: 2026-06-08
- 更新频率: 每周
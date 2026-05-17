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

---

## 持续更新

- 最后更新: 2026-05-18
- 更新频率: 每周
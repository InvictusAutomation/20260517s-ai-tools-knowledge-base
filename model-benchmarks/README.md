# 📊 模型评测多维度对比

> 持续追踪市面主流模型的评测结果 | 前十名多维度对比

---

## 目录

1. [大模型综合榜](./llm-leaderboard.md)
2. [小模型专精榜](./small-model-leaderboard.md)
3. [代码能力榜](./code-capability.md)
4. [推理能力榜](./reasoning-capability.md)
5. [学术论文榜](./academic-papers.md)

---

## 综合评测维度

| 维度 | 主要评测标准 |
|------|--------------|
| **代码能力** | LeetCode, HumanEval, MBPP |
| **推理能力** | 数学、逻辑、 ARC |
| **知识广度** | MMLU, BigBench |
| **长上下文** |大海捞针、VMPR |
| **中文能力** | CMMLU, C-Eval |
| **工具使用** | API 调用、函数执行 |
| **Agent 能力** | 任务规划、自主执行 |

---

## 小模型专精榜 (重点关注)

### 评选标准

- **参数**: < 30B
- **专精领域**: 代码/数学/推理/特定任务
- **性价比**: 能力/资源消耗

### 2026 年 05 月推荐小模型

| 模型 | 参数 | 专精领域 | 评分 | 备注 |
|------|------|----------|------|------|
| Qwen2.5-Coder | 32B | 代码生成 | ⭐⭐⭐⭐ | 开源最强代码模型 |
| Qwen3.6-27B | 28B | 通用 | ⭐⭐⭐⭐⭐ | 综合最强开源 |
| DeepSeek-V4-Flash | 158B | 高效推理 | ⭐⭐⭐⭐ | 性价比高 |
| gemma-4-26B-A4B | 26B | 指令跟随 | ⭐⭐⭐⭐ | Google 小型 |
| Nemotron-3-Nano-Omni | 30B | 多模态 | ⭐⭐⭐⭐ | NVIDIA |

---

## 更新记录

| 日期 | 更新内容 |
|------|----------|
| 2025-03-31 | 初始版本 |
| 2026-05-11 | 更新 Hugging Face trending 模型、排行榜信息 |
| 2026-05-18 | 补充 GitHub trending 新工具 |

---

## 2026 年 05 月重要更新

### 模型动态

> 基于 GitHub Trending 和 Hugging Face 观测

#### DeepSeek-V4 系列
- **DeepSeek-V4-Pro**: 862B 参数，多模态旗舰
- **DeepSeek-V4-Flash**: 158B 参数，高效版本

#### Qwen3.6 系列 (阿里)
- **Qwen3.6-27B**: 最热门开源模型 (2.27M 下载)
- **Qwen3.6-35B-A3B**: MoE 架构 (3.67M 下载)

#### Google Gemma 4
- **gemma-4-31B-it**: 31B Google 助手
- **gemma-4-26B-A4B**: 26B + A3B 蒸馏

#### 其他亮点
- **SulphurAI/Sulphur-2-base**: 视频生成新秀 (144k 下载)
- **MiMo-V2.5-Pro**: 小米万亿参数 (40.1k 下载)
- **Mistral-Medium-3.5-128B**: Mistral 中型 (40.6k 下载)

### 代码能力模型

| 模型 | 参数量 | 专精领域 | 备注 |
|------|--------|----------|------|
| Qwen2.5-Coder | 32B | 代码生成 | 开源最强 |
| DeepSeek-Coder | 33B | 代码+推理 | 推理能力强 |
| CodeLlama | 34B | 代码 | Meta 出品 |
| Phi-3 | 14B | 微软优化 | 小巧高效 |

### 新兴工具/框架

#### AI 编码工具
| 工具 | 描述 | 特点 |
|------|------|------|
| **jcode** | Rust 编码 Agent | 高性能 |
| **free-claude-code** | 免费 Claude Code | 开源替代 |
| **decolua/9router** | 多平台路由器 | 40+ 提供商 |

#### Agent 编排
| 工具 | 描述 | 特点 |
|------|------|------|
| **ruflo** | 多 Agent 编排 | Claude 集成 |
| **hermes-agent** | 成长型 Agent | NousResearch |
| **TradingAgents** | 金融交易框架 | 多 Agent |

#### 浏览器/自动化
| 工具 | 描述 | 特点 |
|------|------|------|
| **CloakBrowser** | 反检测 Chromium | 30/30 通过 |
| **maigret** | OSINT 工具 | 3000+ 站点 |

---

## 数据来源

- [GitHub Trending](https://github.com/trending)
- [Hugging Face](https://huggingface.co/)
- [ArXiv](https://arxiv.org/)

---

> ⚠️ 注意: 排行榜权重不同，对比时请关注同一评测标准。持续更新中...
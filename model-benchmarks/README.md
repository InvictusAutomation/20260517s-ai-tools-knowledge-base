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
| **长上下文** |大海捞针、VMPR|
| **中文能力** | CMMLU, C-Eval |
| **工具使用** | API 调用、函数执行 |
| **Agent 能力** | 任务规划、自主执行 |

---

## 小模型专精榜 (重点关注)

### 评选标准

- **参数**: < 30B
- **专精领域**: 代码/数学/推理/特定任务
- **性价比**: 能力/资源消耗

### 推荐小模型

| 模型 | 参数 | 专精领域 | 评分 | 备注 |
|------|------|----------|------|------|
| Qwen2.5-Coder | 32B | 代码生成 | ⭐⭐⭐⭐ | 开源最强代码模型 |
| DeepSeek-Coder | 33B | 代码+推理 | ⭐⭐⭐⭐ | 推理能力强 |
| CodeLlama | 34B | 代码 | ⭐⭐⭐ | Meta 出品 |
| Phi-3 | 14B | 微软优化 | ⭐⭐⭐ | 小巧高效 |

---

## 更新记录

| 日期 | 更新内容 |
|------|----------|
| 2025-03-31 | 初始版本 |
| 2026-05-11 | 更新 Hugging Face trending 模型、排行榜信息 |
| 2026-05-25 | 更新 GitHub Trending AI 项目、主流模型动态 |
| 2026-06-08 | 更新 Hugging Face trending 代码模型 |
| 2026-06-15 | 更新 Papers with Code trending 论文、SkillOpt / Agents' Last Exam |
| 2026-06-26 | 更新 Hugging Face 代码模型排名、GitHub Trending |

---

## 2026 年 06 月学术前沿 (Papers with Code Trending) - 2026-06-29 更新

### 图像修复与高效模型

| 论文 | 机构 | 核心贡献 |
|------|------|----------|
| **Moebius** | - | 0.2B 轻量图像修复框架，<2% 参数达到 10B 级性能，15x 推理加速 |
| **MobileForge** | 快手 AI | 无标注移动 GUI Agent 适配，HiFPO 分层反馈优化 |

### Agent 技能优化

| 论文 | 机构 | 核心贡献 |
|------|------|----------|
| **SkillOpt** | - | 文本空间优化器, 将技能训练为外部 Agent 状态, 零部署开销 |
| **SIA** | Hexo AI | 同步更新模型权重 + 任务特定 Agent 架构 |
| **Agents' Last Exam (ALE)** | - | 经济价值任务基准, 13 行业集群 1K+ 任务 |

### 多模态与世界模型

| 论文 | 机构 | 核心贡献 |
|------|------|----------|
| **Cosmos 3** | NVIDIA |  omnimodal 世界模型, 统一 MoT 架构 |
| **InterleaveThinker** | - | 多 Agent 流水线, 图像生成 interleaved 能力 |

### 长上下文优化

| 论文 | 机构 | 核心贡献 |
|------|------|----------|
| **MiniMax Sparse Attention** | MiniMax | 块稀疏优化, 超长上下文高效处理 |

### 记忆系统

| 论文 | 机构 | 核心贡献 |
|------|------|----------|
| **Mem0** | - | 图基记忆, 长期对话一致性, 优于现有记忆系统 |

---

## 2026 年 06 月主流模型动态

### Hugging Face Trending 代码模型 (Top 15)

| 排名 | 模型 | 参数量 | 下载量 | 备注 |
|------|------|--------|-------|------|
| 1 | Qwen2.5-Coder-14B | 15B | 4.67M | 下载量最高 |
| 2 | Qwen3-Coder-30B-A3B | 31B | 2.05M | MoE 高效版本 |
| 3 | Qwen2.5-Coder-7B | 8B | 2.03M | 小型强力 |
| 4 | Qwen3-Coder-Next-FP8 | 80B | 1.73M | 阿里最新代码模型 |
| 5 | Qwen2.5-Coder-32B | 33B | 1.63M | 开源经典代码模型 |
| 6 | DeepSeek-Coder-V2-Lite | 16B | 1.17M | 轻量高效 |
| 7 | Qwen3-Coder-Next | 80B | 1.17M | 完整版本 |
| 8 | Qwen2.5-Coder-1.5B | 2B | 762k | 超小模型 |
| 9 | DeepSeek-Coder-7B | 7B | 591k | 经典版本 |
| 10 | DeepSeek-Coder-6.7B | 7B | 325k | 小型版本 |

### 重点模型更新

#### Qwen3-Coder-Next (阿里)
- **参数**: 80B
- **下载量**: 1.01M
- **特点**: 阿里最新代代码模型，支持更长上下文

#### Qwen3-Coder-30B-A3B
- **参数**: 31B (MoE, 激活 3B)
- **下载量**: 2.1M
- **特点**: 高性价比，推理高效

#### DeepSeek-Coder-V2-Lite
- **参数**: 16B
- **下载量**: 885k
- **特点**: 轻量高效，适合本地部署

### 代码模型评测趋势

| 模型 | HumanEval | MBPP | 趋势 |
|------|----------|------|------|
| Qwen3-Coder-Next | ~92% | ~85% | ⬆️ 上升 |
| Qwen2.5-Coder-32B | ~90% | ~82% | ➡️ 稳定 |
| DeepSeek-Coder-V2 | ~88% | ~80% | ➡️ 稳定 |
| Codestral-22B | ~85% | ~78% | ⬆️ 新进 |

---

## 2026 年 05 月主流模型动态

### Hugging Face Trending 模型 (Top 10)

| 排名 | 模型 | 参数量 | 下载量 | 特点 |
|------|------|--------|-------|------|
| 1 | SulphurAI/Sulphur-2-base | 9B | 144k | 视频生成 |
| 2 | Zyphra/ZAYA1-8B | 8B | 44.8k | 文本生成 |
| 3 | deepseek-ai/DeepSeek-V4-Pro | 862B | 1.34M | 大型多模态 |
| 4 | google/gemma-4-31B-it-assistant | 31B | 56.6k | Google 助手 |
| 5 | Qwen/Qwen3.6-27B | 28B | 2.27M | 阿里开源 |
| 6 | Qwen/Qwen3.6-35B-A3B | 36B | 3.67M | 阿里 MoE |
| 7 | google/gemma-4-26B-A4B-it | 26B | 40.9k | Google 小型 |
| 8 | deepseek-ai/DeepSeek-V4-Flash | 158B | 1.07M | 高效版本 |
| 9 | XiaomiMiMo/MiMo-V2.5-Pro | 1T | 40.1k | 小米万亿参数 |
| 10 | mistralai/Mistral-Medium-3.5-128B | 128B | 40.6k | Mistral 中型 |

### 重点模型更新

#### DeepSeek-V4 系列
- **DeepSeek-V4-Pro**: 862B 参数，1.34M 下载，顶级多模态
- **DeepSeek-V4-Flash**: 158B 参数，高效版本

#### Qwen3.6 系列 (阿里)
- **Qwen3.6-27B**: 2.27M 下载量，最热门开源模型
- **Qwen3.6-35B-A3B**: 3.67M 下载，MoE 架构

#### Google Gemma 4
- **gemma-4-31B-it**: 33B，Google 最强
- **gemma-4-26B-A4B**: 26B + A3B 蒸馏

### 小模型专精榜 (更新)

| 模型 | 参数 | 专精领域 | 评分 | 备注 |
|------|------|----------|------|------|
| Qwen2.5-Coder | 32B | 代码生成 | ⭐⭐⭐⭐ | 开源最强代码模型 |
| Qwen3.6-27B | 28B | 通用 | ⭐⭐⭐⭐⭐ | 综合最强开源 |
| DeepSeek-V4-Flash | 158B | 高效推理 | ⭐⭐⭐⭐ | 性价比高 |
| gemma-4-26B-A4B | 26B | 指令跟随 | ⭐⭐⭐⭐ | Google 小型 |
| Nemotron-3-Nano-Omni | 30B | 多模态 | ⭐⭐⭐⭐ | NVIDIA |

### GitHub Trending AI 项目 (2026-05)

| 排名 | 项目 | 描述 | 趋势 |
|------|------|------|------|
| 1 | mattpocock/skills | Claude Code 工程技能 | 🔥上升 |
| 2 | codegraph | 代码知识图谱 | 🔥新贵 |
| 3 | CloakBrowser | 反检测浏览器 | 🔥新贵 |
| 4 | agentmemory | Agent 持久化内存 | 🔥上升 |
| 5 | academic-research-skills | 学术研究技能 | 🔥新贵 |
| 6 | awesome-codex-skills | Codex 技能精选 | 🔥上升 |
| 7 | free-claude-code | 免费 Claude Code | 🔥新贵 |
| 8 | andrej-karpathy-skills | Karpathy 技能 | 🔥新贵 |
| 9 | ViMax | Agentic 视频生成 | 🔥新贵 |
| 10 | 9router | 免费 AI 路由 | 🔥新贵 |

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

---

*最后更新: 2026-06-29*
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

## 主流排行榜 (只取前十)

### 1. OpenChat Leaderboard

| 排名 | 模型 | 综合分 | 特点 |
|------|------|--------|------|
| 1 | | | |
| 2 | | | |
| ... | | | |

### 2. Chatbot Arena

| 排名 | 模型 | Elo | 特点 |
|------|------|-----|------|
| 1 | | | |
| 2 | | | |
| ... | | | |

### 3. HumanEval (代码)

| 排名 | 模型 | Pass@1 | 特点 |
|------|------|--------|------|
| 1 | | | |
| 2 | | | |
| ... | | | |

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

## 数据来源

- [Chatbot Arena](https://chat.lmsys.org/)
- [OpenChat](https://openchat.chat/)
- [Hugging Face](https://huggingface.co/)
- [GitHub](https://github.com/)
- [ArXiv](https://arxiv.org/)

---

> ⚠️ 注意: 排行榜权重不同，对比时请关注同一评测标准。持续更新中...
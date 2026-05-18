# Web Access Skill

> URL: https://github.com/eze-is/web-access
> 来源: 微信公众号 - Agent能力解锁
> 添加日期: 2025-04-01
> 分类: 工具/Skill

## Skill 简介

通用 Agent 联网方案，让 Agent 具备浏览器控制能力。

## 核心功能

| 功能 | 说明 |
|------|------|
| 多平台并发操作 | 同时操作小红书、微博、B站、Boss等10+平台 |
| 自动登录 | 保存会话，无需重复登录 |
| 自动发布 | 填文案、传图片、自动发布 |
| 预约处理 | 如美签预约系统可直接完成预约 |
| 自动过验证码 | 遇到人机验证可自动处理 |
| 经验沉淀 | 自动积累各站点操作经验，越用越顺 |

## Skill 架构

```
Skill = Agent 策略哲学 + 最小完备工具集 + 必要的事实说明
```

## 核心机制

### 1. 经验沉淀机制
Agent 每次操作完一个站点，自动把访问策略沉淀下来：
- 平台特征
- 有效的 URL 模式
- 已知的陷阱

按域名存储，下次访问直接复用。

### 2. Learning Loop
- 有经验 vs 无经验：效率差异显著
- 标记发现日期，当作"可能有效的提示"
- 操作失败自动回退通用模式并更新经验

### 3. Sub Agent 锚定
针对不同平台设计不同的 Sub Agent：
- 小红书 Agent
- 微博 Agent
- B站 Agent
- Boss 直聘 Agent
- GitHub Agent
- 知乎 Agent
- 即刻 Agent
- 豆瓣 Agent
- 36kr Agent
- 虎嗅 Agent

## 支持的 Agent

- Claude Code
- OpenClaw

## 安装地址

https://github.com/eze-is/web-access

## 相关概念

- CDP: Chrome DevTools Protocol，浏览器控制协议
- MCP: Model Context Protocol
- Playwright: 浏览器自动化工具

## 推荐用法

```
开10个 sub agent，分别调研小红书、微博、B站、Boss直聘、github、知乎、即刻、豆瓣、36kr、虎嗅的首页，每个sub agent分别开10个tab，并行调研
```

## 设计哲学

Skill 设计要点：
1. 渐进式披露：没用到的经验不占上下文
2. 最小完备工具集：只提供必要的工具
3. 必要的事实说明：补充关键背景知识，打破模型惯性

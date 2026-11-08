# 🚀 FDE 学习路线图

> 从 **AI 产品 × 内容增长 + Vibe Coding** 到 **Forward Deployed Engineer（前沿部署工程师）** 的转型路线图
> 参考成长标杆：[阿酥 / LofiSu](https://github.com/LofiSu)（字节跳动 DeerFlow 核心维护者）

[![状态](https://img.shields.io/badge/状态-进行中-0E5C50?style=for-the-badge)](https://github.com/1191091728-bot/fde-learning-roadmap)
[![目标](https://img.shields.io/badge/目标-FDE%20实习%20→%20全职-B89254?style=for-the-badge)](https://github.com/1191091728-bot/fde-learning-roadmap)
[![起点](https://img.shields.io/badge/起点-%E5%86%85%E5%AE%B9%E5%A2%9E%E9%95%BF%20%2B%20Vibe%20Coding-E4EEEB?style=for-the-badge)](https://github.com/1191091728-bot)

## 🎯 这是什么

这是一份**公开的个人转型路线图**——把"从 AI 产品实践转 FDE"这件事拆成可以打卡的阶段、任务和交付物。开源它有两个目的：

1. **督促自己**：进度公开，没有借口拖延
2. **给求职加分**：FDE 岗位看重"用 AI 解决问题的证据"，这份仓库本身就是证据

## 💡 为什么选 FDE

FDE（Forward Deployed Engineer）是当前 AI 圈最火的岗位：招聘需求一年暴涨 42 倍，年薪可达百万。

它的工作本质是：**带着 AI 去客户现场，把"场景问题"变成"可用的 AI 解决方案"**。

| FDE 要求 | 我的现状 | 差距 |
|---------|---------|------|
| 理解客户场景与需求 | ✅ Health Timeline 产品负责人 · 用户调研 + MVP 落地 | 无 |
| 用户研究方法 | ✅ 24 问卷 + 8 访谈 · 盲评 9.2/10 | 无 |
| Vibe Coding 快速造物 | ✅ 3 个独立 Demo（最短 4 小时） | 无 |
| Python 编程基础 | ⚠️ 会一点 / 靠 AI 写 | **需系统补** |
| Agent 工程化与部署 | ⚠️ 懂概念，没实操 | **需动手练** |
| 开源贡献记录 | ❌ 无 | **需开始攒** |

## 🗺️ 阶段规划（6 个月）

### Phase 0 · 基础盘点（第 1 周）
- [ ] 明确目标：FDE 实习 → 全职
- [ ] 盘点技术现状：Python / Git / API 调用
- [ ] 读完本路线图，标注自己的起点

### Phase 1 · Python 与 LLM 基础（第 1 个月）
- [ ] Python 够用版：变量 / 函数 / 列表字典 / 文件读写 / 异常
- [ ] 会用 `requests` 调 API（OpenAI / DeepSeek / Kimi 任一）
- [ ] 读 [LLM-NoteBook](https://github.com/LofiSu/LLM-NoteBook) 第三章：RAG、Agent、工作流
- [ ] 交付物：写一个"调用 LLM 的脚本"并开源（小也算）

### Phase 2 · Agent 实战（第 2 个月）
- [ ] 跟做 [Agent_Kimi_ClaudeCode](https://github.com/LofiSu/Agent_Kimi_ClaudeCode)：手把手搭 Deep Research Agent
- [ ] 改造为**自己的** Agent：把"医药可信查询"做成 Agent（三智能体简化版）
- [ ] 交付物：`medical-agent` 仓库（能跑的代码，不是 PRD）

### Phase 3 · 工程化部署（第 3 个月）
- [ ] 读 [deer-flow](https://github.com/bytedance/deer-flow) 架构：sub-agent / memory / sandbox / tools / skills
- [ ] 学 FastAPI + SQLite：把 Demo 升级成带后端、可部署的应用
- [ ] 交付物：`health-timeline-app`（已从本路线图起步）
- [ ] 学 Docker 基础：把应用容器化

### Phase 4 · 开源贡献（持续）
- [ ] 每周 1 次小贡献：typo / 文档 / 坏链接 / 示例代码
- [ ] 参考 [ASu-skills /contributor](https://github.com/Hisn00w/ASu-skills)：先展示 diff，确认后提 PR
- [ ] 目标：3 个月内攒 5+ 个被合并的 PR
- [ ] 复盘：把贡献写成"协作闭环"叙事，进简历

### Phase 5 · 求职（第 4-6 个月）
- [ ] 把学习过程整理成 3 个"可讲 10 分钟"的故事
- [ ] 投递 FDE 实习（字节 / 大模型公司），复用阿酥的实习路径
- [ ] 面试准备：Agent 架构 + 场景题 + 手写小项目

## 📦 配套仓库（都在我的 GitHub）

| 仓库 | 角色 |
|------|------|
| [fde-learning-roadmap](https://github.com/1191091728-bot/fde-learning-roadmap) | 本路线图（学习打卡） |
| [medical-multi-agent](https://github.com/1191091728-bot/medical-multi-agent) | 医药多智能体 PRD（Phase 2 代码化的基础） |
| [health-timeline-app](https://github.com/1191091728-bot/health-timeline-app) | Python 后端真应用（Phase 3 交付物） |
| [health-timeline](https://github.com/1191091728-bot/health-timeline) | 原版 Demo（Vibe Coding 起点） |
| [yangzhini](https://github.com/1191091728-bot/yangzhini) | 原版 Demo（Vibe Coding 起点） |
| [pharma-chain](https://github.com/1191091728-bot/pharma-chain) | 药链通国创赛（叙事素材） |

## 📚 学习资源

| 资源 | 用途 |
|------|------|
| [LofiSu/LLM-NoteBook](https://github.com/LofiSu/LLM-NoteBook) | 大模型系统笔记（含面试题） |
| [LofiSu/Agent_Kimi_ClaudeCode](https://github.com/LofiSu/Agent_Kimi_ClaudeCode) | Agent 手把手实战 |
| [LofiSu/llm-space](https://github.com/LofiSu/llm-space) | prompt/agent 开发工作台 |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | SuperAgent 架构参考 |
| [Hisn00w/ASu-skills](https://github.com/Hisn00w/ASu-skills) | 求职工作流（含开源贡献入口） |

## 📅 每周节奏模板

```
周一：学 Python / 读 LLM 笔记 1 小时
周三：动手写代码 2 小时（阶段交付物）
周五：开源贡献 1 小时（找 typo / 文档）
周末：复盘 + 更新本路线图打卡
```

## 🏁 完成标准

- [ ] 5 个阶段全部完成
- [ ] 3 个"能跑的"项目仓库（非 PRD）
- [ ] 5+ 个被合并的开源 PR
- [ ] 拿到 FDE 实习 offer

---
*© 2026 嘿哈土豆 · 徐玉欣 · 从 AI 产品到 FDE 的路上*

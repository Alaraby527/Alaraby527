# Alaraby

AI 产品经理 | 27 届秋招候选人

专注于把大模型能力落到**可评测、可追溯、有人机兜底**的真实业务流程中。作品覆盖真实实习项目重做、个人研究、比赛项目和 MVP，重点展示需求判断、Agent 工作流、评测迭代与风险兜底。

---

## 👀 建议先看

1. [huohuahub-ai-creator-platform](https://github.com/Alaraby527/huohuahub-ai-creator-platform)：真实实习业务闭环
2. [tv-buying-copilot](https://github.com/Alaraby527/tv-buying-copilot)：Agent 架构与评测迭代
3. [invoice-risk-review-agent](https://github.com/Alaraby527/invoice-risk-review-agent)：高风险场景与人工兜底

## 🎯 精选 AI 项目（按作品集优先级）

### 1. [tv-buying-copilot](https://github.com/Alaraby527/tv-buying-copilot) — 智能电视选购 Copilot

**个人研究项目**。纯 Python 自研 Multi-Agent 电视选购系统（零第三方依赖），Master Router + 5 Worker + Replanner + Compliance 四层架构，内置 MCP 工具服务（商品知识库/促销计算/履约查询），短期会话槽位 + 长期用户记忆，25 条评测驱动迭代，通过率 V1.0 72% → V1.1 92%，幻觉从 4 次降到 0 次。

> 🟢 [在线 Demo](https://alaraby527.github.io/tv-buying-copilot/)

`Python` `Multi-Agent` `MCP` `Memory` `RAG` `Reflection` `零依赖`

### 2. [invoice-risk-review-agent](https://github.com/Alaraby527/invoice-risk-review-agent) — 企业报销票据风险审核 Agent

**个人研究项目**。可评测、可追溯、有人机兜底的高风险财务工作流。二维码/OCR/视觉模型三路线降级提取，确定性规则查重（批次重复/历史重复/近似异常），未接入税务验真前**自动放行率固定 0%**，所有结论附规则和证据交人工复核。

`Python` `Workflow` `Human-in-the-Loop` `OCR` `高风险场景`

### 3. [huohuahub-ai-creator-platform](https://github.com/Alaraby527/huohuahub-ai-creator-platform) — 火花工坊 HUB AI 创作者社区运营平台

**真实实习项目**。24 份用户问卷+访谈推翻四个初始假设，完成平台重设计。用 Dify 落地 4 个应用 + 1 个知识库，8 节点主控 Workflow 串联「数据→周画像→话术→写回飞书」全链路，周复盘从 2 小时压缩到 3 分钟。RAG 问答机器人从 5/15 优化到 15/15（**不是换模型，而是改分块策略**）。

> 子项目：[intern-daily-workstation](https://github.com/Alaraby527/intern-daily-workstation) — 实习生每日 SOP 执行与打卡闭环系统（脱敏版独立仓库）

`Dify` `RAG` `Workflow` `Community-Operations` `用户调研`

### 4. [lucky-growth-agent](https://github.com/Alaraby527/lucky-growth-agent) — 瑞幸用户增长 Agent

**比赛/个人研究项目**。意图驱动的全链路用户增长 Agent，五维信号（时间/天气/位置/行为/社交）感知六大消费意图，「生命周期×意图」24 格策略矩阵自主决策产品/优惠/渠道/文案。V1→V2→V3 三轮迭代：意图识别 68%→89%，人工审核率 85%→15%，单次调用成本降低 44%。2026 AI 先锋未来人才大赛参赛项目。

> Dify DSL 已导出至仓库，可导入任意 Dify 实例自部署运行

`Agent` `User-Growth` `Prompt-Engineering` `三轮迭代`

### 5. [msds-hazard-agent](https://github.com/Alaraby527/msds-hazard-agent) — MSDS 职业危害识别 Agent

**基于真实实习项目重做**。从 MSDS 成分章节提取 CAS 号并匹配职业病危害因素知识表。PDF 文本抽取 + 本地 OCR 降级，CAS 校验位验证保证准确性，高毒目录命中**必须人工复核**。Demo→V1→V2 完整迭代（8/12→11/12），V2 剩余 1 个 OCR 误识别 Case（Sn→Sm）。

> 🟢 [在线 Demo](https://msds-hazard-agent.streamlit.app/)

`Python` `OCR` `Document-AI` `Safety-Critical` `CAS校验`

---

## 🛠️ 补充项目

| 项目 | 说明 |
|------|------|
| [intern-daily-workstation](https://github.com/Alaraby527/intern-daily-workstation) | 【火花工坊子项目】12 名实习生×5 条业务线的 SOP 执行与打卡闭环，React+NestJS+飞书多维表格，填表 30min→5min。**产品判断：确定性场景用表单不用大模型** |
| [ai-pm-coach](https://github.com/Alaraby527/ai-pm-coach) | AI 产品经理求职教练 MVP：简历+JD 差距分析、7 天行动计划、模拟面试四维评分。核心设计：模型不得编造简历中没有的经历。[在线 Demo](https://ai-pm-coach-omega.vercel.app/) |
| [qiuzhao-workbench](https://github.com/Alaraby527/qiuzhao-workbench) | 秋招全流程管理：岗位匹配评分、投递看板、面试复盘、精力管理、训练中心。**产品判断：AI 只做辅助，核心流程由规则和数据模型驱动** |

---

## 📚 学习沉淀

| 项目 | 说明 |
|------|------|
| [aipm-learning-assistant](https://github.com/Alaraby527/aipm-learning-assistant) | AI产品经理系统学习平台：12周学习计划+20道面试题库+15题五维自测+197篇知识地图，纯前端React应用 |
| [ai-pm-skills](https://github.com/Alaraby527/ai-pm-skills) | AI 产品经理方法论工具包：11 个开箱即用的 Skill，覆盖用户研究、产品设计、数据分析、求职发展 |
| [ai-pm-methodology-notes](https://github.com/Alaraby527/ai-pm-methodology-notes) | AI 产品经理学习笔记：评测方法论、能力框架、Dify 实操、提示词框架等 15 篇文档 |

---

## 技能栈

- **AI 产品**：Agent 设计、MCP 工具集成、RAG、Prompt Engineering、评测体系、人机协同、成本优化
- **工程实现**：Python、JavaScript/TypeScript、Node.js、React、Dify、PWA
- **产品方法**：需求分析、PRD 撰写、竞品分析、数据驱动迭代、A/B 测试设计
- **工具链**：Git、飞书多维表格、Streamlit、Vercel、GitHub Pages

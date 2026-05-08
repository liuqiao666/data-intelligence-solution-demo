# data-intelligence-solution-demo

<p align="center">
  <img src="https://img.shields.io/badge/技能类型-数据智能方案生成器-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/适用场景-面试%20%7C%20售前%20%7C%20汇报-0f766e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/输出内容-项目蓝图%20%7C%20指标体系%20%7C%20功能模块-f59e0b?style=for-the-badge" />
</p>

<p align="center">
  <strong>根据 JD 或业务需求，快速生成一套完整的数据智能解决方案演示项目。</strong>
</p>

<p align="center">
  一个面向数据产品、售前方案、面试展示与业务汇报场景的智能体技能。<br />
  它可以把一段 JD、业务需求或招标描述，快速转成一套结构完整、逻辑清晰、适合演示的数据智能解决方案 Demo。
</p>

<p align="center">
  <a href="./README.en.md">English README</a> ·
  <a href="./SKILL.md">技能说明</a>
</p>

---

## 为什么做这个项目

很多真实业务场景里，输入往往只有一段很短的描述，但输出却要求足够完整：

- 要能讲清业务目标
- 要能拆出关键能力模块
- 要能设计指标体系与页面结构
- 要能组织成可演示、可扩展的项目方案
- 最好还能直接变成 Demo、原型或面试作品

`data-intelligence-solution-demo` 的目标，就是把这类“从模糊需求到可展示成果”的过程标准化、结构化、可复用化。

---

## 你可以得到什么

使用这个技能，你可以快速生成：

- JD / 业务需求能力解构
- 行业化指标体系设计
- 数据智能模块映射
- 页面结构与功能蓝图
- Mock 数据字段建议
- README 与演示话术骨架
- 面向面试、售前、汇报的完整 Demo 方案

---

## 功能预览

### 1. 需求解构
自动识别行业、平台类型、业务目标、关键指标与核心能力诉求。

### 2. 能力映射
把需求关键词映射为数据智能模块，例如：

- `MetricSystem`：指标管理
- `MetadataDashboard`：元数据治理
- `MemberPortrait`：客户画像
- `GrowthBrain`：增长实验
- `AICopilot`：AI 智能分析助手
- `Dashboard`：经营概览
- `RiskControl`：风控分析

### 3. 行业指标设计
内置多行业指标盘设计参考，支持快速生成业务指标体系。

覆盖场景包括：

- B2B 平台
- B2C 电商
- 金融科技
- 教育平台
- SaaS / 企业软件
- 内容 / 社区平台
- 广告 / 商业化平台

### 4. 演示项目蓝图输出
输出适合直接做 Demo 的项目蓝图，包括：

- 页面模块建议
- Mock 数据字段
- README 建议结构
- 演示路径与讲解重点
- 可扩展方向

---

## 快速示例

输入一段 JD 或业务描述，例如：

> 需要搭建一个面向企业客户的商旅数据平台 Demo，重点展示经营分析、指标体系、客户分层、供应链覆盖与 AI 智能问数能力。

这个技能可以进一步组织出：

- 行业判断：B2B 商旅 / 企业服务
- 北极星指标：GMV、订单量、客单价、企业客户数、供应商覆盖率
- 功能模块：Dashboard、MetricSystem、MemberPortrait、MetadataDashboard、AICopilot
- 页面结构：经营概览、指标管理、客户画像、元数据治理、AI 助手
- 演示重点：业务增长、数据治理、客户运营、智能分析闭环

---

## 适合谁用

- 数据产品经理
- 数据分析师
- BI / 指标体系设计人员
- 售前顾问
- 需要快速准备 Demo 的团队
- 准备数据智能方向面试作品的候选人

---

## 仓库结构

```text
.
├── SKILL.md
├── README.md
├── README.en.md
├── agents/
│   └── openai.yaml
└── references/
    ├── demo-blueprint.md
    └── industry-metrics.md
```

---

## 文件说明

- `SKILL.md`：技能主体说明与执行流程
- `agents/openai.yaml`：技能展示配置
- `references/industry-metrics.md`：行业指标库
- `references/demo-blueprint.md`：演示项目蓝图、页面结构、Mock 数据字段与 README 建议

---

## 核心理念

它不是只生成一份“方案文档”，而是帮助你生成一套“能讲、能演示、能继续开发”的数据智能项目骨架。

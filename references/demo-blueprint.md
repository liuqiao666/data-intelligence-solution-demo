# 数据智能演示项目蓝图

## 推荐页面

1. Dashboard 经营概览：北极星指标、核心 KPI、趋势图、预警卡片、AI 经营摘要。
2. MetricSystem 指标管理：指标目录、业务口径、计算逻辑、维度、负责人、更新频率。
3. MetadataDashboard 元数据治理：数据表资产、字段质量、血缘链路、质量告警、治理任务。
4. MemberPortrait 客户画像：客户分层、标签、LTV、留存、生命周期阶段、运营建议。
5. GrowthBrain 增长实验：AARRR 漏斗、A/B 实验、实验效果、策略推荐、人群包。
6. AICopilot AI 助手：自然语言问数、SQL 示例、洞察解释、异常归因、行动建议。

## 推荐项目结构

```text
src/
  App.tsx
  main.tsx
  data/
    metrics.ts
    customers.ts
    experiments.ts
    metadata.ts
    aiExamples.ts
  views/
    Dashboard.tsx
    MetricSystem.tsx
    MetadataDashboard.tsx
    MemberPortrait.tsx
    GrowthBrain.tsx
    AICopilot.tsx
  components/
    Layout.tsx
    KpiCard.tsx
    ChartCard.tsx
    DataTable.tsx
    InsightCard.tsx
  styles/
    globals.css
README.md
```

## Mock 数据字段建议

### 指标数据

- `metric_id`：指标编号
- `metric_name`：指标名称
- `domain`：指标域，如经营、用户、渠道、风控
- `definition`：业务口径
- `formula`：计算公式
- `dimensions`：分析维度
- `owner`：负责人
- `update_frequency`：更新频率
- `trend`：趋势
- `status`：正常、预警、异常

### 客户画像数据

- `customer_id`：客户编号
- `customer_name`：客户名称
- `segment`：客户分层
- `ltv`：生命周期价值
- `retention_score`：留存评分
- `risk_level`：流失风险
- `tags`：标签列表
- `next_action`：建议动作

### 实验数据

- `experiment_id`：实验编号
- `name`：实验名称
- `hypothesis`：实验假设
- `target_segment`：目标人群
- `metric`：观察指标
- `control_value`：对照组结果
- `variant_value`：实验组结果
- `uplift`：提升幅度
- `decision`：上线、继续观察、停止

### 元数据数据

- `table_name`：表名
- `domain`：所属主题域
- `owner`：负责人
- `quality_score`：质量评分
- `row_count`：数据量
- `lineage`：上游/下游链路
- `issue_count`：质量问题数
- `last_updated`：最近更新时间

## AI Copilot 示例问题

- “最近 7 天 GMV 下滑的主要原因是什么？”
- “帮我找出高 LTV 但活跃下降的客户群。”
- “哪些指标存在质量风险，会影响经营看板？”
- “本周哪个实验可以上线？为什么？”
- “生成一段面向管理层的经营分析摘要。”

## README 必备章节

1. 项目简介：说明业务背景和演示目标。
2. JD/需求匹配：列出输入需求与项目模块的对应关系。
3. 功能模块：逐页说明展示能力。
4. 指标体系：列出核心指标盘和口径。
5. 技术方案：说明前端、数据、图表、AI 模拟方式。
6. 本地运行：给出安装和启动命令。
7. 演示话术：给出 3-5 分钟讲解路径。
8. 后续扩展：数据库、权限、真实 NL2SQL、调度、治理平台接入。

## 演示话术模板

“这个 Demo 是围绕【行业/平台类型】的数据智能场景构建的。它不是单纯做一个 BI 看板，而是把指标体系、数据资产、客户画像、增长实验和 AI 分析串成一条闭环：先通过经营概览发现问题，再进入指标和元数据确认口径与数据质量，然后用客户画像定位人群，用增长实验验证策略，最后由 AI Copilot 生成洞察和行动建议。”

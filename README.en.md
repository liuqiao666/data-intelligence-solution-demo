# data-intelligence-solution-demo

> Turn a JD or business brief into a complete data intelligence solution demo project.

[中文说明](./README.md)

## What it is

`data-intelligence-solution-demo` is a Codex Skill designed to convert a rough job description, business requirement, RFP, or product brief into a structured, presentation-ready data intelligence demo solution.

Instead of producing a generic outline, it helps generate a more complete demo package, including:

- capability breakdown
- industry metric system
- feature and page modules
- mock data fields
- demo project blueprint
- README guidance, demo narrative, and extension ideas

It is especially useful for interview projects, pre-sales demos, business presentations, data product prototyping, and data intelligence platform showcases.

## What problem it solves

Many data-intelligence-related tasks start with weak input but require strong output:

- the input is often just a JD or a short business brief
- the output must be structured, convincing, and demo-ready
- it needs to feel like both a product solution and a project skeleton

This Skill standardizes that “0 to 1” process and helps produce a practical, explainable, and expandable demo project much faster.

## Core capabilities

### 1. JD / business requirement decomposition
Identify industry type, platform type, user role, business goals, key metrics, and the data intelligence capabilities that should be showcased.

### 2. Module mapping
Map requirement keywords into common data-intelligence modules, such as:

- `MetricSystem` for metric management
- `MetadataDashboard` for metadata governance
- `MemberPortrait` for customer profiling
- `GrowthBrain` for growth experiments
- `AICopilot` for AI-assisted analytics
- `Dashboard` for executive overview
- `RiskControl` for risk analysis

### 3. Industry metric system generation
Provide metric design references for multiple industries and generate a metric framework tailored to the target business scenario.

Currently covered:

- B2B platforms
- B2C ecommerce
- fintech
- education platforms
- SaaS / enterprise software
- content / community platforms
- advertising / monetization platforms

### 4. Demo project blueprint generation
Produce a full demo-project blueprint, including:

- page structure
- module design
- suggested views
- mock data fields
- README sections
- demo narrative template

### 5. Friendly for interviews, pre-sales, and presentations
This Skill does not only generate “features”. It also emphasizes:

- why the design makes sense
- what business problem each module solves
- how to present the demo effectively
- how the demo can evolve into a real product

## Typical use cases

- Build a data-product or data-intelligence interview showcase from a JD
- Create a pre-sales demo from a client business requirement
- Draft BI, metric-system, customer-profile, or growth-experiment prototypes from a business brief
- Kickstart solutions for data platforms, metric platforms, and AI analytics assistants
- Build a project skeleton that is good for business storytelling, product explanation, and technical extension

## Expected output structure

Given a JD or business brief, the Skill typically organizes the output into:

1. input understanding and default assumptions
2. capability breakdown
3. business metric system
4. demo project modules
5. page and data design
6. project structure and implementation plan
7. demo narrative
8. future extension suggestions

## Repository structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── demo-blueprint.md
    └── industry-metrics.md
```

## File guide

- `SKILL.md`: core skill workflow and instructions
- `agents/openai.yaml`: skill metadata for display and invocation
- `references/industry-metrics.md`: industry metric library
- `references/demo-blueprint.md`: demo blueprint, page structure, mock data fields, and README guidance

## Who should use it

This Skill is especially useful for:

- data product managers
- data analysts
- BI / metric-system designers
- pre-sales consultants
- candidates preparing data-intelligence interview demos
- teams that need fast, structured business-demo delivery

## One-line summary

If all you have is a JD or a business brief, but you need a complete, structured, presentation-ready data intelligence demo project, this Skill is built for that workflow.

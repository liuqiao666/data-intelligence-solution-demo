# data-intelligence-solution-demo

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Data%20Intelligence%20Demo%20Generator-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Use%20Case-Interview%20%7C%20Pre--sales%20%7C%20Presentation-0f766e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Output-Project%20Blueprint%20%7C%20Metrics%20%7C%20Modules-f59e0b?style=for-the-badge" />
</p>

<p align="center">
  <strong>Turn a JD or business brief into a complete data intelligence solution demo project.</strong>
</p>

<p align="center">
  An agent skill for data products, pre-sales solutions, interview showcases, and business presentations.<br />
  It transforms a JD, business requirement, or RFP-style brief into a structured, presentation-ready data intelligence demo.
</p>

<p align="center">
  <a href="./README.md">中文 README</a> ·
  <a href="./SKILL.md">Skill Spec</a>
</p>


---

## Installation

### Option 1: Install to the global skill directory (recommended)

Use this if you want to access the skill from any project.

```bash
mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R "/Users/liuqiao/Desktop/数据智能解决方案快速构建 Skill/data-intelligence-solution-demo/"* ~/.codex/skills/data-intelligence-solution-demo/
```

To verify the installation:

```bash
find ~/.codex/skills/data-intelligence-solution-demo -maxdepth 3 -type f | sort
```

### Option 2: Clone from GitHub and install

Using SSH:

```bash
git clone git@github.com:liuqiao666/data-intelligence-solution-demo.git && mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R data-intelligence-solution-demo/* ~/.codex/skills/data-intelligence-solution-demo/
```

Using HTTPS:

```bash
git clone https://github.com/liuqiao666/data-intelligence-solution-demo.git && mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R data-intelligence-solution-demo/* ~/.codex/skills/data-intelligence-solution-demo/
```

### Option 3: Use it directly in the current directory

If you only want to maintain or edit the skill locally, just open the current folder:

```bash
cd "/Users/liuqiao/Desktop/数据智能解决方案快速构建 Skill/data-intelligence-solution-demo"
```

### Usage example

After installing it globally, you can invoke it with a request like:

```text
Turn this JD into a complete data intelligence solution demo project.
```


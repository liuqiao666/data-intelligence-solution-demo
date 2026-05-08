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

The instructions below are for external users who want to install this skill into their local global skill directory.

### Option 1: Install from GitHub (recommended)

Using SSH:

```bash
git clone git@github.com:liuqiao666/data-intelligence-solution-demo.git && mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R data-intelligence-solution-demo/* ~/.codex/skills/data-intelligence-solution-demo/
```

Using HTTPS:

```bash
git clone https://github.com/liuqiao666/data-intelligence-solution-demo.git && mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R data-intelligence-solution-demo/* ~/.codex/skills/data-intelligence-solution-demo/
```

### Option 2: Download ZIP and install

If you downloaded the repository as a ZIP file from GitHub and extracted it into a folder such as `data-intelligence-solution-demo-main`, run:

```bash
mkdir -p ~/.codex/skills/data-intelligence-solution-demo && cp -R data-intelligence-solution-demo-main/* ~/.codex/skills/data-intelligence-solution-demo/
```

### Verify the installation

```bash
find ~/.codex/skills/data-intelligence-solution-demo -maxdepth 3 -type f | sort
```

### Usage example

After installation, you can invoke the skill with a request like:

```text
Turn this JD into a complete data intelligence solution demo project.
```


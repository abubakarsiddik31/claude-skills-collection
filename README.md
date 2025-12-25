# 📦 Claude Skills Collection

**A curated collection of official and community-built Claude Skills.**  
Anthropic Skills are modular tools that extend the capabilities of Claude AI—unlocking workflows for coding, document creation, design, data analysis, research, and more.

This repository gathers and organizes all publicly available Claude Skills, including both built-in tools by Anthropic and creative contributions from the community. Browse by category, explore capabilities, and kickstart your own Skill creation.

> 💡 **Note**: Skills require Claude Pro, Max, Team, or Enterprise access with code execution enabled.

---

## 📚 Table of Contents

- [What Are Claude Skills?](#what-are-claude-skills)
- [Categories](#categories)
  - [📄 Document Skills](#document-skills)
  - [🎨 Creative & Design](#creative--design)
  - [💻 Development & Code Tools](#development--code-tools)
  - [📊 Data & Analysis](#data--analysis)
  - [🔬 Scientific & Research Tools](#scientific--research-tools)
  - [📝 Writing & Research](#writing--research)
  - [📚 Learning & Knowledge](#learning--knowledge)
  - [🎥 Media & Content](#media--content)
  - [🤝 Collaboration & Project Management](#collaboration--project-management)
  - [🔐 Security & Testing](#security--testing)
  - [⚙️ Utility & Automation](#utility--automation)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## What Are Claude Skills?

Claude **Skills** are specialized modules that Claude can use to perform structured, multi-step tasks. Each skill is a lightweight folder with a clear instruction interface, and optionally includes Python code, templates, and assets.

Skills allow Claude to:
- Create and edit documents (Word, Excel, PPT)
- Parse and analyze structured data
- Write and debug code
- Generate creative visual assets
- Automate research, testing, or collaboration tasks

Official Skills are created by Anthropic and auto-invoked when needed. You can also install or build custom skills to meet your unique workflow needs.

---

## 📄 Document Skills

| Name | Description | Link |
|------|-------------|------|
| **docx** | Create and edit Microsoft Word documents with formatting, comments, and tracked changes | [Source](https://github.com/anthropics/skills/tree/main/document-skills/docx) |
| **pdf** | Extract content from PDFs, split/merge documents, or create new ones | [Source](https://github.com/anthropics/skills/tree/main/document-skills/pdf) |
| **pptx** | Generate and edit PowerPoint presentations | [Source](https://github.com/anthropics/skills/tree/main/document-skills/pptx) |
| **xlsx** | Manipulate Excel files, formulas, tables, and charts | [Source](https://github.com/anthropics/skills/tree/main/document-skills/xlsx) |
| **revealjs-skill** | Generate polished, professional presentations using the Reveal.js HTML presentation framework | [Source](https://github.com/ryanbbrown/revealjs-skill/tree/main) |

---

## 🎨 Creative & Design

| Name | Description | Link |
|------|-------------|------|
| **algorithmic-art** | Create generative art using p5.js | [Source](https://github.com/anthropics/skills/tree/main/algorithmic-art) |
| **canvas-design** | Render layout-based visual designs in PNG/PDF | [Source](https://github.com/anthropics/skills/tree/main/canvas-design) |
| **slack-gif-creator** | Generate Slack-optimized animated GIFs | [Source](https://github.com/anthropics/skills/tree/main/slack-gif-creator) |
| **brand-guidelines** | Apply company branding to outputs | [Source](https://github.com/anthropics/skills/tree/main/brand-guidelines) |
| **theme-factory** | Create and apply visual themes for documents | [Source](https://github.com/anthropics/skills/tree/main/theme-factory) |
| **nano-banana-image-generation** | Create images using Nano Banana Pro | [Source](https://github.com/livelabs-ventures/nano-skills/tree/main/skills/nano-image-generator) |

---

## 💻 Development & Code Tools

| Name | Description | Link |
|------|-------------|------|
| **artifacts-builder** | Generate clean HTML/CSS/React UI components | [Source](https://github.com/anthropics/skills/tree/main/artifacts-builder) |
| **MCP Server** | Build Claude-compatible API connectors | [Source](https://github.com/anthropics/skills/tree/main/mcp-builder) |
| **Changelog Generator** | Create changelogs from commit history | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator) |
| **using-git-worktrees** | Manage feature branches safely in isolated Git worktrees | [Source](https://github.com/obra/superpowers/tree/main/skills/using-git-worktrees) |
| **test-driven-development** | Write tests before implementation to drive development | [Source](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) |
| **subagent-driven-development** | Use multiple Claude subagents to coordinate complex implementations | [Source](https://github.com/obra/superpowers/tree/main/skills/subagent-driven-development) |
| **executing-plans** | Execute structured plans with checkpoints and verification steps | [Source](https://github.com/obra/superpowers/tree/main/skills/executing-plans) |
| **finishing-a-development-branch** | Complete development branches with testing and review flow | [Source](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) |
| **preserving-productive-tensions** | Manage architectural decisions by preserving competing viewpoints to balance innovation and stability | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/architecture/preserving-productive-tensions) |
| **web-artifacts-builder** | Create elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui) | [Source](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) |
| **pypict-claude-skill** | Design comprehensive test cases using PICT (Pairwise Independent Combinatorial Testing) for optimized test suites | [Source](https://github.com/omkamal/pypict-claude-skill) |
| **aws-skills** | AWS development with CDK best practices, cost optimization, and serverless/event-driven architecture patterns | [Source](https://github.com/zxkane/aws-skills) |
| **claude-starter** | Production-ready Claude Code configuration template with 40 auto-activating skills and TOON format support | [Source](https://github.com/raintree-technology/claude-starter) |
| **move-code-quality-skill** | Analyzes Move language packages against the official Move Book Code Quality Checklist | [Source](https://github.com/1NickPappas/move-code-quality-skill) |
| **claude-code-terminal-title** | Gives each Claude Code terminal window a dynamic title describing the work being done | [Source](https://github.com/bluzername/claude-code-terminal-title) |


---

## 📊 Data & Analysis

| Name | Description | Link |
|------|-------------|------|
| **csv-data-summarizer** | Generate statistics and charts from CSVs | [Source](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) |
| **root-cause-tracing** | Trace and diagnose the source of data or logic errors | [Source](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) |
| **postgres** | Execute safe read-only SQL queries against PostgreSQL databases with multi-connection support | [Source](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) |

---

## 🔬 Scientific & Research Tools

| Name | Description | Link |
|------|-------------|------|
| **claude-scientific-skills** | 125+ scientific skills for bioinformatics, cheminformatics, clinical research, and machine learning | [Source](https://github.com/K-Dense-AI/claude-scientific-skills) |
| **materials-simulation-skills** | Agent skills for computational materials science: numerical stability, time-stepping, linear solvers, and simulation validation | [Source](https://github.com/HeshamFS/materials-simulation-skills) |

---

## 📝 Writing & Research

| Name | Description | Link |
|------|-------------|------|
| **article-extractor** | Extract full content from web articles | [Source](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) |
| **Content Research Writer** | Research and refine written content with feedback | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer) |
| **internal-comms** | Draft formal internal comms and reports | [Source](https://github.com/anthropics/skills/tree/main/internal-comms) |
| **writing-plans** | Create structured written plans with clear milestones | [Source](https://github.com/obra/superpowers/tree/main/skills/writing-plans) |
| **writing-skills** | Enhance instructional and technical writing quality | [Source](https://github.com/obra/superpowers/tree/main/skills/writing-skills) |
| **brainstorming** | Facilitate creative idea generation sessions | [Source](https://github.com/obra/superpowers/tree/main/skills/brainstorming) |
| **family-history-research** | Provides assistance with planning family history and genealogy research projects | [Source](https://github.com/emaynard/claude-family-history-research-skill) |

---

## 📚 Learning & Knowledge

| Name | Description | Link |
|------|-------------|------|
| **tapestry** | Build a linked knowledge graph from documents | [Source](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) |
| **ship-learn-next** | Recommend next steps based on feedback loops | [Source](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) |
| **using-superpowers** | Learn and apply best practices for Superpowers workflows | [Source](https://github.com/obra/superpowers/tree/main/skills/using-superpowers) |
| **sharing-skills** | Learn how to contribute new skills via pull requests | [Source](https://github.com/obra/superpowers/tree/main/skills/sharing-skills) |
| **collision-zone-thinking** | Combine unrelated concepts to find new creative or problem-solving connections | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/problem-solving/collision-zone-thinking) |
| **inversion-exercise** | Flip assumptions to uncover hidden insights and constraints | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/problem-solving/inversion-exercise) |
| **meta-pattern-recognition** | Identify patterns across domains to uncover universal principles | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/problem-solving/meta-pattern-recognition) |
| **scale-game** | Stress-test ideas at extreme scales to expose hidden weaknesses or truths | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/problem-solving/scale-game) |
| **simplification-cascades** | Reduce complexity by discovering insights that simplify multiple elements at once | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/problem-solving/simplification-cascades) |
| **tracing-knowledge-lineages** | Track how ideas evolve across iterations and influences | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/research/tracing-knowledge-lineages) |


---

## 🎥 Media & Content

| Name | Description | Link |
|------|-------------|------|
| **youtube-transcript** | Summarize YouTube transcripts | [Source](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) |
| **claude-epub-skill** | Parse and analyze EPUB eBooks | [Source](https://github.com/smerchek/claude-epub-skill) |
| **Image Enhancer** | Improve resolution and clarity of screenshots | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/image-enhancer) |
| **Video Downloader** | Download YouTube videos for use in Claude | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/video-downloader) |
| **imagen** | Generate images using Google Gemini's image generation API for UI mockups, icons, and visual assets | [Source](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) |

---

## 🤝 Collaboration & Project Management

| Name | Description | Link |
|------|-------------|------|
| **Meeting Insights Analyzer** | Analyze meeting dynamics and communication patterns | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/meeting-insights-analyzer) |
| **Notion Integration Skills** | Official Notion connectors for Claude | [Source](https://notiondevs.notion.site/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) |
| **commands** | Manage and automate recurring project commands | [Source](https://github.com/obra/superpowers/tree/main/skills/commands) |
| **receiving-code-review** | Process and apply code review feedback | [Source](https://github.com/obra/superpowers/tree/main/skills/receiving-code-review) |
| **requesting-code-review** | Request and manage structured code reviews | [Source](https://github.com/obra/superpowers/tree/main/skills/requesting-code-review) |
| **dispatching-parallel-agents** | Coordinate multiple Claude subagents on shared tasks | [Source](https://github.com/obra/superpowers/tree/main/skills/dispatching-parallel-agents) |
| **remembering-conversations** | Recall facts, insights, and context from past Claude Code sessions | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/collaboration/remembering-conversations) |
| **git-pushing** | Automate git operations and repository interactions | [Source](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) |
| **linear-claude-skill** | Manage Linear issues, projects, and teams with MCP tools and GraphQL fallbacks | [Source](https://github.com/wrsmith108/linear-claude-skill) |
| **linear-cli-skill** | A skill teaching Claude how to use linear-CLI as an alternative to Linear MCP | [Source](https://github.com/Valian/linear-cli-skill) |
| **review-implementing** | Evaluate code implementation plans and align with specs | [Source](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) |
| **test-fixing** | Detect failing tests and propose patches or fixes | [Source](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) |


---

## 🔐 Security & Testing

| Name | Description | Link |
|------|-------------|------|
| **webapp-testing** | UI test automation using Playwright | [Source](https://github.com/anthropics/skills/tree/main/webapp-testing) |
| **ffuf_claude_skill** | Fuzz test web apps with FFUF + Claude | [Source](https://github.com/jthack/ffuf_claude_skill) |
| **defense-in-depth** | Implement multi-layered testing and security best practices | [Source](https://github.com/obra/superpowers/tree/main/skills/defense-in-depth) |
| **systematic-debugging** | Structured debugging with hypothesis testing and validation | [Source](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) |
| **testing-anti-patterns** | Identify and prevent testing anti-patterns | [Source](https://github.com/obra/superpowers/tree/main/skills/testing-anti-patterns) |
| **testing-skills-with-subagents** | Verify new skills using subagents and test cycles | [Source](https://github.com/obra/superpowers/tree/main/skills/testing-skills-with-subagents) |
| **verification-before-completion** | Run verification checks before closing tasks | [Source](https://github.com/obra/superpowers/tree/main/skills/verification-before-completion) |
| **condition-based-waiting** | Use logical conditions to control test flow timing | [Source](https://github.com/obra/superpowers/tree/main/skills/condition-based-waiting) |
| **varlock-claude-skill** | Secure environment variable management ensuring secrets never appear in sessions, terminals, logs, or git commits | [Source](https://github.com/wrsmith108/varlock-claude-skill) |

---

## ⚙️ Utility & Automation

| Name | Description | Link |
|------|-------------|------|
| **file-organizer** | Clean up file structures, rename documents | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/file-organizer) |
| **invoice-organizer** | Parse and categorize invoices | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/invoice-organizer) |
| **raffle-winner-picker** | Pick winners using secure randomness | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/raffle-winner-picker) |
| **skill-creator** | Build your own skill interactively | [Source](https://github.com/anthropics/skills/tree/main/skill-creator) |
| **template-skill** | A starting template for new skills | [Source](https://github.com/anthropics/skills/tree/main/template-skill) |
| **using-superpowers** | Automate Superpowers workflows and validation tasks | [Source](https://github.com/obra/superpowers/tree/main/skills/using-superpowers) |
| **gardening-skills-wiki** | Maintain the skills wiki, ensuring naming consistency and metadata quality | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/meta/gardening-skills-wiki) |
| **pulling-updates-from-skills-repository** | Sync and pull the latest skill updates from repositories | [Source](https://github.com/obra/superpowers-skills/tree/main/skills/meta/pulling-updates-from-skills-repository) |


---

## Getting Started

To use a skill:
1. Clone the [Anthropic Claude Skills](https://github.com/anthropics/skills) repo.
2. Enable Code Execution and Skill loading in Claude.
3. Upload the skill folder (or link to a Git repo with an `SKILL.md`).
4. Ask Claude to activate or use the skill!

---

## Contributing

Have a skill to add?  
Open a pull request or submit your repo link in an issue with:

- Name of the skill  
- Short description  
- Category  
- Link to the source

---

## License

This repo lists and links to skills under various licenses.  
Please refer to each linked repository for license terms.

---

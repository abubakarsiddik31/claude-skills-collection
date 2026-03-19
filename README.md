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
- [Skill Quality Standards & Template](#skill-quality-standards--template)
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
| **frontend-slides** | Create animation-rich single-file HTML presentations with 12 visual styles and zero dependencies | [Source](https://github.com/zarazhangrui/frontend-slides) |
| **web-asset-generator** | Generate favicons, app icons, PWA manifests, and Open Graph images with WCAG contrast validation | [Source](https://github.com/alonw0/web-asset-generator) |

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
| **audit-website** | Cli website auditing tool for seo, performance, security and 140+ other rules | [Source](https://github.com/squirrelscan/skills/tree/main) |
| **stripe-best-practices** | Official Stripe skill for building correct integrations with payments, subscriptions, and webhooks | [Source](https://github.com/stripe/ai/tree/main/skills/stripe-best-practices) |
| **upgrade-stripe** | Official Stripe skill for safely upgrading SDK and API versions | [Source](https://github.com/stripe/ai/tree/main/skills/upgrade-stripe) |
| **expo-app-design** | Official Expo skill for designing and building Expo/React Native apps with best practices | [Source](https://github.com/expo/skills) |
| **supabase-postgres** | Official Supabase skill for PostgreSQL best practices in Supabase projects | [Source](https://github.com/supabase/agent-skills) |
| **terraform-code-generation** | Official HashiCorp skill for generating and validating Terraform HCL code | [Source](https://github.com/hashicorp/agent-skills/tree/main/terraform/code-generation) |
| **terraform-module-generation** | Official HashiCorp skill for creating and refactoring Terraform modules | [Source](https://github.com/hashicorp/agent-skills/tree/main/terraform/module-generation) |
| **terraform-provider-development** | Official HashiCorp skill for developing custom Terraform providers | [Source](https://github.com/hashicorp/agent-skills/tree/main/terraform/provider-development) |
| **terraform-skill** | Comprehensive Terraform/OpenTofu best practices covering testing, modules, CI/CD, and 100+ patterns | [Source](https://github.com/antonbabenko/terraform-skill) |
| **cloudflare-agents-sdk** | Official Cloudflare skill for building stateful AI agents with scheduling, RPC, and MCP on Workers | [Source](https://github.com/cloudflare/skills) |
| **cloudflare-wrangler** | Official Cloudflare skill for deploying and managing Workers, KV, R2, D1, and Queues | [Source](https://github.com/cloudflare/skills) |
| **cloudflare-web-perf** | Official Cloudflare skill for auditing Core Web Vitals and render-blocking resources | [Source](https://github.com/cloudflare/skills) |
| **netlify-functions** | Official Netlify skill for building serverless API endpoints and background tasks | [Source](https://github.com/netlify/context-and-tools) |
| **netlify-db** | Official Netlify skill for managed Postgres with deploy preview branching | [Source](https://github.com/netlify/context-and-tools) |
| **neon-postgres** | Official Neon skill for best practices with Neon Serverless Postgres | [Source](https://github.com/neondatabase/agent-skills) |
| **vercel-react** | Official Vercel skill for React best practices and patterns | [Source](https://github.com/vercel-labs/agent-skills) |
| **next-best-practices** | Official Vercel skill for Next.js recommended patterns and best practices | [Source](https://github.com/vercel-labs/next-skills) |
| **next-upgrade** | Official Vercel skill for upgrading Next.js projects to newer versions | [Source](https://github.com/vercel-labs/next-skills) |
| **react-native-best-practices** | Official Callstack skill for React Native performance optimization patterns | [Source](https://github.com/callstackincubator/agent-skills) |
| **better-auth** | Official Better Auth skill for authentication integration including OAuth, 2FA, and passkeys | [Source](https://github.com/better-auth/skills) |
| **tinybird** | Official Tinybird skill for project guidelines covering datasources, pipes, endpoints, and SQL | [Source](https://github.com/tinybirdco/tinybird-agent-skills) |
| **sanity** | Official Sanity skill for Sanity Studio, GROQ queries, and content workflows | [Source](https://github.com/sanity-io/agent-toolkit) |
| **clickhouse** | Official ClickHouse skill for analytics query best practices | [Source](https://github.com/ClickHouse/agent-skills) |
| **remotion-skill** | Official Remotion skill for programmatic video creation with React | [Source](https://github.com/remotion-dev/skills) |
| **ios-simulator-skill** | 21-script toolkit for iOS simulator automation with accessibility APIs and 96% token reduction | [Source](https://github.com/conorluddy/ios-simulator-skill) |
| **claude-d3js-skill** | Interactive data visualizations using D3.js with reference materials and patterns | [Source](https://github.com/chrisvoncsefalvay/claude-d3js-skill) |
| **playwright-skill** | General-purpose browser automation with Playwright for testing and web interaction | [Source](https://github.com/lackeyjb/playwright-skill) |
| **claude-a11y-skill** | Comprehensive accessibility audits combining axe-core and eslint-plugin-jsx-a11y against WCAG 2.1 | [Source](https://github.com/airowe/claude-a11y-skill) |
| **context-engineering-kit** | Advanced context engineering with multi-agent patterns, reflexion loops, and domain-driven development | [Source](https://github.com/NeoLabHQ/context-engineering-kit) |
| **compound-engineering-plugin** | Pragmatic engineering plugin with ideation, planning, execution, multi-agent review, and knowledge compounding | [Source](https://github.com/EveryInc/compound-engineering-plugin) |

---

## 📊 Data & Analysis

| Name | Description | Link |
|------|-------------|------|
| **csv-data-summarizer** | Generate statistics and charts from CSVs | [Source](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) |
| **root-cause-tracing** | Trace and diagnose the source of data or logic errors | [Source](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) |
| **postgres** | Execute safe read-only SQL queries against PostgreSQL databases with multi-connection support | [Source](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) |
| **read-only-postgres** | Safe read-only PostgreSQL queries with multi-connection support and defense-in-depth security | [Source](https://github.com/jawwadfirdousi/agent-skills) |
| **prompt-template-wizard** | Converts incomplete feature/bug requests into complete structured prompt templates | [Source](https://github.com/jawwadfirdousi/agent-skills) |

---

## 🔬 Scientific & Research Tools

| Name | Description | Link |
|------|-------------|------|
| **claude-scientific-skills** | 125+ scientific skills for bioinformatics, cheminformatics, clinical research, and machine learning | [Source](https://github.com/K-Dense-AI/claude-scientific-skills) |
| **materials-simulation-skills** | Agent skills for computational materials science: numerical stability, time-stepping, linear solvers, and simulation validation | [Source](https://github.com/HeshamFS/materials-simulation-skills) |
| **extract-from-pdfs** | Extract structured data from scientific PDFs using Claude's vision with external validation against GBIF/WFO databases | [Source](https://github.com/brunoasm/my_claude_skills) |
| **phylo-from-buscos** | Phylogenomic workflows from genome assemblies using BUSCO single-copy orthologs | [Source](https://github.com/brunoasm/my_claude_skills) |
| **claude-mountaineering-skills** | Mountain route research aggregating 10+ sources including weather, avalanche forecasts, and hazard analysis | [Source](https://github.com/dreamiurg/claude-mountaineering-skills) |

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
| **avoid-ai-writing** | Audit and rewrite content to remove 21 categories of AI writing patterns with a 43-entry replacement table | [Source](https://github.com/conorbronsdon/avoid-ai-writing) |
| **non-fiction-book-factory** | Complete nonfiction book creation pipeline replicating traditional publishing infrastructure | [Source](https://github.com/robertguss/claude-skills) |
| **ebook-factory** | Focused ebook creation pipeline for producing publication-ready digital books | [Source](https://github.com/robertguss/claude-skills) |

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
| **think-deeply** | Prevents confirmatory answers by encouraging nuanced multi-perspective analysis for complex questions | [Source](https://github.com/brunoasm/my_claude_skills) |

---

## 🎥 Media & Content

| Name | Description | Link |
|------|-------------|------|
| **youtube-transcript** | Summarize YouTube transcripts | [Source](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) |
| **claude-epub-skill** | Parse and analyze EPUB eBooks | [Source](https://github.com/smerchek/claude-epub-skill) |
| **Image Enhancer** | Improve resolution and clarity of screenshots | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/image-enhancer) |
| **Video Downloader** | Download YouTube videos for use in Claude | [Source](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/video-downloader) |
| **imagen** | Generate images using Google Gemini's image generation API for UI mockups, icons, and visual assets | [Source](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) |
| **typefully** | Official Typefully skill for creating and scheduling social media content across X, LinkedIn, Threads, Bluesky, and Mastodon | [Source](https://github.com/typefully/agent-skills) |

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
| **product-manager-skills** | Senior PM agent with 6 knowledge domains, 12 templates, 30+ frameworks covering discovery, strategy, delivery, SaaS metrics, PM career coaching, and AI product craft | [Source](https://github.com/Digidai/product-manager-skills) |
| **read-only-gh-pr-review** | Safe read-only review of backend pull requests using GitHub CLI with local inspection | [Source](https://github.com/jawwadfirdousi/agent-skills) |

---

## 🔐 Security & Testing

| Name | Description | Link |
|------|-------------|------|
| **Trail of Bits Security Skills** | Security skills for static analysis with CodeQL/Semgrep, variant analysis, code auditing, and fix verification | [Source](https://github.com/trailofbits/skills) |
| **webapp-testing** | UI test automation using Playwright | [Source](https://github.com/anthropics/skills/tree/main/webapp-testing) |
| **ffuf_claude_skill** | Fuzz test web apps with FFUF + Claude | [Source](https://github.com/jthack/ffuf_claude_skill) |
| **defense-in-depth** | Implement multi-layered testing and security best practices | [Source](https://github.com/obra/superpowers/tree/main/skills/defense-in-depth) |
| **systematic-debugging** | Structured debugging with hypothesis testing and validation | [Source](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) |
| **testing-anti-patterns** | Identify and prevent testing anti-patterns | [Source](https://github.com/obra/superpowers/tree/main/skills/testing-anti-patterns) |
| **testing-skills-with-subagents** | Verify new skills using subagents and test cycles | [Source](https://github.com/obra/superpowers/tree/main/skills/testing-skills-with-subagents) |
| **verification-before-completion** | Run verification checks before closing tasks | [Source](https://github.com/obra/superpowers/tree/main/skills/verification-before-completion) |
| **condition-based-waiting** | Use logical conditions to control test flow timing | [Source](https://github.com/obra/superpowers/tree/main/skills/condition-based-waiting) |
| **varlock-claude-skill** | Secure environment variable management ensuring secrets never appear in sessions, terminals, logs, or git commits | [Source](https://github.com/wrsmith108/varlock-claude-skill) |
| **security-fuzzing** | Essential fuzzing payloads for SQL injection, command injection, NoSQL injection, and LDAP injection testing | [Source](https://github.com/Eyadkelleh/awesome-claude-skills-security) |
| **security-payloads** | Specialized attack payloads for XSS vectors, XXE, template injection, and file upload bypass testing | [Source](https://github.com/Eyadkelleh/awesome-claude-skills-security) |
| **llm-testing** | AI/ML security testing including bias detection, data leakage, alignment testing, and adversarial resistance | [Source](https://github.com/Eyadkelleh/awesome-claude-skills-security) |

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
| **cc-devops-skills** | 31 DevOps skills covering IaC, CI/CD, Kubernetes, observability, and scripting automation | [Source](https://github.com/akin-ozer/cc-devops-skills) |
| **devops-claude-skills** | DevOps workflow skills for Terraform, K8s troubleshooting, AWS cost optimization, and GitOps | [Source](https://github.com/ahmedasmar/devops-claude-skills) |
| **firecrawl-cli** | Official Firecrawl skill for scraping, crawling, searching, and mapping the web via CLI | [Source](https://github.com/firecrawl/cli) |
| **replicate** | Official Replicate skill for discovering, comparing, and running AI models via API | [Source](https://github.com/replicate/skills) |
| **agentsys** | 36 workflow automation skills for profiling, code review, AI consultation, release management, and drift analysis | [Source](https://github.com/avifenesh/agentsys) |

---

## Getting Started

To use a skill:
1. Clone the [Anthropic Claude Skills](https://github.com/anthropics/skills) repo.
2. Enable Code Execution and Skill loading in Claude.
3. Upload the skill folder (or link to a Git repo with an `SKILL.md`).
4. Ask Claude to activate or use the skill!

---

## Skill Quality Standards & Template

Writing a great skill starts with a well-structured `SKILL.md` file. [AgentSkills.io](https://agentskills.io) provides the canonical specification for the Claude Skills format, including validation rules and a detailed checklist. Anthropic also publishes best practices for skill authoring at [platform.claude.com](https://platform.claude.com).

### Minimal SKILL.md Template

Every skill should include a `SKILL.md` with proper YAML frontmatter at the top:

```yaml
---
name: my-skill-name
description: |
  Generates weekly status reports from project data.
  Use when the user asks for a summary of recent activity.
---
```

The body of `SKILL.md` (below the frontmatter) contains the instructions Claude follows when the skill is activated.

### Key Quality Criteria

- **name** -- Use `kebab-case`, 1-64 characters (e.g., `csv-data-summarizer`, not `CSV Data Summarizer`).
- **description** -- Write in third person. State *what* the skill does and *when* to use it. Keep it under 300 characters.
- **Body length** -- Keep the instruction body under 500 lines. Long skills should be split into focused sub-skills.
- **Progressive disclosure** -- Start with the most common usage, then cover edge cases. Claude reads top-down, so put the critical path first.
- **No secrets in source** -- Never embed API keys, tokens, or credentials in `SKILL.md`. Use environment variables or MCP configuration instead.

### Reference Implementations

- [anthropics/skills](https://github.com/anthropics/skills) -- Anthropic's official skill repository with production-quality examples.
- [AgentSkills.io Validation Checklist](https://agentskills.io) -- Use this to validate your `SKILL.md` before publishing.
- [Anthropic Skill Authoring Guide](https://platform.claude.com) -- Official best practices from Anthropic.

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

# 🤖 Claude Agents Library

> **34 Production-Ready AI Agents for Claude** — Copy, paste, and customize for any professional role.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Agents](https://img.shields.io/badge/Agents-34-green.svg)](#the-agents)
[![Categories](https://img.shields.io/badge/Categories-7-orange.svg)](#categories)

## What is This?

This is a curated library of **34 specialized Claude agent configurations** organized into 7 professional categories. Each agent is a detailed markdown file containing:

- **Purpose** — Who the agent is and what they excel at
- **Core Responsibilities** — Specific tasks and behaviors
- **Key Skills** — Tools, technologies, and expertise
- **Communication Style** — How the agent interacts
- **Example Prompts** — Ready-to-use prompts
- **Related Agents** — Connections to other agents

## Why Use Agents?

Instead of writing prompts from scratch every time, agents give Claude a **persistent persona** with domain expertise, consistent behavior, and task-specific knowledge.

**Simple prompt:**
```
Help me write a marketing email.
```

**With an agent:**
```markdown
# Content Creator Agent

You are an expert content marketer with 10+ years of experience 
creating high-converting copy for B2B SaaS companies...
```

The difference? Consistent quality, faster results, and expertise on demand.

## Categories

| Category | Agents | Description |
|----------|--------|-------------|
| [**Engineering**](./engineering/) | 6 | Frontend, backend, mobile, AI, DevOps, prototyping |
| [**Product**](./product/) | 3 | Research, feedback synthesis, prioritization |
| [**Marketing**](./marketing/) | 7 | Social media, content, growth, ASO |
| [**Design**](./design/) | 5 | UI/UX, branding, visual storytelling |
| [**Project Management**](./project-management/) | 3 | Shipping, tracking, coordination |
| [**Studio Operations**](./studio-operations/) | 5 | Support, analytics, compliance, finance |
| [**Testing**](./testing/) | 5 | QA, API testing, performance, evaluation |

## The Agents

### Engineering (6)
- [Frontend Developer](./engineering/frontend-developer.md) — UI implementation, accessibility, performance
- [Backend Architect](./engineering/backend-architect.md) — System design, APIs, databases
- [Mobile App Builder](./engineering/mobile-app-builder.md) — React Native, Flutter, native development
- [AI Engineer](./engineering/ai-engineer.md) — LLM integration, RAG, MCP, Claude Code
- [DevOps Automator](./engineering/devops-automator.md) — CI/CD, infrastructure, deployment
- [Rapid Prototyper](./engineering/rapid-prototyper.md) — MVPs, hackathons, speed builds

### Product (3)
- [Trend Researcher](./product/trend-researcher.md) — Market analysis, competitor intelligence
- [Feedback Synthesizer](./product/feedback-synthesizer.md) — User feedback aggregation and insights
- [Sprint Prioritizer](./product/sprint-prioritizer.md) — Backlog management, estimation

### Marketing (7)
- [TikTok Strategist](./marketing/tiktok-strategist.md) — Short-form video, trends, engagement
- [Instagram Curator](./marketing/instagram-curator.md) — Visual content, Stories, Reels, Threads
- [X/Twitter Strategist](./marketing/x-twitter-strategist.md) — Threads, real-time engagement
- [Reddit Community Builder](./marketing/reddit-community-builder.md) — Authentic community participation
- [App Store Optimizer](./marketing/app-store-optimizer.md) — ASO, keywords, conversions
- [Content Creator](./marketing/content-creator.md) — Blog posts, emails, landing pages
- [Growth Hacker](./marketing/growth-hacker.md) — Experiments, funnels, acquisition

### Design (5)
- [UI Designer](./design/ui-designer.md) — Interface design, component systems
- [UX Researcher](./design/ux-researcher.md) — User research, testing, insights
- [Brand Guardian](./design/brand-guardian.md) — Brand consistency, guidelines
- [Visual Storyteller](./design/visual-storyteller.md) — Presentations, infographics, data viz
- [Whimsy Injector](./design/whimsy-injector.md) — Delight, micro-interactions, personality

### Project Management (3)
- [Experiment Tracker](./project-management/experiment-tracker.md) — A/B tests, learning documentation
- [Project Shipper](./project-management/project-shipper.md) — Launches, blockers, releases
- [Studio Producer](./project-management/studio-producer.md) — Resource allocation, coordination

### Studio Operations (5)
- [Support Responder](./studio-operations/support-responder.md) — Customer support, issue resolution
- [Analytics Reporter](./studio-operations/analytics-reporter.md) — Dashboards, reports, insights
- [Infrastructure Maintainer](./studio-operations/infrastructure-maintainer.md) — Monitoring, incidents, reliability
- [Legal Compliance Checker](./studio-operations/legal-compliance-checker.md) — GDPR, EU AI Act, policies
- [Finance Tracker](./studio-operations/finance-tracker.md) — Budgets, expenses, metrics

### Testing (5)
- [Tool Evaluator](./testing/tool-evaluator.md) — Technology assessment, comparisons
- [API Tester](./testing/api-tester.md) — API validation, security, performance
- [Workflow Optimizer](./testing/workflow-optimizer.md) — Process improvement, automation
- [Performance Benchmarker](./testing/performance-benchmarker.md) — Load testing, optimization
- [Test Results Analyzer](./testing/test-results-analyzer.md) — Test analysis, quality metrics

## Quick Start

### 1. Using with Claude Code

Create the agent directory in your project:

```bash
mkdir -p .claude/agents
cp -r ./engineering ./.claude/agents/
cp -r ./product ./.claude/agents/
# ... or copy specific agents you need
```

Reference in your `CLAUDE.md`:

```markdown
# Project Agents

## Active Agents
- [Frontend Developer](.claude/agents/engineering/frontend-developer.md)
- [UI Designer](.claude/agents/design/ui-designer.md)
```

### 2. Using with Claude Chat

Copy the agent content and paste it as context:

> "Acting as the Backend Architect agent, design a database schema for a multi-tenant SaaS app."

### 3. Combining Multiple Agents

For complex work, reference multiple agents:

> "Using both the Growth Hacker and Analytics Reporter agents, analyze our funnel data and propose experiments."

## MCP Integration

These agents work great with [Claude's Model Context Protocol (MCP)](https://docs.anthropic.com/claude/docs/model-context-protocol). Example combinations:

| Agent | MCP Server | Enhancement |
|-------|-----------|-------------|
| Backend Architect | Database MCP | Direct schema analysis |
| DevOps Automator | GitHub MCP | Automated PR reviews |
| Analytics Reporter | Database MCP | Real-time dashboards |

## Customization

These agents are starting points. Customize by:

1. **Adding company context** — Include your tech stack, brand voice
2. **Adjusting tone** — Make more formal or casual
3. **Expanding skills** — Add tools specific to your workflow
4. **Linking agents** — Update related agents for your team

## Contributing

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- Add new agents via pull request
- Improve existing agents with better prompts
- Fix issues and enhance documentation

## License

MIT License — See [LICENSE](LICENSE) for details.

---

**Created by [AI Agents Kit](https://aiagentskit.com)** — Your guide to building with AI agents.

⭐ Star this repo if you find it useful!

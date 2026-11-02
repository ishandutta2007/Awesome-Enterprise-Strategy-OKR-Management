# Awesome-Enterprise-Strategy-OKR-Management

# Awesome Enterprise Strategy & OKR Management

> A curated list of top Enterprise Strategy and OKR Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for self-hosted goal tracking and strategy execution.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Atlassian Focus](#atlassian-focus)
  - [Microsoft Viva Goals](#microsoft-viva-goals)
  - [WorkBoard](#workboard)
  - [Quantive (Gtmhub)](#quantive-gtmhub)
  - [Weekdone](#weekdone)
  - [Profit.co](#profitco)
  - [Lattice](#lattice)
  - [Perdoo](#perdoo)
  - [Asana Goals](#asana-goals)
- [Open-Source Software](#-open-source-software)
  - [Operately](#operately)
  - [BurningOKR](#burningokr)
  - [okr2go](#okr2go)
  - [Open OKR](#open-okr)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Enterprise Strategy and OKR Management platforms. These are not open-source but are included as reference points for feature comparison.

### Atlassian Focus
**Type:** Strategy and OKR management integrated with Jira  
A centralized platform for strategic management of business objectives, budgets, and resources. OKR tracking is hierarchical across all organizational levels, with direct integration to Jira showing which teams are contributing to which strategic objectives. Progress is visualized on dashboards and can be updated manually or via linked Key Results. For large organizations, Focus supports combining OKRs (for agility) with balanced scorecards (for long-term stability) [citation:1][citation:13].  
**Best for:** Organizations already using Jira and Confluence that want OKRs tightly connected to daily work.

### Microsoft Viva Goals
**Type:** OKR platform within Microsoft Viva suite  
Helps align teams using the OKR framework by connecting them to organizational strategic priorities. Features include OKR creation, check-ins, progress tracking, scoring, and closing, with configurable OKR time periods and model settings. Integrates across Microsoft 365 and other tools via the Viva Goals integrations overview [citation:2].  
**Best for:** Microsoft 365-centric organizations wanting OKR management native to the Viva employee experience platform.

### WorkBoard
**Type:** AI-native strategy execution platform  
Connects strategy pillars, outcomes, investments, and assumptions, with agent-orchestrated OKR cycles and AI-assisted OKR creation. Provides a single pane of glass from strategy to execution covering outcomes, OKRs, portfolios, initiatives, projects, people, and spend. Includes Portfolio Analyst Agent for real-time insight and automated MBRs, scorecards, and QBR materials. Gartner reviewers highlight friendly UX with drag-and-drop OKR creation from planning modules and semi-automated QBRs [citation:3].  
**Best for:** Enterprises seeking an AI-native platform that connects strategy, OKRs, and portfolio execution with automated business reviews.

### Quantive (Gtmhub)
**Type:** Strategy execution and OKR platform  
Quantive Results supports OKR management with unique Whiteboards for collaborative drafting and alignment. Users can brainstorm ideas, import existing OKRs, convert notes to Objectives, drag-and-drop alignments, and publish directly from the whiteboard to any session. The platform reports 500,000+ users, 2,000+ organizations, and 160+ software integrations [citation:4][citation:15]. Formerly Gtmhub, the platform also supports tags for secondary OKR organization and planning sessions for time-based goal grouping [citation:5].  
**Best for:** Teams wanting collaborative, visual OKR planning alongside standard OKR tracking.

### Weekdone
**Type:** OKR and weekly reporting platform  
Combines quarterly OKRs with weekly progress, plans, and problems (PPP) reporting. Features hierarchical goal trees from company to individual, KPI tracking, happiness ratings and pulse surveys, and automated weekly reports delivered via email, mobile, and web. Includes a lightweight task manager and integrations with Jira and Asana [citation:6].  
**Best for:** Teams wanting OKRs combined with structured weekly reporting and employee pulse checks.

### Profit.co
**Type:** OKR and strategy execution platform  
Supports OKRs, Balanced Scorecard, and Strategy Roadmaps. Recent updates include department-level visibility defaults, Risks & Issues Management at the Key Result level, KPI Summary views across hierarchy levels, and financial reporting widgets in PPM Cockpit. Also includes performance management features like peer reviewer restrictions and goal import with user validation [citation:7].  
**Best for:** Organizations wanting OKRs integrated with balanced scorecard, project portfolio management, and performance reviews.

### Lattice
**Type:** People management platform with OKRs  
Integrates OKRs and Goals within a broader performance management suite. Recent updates include a modernized OKR side panel with clearer hierarchy, expanded controls for editing and updating progress without leaving the panel, and streamlined goal completion. Also provides analytics visualizations for goal updates across employees [citation:8].  
**Best for:** HR-led organizations wanting OKRs embedded within performance reviews, feedback, and people analytics.

### Perdoo
**Type:** OKR and strategy execution platform  
Focuses on program health with an Engagement Dashboard available on Premium and Supreme plans. Tracks Health Score (1–100), goal statistics (OKRs without Key Results, unaligned OKRs, goals out of date), User Reviews streaks, goal update consistency, Pulse survey sentiment, and platform login engagement. Includes nudge functionality to encourage participation [citation:9].  
**Best for:** OKR program managers and Chiefs of Staff who need visibility into adoption and engagement health.

### Asana Goals
**Type:** OKR features within Asana work management  
Provides basic OKR management including time periods, linking related work (opportunities), metrics, owner, and accountable team. Gartner reviewers note that status updating can be confusing—progress updates and status updates are separate actions, leading users to put updates in comments instead. Asana recently updated the UI, but reviewers still find the status update flow unintuitive [citation:10].  
**Best for:** Teams already using Asana for project management who want lightweight goal tracking without a separate tool.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Strategy and OKR Management platforms. All listed projects offer source code you can deploy on your own infrastructure.

### Operately
**Stack:** TypeScript / React / PostgreSQL | **License:** Apache 2.0  
An open-source company operating system with built-in Goals/OKRs, project management, team spaces, message boards, and documents. Positioned as an opinionated alternative to Notion or ClickUp, with proven workflows for goal reviews, project check-ins, and accountability processes. Features include execution cadence with automated progress updates, flat-rate pricing with no per-seat fees, and CLI/API access with published Agent Skills for Codex and Claude Code. Deploys via a single-host tarball with Docker Compose [citation:12].  
**Best for:** Startups and teams of 5–100 wanting an open-source operating system that combines OKRs, projects, and team coordination without per-seat pricing.

### BurningOKR
**Stack:** (Check repository) | **License:** Open Source (per GitHub)  
An open-source OKR management software listed among related OKR projects. The project appears to have been updated approximately 2 years ago based on related repository listings [citation:11].  
**Best for:** Teams wanting a basic open-source OKR tracker; verify maintenance status before committing.

### okr2go
**Stack:** Markdown-based | **License:** Open Source  
A simple local OKR tracker using a Markdown file. No server or database required—just a text file for tracking Objectives and Key Results. Listed with 52 stars and updated in the last year [citation:11].  
**Best for:** Individuals or very small teams wanting zero-infrastructure OKR tracking in plain text.

### Open OKR
**Stack:** (Check repository) | **License:** Open Source (per GitHub)  
Listed as an open-source API-first CMS solution for managing and integrating OKRs into applications. Updated approximately 2 years ago with 67 stars [citation:11].  
**Best for:** Developers wanting to integrate OKR data into custom applications via an API-first approach.

---

## 📊 Comparison at a Glance

| Software | License | Type | AI Features | Self-Hosted | Best For |
|----------|---------|------|-------------|-------------|----------|
| **Atlassian Focus** | Proprietary | OKR + Jira integration | Limited | ❌ | Jira-centric organizations |
| **Viva Goals** | Proprietary | OKR within M365 | Limited | ❌ | Microsoft 365 enterprises |
| **WorkBoard** | Proprietary | AI-native strategy execution | ✅ (Agents) | ❌ | Strategy-to-execution at scale |
| **Quantive** | Proprietary | OKR + Whiteboards | Limited | ❌ | Collaborative OKR planning |
| **Weekdone** | Proprietary | OKR + weekly reporting | ❌ | ❌ | OKRs + team reporting cadence |
| **Profit.co** | Proprietary | OKR + BSC + PPM | Limited | ❌ | OKR + balanced scorecard + PPM |
| **Lattice** | Proprietary | OKR + performance mgmt | ❌ | ❌ | HR-led OKR + reviews |
| **Perdoo** | Proprietary | OKR + engagement analytics | ❌ | ❌ | OKR program health tracking |
| **Asana Goals** | Proprietary | Lightweight OKR in Asana | ❌ | ❌ | Existing Asana users |
| **Operately** | Apache 2.0 | Company OS + OKRs | ✅ (CLI/API agents) | ✅ | Open-source OKR + projects |
| **BurningOKR** | Open Source | OKR management | ❌ | ✅ | Basic OSS OKR (check activity) |
| **okr2go** | Open Source | Markdown OKR tracker | ❌ | ✅ (file) | Zero-infra personal OKRs |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Enterprise Strategy or OKR Management platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐

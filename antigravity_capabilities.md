# Antigravity Workspace Capabilities: MCP Servers & Skills

This document serves as a comprehensive reference for all the specialized Model Context Protocol (MCP) servers and Skills currently loaded in your Antigravity environment.

> [!NOTE]
> **Last updated:** March 2026. Added 38 new skills from GitHub (Anthropics official, obra/superpowers, AgriciDaniel/claude-seo, and community skills).

---

## 🔌 MCP Servers

MCP servers bridge your environment with external platforms, databases, and local advanced tools.

| MCP Server | Integration / Tool | Primary Use Cases |
| :--- | :--- | :--- |
| **companies-house** | UK Companies House API | Search UK companies, retrieve full incorporation details, get financial filings/statements, and find current or past officers/directors. |
| **notebooklm** | Google NotebookLM | Programmatically create notebooks, upload sources (PDFs, Drive files, URLs), conduct AI research, and generate Studio artifacts (podcasts, slide decks, study guides). |
| **pdf-reader** | Local File System | Extract metadata, pull raw text (with optional cleaning), and perform precise text searches across extensive local PDF documents. |
| **magic** | 21st.dev UI Library | Find, import, and refine React/Next.js UI components. Inject high-quality company logos (JSX, TSX, SVG) directly into your codebase. |

---

## 🧠 Built-In Skills

Skills are specialized instructional frameworks that provide deep expertise in specific domains.

### 1. Conversion Rate Optimization (CRO) & Product Flows
* **ab-test-setup**: Plan A/B and multivariate tests to measure if changes improve conversions.
* **churn-prevention**: Design offboarding exit flows, save offers, and "failed payment" recovery sequences to retain users.
* **form-cro**: Optimize non-signup forms (lead capture, contact us, demo requests) to reduce friction.
* **onboarding-cro**: Re-engineer the post-signup "first run" experience to activate users faster and show them value early.
* **page-cro**: Audit and optimize standard marketing pages (Home, Pricing, Features) specifically to increase signups/purchases.
* **paywall-upgrade-cro**: Optimize in-app prompts, limits, and upsell screens to convert free/trial users into paid subscribers.
* **popup-cro**: Design conversion-focused exit-intent popups, slide-ins, and notification banners.
* **signup-flow-cro**: Streamline account creation and trial registration flows to minimize abandoned signups.

### 2. Copywriting & Content Creation
* **ad-creative**: Generate and iterate bulk ad copy (headlines, primary text) for paid channels like Facebook, Google, and LinkedIn.
* **competitor-alternatives**: Craft targeted "Us vs. Them" comparison pages and competitor teardowns to win over comparison-shoppers.
* **content-strategy**: Plan high-level blog topics, editorial calendars, and content pillars for inbound marketing.
* **copy-editing**: Review and tighten up existing text to make it punchier and less wordy.
* **copywriting**: Write persuasive net-new marketing copy for websites, hero sections, value propositions, and calls-to-action.
* **social-content**: Ideate and format content tailored for organic social platforms (Twitter/X threads, LinkedIn posts).

### 3. SEO & Site Architecture
* **ai-seo**: A modern SEO approach aimed at getting your product cited in AI-generated answers (ChatGPT, Perplexity, Google AI Overviews).
* **programmatic-seo**: Strategize the creation of hundreds of template-driven pages targeting specific data-points or locations.
* **schema-markup**: Write JSON-LD structured data so search engines can parse your content and show rich snippets (e.g., star ratings).
* **seo-audit**: Diagnose technical SEO issues, indexing errors, and Core Web Vitals to explain why a site isn't ranking well.
* **site-architecture**: Map out website hierarchy, navigation menus, and internal linking strategies before building.

### 4. Marketing Strategy & Operations
* **analytics-tracking**: Establish Google Analytics (GA4), tag managers, and event tracking to measure marketing effectiveness.
* **free-tool-strategy**: Plan "engineering-as-marketing" campaigns (like calculators or free graders) to generate leads.
* **launch-strategy**: Prepare go-to-market plans for product launches, Beta invites, and platform (e.g., Product Hunt) debuts.
* **marketing-ideas**: Brainstorm creative growth tactics when looking for new ways to promote a project.
* **marketing-psychology**: Apply cognitive biases and behavioral science (like anchoring, social proof, and loss aversion) to strategy.
* **paid-ads**: Advise on strategy, targeting, Return on Ad Spend (ROAS), and budgeting for paid media campaigns.
* **pricing-strategy**: Help determine plan pricing, packaging tiers, freemium viability, and value metrics.
* **product-marketing-context**: Establish your exact Ideal Customer Profile (ICP) and positioning to maintain context across tasks.
* **referral-program**: Design affiliate systems and viral loops to playfully incentivize existing users to bring in new ones.

### 5. Sales & Email Outreach
* **cold-email**: Write B2B cold outreach campaigns designed specifically to get replies from prospects.
* **email-sequence**: Map out automated lifecycle/drip emails (welcome sequences, re-engagement campaigns) for your database.
* **revops**: Optimize "Revenue Operations", including lead scoring, CRM data hygiene, and the marketing-to-sales pipeline handoff.
* **sales-enablement**: Create assets for sales reps to use on calls (pitch decks, objection-handling cheat sheets, demo scripts).

### 6. AI Automation & UI Tooling
* **nlm-skill**: Guides automation workflows specifically utilizing the NotebookLM CLI (`nlm`).
* **notebooklm-mcp-skill**: The direct operating skill that teaches the agent how to effectively link user prompts to the `notebooklm` MCP tools.
* **ui-ux-pro-max**: A massive design-intelligence repository containing 50 styles, 50 font pairings, palettes, and layouts to ensure the code written looks visually premium.

### 7. Accounting, Legal & Cross-Border Tax (Lanzarote Workspace Only)
*Note: These distinct skills are isolated and only load when actively working inside the `D:\DAD\UK_Lanzarote_Repatriation` project folder.*
* **fx-risk-adviser**: Assists with mitigating currency exchange risks when repatriating property sale funds from Euros to GBP.
* **iht-calculator**: Calculates potential Inheritance Tax (IHT) implications on capital and family assets.
* **mvl-process-tracker**: Manages and tracks the complex steps of a Members' Voluntary Liquidation (MVL) to efficiently extract cash upon company closure.
* **spanish-property-compliance**: Specific handler for Spanish tax laws, Capital Gains Tax calculations on foreign properties, and local compliance.
* **uk-cross-border-tax-adviser**: Navigates double-taxation treaties between Spain and the UK, advising on offsetting foreign taxes against domestic UK tax burdens.
* **uk-private-client-solicitor**: Gives private client legal guidance regarding share ownership structures, trust implications, and tax-efficient capital distributions.

---

## 🆕 GitHub Skills (Installed March 2026)

These 38 additional skills were installed from GitHub into `C:\Users\Dean Harrison\.claude\claude_skills` and are available globally across all workspaces.

### Document & File Processing (from `anthropics/skills`)

| Skill | Trigger | Capability |
| :--- | :--- | :--- |
| **pdf** | Mention any `.pdf` file or PDF task | Read, extract text/tables, merge, split, watermark, create, fill forms, encrypt, OCR scanned PDFs. |
| **docx** | Mention `.docx`, Word document tasks | Create, edit, and analyze Word documents with proper styles, tables, images, headers/footers, TOC, tracked changes. |
| **xlsx** | Mention `.xlsx`, Excel, spreadsheet tasks | Create and edit Excel files using real formulas (not hardcoded values), pivot tables, financial models with colour-coded standards. |

### Frontend Design & UI (from `anthropics/skills`)

| Skill | Trigger | Capability |
| :--- | :--- | :--- |
| **frontend-design** | Ask to build a web page, component, or UI | Production-grade frontend code with deliberately non-generic aesthetics — distinctive typography, colour, motion design. Avoids "AI slop". |
| **canvas-design** | Ask for a poster, artwork, or visual design | Creates `.png` and `.pdf` visual art using a "design philosophy" approach. Never copies existing artists' work. |
| **web-artifacts-builder** | Ask for a complex interactive React artifact | Builds multi-component React + Tailwind + shadcn/ui apps, bundles them into a single shareable HTML artifact. |

### Skill Meta-Tools (from `anthropics/skills`)

| Skill | Trigger | Capability |
| :--- | :--- | :--- |
| **skill-creator** | "Create a new skill", "modify an existing skill", "eval this skill" | Full lifecycle: interview → draft SKILL.md → run evals → benchmark → optimise description triggering. |
| **doc-coauthoring** | "Help me write a doc", "draft a proposal/spec" | Structured 3-stage co-authoring: context gathering → iterative drafting → reader-testing with subagents. |

### Agentic Development (from `obra/superpowers`)

| Skill | Trigger | Capability |
| :--- | :--- | :--- |
| **brainstorming** | "Let's brainstorm", "I need ideas about…" | Visual, interactive brainstorming canvas with a live server. Produces structured idea maps. |
| **dispatching-parallel-agents** | Complex tasks amenable to parallelism | Orchestrates spawning and managing multiple Claude subagents to work in parallel on a single large task. |
| **executing-plans** | "Execute this plan", "implement the spec" | Structured plan execution: verify → implement step-by-step → confirm each step before proceeding. |
| **finishing-a-development-branch** | "Finish this branch", "get PR-ready" | Prepares a Git branch for merging: linting, testing, commit cleanup, PR description writing. |
| **receiving-code-review** | "Address review comments", "handle PR feedback" | Processes reviewer comments systematically: acknowledge → categorise → implement → respond. |
| **requesting-code-review** | "I need a code review" | Prepares code for review, runs a built-in AI code reviewer sub-agent, consolidates feedback. |
| **subagent-driven-development** | "Build [feature] using SDD" | SDD methodology: spec → parallel implementation subagents → spec-reviewer → integration. |
| **systematic-debugging** | "Debug this", "find the root cause" | Root-cause tracing using defence-in-depth, condition-based waiting, binary search isolation. |
| **test-driven-development** | "Write tests first", "TDD approach" | Full TDD cycle with anti-pattern guidance and common pitfall avoidance. |
| **using-git-worktrees** | "Use git worktrees", "parallel branches" | Manages Git worktrees for running multiple branches simultaneously without stashing. |
| **using-superpowers** | "What superpowers do I have?" | Meta-guide explaining how to leverage the full superpowers skill framework. |
| **verification-before-completion** | Before marking any task done | Structured checklist to verify work is genuinely complete before reporting success. |
| **writing-plans** | "Write a plan for…", "create a spec" | Produces structured plan documents with clear phases, acceptance criteria, and risk notes. |
| **writing-skills** | "Write a new skill", "improve this skill" | Deep guide for authoring effective SKILL.md files using Anthropic best-practices and persuasion principles. |

### Advanced SEO Suite (from `AgriciDaniel/claude-seo`)

| Skill | Trigger | Capability |
| :--- | :--- | :--- |
| **seo** | Master SEO orchestrator | Routes to the right sub-skill and coordinates multi-skill SEO campaigns end-to-end. |
| **seo-audit** | "Audit my SEO", "why isn't my site ranking?" | Full technical SEO audit: crawlability, indexing, Core Web Vitals, meta, heading structure. |
| **seo-content** | "Write SEO content for…" | Produces E-E-A-T-optimised articles and landing page copy aligned to keyword intent. |
| **seo-competitor-pages** | "Compare us to [Competitor]" | Creates "/alternatives" and "X vs Y" pages optimised to capture competitor-aware traffic. |
| **seo-geo** | "SEO for [country/region]" | Geo-targeted SEO including hreflang planning, local keyword targeting, and regional SERP differences. |
| **seo-hreflang** | "Set up hreflang", "multi-language SEO" | Generates and validates the correct `hreflang` implementation for international sites. |
| **seo-images** | "Optimise my images for SEO" | Alt text, file naming, structured data for images, lazy loading, and next-gen format guidance. |
| **seo-local** | "Local SEO for [business]" | Google Business Profile optimisation, local schema, citation building, and proximity signals. |
| **seo-page** | "Optimise this page for SEO" | On-page SEO: title tags, meta descriptions, heading hierarchy, keyword density, internal links. |
| **seo-plan** | "Create an SEO strategy for…" | Strategic SEO roadmap templates for 6 business types: SaaS, eCommerce, local, publisher, agency, generic. |
| **seo-programmatic** | "Build programmatic SEO pages" | Template-driven page generation at scale: integration pages, location pages, comparison pages. |
| **seo-schema** | "Add schema markup", "structured data" | JSON-LD schema generation: Article, Product, Review, FAQ, HowTo, LocalBusiness, BreadcrumbList. |
| **seo-sitemap** | "Create a sitemap strategy" | Sitemap planning, priority scoring, and generation guidance for large and complex sites. |
| **seo-technical** | "Fix technical SEO issues" | Deep technical: robots.txt, canonical tags, redirect chains, HTTPS, page speed, CWV remediation. |

### Research & Context Engineering (Community)

| Skill | Source | Trigger | Capability |
| :--- | :--- | :--- | :--- |
| **deep-research** | `199-biotechnologies` | "Deep research on…", "comprehensive analysis of…" | Enterprise-grade research pipeline: multi-source retrieval → triangulation → synthesis → McKinsey-style HTML/PDF report with full citations. Modes: quick (3 min), standard (10 min), deep (20 min), ultradeep (45 min). |
| **context-engineering** | `muratcankoylan` | "Help me architect my agent's context", "multi-agent memory systems" | Collection of 10+ sub-skills covering context fundamentals, compression, memory systems, multi-agent patterns, hosted agents, tool design, BDI mental states, and evaluation frameworks. |

---

## 🛠️ How to Use Skills

You do not need to type any special commands or complex prompts to use these skills. The system is designed to **automatically detect** when a skill is needed based on your request.

### 1. Just Ask Naturally (Recommended)
Simply describe your goal, and the most relevant skill will automatically activate.
* *"Can you review the pricing page on my website and tell me why it isn't converting?"* ➡️ Automatically triggers **`page-cro`** and **`pricing-strategy`**.
* *"I need to write a 4-part welcome email series for new signups."* ➡️ Automatically triggers **`email-sequence`**.
* *"Help me come up with 10 Facebook ad headlines for a dog walking app."* ➡️ Automatically triggers **`ad-creative`**.
* *"Read this PDF and extract the financial tables."* ➡️ Automatically triggers **`pdf`**.
* *"Debug why this function keeps failing."* ➡️ Automatically triggers **`systematic-debugging`**.
* *"Deep research on AI assistant market trends 2025."* ➡️ Automatically triggers **`deep-research`**.

### 2. Explicitly Request a Skill
If you want to ensure a specific framework is used, you can mention the skill by name in your prompt.
* *"Please use the **`seo-audit`** skill to review my website's technical health."*
* *"Let's run the **`systematic-debugging`** skill on this error."*
* *"Use **`subagent-driven-development`** to build this feature."*

> [!TIP]
> **Starting a new marketing project?** Begin by saying: *"Let's run the **`product-marketing-context`** skill."* This establishes a foundational profile of your product and target audience. The agent will save this context, ensuring all subsequent marketing tasks are perfectly aligned with your brand positioning!

> [!TIP]
> **Need production-quality code or design?** Use **`frontend-design`** for web UIs (avoids generic AI aesthetics) or **`canvas-design`** for posters and visual assets. Pair with **`web-artifacts-builder`** for complex interactive React applications.

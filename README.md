# Hi, I'm Ohm (Mingrath)

**Building open-source tools for the Claude Code ecosystem** | Vet turned developer | Bangkok

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

## Claude Code Ecosystem Tools

I build open-source tools that make Claude Code better for everyone.

| Project | What it does |
|---------|-------------|
| [**claude-code-statusline**](https://github.com/mingrath/claude-code-statusline) | Real-time rate limit %, context window %, session cost, and git status in your statusline |
| [**claude-code-notify**](https://github.com/mingrath/claude-code-notify) | Push notifications to Mac, iPhone, and Apple Watch when Claude Code needs input |
| [**drawio-mcp**](https://github.com/mingrath/drawio-mcp) | MCP server for creating draw.io diagrams from LLMs — XML, Mermaid, and CSV |
| [**awesome-claude-skills**](https://github.com/mingrath/awesome-claude-skills) | Curated list of 100+ Claude Code skills across dev, data, DevOps, and more |

## AI Agent Frameworks

Reusable patterns and templates extracted from production AI systems I've built.

| Project | What it does |
|---------|-------------|
| [**soul-agent-framework**](https://github.com/mingrath/soul-agent-framework) | Configure AI agents through markdown, not code — SOUL/MEMORY/skills architecture |
| [**ai-expert-chatbot**](https://github.com/mingrath/ai-expert-chatbot) | Deploy a domain-expert AI chatbot in minutes — RAG + SSE streaming + webchat |
| [**agent-factory**](https://github.com/mingrath/agent-factory) | Spin up fully-deployed AI agents for any domain in under 2 minutes |
| [**openclaw-actual-budget**](https://github.com/mingrath/openclaw-actual-budget) | AI agent template — receipt scanning + expense tracking via Telegram + Actual Budget |
| [**telegram-order-dashboard**](https://github.com/mingrath/telegram-order-dashboard) | Telegram bot + zero-dependency Python dashboard for small business order management |

## Veterinary AI

I'm a licensed veterinarian (Chulalongkorn University DVM) building AI tools for animal healthcare — a domain with almost no existing AI tooling.

| Project | What it does |
|---------|-------------|
| [**vetblood-ai**](https://github.com/mingrath/vetblood-ai) | AI-powered animal blood test analyzer for vet clinics — Gemini 3 Hackathon |
| [**tenacitOS**](https://github.com/mingrath/tenacitOS) | Mission control dashboard for monitoring and managing AI agent fleet |

## Hackathons & Competitions

### Super AI Engineer Season 6 — Election OCR (March 2026)

**[GitHub](https://github.com/mingrath/election-ocr-hackathon)** | **[Kaggle Competition](https://www.kaggle.com/competitions/super-ai-engineer-season-6-ocr-2569)** | **Rank: #53** (private leaderboard, jumped +16 spots) | **Score: 0.1587**

Extracted structured voting data from 846 scanned Thai election result documents (Form สส.6/1) from the 2026 general election. Built a multi-model OCR pipeline with AI-powered assembly logic.

**How we built it:**
- **Pipeline:** 846 PNG scans → multi-model OCR → fuzzy party-name assembly → structured CSV
- **OCR stack:** Gemini 3 Flash + Gemini 2.5 Pro + Gemini 2.5 Flash, merged with official กกต. election data
- **Key technique:** Template-based party-name alignment instead of ballot-number mapping — solved the offset bug where 22+ docs had shifted ballot numbers
- **Evaluation:** Built a local TDD eval system (8 tests), but learned that 5-doc local eval had zero correlation with Kaggle — only empirical Kaggle testing worked
- **Iterations:** 16 Kaggle submissions, 6+ submission strategies, 900 OCR API calls (3-pass overnight run)
- **Score journey:** 0.929 → 0.307 → 0.228 → 0.158 (each jump from fixing a different root cause)
- **Tools:** Claude Code with `/loop` for 8+ hours of autonomous overnight monitoring

### MiroFish — Vibe Coding Impact Simulation (March 2026)

Used [MiroFish](https://github.com/666ghj/MiroFish) (a multi-agent swarm intelligence engine) to simulate whether "vibe coding" would create a developer demand boom or bust over 2026-2028.

**Simulation specs:**
- **168 rounds**, **40 AI agents**, **1,484 total actions**
- Agents represented startup founders, security engineers, rescue engineers, AI tool companies, regulators, and Thai SMEs
- Each agent had independent personality, long-term memory (Zep), and behavioral logic
- Seed data included 50+ real research citations (NYU, Stanford, Veracode, IBM breach reports)

**Key finding:** Developer demand **bifurcates** — senior security/rescue engineers see surging demand while junior prompt-only developers face commoditization. Not a uniform boom or bust, but a split.

## Background

- **Doctor of Veterinary Medicine** — Chulalongkorn University, former veterinary neurosurgeon
- **Self-taught developer** — shipped 30+ projects with TypeScript, Python, Next.js, and Claude
- **Daily Claude Code user** — building tools to improve the developer experience for the community

## Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/mingrath)

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mingrath)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mingrath@gmail.com)

# Hi, I'm Ohm (Mingrath)

**Machine learning & AI engineer — veterinary surgeon turned developer** | Bangkok

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)

---

## What I do now

**AI Engineer Intern at AXONS (CP Group)**, working on AI and NLP engineering.

I came to machine learning from veterinary neurosurgery — DVM and MSc
(First-Class Honours) from Chulalongkorn University, eight years of clinical
specialty practice, a published implant-biomechanics paper, and two years
coordinating bioequivalence studies under ICH-GCP for Thai FDA submissions.
What that background gives me is not a shortcut to ML: it is a hard-wired
instinct for evaluation discipline — controls, pass bars fixed before the run,
uncertainty quantification, and refusing to believe a number whose provenance
I cannot trace.

I retrained through **Super AI Engineer Season 6** (Artificial Intelligence
Association of Thailand) — a seven-month national program covering classical
machine learning, computer vision, statistics, and building an LLM from
scratch — completed alongside part-time clinical work.

> **A note on links:** most of the projects below live in private
> repositories. The two public ones are linked; the rest are named and
> described but not linked, because a 404 helps nobody. Happy to walk through
> any of them.

---

## Machine learning

**[equity-return-ranking](https://github.com/mingrath/equity-return-ranking)** —
Cross-sectional equity return ranking over a frozen 30-stock US panel, with a
deterministic paper-only replay. *Places no orders and claims no
profitability.* The point of the project is the evaluation discipline:

- Expanding walk-forward folds with **purge and embargo**; train-fold-only preprocessing
- One 2025 holdout year, revealed exactly once, after model selection was frozen
- Baselines first (no-signal, momentum), then **Elastic Net** and **histogram gradient boosting**
- 2,000-sample **moving-block bootstrap**, robustness slices, cost sensitivity
- Realistic costs (1 bp fee + 5 bps slippage per side), immutable hash-named evidence packages, 53 tests, CI

**[cat-fgs-llm](https://github.com/mingrath/cat-fgs-llm)** — Feline Grimace
Scale pain scoring. The headline deliverable is not the classifier but a
**portable, power-aware confound-attribution protocol** for fine-grained
animal-affect models — a per-action-unit audit that validates on planted
positive *and* negative controls. Engine is a frozen DINOv2 ViT-S/14 with five
per-AU CORN heads. 16 architecture decision records, and a strict gate
run-order where no downstream number is believed until its gate passes. The
0–10 severity layer is marked *inspected-not-validated* and never emits a
validated-claim number.

---

## Competitions & applied ML

### Super AI Engineer Season 6 (AIAT)

**Election OCR** — Structured voting data extracted from 846 scanned Thai
election result documents (Form สส.6/1) from the 2026 general election. A
multi-model OCR pipeline (Gemini 3 Flash + 2.5 Pro + 2.5 Flash) with
template-based party-name alignment, fuzzy assembly, and an 8-test local TDD
eval harness. 16 Kaggle submissions across 3 overnight runs, 900+ OCR API
calls, orchestrated with **Claude Code** `/loop` for autonomous monitoring.

**Parasite Egg Detection** — **YOLOv11m** object-detection model for
identifying parasite eggs in microscope smear images, fine-tuned with
paper-inspired hyperparameters and augmentation tuned for thick-smear
specimens.

**From Data to Insight** — Multi-branch time-series demand forecasting for a
coffee-house chain.

### Siriraj × MIT Hacking Medicine 2025

**3rd Place, Mental Health Track.**

---

## Simulation

### MiroFish — multi-agent "vibe coding" impact simulation

Used [MiroFish](https://github.com/666ghj/MiroFish) (a multi-agent swarm
intelligence engine) to model whether "vibe coding" produces a developer-demand
boom or bust across 2026–2028.

- **168 rounds**, **40 agents**, **1,484 total actions**
- Agents represented startup founders, security engineers, rescue engineers, AI tool companies, regulators, and Thai SMEs
- Each agent carried an independent personality, long-term memory (Zep), and behavioural logic
- Seeded with 50+ real research citations (NYU, Stanford, Veracode, IBM breach reports)

**Key finding:** developer demand **bifurcates** — senior security and rescue
engineers see surging demand while junior prompt-only developers face
commoditization. Not a uniform boom or bust, but a split.

---

## Veterinary AI

A licensed veterinarian building AI for animal healthcare — a domain with
almost no existing AI tooling.

| Project | What it does |
|---------|-------------|
| **vetblood-ai** | AI-powered animal blood test analyzer for Thai vet clinics — Gemini 3 Hackathon |
| **Clinical AI assistant** | Deployed at a Thai animal hospital — SOAP generator, CEO dashboard, and LINE chatbot in one stack |
| **Veterinary knowledge graph** | Graph-first vet knowledge base — replaces a free-text reference with structured, queryable relationships |
| **Pet owner member portal** | Thai vet hospital member portal — vaccine history, appointments, and loyalty points |

---

## Claude Code ecosystem tools

Open-source tooling that makes **Claude Code** better for everyone.

| Project | What it does |
|---------|-------------|
| **claude-code-statusline** | Real-time rate limit %, context window %, session cost, and git status in your statusline |
| **claude-code-notify** | Push notifications to Mac, iPhone, and Apple Watch when Claude Code needs input |
| **drawio-mcp** | MCP server for creating draw.io diagrams from LLMs — XML, Mermaid, and CSV |
| **awesome-claude-skills** | Curated list of 100+ Claude Code skills across dev, data, DevOps, and more |
| **ai-anti-hallucination** | Anti-hallucination rules for AI coding agents |

## AI agent frameworks

Reusable patterns extracted from production AI systems I've built.

| Project | What it does |
|---------|-------------|
| **soul-agent-framework** | Configure AI agents through markdown, not code — SOUL/MEMORY/skills architecture |
| **agent-factory** | Spin up fully-deployed AI agents for any domain in under 2 minutes |
| **agency-orchestrator** | Multi-agent tmux orchestrator for Claude Code — 167 specialized agents in visible parallel waves (Research → Build → QA) |
| **arena-workflow** | Competitive multi-model dispatch — every task gets every model, evidence picks the winner |
| **openclaw-actual-budget** | AI agent template — receipt scanning and expense tracking via Telegram + Actual Budget |
| **obsidian-ai-knowledge-agent** | AI agent for Obsidian — Second Brain, Personal Search Engine, AI Coding Vault, Karpathy LLM Wiki |

---

## Also: web development

I run a small Thai SME web agency on the side — **20+ sites shipped across 7
industries** (vet clinics, industrial B2B, hospitality, services,
construction), and I'm consolidating that work into a multi-tenant CMS. It is
where I learned to ship and maintain software for people who will never read a
changelog.

---

## Background

- **DVM** and **MSc Veterinary Surgery** (First-Class Honours, GPA 3.95) — Chulalongkorn University
- **Former veterinary neurosurgeon** — spinal-injury and epilepsy caseload; published implant-fatigue biomechanics research
- **Medical writer & clinical research coordinator** — bioequivalence studies under ICH-GCP for Thai FDA submissions
- **Super AI Engineer S6** (AIAT) — seven-month national AI program
- I write about ML, local LLMs, and agent design at [mingrath.com](https://mingrath.com)

## Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/mingrath)

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mingrath)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mingrath@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mingrath)

<a href="https://gitroll.io/profile/uW4TR3MvHWpeZ3FpQoh17rmwnUQN2" target="_blank"><img src="https://gitroll.io/api/badges/profiles/v1/uW4TR3MvHWpeZ3FpQoh17rmwnUQN2?theme=dracula" alt="GitRoll Profile Badge"/></a>

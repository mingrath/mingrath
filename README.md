# Hi, I'm Ohm (Mingrath) 👋

---

🐱 **Cat Vet Who Loves Code** | 🧠 **Ex-Neurovet Surgeon** | 🚀 **Building AI for SMEs** | 🎓 **Chulalongkorn DVM**

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Astro](https://img.shields.io/badge/-Astro-BC52EE?style=flat-square&logo=astro&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> From the operating table to the terminal — a veterinary neurosurgeon turned software developer, building AI-powered tools that help small businesses and vet clinics work smarter.

## Projects

### 🤖 AI Agents & OpenClaw

> A personal AI agent framework where multiple autonomous agents run 24/7 — chatting with customers on LINE, managing finances on Telegram, generating images, and checking in proactively via heartbeats.

- 🐾 **OpenClaw** `private` – Multi-agent AI framework with persistent identity and long-term memory. Runs as a systemd gateway service with auto-restart. Features include:
  - **5 project agents** — each with their own workspace, personality (SOUL.md), and memory system
  - **4 chat integrations** — Telegram (2 bots), Discord, LINE OA, and Slack (Socket Mode) — all live and receiving messages
  - **7 shared skills** — ComfyUI image generation, RAG/ChromaDB knowledge retrieval, FFmpeg video editing, web dashboard, skill creator, receipt parser, and budget query
  - **Heartbeat system** — proactive scheduling that checks email, calendar, and notifications without being asked
  - **Bucky** — personal finance agent on Telegram that parses Thai bank slip photos (SCB, KBank, KTB, KTC, BB, PromptPay) via vision OCR and logs transactions to Actual Budget
  - **Team** — LINE OA chatbot for a client clinic with Thai-language RAG knowledge base for customer Q&A
  - Built with Claude Code, Python, Node.js, and Ollama for local LLM fallback
- 💰 **Actual Budget** `private` – Self-hosted personal finance server running on Docker with 10+ bank and brokerage accounts — connected to OpenClaw's Bucky agent for automated expense tracking via `@actual-app/api`
- 🧠 **[SMEAI](https://smeaithai.com)** — Thai-primary AI knowledge hub teaching SME owners how to adopt AI affordably. Articles, case studies, and video content with Pagefind search and Lighthouse 100/100 performance — built with Astro 5, Tailwind CSS v4, and Cloudflare Pages

### 🐾 Veterinary & Cats

- 🐱 **[MeowMed](https://mormeow.com)** `private` – Comprehensive cat health knowledge hub with 826+ vet articles across 21 categories, AI diagnostic chatbot, faceted search, life-stage guides, and hospital directory. Recently shipped v2.2 with full frontend revamp (navy-to-pink color system, Poppins font, Figma-accurate components) — built with Next.js 16, React 19, and Google AI SDK by a licensed DVM
- 🩸 **[vetblood-ai](https://github.com/mingrath/vetblood-ai)** – AI-powered animal blood test analyzer for Thai vet clinics using Google Gemini — Gemini 3 Hackathon project
- 🔬 **Vet Blood Tracker** `private` – Advanced blood test analysis platform with Tesseract OCR for lab report scanning, trend tracking, and Google Gemini 2.0 Flash interpretation — built with Next.js 16, Prisma, and SQLite
- 🏠 **Cat Adopt Questionnaire** `private` – Bilingual cat adoption screening app with personality matching quiz, 30+ question automated scoring, and admin dashboard — built with Next.js 16 and Supabase
- 🏥 **Web Clinic Demo** `private` – Veterinary clinic website with appointment booking, chatbot article integration via RAG, and warm-palette redesign — built with Next.js and TypeScript
- 🏥 **PawClinic Website** `private` – Veterinary clinic website with responsive design — built with Next.js 15 and Tailwind CSS 4

### 🔧 Claude Code & Open-Source Tools

> Open-source tools that make Claude Code's autonomous mode actually usable — know what's happening and get notified when it needs you.

- 📊 **[claude-code-statusline](https://github.com/mingrath/claude-code-statusline)** – Custom statusline showing real-time rate limit usage %, context window %, session cost, and git status with progress bars
- 🔔 **[claude-code-notify](https://github.com/mingrath/claude-code-notify)** – Push notifications to Mac, iPhone, and Apple Watch when Claude Code needs your input — via terminal-notifier + ntfy.sh + hooks
- 🎨 **[drawio-mcp](https://github.com/mingrath/drawio-mcp)** – MCP server enabling LLMs to create and open diagrams in draw.io — supports XML, CSV, and Mermaid formats
- ⭐ **[awesome-claude-skills](https://github.com/mingrath/awesome-claude-skills)** – Curated collection of 100+ Claude Skills covering dev tools, data analysis, business automation, and more

### 💻 Developer Tools & Apps

- 🧩 **Mind Odyssey** `private` – Interactive behavioral assessment platform with GSAP combat animations, life event phases, team vote collection, and clinical report generation with behavioral pattern analysis — built with Next.js, TypeScript, and Vercel
- 💰 **[expense-tracker](https://github.com/mingrath/expense-tracker)** – Personal expense tracking app built with Next.js and TypeScript
- ⛳ **[golf-handicap](https://github.com/mingrath/golf-handicap)** – Mobile-first PWA for pairwise handicap golf scoring with configurable handicaps, turbo holes, game history editing, and play-again config restore — built with Next.js 16, Zustand, and Tailwind CSS 4
- 🎬 **Video Production Tool** `private` – Automated video production and captioning pipeline using Remotion and Whisper.cpp for subtitle generation
- 📡 **Reddit Monitor** `private` – Reddit keyword monitoring and alert system for tracking topics and mentions
- 🕷️ **LBC Scraper** `private` – Web scraper with Next.js dashboard for data visualization — built with Python Scrapy and Next.js
- ⚖️ **Weight & Food Tracker** `private` – Health tracking app for daily weight and food intake monitoring with AI-powered meal suggestions, deployed and dogfooded with Playwright automation — built with Next.js 16

### 🌐 Web & Portfolio

- 🌍 **[mingrath.com](https://mingrath.com)** `private` – AI consultant portfolio with Laws of UX design principles — built with Next.js 15, Tailwind CSS 4, and shadcn/ui
- 📝 **Portfolio Blog** `private` – Personal portfolio and blog website built with Next.js, TypeScript, and MDX
- 🐱 **CatWhoCode** `private` – Web agency portfolio with blog, FAQ, process pages, GA4 event tracking, and GSAP scroll animations — built with Astro 5, TypeScript, and Tailwind CSS 4
- 🚀 **LeaniOS** `private` – Full-stack Next.js boilerplate with auth, user management, admin panel, and role-based access (Supabase) — my first vibe coding project, from my most loving mentor

## Background

- 🎓 **Doctor of Veterinary Medicine** — Chulalongkorn University
- 🧠 **Former veterinary neurosurgeon** — specialized in neurological cases in cats and dogs
- 💻 **Self-taught developer** — building full-stack apps with TypeScript, Next.js, and AI integrations
- 📍 **Based in Bangkok, Thailand**

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/mingrath)

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mingrath)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mingrath@gmail.com)
[![Line](https://img.shields.io/badge/-Line-00C300?style=flat-square&logo=line&logoColor=white)](https://line.me/ti/p/mingrath)

# NexaUX
next-generation UX intelligence 2026

<div align="center">

```
███╗   ██╗███████╗██╗  ██╗ █████╗ ██╗   ██╗██╗  ██╗
████╗  ██║██╔════╝╚██╗██╔╝██╔══██╗██║   ██║╚██╗██╔╝
██╔██╗ ██║█████╗   ╚███╔╝ ███████║██║   ██║ ╚███╔╝ 
██║╚██╗██║██╔══╝   ██╔██╗ ██╔══██║██║   ██║ ██╔██╗ 
██║ ╚████║███████╗██╔╝ ██╗██║  ██║╚██████╔╝██╔╝ ██╗
╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝
```

### *Next-Generation UX Intelligence — AI Prompt Library*

[![License: MIT](https://img.shields.io/badge/License-MIT-0f172a?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-6366f1?style=for-the-badge)](CHANGELOG.md)
[![Works With](https://img.shields.io/badge/Works%20With-Cursor%20%7C%20Copilot%20%7C%20Claude%20%7C%20Windsurf-10b981?style=for-the-badge)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-f59e0b?style=for-the-badge)](CONTRIBUTING.md)

<br/>

> **NexaUX** is a curated library of AI agent prompts that instruct any  
> AI-powered IDE to build, enhance, and optimize your website for you.  
> No manual coding. Just paste, run, and ship.

<br/>

[📖 How It Works](#-how-it-works) · [🧠 Prompt Library](#-prompt-library) · [⚡ Quick Start](#-quick-start) · [🤝 Contributing](#-contributing)

---

</div>

<br/>

## 💡 What is NexaUX?

NexaUX is **not a code library**. It is a **battle-tested collection of AI prompts** written specifically to instruct AI coding agents — like **Cursor**, **GitHub Copilot**, **Claude**, **Windsurf**, **Codeium**, and others — to do the heavy lifting for you.

Each prompt is a precise, opinionated brief that tells the AI agent exactly what to build, what statistics to follow, and how to enhance your existing website — layer by layer — without rebuilding it from scratch.

```
You write nothing.
You paste a prompt into your AI agent.
The agent writes your code.
You review, approve, and ship.
```

---

<br/>

## 🔧 How It Works

### Step 1 — Pick Your AI Agent

NexaUX prompts work with any of these:

| Agent | Where to Paste the Prompt |
|---|---|
| **Cursor** | `Ctrl+L` → Chat panel → Paste prompt |
| **GitHub Copilot** | Copilot Chat sidebar → Paste prompt |
| **Claude** | claude.ai or Claude in your IDE → Paste prompt |
| **Windsurf (Codeium)** | Cascade chat panel → Paste prompt |
| **Zed AI** | AI inline assistant → Paste prompt |
| **Any other AI IDE** | Open the chat / agent panel → Paste prompt |

### Step 2 — Open Your Project

Open your existing website project in your AI-powered IDE. The prompts are written to **enhance what you already have** — not replace it.

### Step 3 — Paste a Prompt

Choose a prompt from the library below, copy it, and paste it into your AI agent's chat. The agent reads your codebase and applies the changes automatically.

### Step 4 — Review & Ship

Review the AI's output, request adjustments if needed, and push to production.

---

<br/>

## 🧠 Prompt Library

All prompts live in the [`/prompts`](./prompts/) folder. Here is what's available:

---

### 🔑 Master Prompt — Full Enhancement (Start Here)
> Runs all 5 layers in sequence. Best for a full website upgrade.

📄 [`prompts/master-enhancement.md`](./prompts/master-enhancement.md)

```
Covers: Responsive design · AI personalization · Behavioral analytics ·
Feature prioritization · 11 CRO quick wins · 2025–2026 benchmark targets
```

---

### 📱 Layer 1 — Responsive Design Prompt
> Makes your site look and work perfectly on phone and desktop.

📄 [`prompts/layer-1-responsive.md`](./prompts/layer-1-responsive.md)

```
Covers: Mobile-first CSS · Fluid grids · Breakpoints · Sticky CTAs ·
Touch targets · Skeleton loaders · Digital wallet detection
```

---

### 🤖 Layer 2 — AI Personalization Prompt
> Instructs the agent to build a client-side personalization engine.

📄 [`prompts/layer-2-personalization.md`](./prompts/layer-2-personalization.md)

```
Covers: Device/time/visit signals · Dynamic hero swaps · CTA variants ·
Returning visitor mode · Segment self-selection · localStorage only
```

---

### 📊 Layer 3 — Behavioral Analytics Prompt
> Builds a zero-dependency, privacy-first analytics and heatmap system.

📄 [`prompts/layer-3-analytics.md`](./prompts/layer-3-analytics.md)

```
Covers: Scroll depth tracking · Click heatmaps · CTA performance ·
Exit-intent detection · Hidden dev dashboard (Shift+Alt+D)
```

---

### 🎯 Layer 4 — Feature Pulse Prompt
> Builds a data-driven feature prioritization widget.

📄 [`prompts/layer-4-feature-pulse.md`](./prompts/layer-4-feature-pulse.md)

```
Covers: Priority scoring algorithm · User upvoting · Trending badges ·
GitHub changelog panel · Feature engagement reports
```

---

### ⚡ Layer 5 — CRO Quick Wins Prompt
> 11 statistically proven improvements applied in one pass.

📄 [`prompts/layer-5-cro-quickwins.md`](./prompts/layer-5-cro-quickwins.md)

```
Covers: Above-fold CTAs · Social proof placement · Form autofill ·
Trust badges · Real-people imagery · Micro-copy rewrites · Video blocks
```

---

<br/>

## 📁 Repository Structure

```
nexa-ux/
│
├── 📂 prompts/
│   ├── master-enhancement.md         # 🔑 Full 5-layer prompt (start here)
│   ├── layer-1-responsive.md         # 📱 Responsive design
│   ├── layer-2-personalization.md    # 🤖 AI personalization engine
│   ├── layer-3-analytics.md          # 📊 Behavioral analytics + heatmaps
│   ├── layer-4-feature-pulse.md      # 🎯 Feature prioritization widget
│   └── layer-5-cro-quickwins.md      # ⚡ 11 proven CRO improvements
│
├── 📂 .github/
│   └── copilot-instructions.md       # Auto-feeds context to GitHub Copilot
│
├── 📂 docs/
│   ├── BENCHMARKS.md                 # Full 2025–2026 CRO statistics
│   └── HOW_TO_USE_WITH_CURSOR.md     # Step-by-step Cursor walkthrough
│
├── README.md                         # ← You are here
├── CHANGELOG.md
├── CONTRIBUTING.md
└── LICENSE
```

---

<br/>

## ⚡ Quick Start

```bash
# 1. Clone NexaUX
git clone https://github.com/mdabir1203/nexa-ux.git

# 2. Open the prompt you need
open prompts/master-enhancement.md

# 3. Copy the full prompt text

# 4. Open your website project in Cursor / Copilot / Claude / Windsurf

# 5. Paste into the AI agent chat and let it work
```

That's it. The AI agent does the rest.

---

<br/>

## 📊 What These Prompts Are Built Around

Every prompt in NexaUX is grounded in real 2025–2026 conversion rate science:

<details>
<summary>⚡ Speed & Performance Targets</summary>

| Stat | Benchmark |
|---|---|
| Sites loading ≤1s vs 5s | **3× higher conversion rate** |
| Users abandoning at 3s+ | **53% leave** |
| Per 1-second improvement | **+4–7% conversions** |

</details>

<details>
<summary>📱 Mobile Conversion Gap</summary>

| Stat | Benchmark |
|---|---|
| Mobile traffic share | **~65% of all visits** |
| Mobile conversion rate | **2.49%** |
| Desktop conversion rate | **5.06%** |
| Sticky CTA lift | **+12%** |
| Digital wallet buttons | **+21% mobile conversions** |

</details>

<details>
<summary>🤖 Personalization Lift</summary>

| Stat | Benchmark |
|---|---|
| Personalized vs generic | **Up to +200% conversions** |
| AI content recommendations | **+19% revenue per session** |

</details>

<details>
<summary>🎨 UX & Design Impact</summary>

| Stat | Benchmark |
|---|---|
| Heatmap-optimized pages | **+14% conversions** |
| CTAs above the fold | **+138% (Enhance Insurance, UK)** |
| Real people vs stock photos | **+20% trust** |
| Social proof above forms | **+50% form submissions** |
| Micro-copy rewrites | **+8% conversion lift** |

</details>

<details>
<summary>🔁 Testing Velocity</summary>

| Stat | Benchmark |
|---|---|
| 10+ tests per month | **Grow 2.1× faster** |
| AI-assisted test ideation | **+23% win rates** |

</details>

---

<br/>

## 🏆 Industry Benchmarks (Know What You're Beating)

| Industry | Average CVR | High-Performer CVR |
|---|---|---|
| eCommerce | 2.96% | 5–7% |
| SaaS | 9.5% | 15%+ |
| B2B Services | 4.94% | 10%+ |
| Finance | 10% | 20%+ |
| Social / Community | 2.4% | 5%+ |

---

<br/>

## 🗺️ Roadmap

- [x] Master enhancement prompt
- [x] Layer 1 — Responsive design prompt
- [x] Layer 2 — AI personalization prompt
- [x] Layer 3 — Behavioral analytics prompt
- [x] Layer 4 — Feature Pulse prompt
- [x] Layer 5 — CRO quick wins prompt
- [ ] Layer 6 — A/B test prompt (no Optimizely needed)
- [ ] Layer 7 — SEO optimization prompt
- [ ] Layer 8 — Accessibility (WCAG 2.2) audit prompt
- [ ] Layer 9 — Performance audit + Lighthouse fix prompt
- [ ] Layer 10 — Multilingual / i18n prompt

---

<br/>

## 🏢 Enterprise Support & Business Optimization

While **NexaUX** is completely open-source, orchestrating highly dynamic, multi-turn AI workflows at enterprise scale introduces unique structural bottlenecks. When human cognitive loads interface with erratic, latency-driven AI agents, small design failures transform into expensive churn metrics.

If your team is deploying mission-critical AI-agent features, we provide specialized architectural advisory, customized implementations, and deep-dive performance engineering.

### 🛑 The AI-UX Bottlenecks We Solve

Traditional frontend frameworks treat interfaces as static presentation layers. When moving to dynamic, agentic environments, product teams typically hit three major infrastructure walls:

* **State-Serialization Failures:** UI components breaking or desynchronizing during complex, multi-turn LLM reasoning loops.
* **Latency-Induced Churn:** High drop-off rates caused by unoptimized streaming states, opaque agent processing windows, and poor perceived performance.
* **Prompt-to-UI Context Leaks:** Frontend architectures that fail to parse, constrain, or pass contextual user states back to backend agents seamlessly.

---

### 🛠️ How We Help Enterprise Teams Scale

We work directly with **CTOs, CPOs, and Engineering Directors** to audit, harden, and optimize their AI product interfaces.




## 🤝 Contributing

Have a prompt that consistently produces great results? Contribute it.

1. Fork the repository
2. Add your prompt to `/prompts/` with a clear filename
3. Include a short header comment explaining what the prompt does
4. Open a Pull Request with a brief description

Read [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

<br/>

## 📄 License

NexaUX is released under the [MIT License](LICENSE).
Free to use, adapt, and share — attribution appreciated.

---

<br/>

<div align="center">

**Prompts that think. Agents that build. You that ship.**

<br/>

⭐ **Star this repo** if NexaUX saved you hours of writing briefs.

<br/>

[![GitHub stars](https://img.shields.io/github/stars/mdabir1203/nexa-ux?style=for-the-badge&color=6366f1)](https://github.com/mdabir1203/nexa-ux/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/mdabir1203/nexa-ux?style=for-the-badge&color=f59e0b)](https://github.com/mdabir1203/nexa-ux/network)
[![GitHub issues](https://img.shields.io/github/issues/mdabir1203/nexa-ux?style=for-the-badge&color=ef4444)](https://github.com/mdabir1203/nexa-ux/issues)

<br/>

*NexaUX — Next-Generation UX Intelligence*

</div>

*NexaUX — Next-Generation UX Intelligence*

</div>

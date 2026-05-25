# 🚀 Hermes Deploy Guide

**Run your own AI agent locally — no cloud, no tokens, no monthly bills.**

A step-by-step interactive guide for non-technical users to deploy [Hermes Agent](https://github.com/NousResearch/hermes-agent) with [Ollama](https://ollama.com) on their own computer. Everything stays private, everything is free.

🌐 **Live site:** [wangboyang1.github.io/hermes-deploy-guide](https://wangboyang1.github.io/hermes-deploy-guide/)

---

## What You'll Learn

| Step | What |
|------|------|
| 1. Environment | Pick your OS (macOS / Windows / Linux) and enter your hardware specs |
| 2. Ollama | Download and install Ollama with OS-specific instructions |
| 3. Model | Choose from 14 recommended models filtered to your hardware |
| 4. Hermes | One command to install Hermes, then `hermes setup` to configure |
| 5. Cloud API | (Optional) Add DeepSeek, Kimi, or GLM for affordable cloud power |
| 6. Messaging | Connect Telegram and WeChat (or 15+ other platforms) |

## Pages

| Page | Description |
|------|-------------|
| **Home** (`index.html`) | Value proposition — why run an AI agent locally, who it's for. Now in 4 languages (EN/中文/한국어/ES) |
| **Deploy** (`deploy.html`) | Interactive 6-step wizard with OS detection, model recommendations, cloud API setup, and copy-paste commands |
| **Commands** (`commands.html`) | Terminal basics for macOS and Windows, full Hermes CLI reference, and Best Practices & Pro Tips from the official docs |
| **Train** (`train.html`) | 🆕 Interactive terminal simulator — 8 training modules with 28 hands-on exercises. Learn profiles, multi-agent, GitHub, messaging, browsing, files, dashboard, and sessions |
| **Search** (`search.html`) | 🆕 Multi-language knowledge base search — find Hermes commands, tips, and config in English/中文/한국어/ES. Type "/" to focus search |
| **Community** (`community.html`) | Idea board where users share how they use Hermes — post and like |

## Features

- 🖥️ **Auto-detects your OS** and shows the right commands
- 🧠 **Hardware-aware model recommendations** — picks the best model for your RAM and GPU
- 📋 **One-click copy** for every command — no typing needed
- 🌓 **Dark theme** throughout — easy on the eyes
- 🌐 **Multi-language** — English, 简体中文, 한국어, Español
- 🎮 **Training simulator** — learn Hermes by typing real commands in a simulated terminal
- 📱 **Responsive** — works on desktop and mobile
- 🔒 **Pure static HTML** — no frameworks, no build step, no tracking

## Tech Stack

Plain HTML, CSS, and vanilla JavaScript. Zero dependencies. Hosted on GitHub Pages.

```
hermes-deploy-guide/
├── index.html        # Home page (4 languages)
├── deploy.html       # Step-by-step deployment wizard
├── commands.html     # Terminal & Hermes command reference + tips
├── train.html        # Interactive terminal training simulator
├── community.html    # Community idea board
└── README.md
```

## Running Locally

```bash
git clone https://github.com/wangboyang1/hermes-deploy-guide.git
cd hermes-deploy-guide
open index.html        # or just drag index.html into your browser
```

No server needed — open any HTML file directly in your browser.

## Contributing

Found a bug, want to add a command, or have a model suggestion? PRs welcome!

1. Fork the repo
2. Make your changes
3. Open a pull request

For broader discussions or questions, head to [Hermes Agent GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions).

## Related Links

- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — the agent itself
- [Ollama](https://ollama.com) — run LLMs locally
- [Hermes Docs](https://hermes-agent.nousresearch.com/docs) — full documentation

---

Built to help people own their AI. No API keys required. 🔑

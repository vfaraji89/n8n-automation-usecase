# Automation Use Cases

> **The Simit-to-Croissant Framework** — A philosophy for building AI automation with any tools

[![n8n](https://img.shields.io/badge/n8n-Automation-orange?style=flat-square&logo=n8n)](https://n8n.io)
[![AI Powered](https://img.shields.io/badge/AI-Powered-blue?style=flat-square&logo=openai)](https://openai.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

---

## What is This?

A comprehensive collection of **prompts**, **templates**, and **documentation** for building AI-powered automation workflows with n8n,power automate and zapier. This repository follows the **Simit-to-Croissant** philosophy:

| Phase | Analogy | Focus |
|-------|---------|-------|
| 🥯 **Simit** | Simple, local, satisfying | Start with immediate needs |
| 🥐 **Croissant** | Layered, refined, sophisticated | Scale with security |

---

## Repository Structure

```
n8n-automation-usecase/
├── 📖 README.md                          # You are here
├── 📂 docs/
│   └── simit-to-croissant-deck.md        # Framework presentation with diagrams
└── 📂 prompts/
    ├── README.md                          # Prompt bank navigation
    ├── master-prompt.md                   # Original v2.0 master prompt
    ├── 📂 meta-prompts/
    │   ├── dynamic-builder.md             # Interview-style prompt generator
    │   └── dynamic-agent-v3.md            # v3.0 Dynamic Agent (2025)
    ├── 📂 tiers/
    │   ├── 01-basic-linear-task-master.md      # Simple automations
    │   ├── 02-intermediate-multi-tool.md       # Multi-tool orchestration
    │   └── 03-advanced-autonomous-empire.md    # Production-grade agents
    └── 📂 reference/
        └── 2025-n8n-features.md           # Key features & best practices
```

---

##  Quick Start

### 1. Choose Your Tier

| Complexity | Prompt | Best For | Build Time |
|------------|--------|----------|------------|
| Basic | [Linear Task](prompts/tiers/01-basic-linear-task-master.md) | Email categorization, notifications | 30 min |
| Intermediate | [Multi-Tool](prompts/tiers/02-intermediate-multi-tool.md) | Customer support, CRM updates | 2-4 hours |
| Advanced | [Autonomous](prompts/tiers/03-advanced-autonomous-empire.md) | research functions | 1-2 days |
| Meta | [Dynamic ](prompts/meta-prompts/dynamic-builder.md) | When you don't know where to start | Varies |

### 2. Copy the Prompt

Navigate to the appropriate tier file and copy the prompt template.

### 3. Customize

Fill in the `[PLACEHOLDERS]` with your specific use case details.


### 4. Import to n8n

Copy the generated JSON workflow and paste it into your n8n canvas (`Cmd+V` / `Ctrl+V`).

---


### The Simit-to-Croissant Framework

Read the full philosophy and see visual diagrams:

[**Simit-to-Croissant Deck**](docs/simit-to-croissant-deck.md)

**Key Concepts:**
- Start simple, solve immediate pain points
- Iterate continuously, automation is not "set and forget"
- Harden for enterprise with security-first approach
- Scale to sophisticated multi-agent systems

---


This repository is optimized for the latest n8n capabilities:

| Feature | Description |
|---------|-------------|
| **AI Agent Node** | Central reasoning engine replacing linear chains |
| **Sub-workflows as Tools** | Modular architecture for clean canvas |
| **Expression Syntax v2** | `{{ $json.field }}` format |
| **Data Pinning** | Test without burning API credits |
| **Postgres Memory** | Long-term conversation persistence |
| **MCP Integration** | Model Context Protocol servers |



---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [n8n.io](https://n8n.io) — The workflow automation platform
- Power Automate official document -
- [Anthropic Claude](https://anthropic.com) — Claude Code (Github Extension)

Note of Disclaimer: Insights or wordings are extended by AI instead of pure writing with AI

---

**Vahid Faraji**

- GitHub: [@vfaraji89](https://github.com/vfaraji89)



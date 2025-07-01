# ChatGPT Governance Suite

> **Version**: v1.1.0  
> **Status**: Modular Governance Live  
> **Last Updated**: July 1, 2025

---

## Overview
The **ChatGPT Governance Suite** is a modular system designed to give advanced users complete control over how ChatGPT behaves — across projects, modes, and sessions. This repo replaces hardcoded trait instructions with external, reusable profiles and macros that simulate memory, session toggles, and behavior control.

---

## Key Components
| Folder            | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| `/traits/`        | Modular behavior profiles (strict, creative, founder, etc.)             |
| `/macros/`        | One-line commands to simulate session toggles and trait switching       |
| `/memory/`        | Simulated session memory, project anchors, and exit hygiene             |
| `/dashboard/`     | Live Behavior Dashboard file showing current state (editable)           |
| `/docs/`          | User onboarding, usage instructions, security guidance                  |

---

## How to Use (Simple Copy/Paste)

### For Most Users (No GitHub Knowledge Needed):
1. Go to ChatGPT → Settings → Personalization → "Customize ChatGPT"
2. In **“How should ChatGPT respond?”**, paste content from:
   - [`traits/trait-default.md`](traits/trait-default.md) — if unsure, start here
3. Begin your next conversation by typing: `!help`
4. Use macros to load modes, e.g., `!strict`, `!founder`, `!prompt-guide`

> Full macro list: [`macros/macro-list.md`](macros/macro-list.md)

---

## Memory & Session Hygiene

This suite helps you:
- Avoid **LLM contamination**
- Simulate **memory states** with markdown session logs
- Toggle modes or restrict access to prior memory
- Define and end project sessions manually (`!exit`, `!commit`, `!reset`)

Use the [Behavior Dashboard](dashboard/behavior-dashboard.md) to track active scope.

---

## GitHub Pages Access
View as a clean interface:
👉 [https://altmoz.github.io/chatgpt-governance-suite](https://altmoz.github.io/chatgpt-governance-suite)

---

## Roadmap (Coming Soon)
- Trait loader UI for GitHub Pages
- Persona-based governance kits
- Session history browser (manual memory replay)
- PKTS/MTP alignment helpers

---

## Quick Start for Power Users
| Macro         | Result                                                   |
|---------------|----------------------------------------------------------|
| `!help`       | Show current behavior macros & mode                      |
| `!strict`     | Switch to security-focused, factual, precise behavior   |
| `!creative`   | Enable brainstorming, exploratory prompts               |
| `!exit`       | End session and prompt memory commitment                |
| `!reset`      | Flush behavior and return to neutral default            |

---

## License
MIT. Use freely, fork, adapt.

> Created by [Peter Foley](https://github.com/AltMoz). Inspired by real-world project management across multiple AI threads and tools.

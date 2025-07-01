# ChatGPT Governance Suite

> **Total behavioral control for ChatGPT across projects.**

Welcome to the official documentation for the `chatgpt-governance-suite`, a high-integrity framework for managing ChatGPT behavior, prompt standards, memory hygiene, and macro commands.

---

## 🧠 Overview
The suite empowers advanced ChatGPT users to:
- Prevent cross-project memory contamination
- Operate in stateless, secure, prompt-safe mode
- Use macros like `!reset-scope` and `!exit-project`
- Track assistant state using a live dashboard
- Enforce clean session exits and prompt reuse discipline

---

## 🔧 Components

| Module | Purpose |
|--------|---------|
| [`trait-instructions.md`](./trait-instructions.md) | Core customization block for ChatGPT → Custom Instructions |
| [`behavior-dashboard.md`](./behavior-dashboard.md) | Live tracking of project scope, macros, and current mode |
| [`command-reference.md`](./command-reference.md) | Output of `!help`, lists available macros |
| [`prompt-writing-guide.md`](./prompt-writing-guide.md) | Structure for secure, stateless, reusable prompt design |
| [`session-exit-policy.md`](./session-exit-policy.md) | Memory hygiene, exit workflows, end-of-session safety tools |
| [`CONTRIBUTING.md`](./CONTRIBUTING.md) | Guidelines for safe collaboration |
| [`versioning.md`](./versioning.md) | Semantic versioning for framework evolution |

---

## 🚦 Supported Modes

| Mode | Description |
|------|-------------|
| `Strict Mode` | Stateless by default, memory disabled unless scoped |
| `Flex Mode` | Light memory usage, safe macro suggestions enabled |
| `Exploratory Mode` | Full creative flow, speculation allowed (but flagged) |

Use macros to toggle modes and control session flow:
```text
!reset-scope     → drop memory & return to clean state
!exit-project    → finalize project and lock memory
!prompt-guide    → show prompt best practices
!mode-status     → show current assistant behavior mode
```

---

## 🚀 Getting Started

1. Paste `trait-instructions.md` into ChatGPT > **Custom Instructions > Traits**
2. Use `behavior-dashboard.md` in a pinned canvas or reference doc
3. Call `!help` to display all macro commands
4. Use `prompt-writing-guide.md` to standardize prompt structure
5. Use `session-exit-policy.md` at the end of any project thread

### 📘 Easy Mode (Copy-Paste Only – No Git Required)

If you're not using Git, just copy from this file instead:

➡️ [How to Use ChatGPT Governance Suite – Beginner Guide](./usage.md)


---

## 📈 Version

Current: `v1.0.0`  
See [`versioning.md`](./versioning.md) for change history and update rules.

---

## 🧩 Badges

![MIT License](https://img.shields.io/badge/license-MIT-green)
![ChatGPT Safe](https://img.shields.io/badge/chatgpt-governed-blue)
![Stateless First](https://img.shields.io/badge/stateless-default-critical)

---

## 📌 Maintainer

Created and maintained by [Peter Foley](https://www.linkedin.com/in/peterfoley)  
[Altmoz Technology Partners](https://altmoz.com)

---

> Want to adapt this for Claude, Gemini, or local agent tooling?  
> Fork the repo or submit a [pull request](https://github.com/AltMoz/chatgpt-governance-suite/pulls).

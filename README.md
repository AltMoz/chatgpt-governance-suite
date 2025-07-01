 # ChatGPT Governance Suite

> A modular, project-scoped control system for using ChatGPT securely, repeatably, and professionally.

The **ChatGPT Governance Suite** is a structured set of trait instructions, prompt best practices, macros, and memory policies designed to give professionals total control over how ChatGPT behaves across projects.

Whether you're a founder, strategist, analyst, or builder — this system ensures your assistant operates with context discipline, security, and clarity.

---

## 🧠 Purpose

- Avoid cross-project memory contamination  
- Enforce secure, reusable prompt patterns  
- Create transparent behavior boundaries  
- Enable fast switching between “strict,” “flex,” and “exploratory” modes  
- Support versioned, repeatable workflows in Git

---

## 📦 What’s Included

| File | Purpose |
|------|---------|
| `trait-instructions.md` | Paste into ChatGPT → Custom Instructions. Governs assistant behavior. |
| `behavior-dashboard.md` | Live control panel for memory, macros, project scope, and mode. |
| `command-reference.md` | Output of `!help`. Lists all assistant macros and toggles. |
| `prompt-writing-guide.md` | Best practices for stateless, redacted, reusable prompt design. |
| `session-exit-policy.md` | Session exit controls and memory hygiene guide. |
| `CONTRIBUTING.md` | How to contribute securely to the framework. |
| `versioning.md` | Semantic versioning rules for trait and macro evolution. |

---

## 🚦 Behavior Modes

You can switch between 3 modes live by using plain text commands in ChatGPT:

- `Strict Mode` – Memory off unless inside active project. Stateless. Secure.  
- `Flex Mode` – Light memory blending and macro use allowed.  
- `Exploratory Mode` – Go wide. Brainstorm. External analogies welcome (but flagged).

Use macros like `!reset-scope`, `!exit-project`, or `!prompt-guide` to control state at any time.

---

## ✅ Getting Started


1. Clone this repo or copy the `.md` files into your ChatGPT project
2. Paste `trait-instructions.md` into **Custom Instructions > “What traits should ChatGPT have?”**
3. Use `behavior-dashboard.md` to track project scope and mode
4. Call `!help` or view `command-reference.md` for available macros
5. Follow `prompt-writing-guide.md` when crafting assistant inputs
6. End sessions with `!exit-project` or `!end-session` for clean memory discipline

### 📘 Easy Mode (Copy-Paste Only – No Git Required)

If you're not using Git, just copy from this file instead:

➡️ [How to Use ChatGPT Governance Suite – Beginner Guide](./usage.md)


---

## 🛡️ Built For

- Technical founders
- Prompt engineers
- AI strategists and analysts
- Anyone using ChatGPT for multi-project or high-integrity workflows

---

## 🧪 Version


View `versioning.md` for update rules and future release tags.

---

## 🤝 Contributing

See `CONTRIBUTING.md` to suggest new macros, prompt structures, or scoped behavior modes.

---

## 🔗 License

MIT — open use and adaptation encouraged.

Maintained by [Peter Foley](https://www.linkedin.com/in/peterfoley) | Altmoz Technology Partners


# Contributing to `chatgpt-governance-suite`

Thank you for your interest in contributing to this disciplined AI assistant behavior framework. This project is built around intentionality, control, and trust in how large language models are used.

## 🧠 Project Purpose
This repo is designed to:
- Prevent cross-project memory contamination
- Support high-trust LLM workflows
- Empower users with transparent control over ChatGPT behavior
- Enable repeatable, safe, secure LLM interactions

## ✍️ How to Contribute
We welcome contributions that:
- Improve behavioral macros or session control commands
- Expand prompt-writing frameworks
- Add integrations for GitHub Copilot, Claude, Gemini, or agent systems
- Clarify documentation or usage workflows

### ✅ Good First Contributions
- Add mode-specific prompt templates
- Extend the command-reference.md macros
- Suggest more session exit edge cases
- Improve language in prompt-writing-guide.md for clarity or coverage

### ❌ Please Avoid
- Adding speculative capabilities that ChatGPT cannot perform
- Mixing memory and stateless systems without clearly labeling scope
- Assuming user behaviors or preferences — always gate with user confirmation

---

## 🧪 Testing Guidelines
All new files should:
- Be Markdown (`.md`) or YAML-based and fully portable
- Use stateless phrasing when applicable
- Include clear headers and instructions

We recommend validating new prompts or behavior structures using:
- GPT-4o (ChatGPT Plus)
- Claude (for comparison testing)
- Manual review with `!show-settings`, `!mode-status`, and `!verify-capability`

---

## 🛡️ Governance Philosophy
This repo is guided by a **minimum contamination, maximum clarity** standard. Contributions should:
- Assume strict mode unless explicitly toggled
- Reinforce modularity, readability, and reuse
- Respect user data privacy and stateless defaults

---

## 🤝 Coordination
This project is maintained by Peter Foley.  
To propose significant changes or new modules:
- Submit an Issue or PR clearly labeled by function (`prompt`, `macro`, `exit-policy`, etc.)
- Tag your contribution with scope (e.g., `project-memory`, `prompt-security`, `dashboard-ui`)

---

Thank you for helping improve the safety and clarity of LLM-driven systems!

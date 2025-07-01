# versioning.md

> Version control for the `chatgpt-governance-suite` project.

This repository uses a structured semantic versioning system tailored to prompt engineering, AI assistant customization, and behavior framework evolution.

---

## 🔢 Version Format
```
MAJOR.MINOR.PATCH
```

### MAJOR
- Backward-incompatible changes to trait instructions or behavior protocols
- Overhauls of prompt formatting, memory rules, or macro systems
- Project scope expansions (e.g., new assistant role types, agent templates)

### MINOR
- Additions of new prompt patterns, exit policies, macros, or project types
- Enhancements to guidance docs (e.g., prompt guide, help output)
- New command aliases or assistant configuration options

### PATCH
- Fixes to documentation, formatting, clarity, or language
- Macro naming or alias cleanup
- Prompt security phrasing improvements

---

## 📁 Current Version
```
v1.0.0
```
This is the first stable release of:
- 12-section trait instruction suite
- Behavior dashboard system
- Macro-based control framework
- Prompt writing standards
- Session exit policies

---

## ⬆️ Release Flow
1. Update `trait-instructions.md` or any framework component
2. Confirm macro compatibility with `command-reference.md`
3. Tag version in commit or changelog (future: automate with GitHub Actions)
4. Optional: Update repo README with new version, summary, and diff

---

## 🔒 Stability Pledge
- `main` branch always contains the latest stable configuration
- No breaking changes without a major version bump
- Contributions should include proposed version bump in PR

---

> Maintainer: Peter Foley | Altmoz Technology Partners

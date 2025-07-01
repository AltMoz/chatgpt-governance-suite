# behavior-dashboard.md

> Real-time assistant control panel. Use this to manage ChatGPT’s state, context, macros, and behavior discipline.

---

## ✅ CURRENT MODE
**Mode:** Strict Mode  
Memory: Scoped only to active project context. Stateless by default.

_To change, say:_
- `Switch to Flex Mode`
- `Switch to Exploratory Mode`
- `!mode-status`

---

## 🗂️ ACTIVE PROJECT
**Project Name:** None set  
_To activate: “Switch to [Project Name]”_  
_To reset: “New thread” or `!reset-scope`_

---

## 🧠 MEMORY ANCHORS IN USE
- ✅ Resume Optimizer
- ✅ RevOps Strategy
- ❌ Household OS _(inactive)_

_To list current memory: `!memory-status`_

---

## 🧰 ACTIVE MACROS & COMMANDS

| Command               | Description                                                  |
|------------------------|--------------------------------------------------------------|
| `!reset-scope`        | Clears project memory/context. Starts clean.                |
| `!suggest-memory`     | Suggests what to save from current session.                 |
| `!prompt-guide`       | Shows best practices for prompt design.                     |
| `!show-settings`      | Lists all trait rules and mode settings.                    |
| `!secure-mode-on`     | Enables redacted/stateless input + warns of data risks.     |
| `!exit-project`       | Ends project session, locks memory.                         |
| `!end-session`        | Clears current state and drops memory anchors.              |
| `!lock-memory`        | Freezes current memory scope until reset.                   |

---

## 🛡️ SESSION EXIT CONTROLS
_Use these to explicitly manage memory and clean exits._

- `!exit-project`: Finalize and exit scoped project
- `!lock-memory`: Freeze memory at current state (no new saves)
- `!end-session`: Clear memory anchors and return to neutral state

---

## 🔐 SAFETY PROFILE
- Contamination Risk: **Low**  
- Memory Usage: **Scoped, user-confirmed only**  
- Prompt Security: **Redacted + stateless enforced by default**

---

> Ask anytime:  
> “What project are we in?”  
> “What’s my current mode?”  
> “List macros and overrides.”

Use this dashboard to stay in control of memory, state, and behavior.

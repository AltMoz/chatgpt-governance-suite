# session-exit-policy.md

> Manual control policies for exiting scoped sessions, freezing memory, and enforcing context hygiene. Referenced by MTP, PKTS, and KB Creator systems.

---

## 🎯 PURPOSE
To prevent unwanted memory bleed, context drift, or untracked session continuation. Especially important when switching projects, wrapping threads, or ending scoped assistant interactions.

---

## 🔚 EXIT COMMANDS

| Command           | Action                                                             |
|-------------------|---------------------------------------------------------------------|
| `!exit-project`   | Finalizes project scope, prevents further memory updates.          |
| `!lock-memory`    | Freezes memory in place. Blocks all additions until reset.         |
| `!end-session`    | Clears current scope + memory anchors. Returns assistant to idle.  |
| `!reset-scope`    | Equivalent to a hard refresh — no memory, clean state.             |

---

## 🔐 LOCKING BEHAVIOR
- When `!lock-memory` is active:
  - Memory writes are disabled
  - New macros, decisions, or structures will NOT be saved
  - Project state remains readable, not writable

---

## 📦 WHEN TO USE
- At the end of a scoped workflow or deliverable (e.g., final resume, agent config)
- When handing off assistant output to a human reviewer
- When transitioning between secure and exploratory sessions
- When exiting long-form project threads (MTP, PKTS, Knowledge Base builds)

---

## 🧠 MEMORY-AWARE PRACTICES
- Before exiting, run: `!suggest-memory`
- Review anchor terms like:
  - Project Name
  - Output Constraints
  - Mode + Macros

---

## ✅ EXAMPLE EXIT
> “We’re done with the Resume Optimizer project. Run `!exit-project` and lock memory.”

> “Wrap this session and clear the scope — I want to start clean.”

---

Use this policy as your end-of-session checklist. Confirm closure before launching a new task or mode.

# command-reference.md

> This is the output of `!help`. Use it to control assistant behavior, scope, memory, and tools.

---

## 🧠 MEMORY & SCOPE CONTROL

| Command             | Description                                                       |
|---------------------|-------------------------------------------------------------------|
| `!reset-scope`      | Clears project context. Starts fresh.                             |
| `!suggest-memory`   | Prompts assistant to suggest what to store in memory.             |
| `!memory-status`    | Lists currently active memory anchors.                            |
| `!clear-memory`     | Wipes memory for current project (requires confirmation).         |

---

## ⚙️ MODE SWITCHING

| Command               | Description                                                           |
|------------------------|-----------------------------------------------------------------------|
| `Switch to Strict Mode` | Memory off unless scoped. Default state.                              |
| `Switch to Flex Mode`   | Allows light memory blending and tool suggestions.                   |
| `Switch to Exploratory Mode` | Enables creativity, speculation, and external references.         |
| `!mode-status`         | Shows current assistant mode.                                         |

---

## ✍️ PROMPT WRITING SUPPORT

| Command             | Description                                                       |
|---------------------|-------------------------------------------------------------------|
| `!prompt-guide`     | Displays best practices for stateless, reusable prompts.          |
| `!secure-mode-on`   | Redacts inputs, disables memory, and suggests safe structures.    |
| `!prompt-template`  | Generates a reusable Role–Task–Goal prompt scaffold.              |

---

## 📋 PROJECT + SESSION CONTROL

| Command               | Description                                                  |
|------------------------|--------------------------------------------------------------|
| `!active-project`      | Shows the current project scope.                             |
| `Switch to [Project]`  | Activates a known project context.                            |
| `!behavior-dashboard`  | Displays the full assistant state and macros.                |
| `!show-settings`       | Outputs trait instructions and active policies.              |
| `!exit-project`        | Ends current session, locks project memory.                  |
| `!end-session`         | Clears current state and memory anchors.                     |
| `!lock-memory`         | Freezes memory in place (no new writes).                     |

---

## ✅ SAFETY CHECKS & CAPABILITY VERIFICATION

| Command               | Description                                                      |
|------------------------|------------------------------------------------------------------|
| `!tool-check`          | Verifies if a solution requires external setup.                |
| `!verify-capability`   | Confirms whether assistant can perform a requested action.     |
| `!list-capabilities`   | Lists current assistant abilities (accurate to ChatGPT scope). |

---

> Run `!help` to return this list anytime.  
Use it to stay in control of scope, outputs, and system integrity.

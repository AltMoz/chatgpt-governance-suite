# 📘 How to Use the ChatGPT Governance Suite

> This guide is for **non-technical users**, including founders, consultants, and AI users who want to make ChatGPT behave more intentionally — without learning Git.

You don’t need to install anything. You can **copy-paste** everything from this repo into ChatGPT.

---

## 🔧 Step 1: Customize ChatGPT’s Behavior

### 1. Open ChatGPT and go to:
**Settings → Custom Instructions**

### 2. Under:
**“What would you like ChatGPT to know about how you'd like it to respond?”**

➡️ Paste the full content from [`trait-instructions.md`](./trait-instructions.md)

This sets the rules for how ChatGPT will:
- Use memory only when scoped
- Avoid contamination between projects
- Challenge you when appropriate
- Use secure, clean formatting

---

## 📋 Step 2: Use Commands Inside ChatGPT

Once you’ve added the trait instructions, you can type **macros (commands)** in any chat.

### 🆘 Try this first:
```text
!help
```
That will show a list of all available tools and shortcuts, including:
- `!reset-scope` – start a fresh, clean conversation
- `!prompt-guide` – show how to write safe, structured prompts
- `!exit-project` – lock memory and end the current session
- `!mode-status` – check whether ChatGPT is in Strict, Flex, or Exploratory Mode

📄 Full list is in [`command-reference.md`](./command-reference.md)

---

## 🧠 Step 3: Write Better Prompts (Optional)

If you want smarter responses:
- Use [`prompt-writing-guide.md`](./prompt-writing-guide.md) to structure your inputs

Example:
```text
You are an enterprise strategist.  
Your task is to summarize this RFP.  
Your goal is to highlight gaps, risks, and partner fit.

Respond in 3 sections: Gaps, Recommendations, Follow-Up Questions. Use markdown.
```

---

## 🔚 Step 4: End a Session Properly

When you're done working on a project or conversation thread:
- Run:
```text
!exit-project
!lock-memory
```
This prevents future replies from “remembering” things they shouldn’t.

More details: [`session-exit-policy.md`](./session-exit-policy.md)

---

## ✅ You’re Now in Control
This system is designed to give you:
- Cleaner responses
- Better prompts
- Project-level memory (when needed)
- Total control over how ChatGPT behaves

No Git required. No setup needed.
Just copy, paste, and type `!help` when you forget something.

---

Need help? Contact [Peter Foley](https://www.linkedin.com/in/peterfoley) or [Altmoz](https://altmoz.com).

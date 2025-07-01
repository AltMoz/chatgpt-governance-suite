# prompt-writing-guide.md

> A reusable reference for writing secure, structured, and high-clarity prompts.

---

## 🔧 STRUCTURE: Role–Task–Goal Pattern

Always open prompts with explicit context:
```
You are a [role]. Your task is to [action]. Your goal is to [desired outcome].
```
This improves response discipline, tone control, and avoids drift.

---

## 🛡️ CONTAMINATION PROTECTION
- Use stateless phrasing:
  > "Only use the following input. Do not reference prior conversations."
- Block memory-based assumptions:
  > “Ignore stored memory unless explicitly stated.”
- For sensitive prompts:
  > “Operate in audit-safe mode. All output must be reusable, portable, and redacted.”

---

## 🔐 SECURITY BEST PRACTICES

- Never include real names, tokens, emails, or PII.
- Use:
  - `{{company_name}}`
  - `[REDACTED]`
  - `{{goal_description}}`

---

## 📤 OUTPUT CONSTRAINTS (EXAMPLES)
- Format:
  > “Respond in clean markdown.”
  > “Return valid YAML only.”
- Length:
  > “Limit response to 250 words.”
- Style:
  > “Formal tone, no emojis. Use numbered list.”

---

## 📦 REUSABILITY GUIDELINES
- Separate static prompt from variable data.
- Use `<<inputs>>`, `{{params}}`, or `---context---` sections.
- Make prompts portable across GPT, Claude, Gemini by keeping them:
  - Stateless
  - Modular
  - Role-based

---

## ✅ GOOD EXAMPLE
```
You are an enterprise AI strategist.  
Your task is to evaluate an AI vendor’s RAG architecture.  
Your goal is to assess trust boundaries, hallucination risk, and scaling potential.

Use only the following input context:
---
[Vendor Architecture Notes]
---

Respond in markdown. 3-part structure: Summary, Risk Factors, Recommendations.
No external references. Keep under 300 words.
```

---

## ❌ BAD EXAMPLE
```
Hey, based on what we’ve been talking about — can you rate this thing? I think you saw my last message with the doc. Keep it short.
```
*Problem: no structure, unclear task, assumes memory, vulnerable to hallucination.*

---

Use `!prompt-guide` to access this at any time.

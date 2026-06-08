# AI Deprint — Claude Skill

Remove AI writing fingerprints from any text. This skill uses a 6-step structured workflow — fixing structure first, then words — to strip the patterns that make writing scream "AI wrote this." Works across LinkedIn posts, reel scripts, carousels, newsletters, and long-form content.

---

## How to Trigger It

Say any of these to Claude and the skill activates automatically:

- "Remove AI fingerprints from this"
- "Deprint this"
- "Make this less AI"
- "Fix the em dashes"
- "Remove fragmented sentences"
- "This sounds too AI"
- "Clean up AI tells"
- "Fix AI writing patterns"
- Paste any text and say "make this less detectable as AI-written"

---

## How to Install

1. Click **`<> Code`** → **`Download ZIP`**
2. Go to **[claude.ai](https://claude.ai)** → **Skills** → **Create Skill**
3. Upload the **ZIP file** directly → **Save**

No API keys, no Python, no setup required.

---

## How It Works — The 6-Step Workflow

| Step | What It Does |
|---|---|
| **1. Read First, Fix Nothing** | Identifies format, AI-heaviness, and writer's intent before touching anything |
| **2. Check Structure Before Words** | Fixes bloated setups, uniform paragraphs, forced transitions, and generic endings |
| **3. Format-Specific Fixes** | Applies targeted fixes for LinkedIn, Reel scripts, Carousels, and Newsletters |
| **4. Word-Level Tells** | Removes em dashes, sycophantic openers, fake depth words, robotic transitions |
| **5. Self-Audit Pass** | Re-reads output fresh to catch over-polished sentences missed in the first pass |
| **6. Read Aloud Check** | Flags 1–2 lines that read fine but would sound unnatural when spoken |

---

## Modes

| Mode | When to Use |
|---|---|
| **Detect** | Audit text for AI patterns (Critical / Moderate / Minor) without rewriting |
| **Light** (default) | Fix only obvious tells, preserve original structure |
| **Deep** | Full rebuild — all fingerprints removed, meaning stays identical |

---

## What It Always Fixes (No Exceptions)

- **Em dashes (—)** → comma, period, or rewrite
- **Sycophantic openers** (Great question! Absolutely!) → deleted entirely
- **Copula avoidance** (serves as, functions as) → replaced with "is"
- **Robotic transitions** (Furthermore, Moreover, Additionally) → removed or simplified
- **Stacked hedging** (could potentially possibly be argued) → one hedge maximum

---

## Requirements

- No API keys needed
- No Python or scripts
- Works entirely inside Claude

---

## Repository Structure

```
ai-deprint/
└── SKILL.md    ← the skill file (installed via ZIP upload)
```

---

## Non-Negotiables

Never changes facts, numbers, dates, or names. Never adds content not in the original. Never flattens a specific claim into a vague one. When unsure if a line is AI or the writer's actual style — leaves it.

---

## Connect with Pruthvi

- Instagram: [instagram.com/ca.pruthvimehta](https://instagram.com/ca.pruthvimehta)
- LinkedIn: [linkedin.com/in/pruthvimehta](https://linkedin.com/in/pruthvimehta)
- YouTube: [youtube.com/@ca.pruthvimehta](https://youtube.com/@ca.pruthvimehta)

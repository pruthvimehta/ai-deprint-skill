# AI Deprint — Claude Skill

Remove AI writing fingerprints from any text. This skill surgically strips the patterns that make writing scream "AI wrote this" — em dashes, fragmented sentences, robotic transitions, fake depth vocabulary, and 8 more tells — without changing your facts, voice, or meaning.

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

That's it. No API keys, no Python, no setup required.

---

## The 12 AI Fingerprints It Removes

| Fingerprint | Fix |
|---|---|
| Em dash (—) | Comma, period, or rewrite |
| Dramatic fragments | Merge into full sentence |
| Furthermore / Moreover / Additionally | Remove or use "also" |
| Delve, tapestry, nuanced, robust, leverage | Replace with plain words |
| Rule of three | Cut to one or two |
| Not just X, but Y | Simplify to one claim |
| Great question! / Absolutely! | Delete |
| Serves as / Functions as | Replace with "is" |
| -ing phrase endings | Cut or make standalone sentence |
| Significance inflation | Delete, just state the fact |
| Generic positive conclusion | End on the last real point |
| Triple hedging | One hedge max |

---

## Modes

| Mode | When to Use |
|---|---|
| **Detect** | Audit text for AI patterns without rewriting — returns a bullet list of issues |
| **Light** (default) | Fix only the obvious tells, preserve original structure |
| **Deep** | Full rebuild — removes all 12 fingerprints, varies rhythm, may look quite different |

Default is **Light** if you don't specify a mode.

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

## How It Works

1. Identifies the mode (detect / light / deep)
2. Reads the full text before touching anything
3. Scans for all 12 AI fingerprints
4. Fixes based on mode — surgical in light, full rebuild in deep
5. Does a "read aloud" test to catch remaining robotic phrasing
6. Returns the cleaned text + a brief list of what was fixed

**Non-negotiables:** Never changes facts, numbers, or names. Never adds content that wasn't in the original. Never flattens a specific claim into a vague one.

---

## Connect with Pruthvi

- Instagram: [instagram.com/ca.pruthvimehta](https://instagram.com/ca.pruthvimehta)
- LinkedIn: [linkedin.com/in/pruthvimehta](https://linkedin.com/in/pruthvimehta)
- YouTube: [youtube.com/@ca.pruthvimehta](https://youtube.com/@ca.pruthvimehta)

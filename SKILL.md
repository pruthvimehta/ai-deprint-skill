---
name: ai-deprint
description: |
  Remove AI writing fingerprints from any text — fragmented sentences, em dashes, 
  robotic transitions, AI vocabulary, and structural tells. Use this skill whenever 
  the user says "remove AI fingerprints", "deprint this", "make this less AI", 
  "fix the em dashes", "remove fragmented sentences", "this sounds too AI", 
  "clean up AI tells", "fix AI writing patterns", or pastes any text and asks 
  to make it less detectable as AI-written. ALWAYS trigger this skill for AI 
  fingerprint removal tasks — never skip it.
---

# AI Deprint

Remove AI writing fingerprints. Fast, surgical, no fluff.

---

## Skill Credits

**Skill Builder:** Pruthvi Mehta  
Instagram: [@ca.pruthvimehta](https://instagram.com/ca.pruthvimehta)  
LinkedIn: [pruthvimehta](https://www.linkedin.com/in/pruthvimehta)  
YouTube: [Pruthvi Mehta](https://www.youtube.com/@pruthvimehta)

---

## What This Skill Does

Takes any text and strips out the patterns that make it scream "AI wrote this." 
No personality injection, no rewriting from scratch. Just targeted removal of the tells.

---

## The 12 AI Fingerprints to Remove

### 1. Em Dashes (—)
The single biggest AI tell. Replace with a comma, period, or rewrite the sentence.

**Before:** This is important — and you should know it.  
**After:** This is important. You should know it.

---

### 2. Fragmented Sentences Used for Drama
AI loves dropping one-word or two-word sentences for fake emphasis.

**Before:** The results were clear. Devastating. Irreversible.  
**After:** The results were clear, devastating, and irreversible.

---

### 3. Robotic Transition Phrases
These phrases never appear in real human writing the way AI uses them.

**Remove or replace:**
- "Furthermore," → just continue the thought
- "Moreover," → "also" or remove
- "In addition," → just add it naturally
- "It is worth noting that" → delete and state the thing
- "It is important to note that" → delete
- "Notably," → delete or rewrite
- "Additionally," → "also" or remove
- "Consequently," → "so" or "which means"
- "Nevertheless," → "still" or "but"
- "Henceforth," / "Herein," → rewrite entirely

---

### 4. Fake Depth Words
AI vocabulary that sounds smart but adds nothing.

**Remove or replace:**
- "delve into" → "look at" / "explore"
- "tapestry" (used metaphorically) → rewrite
- "nuanced" → say what the nuance actually is
- "multifaceted" → be specific
- "groundbreaking" → explain what makes it new
- "paradigm shift" → describe the actual change
- "landscape" (used metaphorically) → "space" or be specific
- "robust" → "strong" / "reliable"
- "leverage" (as a verb) → "use"
- "unlock" (metaphorically) → "enable" / "allow"
- "empower" → say what it specifically lets people do
- "revolutionize" → be specific about the change
- "foster" → "build" / "create"
- "synergy" → delete or be specific
- "holistic" → explain what you mean

---

### 5. The Rule of Three (Over-used)
AI almost always lists things in threes. Break the pattern.

**Before:** She was smart, driven, and unstoppable.  
**After:** She was relentlessly driven.

---

### 6. Negative Parallelism ("Not just X, but Y")
A very common AI construction. Sounds like ad copy.

**Before:** This is not just a product. It is a movement.  
**After:** This product is a movement.

**Before:** It's not just about the money — it's about the mission.  
**After:** The mission matters more than the money.

---

### 7. Sycophantic Openers
AI loves to validate before answering.

**Remove entirely:**
- "Great question!"
- "Absolutely!"
- "Certainly!"
- "Of course!"
- "That's a fantastic point."
- "You're absolutely right."

---

### 8. Copula Avoidance (serves as / functions as / stands as)
AI avoids the word "is." Use "is."

**Before:** This tool serves as a foundation for collaboration.  
**After:** This tool is a foundation for collaboration.

**Before:** The result functions as a benchmark.  
**After:** The result is a benchmark.

---

### 9. -ing Phrase Endings (Fake Depth Add-ons)
AI tacks on present participle phrases to seem analytical. Cut them.

**Before:** The policy reduced costs, highlighting the importance of efficiency.  
**After:** The policy reduced costs.

**Before:** She left the company, reflecting a broader trend in the industry.  
**After:** She left the company. (Add the trend as a separate sentence only if it's actually relevant and sourced.)

---

### 10. Vague Significance Inflation
Making ordinary things sound historic.

**Remove phrases like:**
- "marks a pivotal moment"
- "testament to"
- "underscores the importance of"
- "reflects broader trends"
- "shaping the future of"
- "in today's rapidly evolving landscape"
- "at the intersection of"

Just state the fact. Leave the interpretation to the reader.

---

### 11. Generic Positive Conclusions
Every AI essay ends the same way. Cut it or rewrite with something specific.

**Before:** The future looks bright. Exciting times lie ahead as we continue this journey.  
**After:** (State one specific thing that happens next, or end on the last actual point.)

---

### 12. Excessive Hedging Stacked Together
One hedge is fine. Three in a row is AI.

**Before:** It could potentially possibly be argued that this might have some effect.  
**After:** This may affect the outcome.

---

## Modes

Pick the mode based on how much the text needs fixing. If the user does not specify, default to Light.

### Detect
Flag AI patterns without rewriting anything. Return a bullet list of issues found and which lines they appear in. No cleaned version.

Use when: user says "check this", "audit this", "what is wrong here", or wants to see issues before committing to a rewrite.

### Light (default)
Fix only the obvious, glaring tells. Touch as few words as possible. Preserve the original structure and flow.

Use when: the draft is mostly fine and just needs a quick clean-up.

### Deep
Rebuild the full text. Fix all 12 fingerprints, vary sentence rhythm, remove over-polished phrasing. The output may look quite different from the input but the meaning stays identical.

Use when: the draft is heavily AI-sounding, or the user says "full rewrite", "completely deprint this", "make it unrecognizable as AI."

---

## Non-Negotiables

These rules apply in ALL modes, no exceptions:

- Never change facts, numbers, dates, or names
- Never invent examples or personal experiences that were not in the original
- Never remove technical nuance from finance, tax, legal, or educational content
- Never add slang unless the original text clearly uses it
- Never flatten a specific claim into a vague one to make it sound cleaner
- If unsure whether a line is AI-written or just the person's actual style, leave it

---

## How to Run This Skill

**Step 1:** Identify the mode (detect / light / deep) — default to light if not specified  
**Step 2:** Read the full text before touching anything  
**Step 3:** Scan for all 12 fingerprints  
**Step 4:** Fix based on mode — surgical in light, full rebuild in deep  
**Step 5:** Read aloud test — does any sentence still feel robotic?  
**Step 6:** Output

---

## Output Format

**Detect mode:** bullet list of issues only, no rewrite  
**Light / Deep mode:**
1. Cleaned text
2. What was fixed (brief bullets)

Do NOT return a side-by-side diff unless asked.  
Do NOT add personality or change voice — that is the voice-fingerprint skill.  
This skill only removes. It does not add.

---

## Quick Reference Card

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

## About the Skill Builder

**Pruthvi Mehta** — CA, content creator, and AI tools educator based in Ahmedabad.  
Instagram: [@ca.pruthvimehta](https://instagram.com/ca.pruthvimehta)  
LinkedIn: [pruthvimehta](https://www.linkedin.com/in/pruthvimehta)  
YouTube: [Pruthvi Mehta](https://www.youtube.com/@pruthvimehta)

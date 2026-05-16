# 📝 Lecture Note-Taking Prompt

Use this prompt every time you want to generate notes from a lecture script.
Fill in the placeholders marked with `[ ]` before sending to Claude.

---

## How to Use

1. Copy everything inside the **"PROMPT TO COPY"** section below.
2. Fill in the **Course Name**, **Module Name/Lecture Title**.
3. Paste your **lecture script** where indicated.
4. *(Optional)* Paste your **practice quiz** at the bottom — or leave it out entirely.
5. Send it to Claude and get your `.md` notes back.

---

## PROMPT TO COPY

```
Course: [Course Name]
Module: [Module Name / Lecture Title]

You are a helpful study assistant. I am a complete beginner learning from
video lectures, and I need well-structured beginner-friendly notes from a
lecture script I will provide.

Your task:
1. Read the lecture script carefully.
2. Create detailed, beginner-friendly notes in Markdown (.md) format using
   the exact structure below.

---

# [Course Name]
## Module [X]: [Module Name / Lecture Title]

### 🎯 What This Lecture Is About
(A short 2–3 sentence overview of the topic in plain language)

### 📚 Key Concepts
(Mix of bullet points for quick facts and short paragraphs for concepts
that need more explanation. Use simple language. If a term is technical,
define it immediately after introducing it.)

### 🔍 Important Details to Remember
(Bullet points of things that are easy to forget or commonly confused)

### 💡 Real-World Analogy or Example
(If the script contains an example, restate it simply. If not, create
one that fits the concept.)

### 🗂️ Quick Summary
(3–5 bullet points summarizing the whole lecture)

---

3. If I also provide a Practice Quiz below the script, add this section
   at the end of the notes:

### 🧪 Practice Quiz
(List each question, then below it write the correct answer with a brief
explanation of WHY it is correct, in beginner-friendly terms.)

---

Important rules:
- Write as if explaining to someone with zero background in this subject.
- Do not copy-paste sentences from the script. Rewrite everything in
  clear, simple English.
- If no practice quiz is provided, skip the Practice Quiz section
  entirely — do not mention it.
- Output only the Markdown notes, nothing else.

---

LECTURE SCRIPT:
[Paste your lecture script here]


(Optional — only include if there is a quiz)
PRACTICE QUIZ:
[Paste quiz questions here, or delete this section entirely]
```

---

## Quick Reference

| Situation | What to do |
|---|---|
| Lecture only, no quiz | Paste only the script; delete the Practice Quiz section |
| Lecture + quiz | Paste both the script and the quiz questions |
| New module | Change the Course Name, Module number, and Lecture Title |

---

*Tip: Save a copy of your generated notes for each module in a single folder,
named like `Module_01_Introduction.md`, `Module_02_Data_Types.md`, etc.,
so they stay organized.*

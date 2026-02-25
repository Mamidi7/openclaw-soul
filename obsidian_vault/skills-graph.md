# 🧩 Skill Graphs — Simple Explanation

## What is a Skill Graph?

Think of it like **Wikipedia links** but for AI skills.

### Old Way (Single Skill):
```
python-basics.md (one big file with EVERYTHING)
- Variables
- Lists
- Functions
- Classes
→ One file gets HUGE, hard to find anything
```

### New Way (Skill Graph):
```
python/
├── index.md          → Overview & links
├── basics.md         → Variables, data types
├── data-structures.md → Lists, dicts, tuples
├── functions.md      → def, return, args
└── classes.md        → OOP concepts

Each file links to others:
"Learn [[functions]] after [[basics]]"
"Advanced? See [[classes]]"
```

---

## 🔥 How It Helps Us

| Before | After (Skill Graph) |
|--------|-------------------|
| One giant prompt | Small, linked skills |
| Repeat instructions | Reusable components |
| Hard to find | Click through links |
| One skill = one task | Composable skills |

---

## 📦 Our Skill Graph Plan

```
genai-prep/
├── index.md              → 45-day roadmap
├── python/
│   ├── index.md
│   ├── day1.md           → Python + Gemini API
│   ├── day2.md           → Variables, types
│   ├── day3.md           → Lists, dicts
│   ├── day4.md           → Functions ← WE'RE HERE
│   └── ...
├── gcp/
│   ├── index.md
│   ├── vertex-basics.md
│   └── ...
├── prompts/
│   ├── quiz-master.md
│   ├── subba-rao.md
│   └── ...
└── projects/
    ├── index.md
    └── ...
```

---

## 🎯 Immediate Actions

1. **Install obsidian-cli** → For automation
2. **Create skill links** → Daily notes link to concepts
3. **Build our graph** → Each day adds to the structure

---

## 🔗 Example Link Syntax

```markdown
# In daily-notes/day4.md
Today I learned about [[functions]] and [[modules]].

# In python/functions.md  
See also: [[list-comprehensions]]
```

The AI (that's me!) can follow these links to understand context.

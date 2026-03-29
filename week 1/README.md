````markdown
# 🐍 Week 01: Python Core Foundations
````
 _____ ___  ____  _____   _  __  
| ____/ _ \|  _ \| ____| | |/ /  
|  _| | | | | |_) |  _|   | ' /  
| |___| |_| |  _ <| |___  | . \  
|_____|\___/|_| \_\_____| |_|\_\ 
     IGNITION PHASE // WEEK 01
````

> **Mission:** Mastering the raw materials of high-scale systems.

---

## 📁 Syllabus Structure
````
week_01/
├── 🧱 data_types/
│   ├── primitives.py         # int, float, str, bool, None
│   └── type_casting.py       # explicit vs implicit
├── ✍️  string_ops/
│   ├── methods.py            # strip, split, join, replace
│   └── formatting.py         # f-strings & terminal alignment
├── 🧺 collections/
│   ├── lists.py              # comprehensions & slicing
│   ├── dictionaries.py       # mapping & JSON structures
│   └── sets_and_tuples.py    # uniqueness & immutability
└── 📢 build_in_public/
    └── linkedin_post.md      # social proof & visibility
````

---

## 🧱 Module 01 — Data Types

**Focus:** Memory & Logic

> 💡 **Pro Tip:** In backend dev, `None != False`. Use `isinstance()` for strict checks.

| # | Exercise | Difficulty |
|---|----------|------------|
| 01 | Type Inspector | 🟢 Easy |
| 02 | Temp Converter | 🟡 Medium |
| 03 | Safe Division | 🔴 Hard |

---

## ✍️ Module 02 — String Manipulation

**Mission:** Clean the data, format the output.

| # | Exercise | Difficulty |
|---|----------|------------|
| 01 | Messy CSV Cleaner | 🟢 Easy |
| 02 | Text Stats Pro | 🟡 Medium |
| 03 | CLI Receipt Formatter | 🟡 Medium |

**Messy CSV Cleaner** — Parsing `" Alice , 25 , Lahore "` into structured lists.  
**Text Stats Pro** — Analyzing paragraphs for word frequency and average length.  
**CLI Receipt Formatter** — Mastering terminal UI using `{item:>15}` padding.

---

## 🧺 Module 03 — Collections: Lists

> [!IMPORTANT]  
> List Comprehensions are your best friend. They make your code faster and much more readable.
```python
# The Week 1 Goal: Write elegant Python
squared_evens = [x**2 for x in data if x % 2 == 0]
```

| # | Exercise | Difficulty |
|---|----------|------------|
| 01 | One-Line Squared Evens | 🟡 Medium |
| 02 | Deep Flatten | 🔴 Hard |
| 03 | List Comparison | 🟡 Medium |

**Deep Flatten** — Converting complex nested lists without libraries.  
**List Comparison** — Logical difference tracking without sets.

---

## 🗺️ Module 04 — Collections: Dictionaries

> **Why Dictionaries matter:** They are the Python equivalent of JSON.

| # | Exercise | Difficulty |
|---|----------|------------|
| 01 | Frequency Counter | 🟢 Easy |
| 02 | Recursive Deep Merge | 🔴 Hard |
| 03 | Inventory Management | 🟡 Medium |

**Frequency Counter** — Sortable word-occurrence mapping.  
**Recursive Deep Merge** — Merging nested data structures *(Senior Level)*.  
**Inventory Management** — Alert systems for low-stock thresholds.

---

## ⚡ Module 05 — Collections: Sets & Tuples
```python
# The Secret Sauce
Set   = "Speed & Uniqueness"
Tuple = "Safety & Immutability"
```

| # | Exercise | Difficulty |
|---|----------|------------|
| 01 | Visitor Analytics | 🟢 Easy |
| 02 | 3D Coordinate System | 🟡 Medium |
| 03 | Blog Tagging System | 🟡 Medium |

**Visitor Analytics** — Intersection & difference operations.  
**3D Coordinate System** — Using `namedtuple` for cleaner data containers.  
**Blog Tagging System** — Multi-tag filtering logic using Sets.

---

## 📢 Build in Public

Building in Public stands out. 🌟

**This week's task:**

1. Pick your favorite logic (e.g., *Recursive Deep Merge*)
2. Post a clean snippet or terminal output
3. Tag: `#100DaysOfCode` `#BackendRoadmap` `#PythonCore`

---

> ✅ Ignition complete. Moving to **Week 02: Functions & Error Handling.**
>
> *Built with ❤️ for the `rebooted_engineer` community.*
````
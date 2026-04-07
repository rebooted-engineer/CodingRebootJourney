```md
# 🐍 Week 01: Python Core Foundations

> **Mission:** Rebuild the foundation. Master the raw materials of real-world backend systems.

---

## 📁 Syllabus Structure

```

week_01/
├── 🧱 data_types/
│   ├── primitives.py         # int, float, str, bool, None
│   └── type_casting.py       # explicit vs implicit
├── ✍️ string_ops/
│   ├── methods.py            # strip, split, join, replace
│   └── formatting.py         # f-strings & alignment
├── 🧺 collections/
│   ├── lists.py              # comprehensions & slicing
│   ├── dictionaries.py       # mapping & JSON structures
│   └── sets_and_tuples.py    # uniqueness & immutability
└── 📢 build_in_public/
└── linkedin_post.md      # documenting the journey

````

---

## 🧱 Module 01 — Data Types

**Focus:** Understanding how data lives in memory & flows through logic.

```python
age = 25          # int
price = 99.99     # float
name = "Ali"      # str
is_ready = True   # bool
data = None       # absence of value
````

> 💡 **Pro Tip:** `None` is not `False`. Always check types explicitly when building backend logic.

```python
isinstance(age, int)
```

| #  | Exercise       | Difficulty |
| -- | -------------- | ---------- |
| 01 | Type Inspector | 🟢 Easy    |
| 02 | Temp Converter | 🟡 Medium  |
| 03 | Safe Division  | 🔴 Hard    |

---

## ✍️ Module 02 — String Manipulation

**Mission:** Clean messy data. Format clean outputs.

```python
text = "  hello world  "

clean = text.strip().upper()
print(clean)
```

### ⚡ Formatting Power

```python
name = "Ali"
age = 25

print(f"My name is {name} and I am {age}")
```

| #  | Exercise              | Difficulty |
| -- | --------------------- | ---------- |
| 01 | Messy CSV Cleaner     | 🟢 Easy    |
| 02 | Text Stats Pro        | 🟡 Medium  |
| 03 | CLI Receipt Formatter | 🟡 Medium  |

* **Messy CSV Cleaner** → `" Alice , 25 , Lahore "` → `["Alice", "25", "Lahore"]`
* **Text Stats Pro** → Word count, frequency, averages
* **CLI Receipt Formatter** → Clean terminal output

---

## 🧺 Module 03 — Collections: Lists

> ⚠️ Lists are the backbone of iteration and transformation.

```python
# Elegant Python mindset
squared_evens = [x**2 for x in data if x % 2 == 0]
```

| #  | Exercise               | Difficulty |
| -- | ---------------------- | ---------- |
| 01 | One-Line Squared Evens | 🟡 Medium  |
| 02 | Deep Flatten           | 🔴 Hard    |
| 03 | List Comparison        | 🟡 Medium  |

💡 **Insight:**

> Cleaner logic = faster thinking = better developer.

---

## 🗺️ Module 04 — Collections: Dictionaries

> **Why Dictionaries Matter:** They represent real-world data (APIs, JSON, databases).

```python
user = {
    "name": "Ali",
    "age": 25
}
```

### 🔥 Real Power

```python
freq = {}
for word in words:
    freq[word] = freq.get(word, 0) + 1
```

| #  | Exercise             | Difficulty |
| -- | -------------------- | ---------- |
| 01 | Frequency Counter    | 🟢 Easy    |
| 02 | Recursive Deep Merge | 🔴 Hard    |
| 03 | Inventory Management | 🟡 Medium  |

---

## ⚡ Module 05 — Sets & Tuples

```python
# Core Concept
Set   = "Uniqueness"
Tuple = "Immutability"
```

### Sets

```python
a = {1, 2, 3}
b = {2, 3, 4}

print(a & b)  # intersection
```

### Tuples

```python
point = (1, 2)
```

| #  | Exercise             | Difficulty |
| -- | -------------------- | ---------- |
| 01 | Visitor Analytics    | 🟢 Easy    |
| 02 | 3D Coordinate System | 🟡 Medium  |
| 03 | Blog Tagging System  | 🟡 Medium  |

---

## 🧠 Mindset Shift (This Week)

Before:

* ❌ Writing random code
* ❌ Copy-paste learning

Now:

* ✅ Understanding data deeply
* ✅ Writing structured logic
* ✅ Thinking like a backend engineer

---

## ⚔️ Challenges Faced

* List comprehensions 🤯
* Remembering methods
* Writing logic without help

---

## 📢 Build in Public

This journey is not private.

### This Week’s Task:

1. Pick one concept (e.g., *Frequency Counter*)
2. Share code or output
3. Use hashtags:

```
#100DaysOfCode #RebootedEngineer #PythonCore #BackendJourney
```

---

## 🚀 What’s Next?

```
Week 02:
→ Functions
→ Loops (Deep Dive)
→ Error Handling
```

---

## 🏁 Status

```
[██████████] 100% Complete
```

> ✅ Foundation rebuilt
> 🧠 Thinking upgraded
> 🔥 Discipline activated

---

## 💭 Final Thought

> “This is not just coding… this is me rebuilding my identity.”

---

⭐ Follow the journey → *Rebooted Engineer*

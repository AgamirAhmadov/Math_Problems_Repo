# 📘 Task 5 — Combinations

## 🎯 Goal
Solve selection problems where:
- Order does **NOT** matter  
- We choose a subset of elements  

---

## 📌 Formula

C(n, k) = n! / (k!(n - k)!)

---

# 🧩 Problem 1 — Committee of 4 from 12 students

### ✔️ Model
- Selecting 4 people out of 12  
- Order does NOT matter → **Combination**

### 🔢 Calculation

C(12,4) = 12! / (4! * 8!)

= (12 × 11 × 10 × 9) / (4 × 3 × 2 × 1)  
= 495

### ✅ Answer
**495**

---

# 🧩 Problem 2 — Committees containing a particular student

### ✔️ Idea
Fix that student first.

Now choose the remaining 3 members from the other 11 students.

### 🔢 Calculation

C(11,3) = 11! / (3! * 8!)  
= 165

### ✅ Answer
**165**

---

# 🧩 Problem 3 — Committees containing at least one of two particular students

### ✔️ Idea: Complement Method

Instead of counting directly:
- Count all committees  
- Subtract committees with **none** of the two students  

### 🔢 Step 1: Total committees

C(12,4) = 495

### 🔢 Step 2: Committees with none of the two students

C(10,4) = 210

### 🔢 Step 3: Subtract

495 − 210 = 285

### ✅ Answer
**285**

---

# 🧩 Problem 4 — Committees with exactly 2 women  
(7 men, 5 women)

### ✔️ Idea
Split into two independent selections:
- Choose 2 women  
- Choose 2 men  

Then multiply the results.

### 🔢 Calculation

C(5,2) = 10  
C(7,2) = 21  

10 × 21 = 210

### ✅ Answer
**210**

---

# 📊 Summary

| Problem | Description | Result |
|--------|------------|--------|
| 1 | Choose 4 from 12 | 495 |
| 2 | Contains a specific student | 165 |
| 3 | At least one of two students | 285 |
| 4 | Exactly 2 women | 210 |

---

# 💡 Key Takeaways

- Use **combinations** when order does NOT matter  
- “At least one” → Use **complement method**  
- “Exactly k from a group” → Split into parts and multiply  
- Fixing elements simplifies problems  

# 📘 Task 2 — Permutations

## 🎯 Goal
Solve permutation problems by:
- identifying constraints,
- choosing the correct model,
- computing the result step by step.

---

## 🧩 Problem 1 — Arranging 8 different books

All books are distinct and arranged in a line.

- Using all objects → YES  
- Order matters → YES  

👉 Model: **Permutation**

**Formula:**  
n!

**Calculation:**  
8! = 40320  

**Answer:** `40320`

---

## 🧩 Problem 2 — 8 people, two must sit together

Treat the two specific people as a single block.

- Total units: 7 (6 others + 1 block)  

Arrange the block and others:
7!

Inside the block, the two people can swap:
2!

**Calculation:**  
7! × 2 = 5040 × 2 = 10080  

**Answer:** `10080`

---

## 🧩 Problem 3 — 8 people, two must NOT sit together

Use complement counting:

Total arrangements:
8! = 40320  

Subtract cases where they sit together (from Problem 2):
10080  

**Calculation:**  
40320 − 10080 = 30240  

**Answer:** `30240`

---

## 🧩 Problem 4 — Ordering 10 test questions (first fixed)

The first question is already fixed, so only the remaining 9 can be arranged.

- Using all remaining objects → YES  
- Order matters → YES  

👉 Model: **Permutation**

**Calculation:**  
9! = 362880  

**Answer:** `362880`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| 1 | 40320 |
| 2 | 10080 |
| 3 | 30240 |
| 4 | 362880 |

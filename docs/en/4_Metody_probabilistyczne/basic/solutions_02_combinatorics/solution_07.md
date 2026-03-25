# 📘 Task 7 — k-Permutations (Ordered Selections Without Repetition)

## 🎯 Goal
Solve problems where:
- order matters,
- only some elements are selected,
- repetition is NOT allowed.

**Formula:**  
P(n, k) = n! / (n − k)!

---

## 🧩 Problem 1 — Assigning first three places among 12 runners

- Choose 3 out of 12  
- Order matters (1st, 2nd, 3rd are different)  

👉 Model: **k-permutation**

**Calculation:**  
P(12,3) = 12 × 11 × 10 = 1320  

**Answer:** `1320`

---

## 🧩 Problem 2 — 4-digit numbers from digits 1–9 (no repetition)

- Digits available: 1–9 (9 digits)  
- Choose 4 digits  
- Order matters  
- No repetition  

👉 Model: **k-permutation**

**Calculation:**  
P(9,4) = 9 × 8 × 7 × 6 = 3024  

**Answer:** `3024`

---

## 🧩 Problem 3 — Numbers divisible by 5

A number is divisible by 5 if it ends in **5** (since 0 is not allowed).

Fix last digit = 5  

Now choose remaining 3 digits from the remaining 8 digits (1–9 except 5), without repetition.

👉 Model: **k-permutation**

**Calculation:**  
P(8,3) = 8 × 7 × 6 = 336  

**Answer:** `336`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| 1 | 1320 |
| 2 | 3024 |
| 3 | 336 |

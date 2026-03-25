# 📘 Task 3 — Permutations with Repeated Elements

## 🎯 Goal
Solve problems where:
- all objects are arranged,
- some elements are identical,
- we count only *distinct* arrangements.

**Formula:**  
If total elements = n, and repetitions are n₁, n₂, ..., then:

n! / (n₁! · n₂! · ...)

---

## 🧩 Problem 1 — Arrangements of MISSISSIPPI

**Step 1: Count letters**
- M = 1  
- I = 4  
- S = 4  
- P = 2  

Total letters: 11  

👉 Model: Permutation with repeated elements  

**Calculation:**  
11! / (4! · 4! · 2!)

11! = 39916800  
4! = 24  
2! = 2  

Denominator: 24 × 24 × 2 = 1152  

39916800 / 1152 = 34650  

**Answer:** `34650`

---

## 🧩 Problem 2 — Arrangements of STATISTICS

**Step 1: Count letters**
- S = 3  
- T = 3  
- A = 1  
- I = 2  
- C = 1  

Total letters: 10  

👉 Model: Permutation with repeated elements  

**Calculation:**  
10! / (3! · 3! · 2!)

10! = 3628800  
3! = 6  
2! = 2  

Denominator: 6 × 6 × 2 = 72  

3628800 / 72 = 50400  

**Answer:** `50400`

---

## 🧩 Problem 3 — Arrangements of STATISTICS starting with S

Fix the first letter as **S**.

Remaining letters:
- S = 2  
- T = 3  
- A = 1  
- I = 2  
- C = 1  

Total remaining: 9  

👉 Model: Permutation with repeated elements  

**Calculation:**  
9! / (2! · 3! · 2!)

9! = 362880  
2! = 2  
3! = 6  

Denominator: 2 × 6 × 2 = 24  

362880 / 24 = 15120  

**Answer:** `15120`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| MISSISSIPPI | 34650 |
| STATISTICS | 50400 |
| STATISTICS (start with S) | 15120 |

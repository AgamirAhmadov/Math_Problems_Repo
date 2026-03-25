# 📘 Task 9 — Digit Restrictions

## 🎯 Goal
Count numbers under digit constraints using:
- sequences,
- permutations,
- complement counting.

---

## 🧩 Problem 1 — How many 5-digit numbers exist?

A 5-digit number cannot start with 0.

- First digit: 1–9 → 9 choices  
- Remaining 4 digits: 0–9 → 10 choices each  

👉 Model: **Sequence with repetition**

**Calculation:**  
9 × 10^4 = 9 × 10000 = 90000  

**Answer:** `90000`

---

## 🧩 Problem 2 — How many are even?

A number is even if the last digit is 0, 2, 4, 6, or 8 → 5 choices

Split into cases:

### Case 1: Last digit = 0  
- First digit: 1–9 → 9 choices  
- Middle 3 digits: 10^3  

Total:  
9 × 10^3 = 9000  

### Case 2: Last digit = 2,4,6,8 (4 choices)  
- First digit: 1–9 → 9 choices  
- Middle 3 digits: 10^3  

Total:  
9 × 10^3 × 4 = 36000  

**Total:**  
9000 + 36000 = 45000  

**Answer:** `45000`

---

## 🧩 Problem 3 — No repeated digits

- First digit: 1–9 → 9 choices  
- Remaining digits (no repetition):  
  9 × 8 × 7 × 6  

**Calculation:**  
9 × 9 × 8 × 7 × 6 = 27216  

**Answer:** `27216`

---

## 🧩 Problem 4 — At least one repeated digit

Use complement:

Total numbers:
90000  

Numbers with all distinct digits:
27216  

**Calculation:**  
90000 − 27216 = 62784  

**Answer:** `62784`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| Total 5-digit numbers | 90000 |
| Even numbers | 45000 |
| No repeated digits | 27216 |
| At least one repeated digit | 62784 |


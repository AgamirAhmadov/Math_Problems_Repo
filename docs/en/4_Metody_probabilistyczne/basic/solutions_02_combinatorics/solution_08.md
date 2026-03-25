# 📘 Task 8 — Sequences with Repetition

## 🎯 Goal
Solve problems where:
- order matters,
- repetition may be allowed,
- positions are filled independently.

**Formula (with repetition):**  
n^k  

---

## 🧩 Problem 1 — 5-digit PIN codes (digits may repeat)

- Digits: 0–9 → 10 choices  
- Length: 5  
- Repetition allowed  

👉 Model: **Sequence with repetition**

**Calculation:**  
10^5 = 100000  

**Answer:** `100000`

---

## 🧩 Problem 2 — Codes with at least one repeated digit

Use complement:

Total codes:
10^5 = 100000  

Codes with all digits different:
P(10,5) = 10 × 9 × 8 × 7 × 6 = 30240  

**Calculation:**  
100000 − 30240 = 69760  

**Answer:** `69760`

---

## 🧩 Problem 3 — Codes with all digits different

- Order matters  
- No repetition  

👉 Model: **k-permutation**

**Calculation:**  
P(10,5) = 30240  

**Answer:** `30240`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| Total codes | 100000 |
| At least one repeated digit | 69760 |
| All digits different | 30240 |

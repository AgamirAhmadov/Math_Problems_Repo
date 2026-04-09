# 📘 Task 5 — Combinations
1. A committee of 4 people is chosen from 12 students. How many committees are possible?
2. How many committees contain a particular student?
3. How many committees contain at least one of two particular students?
4. How many committees contain exactly two women if the group consists of 7 men and 5 women?

## 🎯 Goal
Solve selection problems where:
- order does NOT matter,
- we choose a subset of elements.

**Formula:**  
C(n, k) = n! / (k!(n − k)!)

---

## 🧩 Problem 1 — Committee of 4 from 12 students

- Selecting 4 people  
- Order does NOT matter  

👉 Model: **Combination**

**Calculation:**  
C(12,4) = 495  

**Answer:** `495`

---

## 🧩 Problem 2 — Committees containing a particular student

Fix the chosen student.

Now choose remaining 3 members from the other 11 students.

👉 Model: **Combination**

**Calculation:**  
C(11,3) = 165  

**Answer:** `165`

---

## 🧩 Problem 3 — Committees containing at least one of two particular students

Use complement counting.

Total committees:
C(12,4) = 495  

Committees with NONE of the two students:
Choose all 4 from remaining 10:
C(10,4) = 210  

**Calculation:**  
495 − 210 = 285  

**Answer:** `285`

---

## 🧩 Problem 4 — Committees with exactly two women (7 men, 5 women)

We must choose:
- 2 women from 5  
- 2 men from 7  

👉 Model: **Combination + Product Rule**

**Calculation:**  
C(5,2) × C(7,2)

C(5,2) = 10  
C(7,2) = 21  

10 × 21 = 210  

**Answer:** `210`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| 1 | 495 |
| 2 | 165 |
| 3 | 285 |
| 4 | 210 |

# 📘 Task 4 — Circular Permutations
1. In how many ways can 7 people sit around a round table?
2. In how many ways can they sit if two particular people must sit next to each other?
3. In how many ways can they sit if those two people must sit opposite each other?

## 🎯 Goal
Solve seating problems around a round table where:
- rotations are considered the same,
- only relative positions matter.

**Key Formula:**  
Number of circular permutations of n distinct objects:
(n − 1)!

---

## 🧩 Problem 1 — 7 people around a round table

- Circular arrangement  
- All people distinct  

👉 Model: **Circular permutation**

**Calculation:**  
(7 − 1)! = 6! = 720  

**Answer:** `720`

---

## 🧩 Problem 2 — Two particular people must sit together

Treat the two people as one block.

- Total units: 6 (5 others + 1 block)  

Circular arrangements:
(6 − 1)! = 5! = 120  

Inside the block, they can switch places:
2!

**Calculation:**  
5! × 2 = 120 × 2 = 240  

**Answer:** `240`

---

## 🧩 Problem 3 — Two particular people must sit opposite each other

Fix one person (to remove rotational symmetry).

Now the opposite seat is fixed for the second person.

Remaining 5 people can be arranged freely.

**Calculation:**  
5! = 120  

**Answer:** `120`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| 1 | 720 |
| 2 | 240 |
| 3 | 120 |

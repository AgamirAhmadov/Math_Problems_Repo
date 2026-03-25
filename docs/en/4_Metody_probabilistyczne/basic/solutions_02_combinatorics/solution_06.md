# 📘 Task 6 — Combinations in Card Problems

## 🎯 Goal
Solve card-selection problems using combinations and counting techniques.

**Deck facts:**
- Total cards = 52  
- Hearts = 13  
- Non-hearts = 39  
- Face cards (J, Q, K) = 12  
- Non-face cards = 40  

**Formula:**  
C(n, k) = n! / (k!(n − k)!)

---

## 🧩 Problem 1 — Exactly 2 hearts in a 5-card hand

Choose:
- 2 hearts from 13  
- 3 non-hearts from 39  

👉 Model: **Combination + Product Rule**

**Calculation:**  
C(13,2) × C(39,3)

C(13,2) = 78  
C(39,3) = 9139  

78 × 9139 = 712842  

**Answer:** `712842`

---

## 🧩 Problem 2 — At least one heart

Use complement:

Total 5-card hands:
C(52,5) = 2598960  

Hands with NO hearts:
C(39,5) = 575757  

**Calculation:**  
2598960 − 575757 = 2023203  

**Answer:** `2023203`

---

## 🧩 Problem 3 — No face cards (J, Q, K)

Face cards = 12 → Non-face = 40  

Choose all 5 cards from non-face cards.

👉 Model: **Combination**

**Calculation:**  
C(40,5) = 658008  

**Answer:** `658008`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| Exactly 2 hearts | 712842 |
| At least one heart | 2023203 |
| No face cards | 658008 |

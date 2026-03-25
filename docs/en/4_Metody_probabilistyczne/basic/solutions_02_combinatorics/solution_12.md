# 📘 Task 12 — Mixed Counting Problem

## 🎯 Goal
For each part:
- identify the correct counting model,
- compute the number of outcomes.

---

# 🧩 1. Student ID Codes

Format: 2 letters (A–E) + 3 digits (0–9)

---

## (1) Letters and digits may repeat

- Letters: 5 choices each → 5²  
- Digits: 10 choices each → 10³  

👉 Model: **Sequence with repetition**

**Calculation:**  
5² × 10³ = 25 × 1000 = 25000  

**Answer:** `25000`

---

## (2) Letters cannot repeat, digits can repeat

- Letters: P(5,2) = 5 × 4 = 20  
- Digits: 10³  

👉 Model: **k-permutation + sequence**

**Calculation:**  
20 × 1000 = 20000  

**Answer:** `20000`

---

## (3) Neither letters nor digits may repeat

- Letters: P(5,2) = 20  
- Digits: P(10,3) = 10 × 9 × 8 = 720  

👉 Model: **k-permutation**

**Calculation:**  
20 × 720 = 14400  

**Answer:** `14400`

---

# 🧩 2. Medal Assignment

---

## (1) Assign gold, silver, bronze (12 runners)

👉 Model: **k-permutation**

**Calculation:**  
P(12,3) = 12 × 11 × 10 = 1320  

**Answer:** `1320`

---

## (2) Two particular runners must both get medals

Choose positions for the two runners:
P(3,2) = 3 × 2 = 6  

Choose third medalist from remaining 10:
10  

👉 Model: **k-permutation + product rule**

**Calculation:**  
6 × 10 = 60  

**Answer:** `60`

---

# 🧩 3. Committee Selection

(6 men, 4 women)

---

## (1) Total committees

👉 Model: **Combination**

**Calculation:**  
C(10,4) = 210  

**Answer:** `210`

---

## (2) Exactly two women

- Choose 2 women from 4  
- Choose 2 men from 6  

👉 Model: **Combination + product rule**

**Calculation:**  
C(4,2) × C(6,2) = 6 × 15 = 90  

**Answer:** `90`

---

## (3) At least one woman

Use complement:

Total committees:
210  

No women (all men):
C(6,4) = 15  

**Calculation:**  
210 − 15 = 195  

**Answer:** `195`

---

# 🧩 4. Circular Seating (7 people)

---

## (1) Total arrangements

👉 Model: **Circular permutation**

**Calculation:**  
(7−1)! = 6! = 720  

**Answer:** `720`

---

## (2) Two particular people sit together

Treat them as one block → 6 units

Circular arrangements:
(6−1)! = 5! = 120  

Internal arrangement:
2!  

**Calculation:**  
120 × 2 = 240  

**Answer:** `240`

---

# 🧩 5. Passwords

Characters:
- 10 digits + 26 letters = 36 symbols  

---

## (1) Repetition allowed

👉 Model: **Sequence with repetition**

**Calculation:**  
36⁵ = 60466176  

**Answer:** `60466176`

---

## (2) No repetition

👉 Model: **k-permutation**

**Calculation:**  
P(36,5) = 36 × 35 × 34 × 33 × 32 = 45239040  

**Answer:** `45239040`

---

## (3) Models used

- With repetition → **sequence with repetition (n^k)**  
- Without repetition → **k-permutation (P(n,k))**

---

# ✅ Final Summary

| Section | Result |
|--------|--------|
| IDs (repeat) | 25000 |
| IDs (no letter repeat) | 20000 |
| IDs (no repeats at all) | 14400 |
| Medals | 1320 |
| Medals (2 fixed) | 60 |
| Committees | 210 |
| Committees (2 women) | 90 |
| Committees (≥1 woman) | 195 |
| Circular seating | 720 |
| Circular (together) | 240 |
| Passwords (repeat) | 60466176 |
| Passwords (no repeat) | 45239040 |


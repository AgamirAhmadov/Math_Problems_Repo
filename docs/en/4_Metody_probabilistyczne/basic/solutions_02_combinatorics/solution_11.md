# 📘 Task 11 — Modeling Outcomes

## 🎯 Goal
Understand how counting depends on:
- distinguishable vs indistinguishable objects,
- whether order is recorded,
- how outcomes are defined.

---

# 🧩 1. Distinguishable vs Indistinguishable Objects

## (1) Balls of same color are indistinguishable

- Red = 4  
- Blue = 4  
- Green = 3  
- Total = 11  

👉 Model: **Permutation with repeated elements**

**Calculation:**  
11! / (4! · 4! · 3!)

11! = 39916800  
4! = 24  
3! = 6  

Denominator: 24 × 24 × 6 = 3456  

39916800 / 3456 = 11550  

**Answer:** `11550`

---

## (2) All balls are individually labeled

Now all 11 balls are distinct.

👉 Model: **Permutation**

**Calculation:**  
11! = 39916800  

**Answer:** `39916800`

---

## (3) Why are the answers different?

- When balls are **indistinguishable**, swapping same-colored balls does NOT create new arrangements  
- When balls are **distinguishable**, every swap creates a new arrangement  

👉 Therefore, indistinguishability reduces the total number of outcomes.

---

# 🧩 2. Recording Order vs Ignoring Order

We draw 3 balls without replacement.

---

## (1) Only colors recorded (order ignored)

We count combinations of colors.

Possible color cases:
- 3 same color:
  - RRR, BBB, GGG → 3 cases  

- 2 of one color + 1 of another:
  - Choose color for pair (3 ways)  
  - Choose different color (2 ways)  
  → 3 × 2 = 6 cases  

- All different:
  - RGB → 1 case  

**Total:**  
3 + 6 + 1 = 10  

**Answer:** `10`

---

## (2) Sequence of colors recorded (order matters)

Now each ordering is different.

Total outcomes = permutations of 3 balls from 11:

👉 Model: **k-permutation**

**Calculation:**  
P(11,3) = 11 × 10 × 9 = 990  

**Answer:** `990`

---

## (3) Why does order change the result?

- Ignoring order → outcomes are **sets**  
- Recording order → outcomes are **sequences**  

👉 Sequences produce many more outcomes because different orders count separately.

---

# 🧩 3. PIN Code vs Number

---

## (1) 4-digit PIN codes (repetition allowed)

- Digits: 0–9 → 10 choices  
- Length: 4  

👉 Model: **Sequence with repetition**

**Calculation:**  
10⁴ = 10000  

**Answer:** `10000`

---

## (2) 4-digit numbers (first digit ≠ 0)

- First digit: 1–9 → 9 choices  
- Remaining digits: 0–9 → 10 choices each  

**Calculation:**  
9 × 10³ = 9000  

**Answer:** `9000`

---

## (3) Why are they different?

- PIN codes:
  - Can start with 0  
  - Treated as sequences  

- Numbers:
  - Cannot start with 0  
  - Must represent valid numerical values  

👉 Different rules → different counting models.

---

## (4) Why are 1234 and 4321 different?

- In PIN codes, **order matters**  
- Each position is independent  

👉 Therefore:
1234 ≠ 4321  

They are different sequences → different outcomes.


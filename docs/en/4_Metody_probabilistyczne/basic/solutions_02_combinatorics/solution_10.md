# 📘 Task 10 — Urn Models

## 🎯 Goal
Work with drawing balls from an urn under different rules:
- with / without order,
- with / without replacement (here: without replacement),
- counting outcomes correctly.

**Urn contents:**
- Red = 5  
- Blue = 4  
- Green = 3  
- Total = 12  

---

## 🧩 Problem 1 — 3 balls, no order (without replacement)

- Selecting 3 balls  
- Order does NOT matter  

👉 Model: **Combination**

**Calculation:**  
C(12,3) = 220  

**Answer:** `220`

---

## 🧩 Problem 2 — Exactly 2 red balls (no order)

Choose:
- 2 red from 5  
- 1 non-red from 7 (blue + green)

👉 Model: **Combination + Product Rule**

**Calculation:**  
C(5,2) × C(7,1)

C(5,2) = 10  
C(7,1) = 7  

10 × 7 = 70  

**Answer:** `70`

---

## 🧩 Problem 3 — 3 balls, order matters (colors recorded)

We record only colors (R, B, G), not individual balls.

Total balls = 12, without replacement.

👉 Model: **k-permutation**

**Calculation:**  
P(12,3) = 12 × 11 × 10 = 1320  

**Answer:** `1320`

---

## 🧩 Problem 4 — Exactly 2 red balls (order matters)

We count ordered sequences of colors.

### Step 1: Choose positions for red balls  
Choose 2 positions out of 3:  
C(3,2) = 3  

### Step 2: Choose actual balls  
- Red balls: P(5,2) = 5 × 4 = 20  
- Non-red ball: 7 choices  

### Step 3: Multiply  
3 × 20 × 7 = 420  

**Answer:** `420`

---

## ✅ Summary

| Problem | Result |
|--------|--------|
| No order (3 balls) | 220 |
| Exactly 2 red (no order) | 70 |
| Order matters | 1320 |
| Exactly 2 red (order matters) | 420 |

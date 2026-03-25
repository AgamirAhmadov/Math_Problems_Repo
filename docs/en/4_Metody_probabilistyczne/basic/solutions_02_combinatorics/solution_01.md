# Solution

# 📘 Task 1 — Applying Counting Models

## 🎯 Goal
For each problem:
- Identify the correct counting model  
- Compute the number of outcomes  
- Justify the choice  

---

## 🧩 Problem 1 — Arranging 7 students in a line

**Model:** Permutation  
- Using all objects  
- Order matters  
- No repetition  

**Formula:**  
Pₙ = n!

**Calculation:**  
7! = 5040  

**Answer:** `5040`

---

## 🧩 Problem 2 — Choosing 4 members from 12 people

**Model:** Combination  
- Using some objects  
- Order does NOT matter  

**Formula:**  
C(n, k) = n! / (k!(n−k)!)

**Calculation:**  
C(12,4) = 12! / (4!·8!) = 495  

**Answer:** `495`

---

## 🧩 Problem 3 — Assigning gold, silver, bronze (15 athletes)

**Model:** k-permutation  
- Using some objects  
- Order matters  
- No repetition  

**Formula:**  
P(n,k) = n! / (n−k)!

**Calculation:**  
P(15,3) = 15 × 14 × 13 = 2730  

**Answer:** `2730`

---

## 🧩 Problem 4 — Forming a 6-digit PIN code

**Model:** Sequence with repetition  
- Order matters  
- Repetition allowed  

**Formula:**  
nᵏ  

**Calculation:**  
10⁶ = 1,000,000  

**Answer:** `1,000,000`

---

## 🧩 Problem 5 — Arranging letters of BANANA

**Model:** Permutation with repeated elements  
- Using all objects  
- Some elements identical  

**Letter counts:**  
- A = 3  
- N = 2  
- B = 1  

**Formula:**  
n! / (n₁! · n₂! · ...)

**Calculation:**  
6! / (3!·2!) = 720 / (6·2) = 60  

**Answer:** `60`

---

## 🧩 Problem 6 — Seating 6 people around a round table

**Model:** Circular permutation  
- Using all objects  
- Circular arrangement  

**Formula:**  
(n−1)!

**Calculation:**  
5! = 120  

**Answer:** `120`

---

## ✅ Summary Table

| Problem | Model                          | Result     |
|--------|--------------------------------|------------|
| 1      | Permutation                    | 5040       |
| 2      | Combination                    | 495        |
| 3      | k-permutation                  | 2730       |
| 4      | Sequence with repetition       | 1,000,000  |
| 5      | Permutation with repetition    | 60         |
| 6      | Circular permutation           | 120        |

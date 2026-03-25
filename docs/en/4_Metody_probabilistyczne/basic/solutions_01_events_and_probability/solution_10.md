# 📘 Task 10 — Events and Probabilities in Buffon’s Needle Experiment

## 🎯 Goal
Work with a **continuous sample space** and compute probabilities using geometry.

---

## 🧩 Model

Variables:
- X ∈ [0, d/2] → distance to nearest line  
- θ ∈ [0, π/2] → angle  

Assumptions:
- X and θ are independent  
- Both are uniformly distributed  

👉 Sample space:
Ω = { (X, θ) | 0 ≤ X ≤ d/2, 0 ≤ θ ≤ π/2 }

Total area:
(d/2) × (π/2) = dπ/4  

---

# 🧩 Key Condition

The needle intersects a line if:

X ≤ (L/2) · sin(θ)

---

# 🧩 Events

## A — needle intersects a line

Region:
0 ≤ X ≤ (L/2) sin(θ)

👉 Probability:
P(A) = (2L) / (πd)

---

## B — needle does not intersect

Complement of A:

P(B) = 1 − (2L)/(πd)

---

## C — angle < π/6

θ ∈ [0, π/6]

👉 Probability:
(π/6) / (π/2) = 1/3  

---

## D — X < d/4

X ∈ [0, d/4]

👉 Probability:
(d/4) / (d/2) = 1/2  

---

## E — intersection AND θ > π/4

We compute:

P(E) = (4 / (dπ)) ∫[π/4 → π/2] (L/2) sin(θ) dθ  

= (2L / (dπ)) ∫[π/4 → π/2] sin(θ) dθ  

Integral:
∫ sin(θ)dθ = −cos(θ)

So:
= (2L / (dπ)) [−cos(θ)] from π/4 to π/2  

= (2L / (dπ)) (cos(π/4) − cos(π/2))  

= (2L / (dπ)) (√2/2 − 0)  

= (L√2) / (πd)

---

# ✅ Summary

| Event | Probability |
|------|------------|
| A (intersect) | 2L / (πd) |
| B (no intersect) | 1 − 2L/(πd) |
| C (θ < π/6) | 1/3 |
| D (X < d/4) | 1/2 |
| E (intersect & θ > π/4) | (L√2)/(πd) |

---

## 🚀 Key Ideas
- Continuous probability = area ratio  
- Use geometric conditions (X ≤ (L/2) sinθ)  
- Integrals replace counting  
- Independence simplifies calculations  

Buffon’s needle is a classic bridge between:
👉 geometry + probability + π estimation

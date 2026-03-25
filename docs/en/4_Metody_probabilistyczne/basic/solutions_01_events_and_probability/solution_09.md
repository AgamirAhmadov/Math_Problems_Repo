# 📘 Task 9 — Events and Probabilities in Weekly Weather Observation

## 🎯 Goal
- Work with sequences of independent outcomes  
- Describe events as subsets of Ω₇  
- Compute probabilities  

**Model:**
- 7 independent days  
- Each day: {S, C, R}  
- P(S) = P(C) = P(R) = 1/3  

---

## 🧩 Sample Space

Ω₇ = all sequences of length 7 over {S, C, R}  

|Ω₇| = 3⁷ = 2187  

Each outcome has probability:
(1/3)⁷  

---

# 🧩 Events

## A — weekend is sunny (Sat & Sun)

Fix 2 days = S  
Other 5 days arbitrary  

👉 Probability:
(1/3)² = 1/9  

---

## B — Wed, Thu, Fri all rainy

Fix 3 days = R  

👉 Probability:
(1/3)³ = 1/27  

---

## C — at least one sunny day

Use complement:

No sunny days → only C or R:
(2/3)⁷  

👉 Probability:
1 − (2/3)⁷  

---

## D — no rainy day

Only S or C allowed:

👉 Probability:
(2/3)⁷  

---

## E — exactly two sunny days

- Choose 2 days out of 7: C(7,2) = 21  
- Each such sequence:
(1/3)² × (2/3)⁵  

👉 Probability:
21 × (1/3)² × (2/3)⁵  

= 21 × (1/9) × (32/243)  
= 672 / 2187  

---

# 🧩 Additional Event

## F — all days different from previous (no two consecutive days equal)

- First day: 3 choices  
- Each next day: 2 choices (cannot repeat previous)  

Total sequences:
3 × 2⁶ = 192  

👉 Probability:
192 / 2187  

---

# ✅ Summary

| Event | Probability |
|------|------------|
| A | 1/9 |
| B | 1/27 |
| C | 1 − (2/3)⁷ |
| D | (2/3)⁷ |
| E | 672/2187 |
| F | 192/2187 |

---

## 🚀 Key Ideas
- Independent events → multiply probabilities  
- Fixing days → reduces degrees of freedom  
- “At least one” → use complement  
- Exact counts → combination × probability  

# 📘 Task 2 — Rolling a Die

## 🎯 Goal
Construct sample spaces for repeated die rolls and understand:
- ordered outcomes,
- how sample size grows,
- meaning of elementary outcomes.

---

## 🧩 1. One Roll of a Die

Possible outcomes:
- 1, 2, 3, 4, 5, 6  

👉 Sample space:
Ω₁ = {1, 2, 3, 4, 5, 6}

**Number of outcomes:**  
|Ω₁| = 6  

**Explanation:**  
An elementary outcome is the result of a single die roll.

---

## 🧩 2. Two Consecutive Rolls

Order matters → outcomes are ordered pairs.

👉 Sample space:
Ω₂ = {
(1,1), (1,2), (1,3), (1,4), (1,5), (1,6),  
(2,1), (2,2), ..., (2,6),  
...  
(6,1), (6,2), ..., (6,6)
}

**Number of outcomes:**  
|Ω₂| = 6 × 6 = 36  

**Explanation:**  
Each elementary outcome is an ordered pair:
(first roll, second roll)

Example:
(3,5) → first roll = 3, second roll = 5

---

## 🧩 3. Three Consecutive Rolls

👉 Sample space:
Ω₃ = all ordered triples:
(a, b, c), where a, b, c ∈ {1,2,3,4,5,6}

Examples:
(1,1,1), (2,3,4), (6,5,2), ..., (6,6,6)

**Number of outcomes:**  
|Ω₃| = 6³ = 216  

**Explanation:**  
Each elementary outcome is an ordered triple:
(first, second, third roll)

---

## 📊 Summary

| Experiment | Sample Space Size |
|-----------|------------------|
| 1 roll | 6 |
| 2 rolls | 36 |
| 3 rolls | 216 |

---

## 🚀 Key Insight

The number of outcomes follows:
6ⁿ

- Each roll has 6 possible results  
- Multiply for each step  

So:
- 1 roll → 6¹ = 6  
- 2 rolls → 6² = 36  
- 3 rolls → 6³ = 216  

---

## 🧠 What is an Elementary Outcome?

An elementary outcome is:
- one complete sequence of die results,
- one path in the experiment.

Examples:
- (2,6) → two rolls  
- (4,1,3) → three rolls  

Each outcome records the exact order of results.

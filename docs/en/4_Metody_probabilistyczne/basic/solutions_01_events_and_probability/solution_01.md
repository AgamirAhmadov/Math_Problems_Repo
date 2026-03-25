# 📘 Task 1 — Coin Tossing

## 🎯 Goal
Construct sample spaces for repeated coin tosses and understand:
- what an elementary outcome is,
- how the number of outcomes grows,
- why order matters.

---

## 🧩 1. One Coin Toss

Possible outcomes:
- H (Heads)
- T (Tails)

👉 Sample space:
Ω₁ = {H, T}

**Number of outcomes:**  
|Ω₁| = 2  

**Explanation:**  
An elementary outcome represents the result of one coin toss.

---

## 🧩 2. Two Coin Tosses

Order matters → outcomes are sequences.

👉 Sample space:
Ω₂ = {
(H,H), (H,T), (T,H), (T,T)
}

**Number of outcomes:**  
|Ω₂| = 4  

**Explanation:**  
Each elementary outcome is an ordered pair showing results of:
- first toss,
- second toss.

---

## 🧩 3. Three Coin Tosses

👉 Sample space:
Ω₃ = {
(H,H,H),
(H,H,T),
(H,T,H),
(H,T,T),
(T,H,H),
(T,H,T),
(T,T,H),
(T,T,T)
}

**Number of outcomes:**  
|Ω₃| = 8  

**Explanation:**  
Each elementary outcome is an ordered triple representing:
- first toss,
- second toss,
- third toss.

---

## 📊 Summary

| Experiment | Sample Space Size |
|-----------|------------------|
| 1 toss | 2 |
| 2 tosses | 4 |
| 3 tosses | 8 |

---

## 🚀 Key Insight

The number of outcomes follows:
2ⁿ

- Each toss has 2 possible results  
- Outcomes multiply at each step  

So:
- 1 toss → 2¹ = 2  
- 2 tosses → 2² = 4  
- 3 tosses → 2³ = 8  

---

## 🧠 What is an Elementary Outcome?

An elementary outcome is:
- a complete description of the experiment,
- a single path in a tree diagram,
- one exact sequence of results.

Examples:
- (H,T) → first toss Heads, second toss Tails  
- (T,H,H) → sequence of three tosses  

---

## 🌳 Tree Diagram Idea (optional)

Each level = one coin toss  
Each branch = H or T  

This helps visualize how:
- outcomes double each step,
- sequences are formed.

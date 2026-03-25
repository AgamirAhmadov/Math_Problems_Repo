# 📘 Task 4 — Weekly Weather Observation

## 🎯 Goal
Construct sample spaces for repeated observations and understand:
- sequences of outcomes,
- growth of sample space,
- meaning of elementary outcomes.

**Weather states:**
- S = Sunny  
- C = Cloudy  
- R = Rainy  

---

## 🧩 1. One Day Observation

👉 Sample space:
Ω₁ = {S, C, R}

**Number of outcomes:**  
|Ω₁| = 3  

**Explanation:**  
An elementary outcome represents the weather on a single day.

---

## 🧩 2. Two Consecutive Days

Order matters → outcomes are ordered pairs.

👉 Sample space:
Ω₂ = {
(S,S), (S,C), (S,R),  
(C,S), (C,C), (C,R),  
(R,S), (R,C), (R,R)
}

**Number of outcomes:**  
|Ω₂| = 3² = 9  

**Explanation:**  
Each outcome represents:
(first day weather, second day weather)

---

## 🧩 3. Seven Consecutive Days

👉 Sample space:
Ω₇ = all ordered sequences:
(w₁, w₂, w₃, w₄, w₅, w₆, w₇),  
where each wᵢ ∈ {S, C, R}

Examples:
(S,S,S,S,S,S,S)  
(S,C,R,S,C,R,S)  
(R,R,C,S,S,C,R)  
...  

**Number of outcomes:**  
|Ω₇| = 3⁷ = 2187  

---

## 📊 Summary

| Experiment | Sample Space Size |
|-----------|------------------|
| 1 day | 3 |
| 2 days | 9 |
| 7 days | 2187 |

---

## 🚀 Key Insight

The number of outcomes follows:
3ⁿ

- Each day has 3 possible states  
- Outcomes multiply across days  

So:
- 1 day → 3¹ = 3  
- 2 days → 3² = 9  
- 7 days → 3⁷ = 2187  

---

## 🧠 What is an Elementary Outcome?

An elementary outcome is:
- a complete description of the weather over the observed period,
- a full sequence of daily weather states.

Examples:
- (S,C,R,S,S,R,C) → weather over 7 days  
- (R,R,R,R,R,R,R) → all days rainy  

👉 Each outcome records the exact order of weather conditions.

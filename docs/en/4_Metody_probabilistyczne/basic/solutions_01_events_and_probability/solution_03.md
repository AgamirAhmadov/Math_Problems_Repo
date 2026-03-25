# 📘 Task 3 — Drawing Cards

## 🎯 Goal
Construct sample spaces for card draws and understand:
- ordered outcomes,
- difference between with/without replacement,
- meaning of elementary outcomes.

**Deck size:** 52 cards  

---

## 🧩 1. One Card Draw

👉 Sample space:
Ω₁ = {all 52 distinct cards}

Examples:
(A♠, K♦, 7♥, ...)

**Number of outcomes:**  
|Ω₁| = 52  

**Explanation:**  
An elementary outcome is a single specific card drawn.

---

## 🧩 2. Two Draws WITH Replacement

- After first draw, card is returned  
- Second draw again has 52 choices  

👉 Sample space:
Ω₂ = {(c₁, c₂) | c₁, c₂ ∈ deck}

Examples:
(A♠, A♠), (A♠, K♦), (7♥, 7♥), ...

**Number of outcomes:**  
|Ω₂| = 52 × 52 = 52² = 2704  

**Explanation:**  
Each outcome is an ordered pair:
(first card, second card)

Cards can repeat.

---

## 🧩 3. Two Draws WITHOUT Replacement

- First draw: 52 choices  
- Second draw: 51 choices  

👉 Sample space:
Ω₂′ = {(c₁, c₂) | c₁ ≠ c₂}

Examples:
(A♠, K♦), (7♥, Q♣), ...

**Number of outcomes:**  
|Ω₂′| = 52 × 51 = 2652  

**Explanation:**  
Each outcome is an ordered pair:
(first card, second card)

No card can appear twice.

---

## 📊 Summary

| Experiment | Sample Space Size |
|-----------|------------------|
| One draw | 52 |
| Two draws (with replacement) | 2704 |
| Two draws (without replacement) | 2652 |

---

## 🚀 Key Insight

- With replacement → number of choices stays constant  
- Without replacement → number of choices decreases  

Formulas:
- With replacement: n²  
- Without replacement: n × (n−1)

---

## 🧠 What is an Elementary Outcome?

An elementary outcome is:
- a complete ordered description of the experiment  

Examples:
- (A♠, K♦) → first draw Ace of spades, second draw King of diamonds  
- (7♥, 7♥) → only possible with replacement  

👉 Order matters, so:
(A♠, K♦) ≠ (K♦, A♠)

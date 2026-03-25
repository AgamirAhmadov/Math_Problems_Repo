# 📘 Task 8 — Events and Probabilities in Card Drawing

## 🎯 Goal
- Assign probabilities to outcomes  
- Describe events as subsets  
- Compute probabilities (with / without replacement)  

**Deck facts:**
- Total cards = 52  
- Hearts = 13  
- Kings = 4  
- Aces = 4  
- Face cards (J,Q,K) = 12  

---

# 🧩 1. Probabilities of Elementary Outcomes

## One draw (Ω₁)
|Ω₁| = 52 → each outcome:
P = 1/52  

---

## Two draws with replacement (Ω₂)
|Ω₂| = 52² = 2704 → each outcome:
P = 1/2704  

---

## Two draws without replacement (Ω₂′)
|Ω₂′| = 52 × 51 = 2652 → each outcome:
P = 1/2652  

---

# 🧩 2. One Card Draw

## A₁ — heart
13 hearts  

P(A₁) = 13/52 = 1/4  

---

## B₁ — king
4 kings  

P(B₁) = 4/52 = 1/13  

---

## C₁ — not a face card
Non-face cards = 52 − 12 = 40  

P(C₁) = 40/52 = 10/13  

---

# 🧩 3. Two Cards (WITH replacement)

## A₂ — both hearts
(13/52) × (13/52) = (1/4)² = 1/16  

---

## B₂ — same rank

- First card: anything  
- Second card: same rank → 4/52 = 1/13  

P(B₂) = 1/13  

---

## C₂ — at least one ace

Use complement:

No ace:
(48/52)² = (12/13)² = 144/169  

P(C₂) = 1 − 144/169 = 25/169  

---

# 🧩 4. Two Cards (WITHOUT replacement)

## A₃ — both hearts

(13/52) × (12/51)  

= (1/4) × (12/51)  
= 12/204 = 1/17  

---

## B₃ — same rank

- Choose rank: 13  
- Choose 2 of 4 cards: C(4,2) = 6  

Total favorable: 13 × 6 = 78  

P(B₃) = 78 / 2652 = 1/34  

---

## C₃ — one king and one queen

- Kings: 4  
- Queens: 4  

Ordered outcomes:
(K,Q) or (Q,K)

Total favorable:
4 × 4 × 2 = 32  

P(C₃) = 32 / 2652 = 8 / 663  

---

# 🧩 5. Additional Event

## D₃ — both cards are aces

(Without replacement)

- First ace: 4/52  
- Second ace: 3/51  

P(D₃) = (4/52) × (3/51) = 12/2652 = 1/221  

---

# ✅ Summary

| Event | Probability |
|------|------------|
| A₁ | 1/4 |
| B₁ | 1/13 |
| C₁ | 10/13 |
| A₂ | 1/16 |
| B₂ | 1/13 |
| C₂ | 25/169 |
| A₃ | 1/17 |
| B₃ | 1/34 |
| C₃ | 8/663 |
| D₃ | 1/221 |

---

## 🚀 Key Ideas
- With replacement → independent events  
- Without replacement → probabilities change  
- “At least one” → use complement  
- Count carefully: rank vs suit matters  

# 📘 Task 6 — Events and Probabilities in Coin Tossing

## 🎯 Goal
- Assign probabilities to elementary outcomes  
- Describe events as subsets of the sample space  
- Compute probabilities  

**Assumption:** fair coin → all outcomes equally likely  

---

# 🧩 1. Probabilities of Elementary Outcomes

## One toss (Ω₁)
Ω₁ = {H, T}  

Each outcome:
P(H) = P(T) = 1/2  

---

## Two tosses (Ω₂)
Ω₂ = {(H,H), (H,T), (T,H), (T,T)}  

Each outcome:
P = 1/4  

---

## Three tosses (Ω₃)
Ω₃ = {
(H,H,H), (H,H,T), (H,T,H), (H,T,T),  
(T,H,H), (T,H,T), (T,T,H), (T,T,T)
}

Each outcome:
P = 1/8  

---

# 🧩 2. One Coin Toss

## A₁ — result is heads
A₁ = {H}  

P(A₁) = 1/2  

---

## B₁ — result is tails
B₁ = {T}  

P(B₁) = 1/2  

---

## C₁ — result is not tails
C₁ = {H}  

P(C₁) = 1/2  

---

# 🧩 3. Two Coin Tosses

## A₂ — exactly one head
A₂ = {(H,T), (T,H)}  

P(A₂) = 2/4 = 1/2  

---

## B₂ — at least one head
B₂ = {(H,H), (H,T), (T,H)}  

P(B₂) = 3/4  

---

## C₂ — both tosses same
C₂ = {(H,H), (T,T)}  

P(C₂) = 2/4 = 1/2  

---

# 🧩 4. Three Coin Tosses

## A₃ — exactly two heads
A₃ = {(H,H,T), (H,T,H), (T,H,H)}  

P(A₃) = 3/8  

---

## B₃ — at least one tail
B₃ = Ω₃ \ {(H,H,H)}  

P(B₃) = 7/8  

---

## C₃ — all same
C₃ = {(H,H,H), (T,T,T)}  

P(C₃) = 2/8 = 1/4  

---

# 🧩 5. Additional Event (Example)

## D₃ — exactly one head
D₃ = {(H,T,T), (T,H,T), (T,T,H)}  

P(D₃) = 3/8  

---

# ✅ Summary

| Event | Probability |
|------|------------|
| A₁ | 1/2 |
| B₁ | 1/2 |
| C₁ | 1/2 |
| A₂ | 1/2 |
| B₂ | 3/4 |
| C₂ | 1/2 |
| A₃ | 3/8 |
| B₃ | 7/8 |
| C₃ | 1/4 |
| D₃ | 3/8 |

---

## 🚀 Key Ideas
- Equal probability → P(event) = favorable / total  
- Events = subsets of sample space  
- “At least one” → often easier using complement  
- Counting outcomes correctly is the key step  

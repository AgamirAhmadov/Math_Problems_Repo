# 📘 Task 7 — Events and Probabilities in Die Rolling

## 🎯 Goal
- Assign probabilities to elementary outcomes  
- Describe events as subsets  
- Compute probabilities using counting  

**Assumption:** fair die → all outcomes equally likely  

---

# 🧩 1. Probabilities of Elementary Outcomes

## One roll (Ω₁)
Ω₁ = {1,2,3,4,5,6}  

Each outcome:
P = 1/6  

---

## Two rolls (Ω₂)
All ordered pairs (a,b), a,b ∈ {1,...,6}  

|Ω₂| = 36 → each outcome:
P = 1/36  

---

## Three rolls (Ω₃)
All ordered triples (a,b,c)  

|Ω₃| = 216 → each outcome:
P = 1/216  

---

# 🧩 2. One Die Roll

## A₁ — result is even
A₁ = {2,4,6}  

P(A₁) = 3/6 = 1/2  

---

## B₁ — result > 4
B₁ = {5,6}  

P(B₁) = 2/6 = 1/3  

---

## C₁ — result ≤ 3
C₁ = {1,2,3}  

P(C₁) = 3/6 = 1/2  

---

# 🧩 3. Two Die Rolls

## A₂ — sum = 7
A₂ = {(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)}  

P(A₂) = 6/36 = 1/6  

---

## B₂ — both results same
B₂ = {(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)}  

P(B₂) = 6/36 = 1/6  

---

## C₂ — sum ≥ 10

Possible sums:
- 10 → (4,6),(5,5),(6,4) → 3  
- 11 → (5,6),(6,5) → 2  
- 12 → (6,6) → 1  

Total = 6  

P(C₂) = 6/36 = 1/6  

---

# 🧩 4. Three Die Rolls

## A₃ — sum = 10

Number of solutions:
27 outcomes  

P(A₃) = 27/216 = 1/8  

---

## B₃ — exactly two equal

- Choose value for the pair: 6  
- Choose value for different number: 5  
- Choose position of different number: 3  

Total = 6 × 5 × 3 = 90  

P(B₃) = 90/216 = 5/12  

---

## C₃ — two 2s and one 3

Permutations of (2,2,3):

Number of arrangements:
3  

P(C₃) = 3/216 = 1/72  

---

# 🧩 5. Additional Event

## D₃ — all three rolls different

- Choose 3 different numbers from 6: C(6,3) = 20  
- Arrange them: 3! = 6  

Total = 20 × 6 = 120  

P(D₃) = 120/216 = 5/9  

---

# ✅ Summary

| Event | Probability |
|------|------------|
| A₁ | 1/2 |
| B₁ | 1/3 |
| C₁ | 1/2 |
| A₂ | 1/6 |
| B₂ | 1/6 |
| C₂ | 1/6 |
| A₃ | 1/8 |
| B₃ | 5/12 |
| C₃ | 1/72 |
| D₃ | 5/9 |

---

## 🚀 Key Ideas
- Equal probability → count outcomes  
- Use symmetry and patterns (like sums)  
- Break problems into cases  
- For repeated values:
  - choose numbers,
  - choose positions,
  - multiply  

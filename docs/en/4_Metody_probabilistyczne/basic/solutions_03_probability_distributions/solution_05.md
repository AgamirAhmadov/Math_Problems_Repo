# 📘 Task 05 – Event Algebra in Card and Urn Problems

## 🎯 Goal
- Describe events using **set notation**
- Then compute probabilities using **basic rules**

---

# 🃏 1. Card Problem

## Sample Space
Standard deck → 52 cards

---

## Events

- **A:** card is a heart  
\[
A = \{\text{13 heart cards}\}
\]

- **B:** card is a king  
\[
B = \{\text{4 kings}\}
\]

---

## Set Operations

### Union \( A \cup B \)
\[
A \cup B = \{\text{hearts or kings}\}
\]

👉 includes all hearts + all kings (avoid double counting)

---

### Intersection \( A \cap B \)
\[
A \cap B = \{\text{King of Hearts}\}
\]

---

### Complement \( A^c \)
\[
A^c = \{\text{all non-heart cards}\}
\]

---

### Difference \( B \setminus A \)
\[
B \setminus A = \{\text{kings that are NOT hearts}\}
\]

👉 (3 kings: ♣ ♦ ♠)

---

# 🎱 2. Urn Problem

## Given
- 5 red  
- 3 blue  
- 2 green  
- Total = 10 balls  

---

## Events

- **A:** red  
\[
P(A) = \frac{5}{10} = 0.5
\]

- **B:** not green  
\[
B = \{\text{red or blue}\}
\]

\[
P(B) = \frac{5+3}{10} = \frac{8}{10} = 0.8
\]

---

## Intersection \( A \cap B \)

Red AND not green → still red

\[
A \cap B = A
\]

\[
P(A \cap B) = 0.5
\]

---

## Union \( A \cup B \)

Since A ⊆ B:

\[
A \cup B = B
\]

\[
P(A \cup B) = 0.8
\]

---

# 👩‍🎓 3. Delegation Problem

## Given
- 12 girls  
- 15 boys  
- Total = 27 people  
- Choose 3 people  

---

## Event

- **A:** at least one girl  

👉 Use complement:

- \( A^c \): no girls → all boys

---

## Step 1: Compute \( P(A^c) \)

Ways to choose 3 boys:

\[
\binom{15}{3}
\]

Total ways:

\[
\binom{27}{3}
\]

\[
P(A^c) = \frac{\binom{15}{3}}{\binom{27}{3}}
\]

---

## Step 2: Compute values

\[
\binom{15}{3} = 455
\]

\[
\binom{27}{3} = 2925
\]

\[
P(A^c) = \frac{455}{2925} \approx 0.1556
\]

---

## Step 3: Use complement

\[
P(A) = 1 - P(A^c)
\]

\[
P(A) = 1 - 0.1556 = 0.8444
\]

---

# 🧠 Summary

| Problem | Key Idea |
|--------|--------|
| Cards | Intersection avoids double counting |
| Urn | Subset simplifies union/intersection |
| Delegation | “At least one” → use complement |

---

# ✅ Final Insight

- Always define events as **sets first**
- Look for **subset relationships**
- Use complement for:
  - “at least one”
  - “none”
- Simplify before calculating

👉 Smart setup = easy solution

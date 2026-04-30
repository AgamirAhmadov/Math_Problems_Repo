# 📘 Task 07 – Conditional Probability in Dice, Cards, and Selection Problems

## 🎯 Goal
Solve the following problems.

1. Two fair dice are rolled. What is the probability that the sum is 6, given that at least one die shows a prime number?
2. From a group of 4 men and 3 women, 2 people are chosen at random. What is the probability that both chosen people are women?
3. A card is drawn from a standard deck. What is the probability that it is a face card, given that it is black?
4. two cards are drawn without replacement. What is the probability that both are aces, given that at least one is an ace?
---


# 📘 Task 07 – Simple Explanation + Solutions

## 🧠 Basic Concepts

### 🔹 Prime Number
A **prime number** is a number greater than 1 that has only **two divisors**:
- 1 and itself

Examples:
- 2, 3, 5 ✅
- 4 ❌ (divisible by 1,2,4)

👉 For a die (1–6), primes are:
\[
\{2,3,5\}
\]

---

### 🔹 Event
An **event** is a **set of outcomes**.

Example:
- Rolling a die → outcomes: {1,2,3,4,5,6}  
- Event “even number” → {2,4,6}

👉 Event = outcomes we care about

---

# 🎲 1. Two Dice Problem

### Given:
- A: sum = 6  
- B: at least one prime  

---

### Step 1: Total outcomes
\[
36
\]

---

### Step 2: A (sum = 6)
\[
(1,5),(2,4),(3,3),(4,2),(5,1)
\]  
→ 5 outcomes

---

### Step 3: B (at least one prime)

Non-prime = {1,4,6}  
Both non-prime:
\[
3 \times 3 = 9
\]

\[
|B| = 36 - 9 = 27
\]

---

### Step 4: A ∩ B
All 5 outcomes valid

---

### Result:
\[
P(A|B) = \frac{5}{27}
\]

---

# 👨‍👩‍👧 2. Selecting People

### Given:
- 3 women, 4 men  
- choose 2  

---

### Probability both women:
\[
P = \frac{\binom{3}{2}}{\binom{7}{2}} = \frac{3}{21} = \frac{1}{7}
\]

---

# 🃏 3. Card Problem

### Given:
- A: face card (J,Q,K → 12 cards)  
- B: black cards (26 cards)

---

### Black face cards:
6 cards (♠ and ♣)

---

### Result:
\[
P(A|B) = \frac{6}{26} = \frac{3}{13}
\]

---

# 🂡 4. Two Cards (Aces)

### Given:
- A: both aces  
- B: at least one ace  

---

### Total pairs:
\[
\binom{52}{2} = 1326
\]

---

### Both aces:
\[
\binom{4}{2} = 6
\]

---

### At least one ace:
\[
\binom{48}{2} = 1128
\]

\[
P(B) = 1 - \frac{1128}{1326} = \frac{198}{1326}
\]

---

### Result:
\[
P(A|B) = \frac{6}{198} = \frac{1}{33}
\]

---

# ✅ Final Answers

| Problem | Answer |
|--------|--------|
| Dice | \( \frac{5}{27} \) |
| People | \( \frac{1}{7} \) |
| Cards | \( \frac{3}{13} \) |
| Aces | \( \frac{1}{33} \) |

---

# 💡 Key Idea

- Prime → special numbers (2,3,5)  
- Event → group of outcomes  
- Conditional probability →  
👉 only consider cases where condition is true

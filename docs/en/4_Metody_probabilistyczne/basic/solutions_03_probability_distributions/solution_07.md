# 📘 Task 07 – Conditional Probability in Dice, Cards, and Selection Problems

## 🎯 Goal
Solve the following problems.

Two fair dice are rolled. What is the probability that the sum is 6, given that at least one die shows a prime number?
From a group of 4 men and 3 women, 2 people are chosen at random. What is the probability that both chosen people are women?
A card is drawn from a standard deck. What is the probability that it is a face card, given that it is black?
Two cards are drawn without replacement. What is the probability that both are aces, given that at least one is an ace?
---

# 🎲 1. Two Dice Problem

## Define Events

- **A:** sum = 6  
- **B:** at least one die shows a prime (2,3,5)

---

## Sample Space Size
\[
|\Omega| = 36
\]

---

## Step 1: Event A (sum = 6)

Possible outcomes:
\[
A = \{(1,5),(2,4),(3,3),(4,2),(5,1)\}
\]

---

## Step 2: Event B (at least one prime)

Prime numbers: 2,3,5  

Instead of listing directly, use complement:

- no primes = both in {1,4,6}

\[
|B^c| = 3 \times 3 = 9
\]

\[
|B| = 36 - 9 = 27
\]

---

## Step 3: Intersection \( A \cap B \)

From A, keep outcomes with at least one prime:

- (1,5) ✅  
- (2,4) ✅  
- (3,3) ✅  
- (4,2) ✅  
- (5,1) ✅  

\[
|A \cap B| = 5
\]

---

## Step 4: Conditional Probability

\[
P(A \mid B) = \frac{5/36}{27/36} = \frac{5}{27}
\]

✅ **Answer:**  
\[
P = \frac{5}{27}
\]

---

# 👨‍👩‍👧 2. Selection Problem

## Given
- 4 men, 3 women → total 7

---

## Event

Probability both selected are women:

\[
P = \frac{\binom{3}{2}}{\binom{7}{2}}
\]

\[
= \frac{3}{21} = \frac{1}{7}
\]

✅ **Answer:**  
\[
P = \frac{1}{7}
\]

---

# 🃏 3. Card Problem

## Define Events

- **A:** face card (J, Q, K → 12 cards)
- **B:** black card (26 cards)

---

## Intersection

Black face cards:
- J♠ Q♠ K♠  
- J♣ Q♣ K♣  

\[
|A \cap B| = 6
\]

---

## Conditional Probability

\[
P(A \mid B) = \frac{6}{26} = \frac{3}{13}
\]

✅ **Answer:**  
\[
P = \frac{3}{13}
\]

---

# 🂡 4. Two Cards Without Replacement

## Define Events

- **A:** both cards are aces  
- **B:** at least one ace  

---

## Step 1: Total ways
\[
\binom{52}{2} = 1326
\]

---

## Step 2: Event A (both aces)

\[
\binom{4}{2} = 6
\]

\[
P(A) = \frac{6}{1326}
\]

---

## Step 3: Event B (at least one ace)

Use complement:

- no ace = choose from 48 non-aces

\[
\binom{48}{2} = 1128
\]

\[
P(B) = 1 - \frac{1128}{1326} = \frac{198}{1326}
\]

---

## Step 4: Conditional Probability

Since \( A \subseteq B \):

\[
P(A \mid B) = \frac{P(A)}{P(B)} = \frac{6/1326}{198/1326} = \frac{6}{198}
\]

\[
= \frac{1}{33}
\]

✅ **Answer:**  
\[
P = \frac{1}{33}
\]

---

# 🧠 Summary

| Problem | Result |
|--------|--------|
| Dice | \( \frac{5}{27} \) |
| Selection | \( \frac{1}{7} \) |
| Cards (black → face) | \( \frac{3}{13} \) |
| Two cards (aces) | \( \frac{1}{33} \) |

---

# ✅ Final Insight

- Always define events clearly  
- Use complement to simplify  
- If \( A \subseteq B \), then:
\[
P(A \mid B) = \frac{P(A)}{P(B)}
\]

👉 Conditional probability = **restricted sample space**

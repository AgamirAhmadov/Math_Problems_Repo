# 📘 Task 01 – Basic Event Notation and Set Operations

## 🎯 Goal
For each experiment:
- Define the **sample space** \( \Omega \)
- Define **events**
- Express them using **set operations** (union, intersection, complement, difference)

---

# 🧪 1. One Toss of a Coin

## Sample Space
\[
\Omega = \{H, T\}
\]

## Events

- **A: result is heads**
\[
A = \{H\}
\]

- **B: result is not tails**
\[
B = T^c = \{H\}
\]

## Complement
\[
A^c = \{T\}
\]

---

# 🎲 2. One Roll of a Fair Die

## Sample Space
\[
\Omega = \{1,2,3,4,5,6\}
\]

## Events

- **A: even number**
\[
A = \{2,4,6\}
\]

- **B: number greater than 3**
\[
B = \{4,5,6\}
\]

## Set Operations

- **Intersection (A AND B)**
\[
A \cap B = \{4,6\}
\]

- **Union (A OR B)**
\[
A \cup B = \{2,4,5,6\}
\]

- **Difference (A but not B)**
\[
A \setminus B = \{2\}
\]

- **Complement of A**
\[
A^c = \{1,3,5\}
\]

---

# 🪙🪙 3. Two Tosses of a Coin

## Sample Space
\[
\Omega = \{HH, HT, TH, TT\}
\]

## Events

- **A: at least one head**
\[
A = \Omega \setminus \{TT\} = \{HH, HT, TH\}
\]

- **B: both tosses give the same result**
\[
B = \{HH, TT\}
\]

## Set Operations

- **Intersection**
\[
A \cap B = \{HH\}
\]

- **Union**
\[
A \cup B = \{HH, HT, TH, TT\} = \Omega
\]

---

# 🃏 4. Drawing One Card from a Deck

## Sample Space
\[
\Omega = \text{all 52 cards}
\]

## Events

- **A: card is a heart**
\[
A = \{\text{13 heart cards}\}
\]

- **B: card is a face card (J, Q, K)**
\[
B = \{\text{J, Q, K of all suits}\}
\]

## Set Operations

- **Intersection (heart AND face card)**
\[
A \cap B = \{\text{J♥, Q♥, K♥}\}
\]

- **Union (heart OR face card)**
\[
A \cup B = A + B - (A \cap B)
\]

- **Difference (heart but not face)**
\[
A \setminus B = \{\text{hearts except J, Q, K}\}
\]

- **Complement of A**
\[
A^c = \{\text{all non-heart cards}\}
\]

---

# 🧠 Summary

## Key Translations

- "at least one" → use complement  
- "both" → intersection  
- "or" → union  
- "not" → complement  

## Set Operations

| Operation | Meaning |
|----------|--------|
| \( A \cup B \) | A OR B |
| \( A \cap B \) | A AND B |
| \( A^c \) | NOT A |
| \( A \setminus B \) | A but NOT B |

---

# ✅ Final Insight

The main idea is to translate:

**words → sets → operations**

This is the foundation for probability calculations.

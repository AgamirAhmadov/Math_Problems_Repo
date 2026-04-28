# 📘 Task 03 – Event Algebra for Two Coin Tosses

## 🎯 Given

Experiment: toss a fair coin twice

---

# 🧪 Sample Space

\[
\Omega = \{HH, HT, TH, TT\}
\]

---

# 🎲 Events

## Event A: “at least one head occurs”

👉 Easier using complement:
- no head = TT

\[
A = \{HH, HT, TH\}
\]

---

## Event B: “both tosses give the same result”

\[
B = \{HH, TT\}
\]

---

# 🔢 Computations

## 1. Union \( A \cup B \)

\[
A \cup B = \{HH, HT, TH, TT\} = \Omega
\]

👉 **Meaning:** at least one head OR same result (always happens)

---

## 2. Intersection \( A \cap B \)

\[
A \cap B = \{HH\}
\]

👉 **Meaning:** at least one head AND same result

---

## 3. Complement of A \( A^c \)

\[
A^c = \{TT\}
\]

👉 **Meaning:** no head occurs

---

## 4. Complement of B \( B^c \)

\[
B^c = \{HT, TH\}
\]

👉 **Meaning:** different results

---

## 5. Difference \( A \setminus B \)

\[
A \setminus B = \{HT, TH\}
\]

👉 **Meaning:** at least one head but NOT same result

---

## 6. Difference \( B \setminus A \)

\[
B \setminus A = \{TT\}
\]

👉 **Meaning:** same result but NO head

---

# ❓ Properties

## Are A and B mutually exclusive?

Check:
\[
A \cap B = \{HH\} \neq \emptyset
\]

❌ **No, they are NOT mutually exclusive**

---

## Are A and B independent?

Check independence:
\[
P(A \cap B) = P(A) \cdot P(B)
\]

### Step 1: Probabilities

\[
P(A) = \frac{3}{4}, \quad P(B) = \frac{2}{4} = \frac{1}{2}
\]

\[
P(A \cap B) = \frac{1}{4}
\]

### Step 2: Compare

\[
P(A) \cdot P(B) = \frac{3}{4} \cdot \frac{1}{2} = \frac{3}{8}
\]

\[
P(A \cap B) = \frac{1}{4}
\]

Since:
\[
\frac{1}{4} \neq \frac{3}{8}
\]

❌ **A and B are NOT independent**

---

# 🧠 Summary

| Expression | Result | Meaning |
|----------|--------|--------|
| \( A \cup B \) | Ω | always occurs |
| \( A \cap B \) | {HH} | head and same |
| \( A^c \) | {TT} | no head |
| \( B^c \) | {HT, TH} | different |
| \( A \setminus B \) | {HT, TH} | head but different |
| \( B \setminus A \) | {TT} | same but no head |

---

# ✅ Final Insight

- “At least one” → use complement  
- Independence ≠ mutual exclusivity  
- Always check independence using probabilities  

👉 Events can overlap but still be dependent

# 📘 Task 02 – Algebra of Events in a Finite Sample Space

## 🎯 Given

Experiment: roll a fair die once

## Sample Space
\[
\Omega = \{1,2,3,4,5,6\}
\]

## Events

- **A: even numbers**
\[
A = \{2,4,6\}
\]

- **B: prime numbers**
\[
B = \{2,3,5\}
\]

---

# 🔢 Computations

## 1. Union \( A \cup B \)

All elements that are in A or B:

\[
A \cup B = \{2,3,4,5,6\}
\]

👉 **Meaning:** number is even OR prime

---

## 2. Intersection \( A \cap B \)

Common elements:

\[
A \cap B = \{2\}
\]

👉 **Meaning:** number is both even AND prime

---

## 3. Complement of A \( A^c \)

Elements not in A:

\[
A^c = \{1,3,5\}
\]

👉 **Meaning:** number is NOT even (odd numbers)

---

## 4. Complement of B \( B^c \)

Elements not in B:

\[
B^c = \{1,4,6\}
\]

👉 **Meaning:** number is NOT prime

---

## 5. Difference \( A \setminus B \)

Elements in A but NOT in B:

\[
A \setminus B = \{4,6\}
\]

👉 **Meaning:** even but NOT prime

---

## 6. Difference \( B \setminus A \)

Elements in B but NOT in A:

\[
B \setminus A = \{3,5\}
\]

👉 **Meaning:** prime but NOT even

---

# ❓ Properties

## Are A and B mutually exclusive?

Mutually exclusive means:
\[
A \cap B = \emptyset
\]

But:
\[
A \cap B = \{2\} \neq \emptyset
\]

❌ **No, they are NOT mutually exclusive**

---

## Is one event a subset of the other?

Check:

- Is \( A \subseteq B \)? → ❌ (4,6 not in B)
- Is \( B \subseteq A \)? → ❌ (3,5 not in A)

❌ **No subset relation**

---

# 🧠 Summary

| Expression | Result | Meaning |
|----------|--------|--------|
| \( A \cup B \) | {2,3,4,5,6} | even OR prime |
| \( A \cap B \) | {2} | even AND prime |
| \( A^c \) | {1,3,5} | not even |
| \( B^c \) | {1,4,6} | not prime |
| \( A \setminus B \) | {4,6} | even but not prime |
| \( B \setminus A \) | {3,5} | prime but not even |

---

# ✅ Final Insight

- Intersection shows **overlap**
- Union combines **all possibilities**
- Difference isolates **what is unique**
- Complement flips the event

👉 Always think: **set operations = logic of events**

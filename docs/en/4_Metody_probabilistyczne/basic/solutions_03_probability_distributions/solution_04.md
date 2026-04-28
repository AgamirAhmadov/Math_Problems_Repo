# 📘 Task 04 – Basic Probability Properties

## 🎯 Goal
Use standard probability rules:
- Complement rule  
- Inclusion–Exclusion formula  
- Properties of mutually exclusive and independent events  

---

# 🔢 1. Complement Rule

Given:
\[
P(A) = 0.35
\]

Use:
\[
P(A^c) = 1 - P(A)
\]

\[
P(A^c) = 1 - 0.35 = 0.65
\]

✅ **Answer:**  
\[
P(A^c) = 0.65
\]

---

# 🔢 2. Inclusion–Exclusion Formula

Given:
\[
P(A) = 0.4,\quad P(B) = 0.5,\quad P(A \cap B) = 0.2
\]

Use:
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

\[
P(A \cup B) = 0.4 + 0.5 - 0.2 = 0.7
\]

✅ **Answer:**  
\[
P(A \cup B) = 0.7
\]

---

# 🔢 3. Mutually Exclusive Events

Given:
\[
P(A) = 0.18,\quad P(B) = 0.27
\]

For mutually exclusive events:
\[
P(A \cap B) = 0
\]

So:
\[
P(A \cup B) = P(A) + P(B)
\]

\[
P(A \cup B) = 0.18 + 0.27 = 0.45
\]

✅ **Answer:**  
\[
P(A \cup B) = 0.45
\]

---

# 🔢 4. Find Intersection

Given:
\[
P(A \cup B) = 0.9,\quad P(A) = 0.6,\quad P(B) = 0.5
\]

Use:
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

Solve:
\[
0.9 = 0.6 + 0.5 - P(A \cap B)
\]

\[
0.9 = 1.1 - P(A \cap B)
\]

\[
P(A \cap B) = 1.1 - 0.9 = 0.2
\]

✅ **Answer:**  
\[
P(A \cap B) = 0.2
\]

---

# ❓ 5. Can Events Be Both Mutually Exclusive and Independent?

## Conditions

- Mutually exclusive:
\[
P(A \cap B) = 0
\]

- Independent:
\[
P(A \cap B) = P(A)\cdot P(B)
\]

## Combine both:

\[
0 = P(A)\cdot P(B)
\]

This implies:
\[
P(A) = 0 \quad \text{or} \quad P(B) = 0
\]

---

## Conclusion

❌ **No, they cannot both be true if both probabilities are positive**

Because:
- If \( P(A) > 0 \) and \( P(B) > 0 \), then  
\[
P(A)\cdot P(B) > 0
\]
- But mutual exclusivity requires:
\[
P(A \cap B) = 0
\]

⚠️ Contradiction

---

# ✅ Final Insight

- Complement rule is the simplest tool  
- Inclusion–Exclusion avoids double counting  
- Mutually exclusive ≠ independent  
- Independence requires multiplication, not zero overlap  

👉 Always check definitions carefully before computing

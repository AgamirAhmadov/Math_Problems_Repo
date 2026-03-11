## Task 8

### Useful Definitions and Formulas

**Classical probability**

If all outcomes are equally likely, the probability of an event $A$ is

$$
P(A) = \frac{|A|}{|\Omega|}
$$

where

- $|A|$ – number of favorable outcomes  
- $|\Omega|$ – number of all possible outcomes

---

**Conditional probability**

If event $B$ occurs after event $A$, then

$$
P(B|A) = \frac{P(A \cap B)}{P(A)}
$$

When events occur sequentially, we often use

$$
P(A \cap B) = P(A) \cdot P(B|A)
$$

---

### Given Data

Total number of pulses:

$$
7
$$

Composition of pulses:

- $4$ pulses of type $A$
- $2$ pulses of type $B$
- $1$ pulse of type $C$

Thus

$$
4 + 2 + 1 = 7
$$

All pulse arrangements are assumed **random**.

---

# 1. Probability that the first received pulse will be $A$

Number of pulses of type $A$:

$$
4
$$

Total pulses:

$$
7
$$

Therefore

$$
P(A_1) = \frac{4}{7}
$$

---

# 2. Probability that the first received pulse will be $A$ or $C$

Number of favorable pulses:

- $A$: $4$
- $C$: $1$

Total favorable outcomes:

$$
4 + 1 = 5
$$

Thus

$$
P(A \text{ or } C) = \frac{5}{7}
$$

---

# 3. Probability that the first two pulses will be $A$ and $C$ (in that order)

Step 1: Probability that the first pulse is $A$

$$
P(A_1) = \frac{4}{7}
$$

Step 2: After removing one $A$, the remaining pulses are:

- $3$ pulses of $A$
- $2$ pulses of $B$
- $1$ pulse of $C$

Total remaining pulses:

$$
6
$$

Probability that the second pulse is $C$:

$$
P(C_2|A_1) = \frac{1}{6}
$$

Step 3: Multiply the probabilities

$$
P(A_1 \cap C_2) = P(A_1) \cdot P(C_2|A_1)
$$

$$
P(A_1 \cap C_2) = \frac{4}{7} \cdot \frac{1}{6}
$$

$$
P(A_1 \cap C_2) = \frac{4}{42}
$$

$$
P(A_1 \cap C_2) = \frac{2}{21}
$$

---

# Final Results

$$
P(\text{first pulse } = A) = \frac{4}{7}
$$

$$
P(\text{first pulse } = A \text{ or } C) = \frac{5}{7}
$$

$$
P(\text{first two pulses } = A,C) = \frac{2}{21}
$$

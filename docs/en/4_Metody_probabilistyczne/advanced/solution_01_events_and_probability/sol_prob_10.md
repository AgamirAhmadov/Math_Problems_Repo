## Task 10

### Useful Definitions and Formulas

**Total Probability Formula**

If a received signal can originate from several transmitted signals, then the probability of receiving a specific signal $B$ is

$$
P(B) = \sum_i P(A_i)P(B|A_i)
$$

where  

- $A_i$ – transmitted signals  
- $B$ – received signal  

---

**Independent transmission errors**

Each letter is affected by interference **independently**.  
Therefore the probability of receiving a sequence is the **product of the probabilities for each letter**.

$$
P(X_1X_2X_3X_4) = P(X_1)\cdot P(X_2)\cdot P(X_3)\cdot P(X_4)
$$

---

## Given Data

Possible transmitted sequences:

$$
AAAA \quad P=0.4
$$

$$
BBBB \quad P=0.3
$$

$$
CCCC \quad P=0.3
$$

Single-letter transmission probabilities:

| Transmitted → Received | A | B | C |
|---|---|---|---|
| A | 0.8 | 0.1 | 0.1 |
| B | 0.1 | 0.8 | 0.1 |
| C | 0.1 | 0.1 | 0.8 |

---

# 1. Probability of receiving signal $AAAA$

Using total probability:

$$
P(AAAA) =
P(AAAA|AAAA)P(AAAA)
+
P(AAAA|BBBB)P(BBBB)
+
P(AAAA|CCCC)P(CCCC)
$$

---

### Case 1: transmitted $AAAA$

$$
P(AAAA|AAAA) = 0.8^4
$$

$$
0.8^4 = 0.4096
$$

Contribution:

$$
0.4 \cdot 0.4096 = 0.16384
$$

---

### Case 2: transmitted $BBBB$

Each $B$ must be received as $A$:

$$
P(AAAA|BBBB) = 0.1^4
$$

$$
0.1^4 = 0.0001
$$

Contribution:

$$
0.3 \cdot 0.0001 = 0.00003
$$

---

### Case 3: transmitted $CCCC$

Each $C$ must be received as $A$:

$$
P(AAAA|CCCC) = 0.1^4
$$

Contribution:

$$
0.3 \cdot 0.0001 = 0.00003
$$

---

### Final probability

$$
P(AAAA) = 0.16384 + 0.00003 + 0.00003
$$

$$
P(AAAA) = 0.16390
$$

---

# 2. Probability of receiving signal $ACAA$

Again apply total probability.

$$
P(ACAA) =
P(ACAA|AAAA)P(AAAA)
+
P(ACAA|BBBB)P(BBBB)
+
P(ACAA|CCCC)P(CCCC)
$$

---

### Case 1: transmitted $AAAA$

Required transitions:

- $A \to A = 0.8$
- $A \to C = 0.1$
- $A \to A = 0.8$
- $A \to A = 0.8$

$$
P(ACAA|AAAA) = 0.8 \cdot 0.1 \cdot 0.8 \cdot 0.8
$$

$$
P(ACAA|AAAA) = 0.0512
$$

Contribution:

$$
0.4 \cdot 0.0512 = 0.02048
$$

---

### Case 2: transmitted $BBBB$

Required transitions:

- $B \to A = 0.1$
- $B \to C = 0.1$
- $B \to A = 0.1$
- $B \to A = 0.1$

$$
P(ACAA|BBBB) = 0.1^4
$$

Contribution:

$$
0.3 \cdot 0.0001 = 0.00003
$$

---

### Case 3: transmitted $CCCC$

Required transitions:

- $C \to A = 0.1$
- $C \to C = 0.8$
- $C \to A = 0.1$
- $C \to A = 0.1$

$$
P(ACAA|CCCC) = 0.1 \cdot 0.8 \cdot 0.1 \cdot 0.1
$$

$$
P(ACAA|CCCC) = 0.0008
$$

Contribution:

$$
0.3 \cdot 0.0008 = 0.00024
$$

---

### Final probability

$$
P(ACAA) = 0.02048 + 0.00003 + 0.00024
$$

$$
P(ACAA) = 0.02075
$$

---

# Final Results

$$
P(AAAA) = 0.16390
$$

$$
P(ACAA) = 0.02075
$$

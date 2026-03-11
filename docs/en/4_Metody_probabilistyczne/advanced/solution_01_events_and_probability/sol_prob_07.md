## Task 7

### Useful Definitions and Formulas

**Total Probability Formula**

If a signal can originate from different sources (events) $A_1, A_2$, then the probability of receiving a specific signal $B$ is

$$
P(B) = P(A_1)P(B|A_1) + P(A_2)P(B|A_2)
$$

---

**Independent disturbances**

If each transmitted symbol is disturbed **independently**, the probability of receiving a sequence equals the **product of the probabilities for each symbol**.

$$
P(XYZ) = P(X) \cdot P(Y) \cdot P(Z)
$$

---

### Given Data

Two possible transmitted signals:

$$
111 \quad \text{with probability} \quad 0.65
$$

$$
000 \quad \text{with probability} \quad 0.35
$$

Noise properties:

- $1 \rightarrow 0$ with probability $0.2$
- $1 \rightarrow 1$ with probability $0.8$

- $0 \rightarrow 1$ with probability $0.2$
- $0 \rightarrow 0$ with probability $0.8$

Errors occur **independently for each symbol**.

---

# 1. Probability of receiving signal 111

Using total probability:

$$
P(111) = P(111|111)P(111) + P(111|000)P(000)
$$

First compute the conditional probabilities.

If **111 was transmitted**:

$$
P(111|111) = 0.8 \cdot 0.8 \cdot 0.8
$$

$$
P(111|111) = 0.512
$$

If **000 was transmitted**:

$$
P(111|000) = 0.2 \cdot 0.2 \cdot 0.2
$$

$$
P(111|000) = 0.008
$$

Now apply total probability:

$$
P(111) = 0.65 \cdot 0.512 + 0.35 \cdot 0.008
$$

$$
P(111) = 0.3328 + 0.0028
$$

$$
P(111) = 0.3356
$$

---

# 2. Probability of receiving signal 000

Again apply total probability:

$$
P(000) = P(000|111)P(111) + P(000|000)P(000)
$$

If **111 was transmitted**:

$$
P(000|111) = 0.2 \cdot 0.2 \cdot 0.2
$$

$$
P(000|111) = 0.008
$$

If **000 was transmitted**:

$$
P(000|000) = 0.8 \cdot 0.8 \cdot 0.8
$$

$$
P(000|000) = 0.512
$$

Substitute values:

$$
P(000) = 0.65 \cdot 0.008 + 0.35 \cdot 0.512
$$

$$
P(000) = 0.0052 + 0.1792
$$

$$
P(000) = 0.1844
$$

---

# 3. Probability of receiving signal 010

Using total probability:

$$
P(010) = P(010|111)P(111) + P(010|000)P(000)
$$

---

If **111 was transmitted**:

- $1 \rightarrow 0$ with probability $0.2$
- $1 \rightarrow 1$ with probability $0.8$
- $1 \rightarrow 0$ with probability $0.2$

$$
P(010|111) = 0.2 \cdot 0.8 \cdot 0.2
$$

$$
P(010|111) = 0.032
$$

---

If **000 was transmitted**:

- $0 \rightarrow 0$ with probability $0.8$
- $0 \rightarrow 1$ with probability $0.2$
- $0 \rightarrow 0$ with probability $0.8$

$$
P(010|000) = 0.8 \cdot 0.2 \cdot 0.8
$$

$$
P(010|000) = 0.128
$$

---

Now apply total probability:

$$
P(010) = 0.65 \cdot 0.032 + 0.35 \cdot 0.128
$$

$$
P(010) = 0.0208 + 0.0448
$$

$$
P(010) = 0.0656
$$

---

# Final Results

$$
P(111) = 0.3356
$$

$$
P(000) = 0.1844
$$

$$
P(010) = 0.0656
$$

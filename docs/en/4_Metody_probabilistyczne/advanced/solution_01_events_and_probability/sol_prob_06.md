## Task 6

### Useful Definitions and Formulas

**Total Probability Formula**

If events $A_1, A_2, ..., A_n$ form a partition of the sample space, then the probability of event $B$ is

$$
P(B) = \sum_{i=1}^{n} P(A_i)P(B|A_i)
$$

---

**Bayes' Theorem**

Bayes' theorem allows us to compute the probability of a cause given the observed event.

$$
P(A_i|B) = \frac{P(A_i)P(B|A_i)}{P(B)}
$$

where

- $A_i$ – possible causes
- $B$ – observed event

---

## Given Data

Production ratio:

$$
3 : 2
$$

Thus the probabilities that a randomly selected product comes from each machine are

$$
P(A_1) = \frac{3}{5}, \quad P(A_2) = \frac{2}{5}
$$

Quality probabilities:

$$
P(B|A_1) = 0.65
$$

$$
P(B|A_2) = 0.85
$$

where

- $B$ = event "product is first-grade"

---

# 1. Probability that the selected product is first-grade

Using the **total probability formula**:

$$
P(B) = P(A_1)P(B|A_1) + P(A_2)P(B|A_2)
$$

Substitute the values:

$$
P(B) = \frac{3}{5} \cdot 0.65 + \frac{2}{5} \cdot 0.85
$$

Calculate each part:

$$
\frac{3}{5} \cdot 0.65 = 0.39
$$

$$
\frac{2}{5} \cdot 0.85 = 0.34
$$

Add the results:

$$
P(B) = 0.39 + 0.34
$$

$$
P(B) = 0.73
$$

---

# 2. Probability that the product came from the first machine

We use **Bayes' theorem**.

$$
P(A_1|B) = \frac{P(A_1)P(B|A_1)}{P(B)}
$$

Substitute the values:

$$
P(A_1|B) = \frac{\frac{3}{5} \cdot 0.65}{0.73}
$$

Compute the numerator:

$$
\frac{3}{5} \cdot 0.65 = 0.39
$$

Thus

$$
P(A_1|B) = \frac{0.39}{0.73}
$$

$$
P(A_1|B) \approx 0.534
$$

---

# Final Results

$$
P(\text{first-grade product}) = 0.73
$$

$$
P(\text{product from machine 1 | first-grade}) \approx 0.534
$$

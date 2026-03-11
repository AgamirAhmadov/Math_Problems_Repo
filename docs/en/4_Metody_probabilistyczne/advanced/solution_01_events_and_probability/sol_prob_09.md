## Task 9

### Useful Definitions and Formulas

**Independent events**

Events are independent if the occurrence of one does not affect the probability of the other.  
If events $A$ and $B$ are independent:

$$
P(A \cap B) = P(A)\cdot P(B)
$$

---

**Complement of an event**

The complement of event $A$ means that event $A$ does **not occur**.

$$
P(A') = 1 - P(A)
$$

---

**Probability that at least one event occurs**

For independent events $A_1, A_2, ..., A_n$, the probability that **at least one occurs** is

$$
P(\text{at least one}) = 1 - P(A_1' \cap A_2' \cap ... \cap A_n')
$$

---

## Given Data

Three plants produce goods.

Probability of producing a first-quality item:

$$
P(A_1) = 0.97
$$

$$
P(A_2) = 0.90
$$

$$
P(A_3) = 0.86
$$

One item is taken **from each plant**, so the events are independent.

We want the probability that **a randomly taken item among the three is of first quality**,  
which means **at least one of the three items is first-quality**.

---

## Step 1: Compute probabilities of non–first-quality items

$$
P(A_1') = 1 - 0.97 = 0.03
$$

$$
P(A_2') = 1 - 0.90 = 0.10
$$

$$
P(A_3') = 1 - 0.86 = 0.14
$$

---

## Step 2: Probability that none of the items is first-quality

Since the events are independent:

$$
P(A_1' \cap A_2' \cap A_3') =
0.03 \cdot 0.10 \cdot 0.14
$$

$$
P(A_1' \cap A_2' \cap A_3') = 0.00042
$$

---

## Step 3: Probability that at least one item is first-quality

$$
P(\text{at least one first-quality}) =
1 - P(A_1' \cap A_2' \cap A_3')
$$

$$
P = 1 - 0.00042
$$

$$
P = 0.99958
$$

---

## Final Result

$$
P(\text{at least one first-quality item}) = 0.99958
$$

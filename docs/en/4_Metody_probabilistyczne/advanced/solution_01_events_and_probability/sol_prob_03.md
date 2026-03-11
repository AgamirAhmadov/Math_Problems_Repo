## Task 3

### Useful Definitions and Formulas

**Sample space**

The sample space is the set of all possible elementary outcomes of an experiment.

$$
\Omega = \{\omega_1, \omega_2, ..., \omega_n\}
$$

---

**Classical probability definition**

If all elementary outcomes are equally likely, the probability of event $A$ is

$$
P(A) = \frac{|A|}{|\Omega|}
$$

where

- $|A|$ = number of favorable outcomes  
- $|\Omega|$ = total number of possible outcomes

---

**Elementary event representation**

In this problem each outcome is a pair

$$
(time,\ errors)
$$

---

## Step 1: Construct the Sample Space

Possible times:

$$
T = \{4,5,6\}
$$

Possible number of errors:

$$
E = \{0,1,2\}
$$

All combinations give the sample space:

$$
\Omega =
\{(4,0),(4,1),(4,2),
(5,0),(5,1),(5,2),
(6,0),(6,1),(6,2)\}
$$

Total number of outcomes:

$$
|\Omega| = 9
$$

---

# 1. The job will be completed in 4 hours

Event:

$$
A = \{(4,0),(4,1),(4,2)\}
$$

Number of favorable outcomes:

$$
|A| = 3
$$

Probability:

$$
P(A) = \frac{3}{9}
$$

$$
P(A) = \frac{1}{3}
$$

---

# 2. The job will be completed flawlessly in 6 hours

"Flawlessly" means **0 errors**.

Event:

$$
B = \{(6,0)\}
$$

Number of favorable outcomes:

$$
|B| = 1
$$

Probability:

$$
P(B) = \frac{1}{9}
$$

---

# 3. The job will be completed in at most 5 hours

"At most 5 hours" means **4 or 5 hours**.

Event:

$$
C =
\{(4,0),(4,1),(4,2),
(5,0),(5,1),(5,2)\}
$$

Number of favorable outcomes:

$$
|C| = 6
$$

Probability:

$$
P(C) = \frac{6}{9}
$$

$$
P(C) = \frac{2}{3}
$$

---

# 4. The job will be completed in at most 5 hours and with at most one error

Conditions:

- time $\le 5$
- errors $\le 1$

Possible outcomes:

$$
D = \{(4,0),(4,1),(5,0),(5,1)\}
$$

Number of favorable outcomes:

$$
|D| = 4
$$

Probability:

$$
P(D) = \frac{4}{9}
$$

---

# Final Results

$$
P(\text{4 hours}) = \frac{1}{3}
$$

$$
P(\text{6 hours with 0 errors}) = \frac{1}{9}
$$

$$
P(\text{at most 5 hours}) = \frac{2}{3}
$$

$$
P(\text{at most 5 hours and at most 1 error}) = \frac{4}{9}
$$

## Task 4

### Useful Definitions and Formulas

**Union of events**

The union of two events means that **at least one of them occurs**.

$$
A_1 \cup A_2
$$

represents the event that **element $a_1$ or element $a_2$ is functional**.

---

**Intersection of events**

The intersection represents the event that **both events occur simultaneously**.

$$
A_1 \cap A_2
$$

---

**Addition rule for probabilities**

For any two events $A$ and $B$:

$$
P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$

This formula avoids **double counting** when both events occur.

---

### Step 1: Describe the event of continuous current flow

The two elements $a_1$ and $a_2$ are connected **in parallel**.

In a parallel circuit, the current flows if **at least one element remains functional**.

Therefore, the event that the current flows for at least time $t$ is

$$
A = A_1 \cup A_2
$$

---

### Step 2: Apply the probability addition rule

Using the union probability formula:

$$
P(A_1 \cup A_2) = P(A_1) + P(A_2) - P(A_1 \cap A_2)
$$

---

### Step 3: Substitute the given probabilities

Given:

$$
P(A_1) = p
$$

$$
P(A_2) = p
$$

$$
P(A_1 \cap A_2) = p^2
$$

Substitute these values:

$$
P(A_1 \cup A_2) = p + p - p^2
$$

---

### Step 4: Simplify the expression

$$
P(A_1 \cup A_2) = 2p - p^2
$$

---

## Final Result

The probability that the current flows continuously for at least time $t$ is

$$
P(A) = P(A_1 \cup A_2) = 2p - p^2
$$

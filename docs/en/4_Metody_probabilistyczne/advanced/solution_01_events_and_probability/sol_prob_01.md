# Solution

## Task 1

### Useful Definitions and Formulas

**Sample space**  
The set of all possible elementary outcomes of an experiment.

$$
\Omega = \{\omega_1, \omega_2, ..., \omega_n\}
$$

**Union of events**  
The union of two events contains all elements that belong to **at least one** of the events.

$$
A \cup B = \{ \omega : \omega \in A \text{ or } \omega \in B \}
$$

**Intersection of events**  
The intersection contains elements that belong to **both** events.

$$
A \cap B = \{ \omega : \omega \in A \text{ and } \omega \in B \}
$$

**Difference of events**  
The difference contains elements that belong to one event but **not** to the other.

$$
A \setminus B = \{ \omega : \omega \in A \text{ and } \omega \notin B \}
$$

---

## Given Data

Sample space:

$$
\Omega = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
$$

Events:

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

---

## 1. Union of Events

The union includes all elements that appear in **A**, **B**, or both.

Step 1: List elements of A  

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

Step 2: List elements of B  

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

Step 3: Combine all unique elements

$$
A \cup B = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
$$

---

## 2. Intersection of Events

The intersection contains only elements common to both sets.

Step 1: Compare elements of A and B.

- $\omega_1$ is only in A  
- $\omega_2$ is only in B  
- $\omega_3$ is in both A and B  
- $\omega_4$ is only in B  
- $\omega_5$ is only in A  

Step 2: Select common elements

$$
A \cap B = \{\omega_3\}
$$

---

## 3. Difference of Events (B \\ A)

This means elements that belong to **B but not to A**.

Step 1: Write set B

$$
B = \{\omega_2, \omega_3, \omega_4\}
$$

Step 2: Remove elements that also appear in A.

Since $\omega_3$ belongs to A, it must be removed.

Step 3: Remaining elements

$$
B \setminus A = \{\omega_2, \omega_4\}
$$

---

## 4. Difference of Events (A \\ B)

This means elements that belong to **A but not to B**.

Step 1: Write set A

$$
A = \{\omega_1, \omega_3, \omega_5\}
$$

Step 2: Remove elements that appear in B.

Since $\omega_3$ belongs to B, it must be removed.

Step 3: Remaining elements

$$
A \setminus B = \{\omega_1, \omega_5\}
$$

---

## Final Results

$$
A \cup B = \{\omega_1, \omega_2, \omega_3, \omega_4, \omega_5\}
$$

$$
A \cap B = \{\omega_3\}
$$

$$
B \setminus A = \{\omega_2, \omega_4\}
$$

$$
A \setminus B = \{\omega_1, \omega_5\}
$$

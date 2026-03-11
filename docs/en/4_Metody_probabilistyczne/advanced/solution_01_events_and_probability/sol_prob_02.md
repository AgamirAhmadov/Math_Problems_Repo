## Task 2

### Useful Definitions and Formulas

**Series connection**

In a series circuit, the current flows only if **all elements are functional**.  
In probability/event notation this corresponds to the **intersection** of events.

$$
A_{series} = A_1 \cap A_2 \cap A_3
$$

(when all elements are in series)

---

**Parallel connection**

In a parallel circuit, the current flows if **at least one element is functional**.  
In event notation this corresponds to the **union** of events.

$$
A_{parallel} = A_2 \cup A_3
$$

---

**Intersection of events**

The intersection means that **both events occur simultaneously**.

$$
A \cap B = \{ \omega : \omega \in A \text{ and } \omega \in B \}
$$

---

**Union of events**

The union means that **at least one event occurs**.

$$
A \cup B = \{ \omega : \omega \in A \text{ or } \omega \in B \}
$$

---

## Given Information

The circuit structure is:

- Element $a_1$ is connected **in series**
- Elements $a_2$ and $a_3$ are connected **in parallel**

Events:

$$
A_1 = \text{"element } a_1 \text{ is functional"}
$$

$$
A_2 = \text{"element } a_2 \text{ is functional"}
$$

$$
A_3 = \text{"element } a_3 \text{ is functional"}
$$

We want to describe event:

$$
A = \text{"current flows through the circuit"}
$$

---

## Step 1: Describe the parallel block

Elements $a_2$ and $a_3$ are in **parallel**, so the current flows through this block if **at least one works**.

Therefore the event describing the parallel block is

$$
A_2 \cup A_3
$$

---

## Step 2: Combine with the series element

Element $a_1$ is **in series** with the parallel block.  
In a series connection, **all required parts must work**.

Thus:

- $a_1$ must work
- the parallel block must work

This corresponds to the **intersection** of events.

---

## Step 3: Write the final event expression

The event that current flows through the whole circuit is

$$
A = A_1 \cap (A_2 \cup A_3)
$$

---

## Final Result

The event describing uninterrupted current flow in the circuit is

$$
A = A_1 \cap (A_2 \cup A_3)
$$

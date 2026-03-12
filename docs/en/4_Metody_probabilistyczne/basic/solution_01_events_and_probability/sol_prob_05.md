## Task 5 — Buffon's Needle Experiment

### Useful Definitions

**Sample space**

The sample space $\Omega$ is the set of all possible elementary outcomes of an experiment.

$$
\Omega = \{\omega\}
$$

Each $\omega$ represents one possible outcome of the experiment.

---

**Elementary outcome**

An elementary outcome describes the result of one experiment using parameters that fully determine the situation.

---

**Continuous sample space**

A sample space is **continuous** if its outcomes are described by variables that can take **infinitely many real values within an interval**.

---

## Step 1: Description of the experiment

A needle of length $L$ is thrown randomly onto a floor that has **parallel lines spaced at distance $d$**.

The outcome of the experiment depends on:

- the **position of the needle relative to the nearest line**
- the **orientation (angle) of the needle**

These two parameters completely describe a single throw.

---

## Step 2: Parameters describing an elementary outcome

Let

- $x$ = distance from the **center of the needle to the nearest parallel line**
- $\theta$ = **angle between the needle and the parallel lines**

Using symmetry of the geometric situation, we can restrict the variables to:

$$
x \in [0, \frac{d}{2}]
$$

$$
\theta \in [0, \frac{\pi}{2}]
$$

---

## Step 3: Representation of an elementary outcome

Each elementary outcome can therefore be written as a pair:

$$
\omega = (x,\theta)
$$

where

- $x$ determines the **position of the needle**
- $\theta$ determines the **orientation of the needle**

---

## Step 4: Sample space of the experiment

The sample space consists of **all possible combinations** of these two variables.

$$
\Omega =
\{(x,\theta) \;|\;
x \in [0,\frac{d}{2}],\;
\theta \in [0,\frac{\pi}{2}]
\}
$$

Thus the sample space is a **two-dimensional region** defined by the possible values of $x$ and $\theta$.

---

## Step 5: Why the sample space is continuous

In previous tasks, the sample space consisted of **discrete outcomes**, such as:

- specific signals (e.g., $111$, $000$)
- specific numbers of errors
- specific sequences of pulses.

These outcomes could be **counted**.

In Buffon's needle experiment, the variables

$$
x \quad \text{and} \quad \theta
$$

can take **any real value within their intervals**.

Therefore there are **infinitely many possible outcomes**, which means the sample space is **continuous** rather than discrete.

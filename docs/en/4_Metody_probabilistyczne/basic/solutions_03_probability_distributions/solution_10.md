# LIst 4 Task 5 — Multinomial Model (Categories of Outcomes)
The outcomes are grouped into three categories:

small numbers (1–2)
medium numbers (3–4)
large numbers (5–6)
Tasks

Describe the random experiment.
Define the sample space.
Specify the multinomial distribution.
Explain the interpretation of the parameters.

## 1. Description of the Random Experiment

A player rolls a fair six-sided die 5 times.  
Each outcome of a roll is classified into one of three categories:

- **Small numbers:** 1 or 2
- **Medium numbers:** 3 or 4
- **Large numbers:** 5 or 6

We observe how many times each category occurs during the 5 rolls.

---

## 2. Sample Space

The sample space consists of all possible sequences of 5 die rolls.

\[
\Omega = \{1,2,3,4,5,6\}^5
\]

Each element of the sample space is an ordered sequence of 5 outcomes, for example:

\[
(1,3,6,2,5)
\]

Instead of tracking exact numbers, we may also represent outcomes by category counts:

\[
(X_1, X_2, X_3)
\]

where:

- \(X_1\) = number of small outcomes
- \(X_2\) = number of medium outcomes
- \(X_3\) = number of large outcomes

subject to:

\[
X_1 + X_2 + X_3 = 5
\]

---

## 3. Multinomial Distribution

The random vector:

\[
(X_1, X_2, X_3)
\]

follows a multinomial distribution:

\[
(X_1, X_2, X_3) \sim \text{Multinomial}(n=5; p_1, p_2, p_3)
\]

Since the die is fair:

- Probability of a small number:

\[
p_1 = \frac{2}{6} = \frac{1}{3}
\]

- Probability of a medium number:

\[
p_2 = \frac{2}{6} = \frac{1}{3}
\]

- Probability of a large number:

\[
p_3 = \frac{2}{6} = \frac{1}{3}
\]

Therefore:

\[
(X_1, X_2, X_3) \sim \text{Multinomial}\left(5; \frac13,\frac13,\frac13\right)
\]

The probability mass function is:

\[
P(X_1=x_1, X_2=x_2, X_3=x_3)
=
\frac{5!}{x_1!x_2!x_3!}
\left(\frac13\right)^{x_1}
\left(\frac13\right)^{x_2}
\left(\frac13\right)^{x_3}
\]

where:

\[
x_1 + x_2 + x_3 = 5
\]

---

## 4. Interpretation of the Parameters

### Number of Trials

\[
n = 5
\]

The die is rolled 5 times.

### Categories

There are 3 possible categories for each roll:

1. Small
2. Medium
3. Large

### Category Probabilities

\[
p_1 = p_2 = p_3 = \frac13
\]

Each category has probability \(1/3\) because each category contains two equally likely die outcomes.

### Random Variables

- \(X_1\): number of small results
- \(X_2\): number of medium results
- \(X_3\): number of large results

These variables count how many times each category appears in the 5 rolls.

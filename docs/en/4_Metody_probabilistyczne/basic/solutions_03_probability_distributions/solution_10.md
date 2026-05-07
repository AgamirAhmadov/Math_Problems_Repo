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

# Task 5 — Multinomial Model

## 1. Random Experiment

A player rolls a fair die 5 times.

Each result is placed into one of these categories:

- Small numbers → 1 or 2
- Medium numbers → 3 or 4
- Large numbers → 5 or 6

We count how many times each category appears.

---

# 2. Sample Space

The sample space is all possible results from 5 die rolls.

Example outcomes:

- (1, 3, 5, 2, 6)
- (2, 2, 4, 5, 1)
- (6, 6, 3, 4, 2)

Each roll can be:

- small
- medium
- large

---

# 3. Multinomial Distribution

Let:

- X₁ = number of small results
- X₂ = number of medium results
- X₃ = number of large results

Since the die is fair:

- P(small) = 2/6 = 1/3
- P(medium) = 2/6 = 1/3
- P(large) = 2/6 = 1/3

The distribution is:

(X₁, X₂, X₃) ~ Multinomial(5, 1/3, 1/3, 1/3)

Also:

X₁ + X₂ + X₃ = 5

because there are 5 rolls in total.

---

# 4. Interpretation of Parameters

- 5  
  Total number of die rolls

- 1/3  
  Probability of each category

- X₁  
  Counts small numbers

- X₂  
  Counts medium numbers

- X₃  
  Counts large numbers

These variables show how many times each category appears in the 5 rolls.

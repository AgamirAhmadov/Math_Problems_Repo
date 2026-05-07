# Task 6 — Binomial Model
The probability of producing a defective part is 0.04.

An inspector checks 10 parts.

Calculate the probability that:

exactly 2 parts are defective,
at least one part is defective.

## Given Information

- Probability that a part is defective:

  p = 0.04

- Number of inspected parts:

  n = 10

The number of defective parts follows a binomial distribution:

X ~ Binomial(n = 10, p = 0.04)

---

# 1. Probability That Exactly 2 Parts Are Defective

For a binomial distribution:

P(X = k) = C(n,k) · p^k · (1-p)^(n-k)

Substitute the values:

P(X = 2) = C(10,2) · (0.04)^2 · (0.96)^8

Calculate step by step:

- C(10,2) = 45
- (0.04)^2 = 0.0016
- (0.96)^8 ≈ 0.72139

Therefore:

P(X = 2) ≈ 45 × 0.0016 × 0.72139

P(X = 2) ≈ 0.0519

## Final Answer

Probability that exactly 2 parts are defective:

P(X = 2) ≈ 0.0519

≈ 5.19%

---

# 2. Probability That At Least One Part Is Defective

“At least one” means:

P(X ≥ 1)

It is easier to use the complement rule:

P(X ≥ 1) = 1 − P(X = 0)

Calculate:

P(X = 0) = (0.96)^10

P(X = 0) ≈ 0.6648

Therefore:

P(X ≥ 1) = 1 − 0.6648

P(X ≥ 1) ≈ 0.3352

## Final Answer

Probability that at least one part is defective:

P(X ≥ 1) ≈ 0.3352

≈ 33.52%

---

# Interpretation

- There is about a 5.19% chance that exactly 2 out of 10 parts are defective.
- There is about a 33.52% chance that at least one defective part appears among the 10 inspected parts.

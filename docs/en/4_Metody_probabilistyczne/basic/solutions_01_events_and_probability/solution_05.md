# 📘 Task 5 — Buffon’s Needle Experiment

## 🎯 Goal
Describe a continuous sample space using geometric variables.

---

## 🧩 1. Description of the Experiment

A needle of length L is dropped randomly onto a plane with parallel lines spaced at distance d.

The outcome depends on:
- where the needle lands,
- how it is oriented.

---

## 🧩 2. Parameters Determining an Outcome

A single outcome is fully determined by two variables:

1. x → distance from the center of the needle to the nearest line  
2. θ → angle between the needle and the parallel lines  

---

## 🧩 3. Representation of an Elementary Outcome

An elementary outcome can be written as:

(x, θ)

where:
- x describes position,
- θ describes orientation.

---

## 🧩 4. Sample Space Ω

Using symmetry, we restrict:

- x ∈ [0, d/2]  
- θ ∈ [0, π/2]  

👉 Therefore:

Ω = { (x, θ) | 0 ≤ x ≤ d/2, 0 ≤ θ ≤ π/2 }

---

## 🧩 5. Interpretation

Each point (x, θ) represents:
- a specific position of the needle,
- a specific angle at which it lands.

---

## 🧠 Why is the Sample Space Continuous?

Unlike previous tasks (coin tosses, dice, cards):

- Those had **discrete outcomes** (finite/countable sets)
- Here:
  - x can take infinitely many real values  
  - θ can take infinitely many real values  

👉 Therefore:
- The sample space contains infinitely many outcomes  
- It forms a **continuous region** in the plane  

---

## 🚀 Key Insight

- Discrete experiments → outcomes are countable  
- Geometric experiments → outcomes are continuous  

Buffon’s needle is a classic example where:
- probability is computed using **geometry + integration**
- not simple counting

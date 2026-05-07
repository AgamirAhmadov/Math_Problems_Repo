# 📘 lab4 Task 4 — Poisson Model (Arrival of Events)

Tasks

1. Describe the random experiment.
2. Determine the sample space ( \Omega ).
3. Provide the formula of the probability distribution.
4. Interpret the parameter ( \lambda ).

## 🎯 Given
A web service receives on average **3 error reports per hour**.

We assume a **Poisson distribution**.

---

# 🧪 1. Random Experiment

👉 Observe the number of error reports in a fixed time interval (e.g., 1 hour).

- We repeat the same observation:
  - “How many errors occur in one hour?”

✔️ The outcome is a **number of events** (0, 1, 2, ...)

---

# 🎲 2. Sample Space \( \Omega \)

All possible numbers of error reports:

\[
\Omega = \{0,1,2,3,4,5,\dots\}
\]

👉 Infinite set of non-negative integers

---

# 📊 3. Probability Distribution (Poisson Formula)

\[
P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}
\]

Where:
- \( k = 0,1,2,\dots \)
- \( \lambda \) = average number of events
- \( e \approx 2.718 \)

---

# ⚙️ 4. Parameter \( \lambda \)

\[
\lambda = 3
\]

👉 Interpretation:

- Average number of errors per hour = **3**
- Also represents:
  - expected value  
  - rate of occurrence  

---

# 🧠 Summary

| Concept | Meaning |
|--------|--------|
| Random experiment | Count errors in a time interval |
| Sample space | {0,1,2,...} |
| Distribution | Poisson formula |
| Parameter \( \lambda \) | average rate (3 errors/hour) |

---

# ✅ Final Insight

- Poisson is used for:
  - rare events  
  - counts over time  
- Only one parameter:
\[
\lambda = \text{average rate}
\]

👉 Think: “How many events happen in a fixed time?”

# 📘 Lab 4  Task 4 — Poisson Model (Arrival of Events)



## 🎯 Given
A web service receives on average **3 error reports per hour**.

---

# 🧪 1. Random Experiment

Observe how many error reports occur in **one hour**.

👉 Outcome = number of errors (0,1,2,...)

---

# 🎲 2. Sample Space

Ω = {0,1,2,3,4,5,...}

👉 All non-negative integers

---

# 📊 3. Probability Distribution (Poisson)

P(X = k) = (λ^k * e^(-λ)) / k!

Where:
- k = 0,1,2,...
- λ = average rate
- e ≈ 2.718

---

# ⚙️ 4. Parameter λ

λ = 3

👉 Meaning:
- On average → 3 errors per hour

---

# 🧠 Example

Probability of exactly 2 errors:

P(X = 2) = (3² * e^(-3)) / 2!  
= (9 * e^(-3)) / 2

---

# ✅ Final Insight

- Poisson → counts events over time  
- λ = average number of events  
- Only one parameter controls everything

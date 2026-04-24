# 📘 Week 2 – Marketing Analytics (DETAILED THEORY + Q&A)

## 🔥 Topics Covered
- Need vs Want vs Demand
- Consumer Behavior
- Conjoint Analysis
- Choice-Based Conjoint (CBC)
- Basic Statistics (Z-score, Variance, R²)
- Regression Concepts

---

# 🧠 PART 1: NEED vs WANT vs DEMAND (VERY IMPORTANT 🔥)

---

### ❓ Q1. What is a Need?
👉 Basic requirement for survival  

👉 Examples:
- Food  
- Water  
- Shelter  

---

### ❓ Q2. What is a Want?
👉 Desire for something beyond basic needs  

👉 Example:
- Luxury hotel  
- Branded clothes  

---

### ❓ Q3. What is Demand?
👉 Want + ability to pay  

---

### ❓ Q4. Statement:
👉 Want = survival requirement  
👉 ❌ False  

---

### ❓ Q5. Key Difference:

👉 
- Need → essential  
- Want → desire  
- Demand → desire + money  

---

# 🔴 PART 2: CONSUMER BEHAVIOR

---

### ❓ Q6. What is consumer behavior?
👉 Study of how consumers make decisions  

---

### ❓ Q7. How do companies understand consumers?

👉 
- Surveys  
- Reviews  
- Behavior tracking  
- Data analytics  

---

### ❓ Q8. Why is consumer behavior important?
👉 
- Product design  
- Pricing decisions  
- Marketing strategy  

---

# 🔴 PART 3: CONJOINT ANALYSIS (MOST IMPORTANT 🔥🔥)

---

### ❓ Q9. What is conjoint analysis?
👉 Technique to understand **consumer preferences** by breaking product into attributes  

---

### 💡 Example:
👉 Laptop:
- Price  
- Brand  
- Battery  

---

### ❓ Q10. What does conjoint analysis help with?

👉 
- Product design  
- Pricing  
- Market share prediction  

---

### ❓ Q11. Conjoint analysis is used for?
👉 Products and pricing research  

---

### ❓ Q12. Can conjoint lead to heuristic responses?
👉 ✅ Yes  

---

### ❓ Q13. What are attributes and levels?

👉 
- Attribute = feature (price)  
- Level = value (₹50k, ₹60k)  

---

### ❓ Q14. Total combinations formula:
👉 Levels^Attributes  

---

# 🔴 PART 4: CHOICE-BASED CONJOINT (CBC)

---

### ❓ Q15. What is CBC?
👉 Customers choose one option from set  

---

### ❓ Q16. Does CBC use linear regression?
👉 ❌ No  
Good catch — this is a **very common confusion** 👍

---

### ❓ Q16. Does Choice-Based Conjoint (CBC) use linear regression?

👉 ❌ **Incorrect statement:** CBC uses linear regression
👉 ✅ **Correct answer:** **No**

---

### ✅ What does CBC actually use?

👉 CBC typically uses:

* **Logistic Regression**
* **Multinomial Logit Models (MNL)**

---

### 💡 Why not linear regression?

* Linear regression → continuous output
* CBC → **choice data (discrete: choose A/B/C)**

👉 So we need **probability-based models**, not linear ones.

---

### 🧠 Final Exam Line (remember this):

👉 **CBC = Choice → Logistic / Logit model**
👉 **NOT linear regression**

---

### 🔁 Quick Comparison

| Method                  | Used for          |
| ----------------------- | ----------------- |
| Linear Regression       | Continuous values |
| Logistic Regression     | Binary choice     |
| Multinomial Logit (CBC) | Multiple choices  |


---

### ❓ Q17. Why CBC is better?
👉 
- More realistic  
- Mimics real decisions  

---

# 🔴 PART 5: STATISTICS BASICS

---

### ❓ Q18. What is Z-score?
👉 Number of standard deviations from mean  

---

### ❓ Q19. What does variance measure?
👉 Spread of data  

---

### ❓ Q20. Formula idea:
👉 Variance = deviation from mean  

---

### ❓ Q21. What are standardized beta coefficients?
👉 Regression coefficients scaled to compare impact  

---

### ❓ Q22. What is R-square?
👉 Explains variance in dependent variable  

---

### ❓ Q23. Can R-square be negative?
👉 ✅ Yes (if no constant term)  

---

# 🔴 PART 6: MODEL FIT (IMPORTANT)

---

# 🧠 RMSEA (Root Mean Square Error of Approximation)

---

## ❓ Q24. What is RMSEA?

👉 A **model fit measure** used in:

- Structural Equation Modeling (SEM)
- Confirmatory Factor Analysis (CFA)

👉 It indicates **how well a model fits the population (not just the sample)**

---

## 📌 Conceptual Formula

$$
RMSEA = \sqrt{\frac{\chi^2 - df}{df (N - 1)}}
$$

---

## 🧠 Components

- **χ²** → Chi-square value  
- **df** → Degrees of freedom  
- **N** → Sample size  

---

## 🎯 Interpretation (Important)

| RMSEA Value | Meaning        |
|------------|----------------|
| < 0.05     | Excellent fit  |
| 0.05 – 0.08| Good fit       |
| 0.08 – 0.10| Moderate fit   |
| > 0.10     | Poor fit       |

---

## 🔥 Key Exam Points

### ❓ What does RMSEA measure?

👉 Model fit

---

### ❓ Is lower RMSEA better?

👉 ✅ Yes — **Lower = better fit**

---

### ❓ Why is RMSEA preferred?

👉 Because it:

- Adjusts for **model complexity (df)**
- Is **less sensitive to sample size**

---

### ❓ RMSEA helps avoid which issue?

👉 Sample size problem

---

## 💡 Examples

- **RMSEA = 0.04** → Excellent fit  
- **RMSEA = 0.12** → Poor fit  

---

## ⚠️ Common Mistakes (Exam Traps)

- ❌ High RMSEA = Good model  
- ❌ RMSEA measures variance  
- ❌ RMSEA is a regression coefficient  

---

## 🧠 Memory Trick

👉 **RMSEA ↓ → Model 👍**  
👉 **RMSEA ↑ → Model 👎**

---

## 🎯 Final Exam Line

👉 *RMSEA is a goodness-of-fit measure that evaluates how well a model approximates the population covariance matrix while accounting for model complexity.*

---

# ❓ Q25. Why is RMSEA used?

👉 RMSEA is used because it:

- Reduces **sample size bias**
- Adjusts for **model complexity**
- Provides a **more realistic estimate of model fit**
- Reflects how well the model would fit the **population**, not just the sample

---

## 🎯 One-Line Answer (Exam Ready)

👉 *RMSEA is used because it provides a sample-size adjusted measure of model fit that accounts for model complexity.*

---

# 🔴 PART 7: R FUNCTIONS

---

### ❓ Q26. What does str() function do?
👉 Displays structure of object  

---

# 🔴 PART 8: PRACTICAL QUESTIONS

---

### ❓ Q27. Want + ability to pay = ?
👉 Demand  

---

### ❓ Q28. Conjoint is used for?
👉 Product + pricing  

---

### ❓ Q29. Z-score measures?
👉 Distance from mean  

---

# 🔴 PART 9: EXAM TRAPS (VERY IMPORTANT)

---

### ❓ Q30. CBC uses linear regression?
👉 ❌ False  

---

### ❓ Q31. Want = need?
👉 ❌ False  

---

### ❓ Q32. Variance measures average?
👉 ❌ False  

---

### ❓ Q33. R-square always positive?
👉 ❌ False  

---

# 🔴 PART 10: HIGH-PROBABILITY MCQs

---

### ❓ Q34. Demand means?
👉 Want + ability to pay  

---

### ❓ Q35. Conjoint used for?
👉 Product + pricing  

---

### ❓ Q36. Z-score measures?
👉 Standard deviation distance  

---

### ❓ Q37. RMSEA measures?
👉 Model fit  

---

### ❓ Q38. str() function?
👉 Structure  

---

# 🚨 FINAL QUICK REVISION

👉 Remember:

- Need = survival  
- Want = desire  
- Demand = money  
- Conjoint = preferences  
- Z-score = distance  
- Variance = spread  

---

# 🎯 FINAL TIP

👉 Week 2 is:
- VERY HIGH weight  
- Concept-based  
- Frequently repeated  

Focus on:
✔ Need vs Want vs Demand  
✔ Conjoint  
✔ Z-score  
✔ R-square  

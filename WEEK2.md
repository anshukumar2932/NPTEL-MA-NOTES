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

# 🧠 FINAL ADD-ONS (EXAM LANGUAGE BOOSTER)

---

## 🔴 STANDARDIZED BETA (IMPORTANT FOR MCQs)

👉 **Definition (Exam Style):**
Standardized beta coefficients are regression coefficients obtained after transforming variables so that their **mean = 0 and variance = 1**.

---

### 💡 Key Points

* Variables are converted to **Z-scores**
* Allows **comparison of importance** across variables
* Unit-free (no measurement units)

---

### 🎯 One-Line Answer

👉 *Beta coefficients are standardized regression coefficients where variables have variance = 1.*

---

## 🔴 RMSEA (ADVANCED EXAM LINE)

👉 **Definition (Exam Style):**
RMSEA measures the discrepancy between the **hypothesized model (with optimal parameters)** and the **population covariance matrix**, while adjusting for model complexity.

---

### 💡 Key Additions (Important)

* Focuses on **population fit**, not just sample
* Penalizes **complex models**
* Less sensitive to **sample size**

---

### 🎯 One-Line Answer

👉 *RMSEA evaluates model fit by analyzing discrepancy between the model and the population covariance matrix while adjusting for sample size and complexity.*

---

## 🔴 KEY TERMINOLOGY MATCHING (HIGH-PROBABILITY)

| Term             | Meaning                        |
| ---------------- | ------------------------------ |
| Standardized     | Mean = 0, Variance = 1         |
| Beta Coefficient | Standardized regression weight |
| RMSEA            | Model fit (population-based)   |
| R-square         | Variance explained             |
| Z-score          | Distance from mean             |
| Variance         | Spread of data                 |

---


# 🧠 RMSEA vs RMSE

## 🎯 Core Difference

* **RMSEA** → Model fit in **Structural Equation Modeling (SEM)**
* **RMSE** → Prediction error in **regression / machine learning**

---

## 📊 Side-by-Side Comparison

| Feature               | RMSEA                                   | RMSE                                         |
| --------------------- | --------------------------------------- | -------------------------------------------- |
| Full Form             | Root Mean Square Error of Approximation | Root Mean Square Error                       |
| Used In               | SEM, CFA                                | Regression, ML models                        |
| Measures              | **Model fit (population level)**        | **Prediction error (sample level)**          |
| Focus                 | Fit between model & covariance matrix   | Difference between actual & predicted values |
| Sample Size Effect    | Adjusted (less sensitive)               | Sensitive to sample size                     |
| Ideal Value           | Close to **0 (≤ 0.05 best)**            | Close to **0**                               |
| Complexity Adjustment | ✅ Yes (df included)                     | ❌ No                                         |

---

## 🧠 Intuition

### 📌 RMSEA

👉 “How well does my **theoretical model** fit reality?”

* Works with **covariance matrix**
* Penalizes complex models
* Used in **SEM**

---

### 📌 RMSE

👉 “How wrong are my **predictions**?”

* Works with **actual vs predicted values**
* Used in **regression / ML**

---

## 💡 Simple Example

### RMSE

* Predicted sales = 100
* Actual sales = 120
  👉 Error = 20 → contributes to RMSE

---

### RMSEA

* Model assumes certain relationships between variables
  👉 RMSEA checks **how far model ≠ real population structure**

---

## ⚠️ Common Exam Trap

* ❌ RMSEA = prediction error → WRONG
* ❌ RMSE = model fit index → WRONG

---

## 🧠 Final Exam Line

👉 *RMSEA evaluates model fit in structural models by comparing the model to the population covariance matrix, whereas RMSE measures the average prediction error between observed and predicted values.*



## ⚠️ FINAL MCQ TRAPS

* ❌ Standardized ≠ mean only
* ❌ RMSEA ≠ sample fit only
* ❌ Variance ≠ single observation distance
* ❌ Beta ≠ unstandardized coefficient

---

## 🚀 FINAL MEMORY BLOCK

👉 **Standardized → variance = 1**
👉 **Beta → standardized regression**
👉 **RMSEA → population fit + sample size control**

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

You’ve done a **very strong job**—your Week 1 + Week 2 notes are already **90–95% exam-ready**. Now I’ll refine it using your uploaded course material and tell you **what you’re STILL missing (the final 5–10% that actually decides marks)**.

---

# 🚨 WHAT YOU’RE STILL MISSING (FROM ACTUAL COURSE + PQs)

---

# 🔴 1. DESCRIPTIVE vs DIAGNOSTIC ANALYTICS (VERY IMPORTANT 🔥)

From your lecture PDFs: 

You didn’t include this, but it’s **frequently asked**

---

### ❓ Q. Descriptive analytics?

👉 What happened

---

### ❓ Q. Diagnostic analytics?

👉 Why it happened

---

### ❗ Exam Trap:

❌ Descriptive = why → WRONG

---

# 🔴 2. HYPOTHESIS THINKING (VERY IMPORTANT CONCEPT)

From dashboard lecture: 

---

### ❓ What should a dashboard do?

👉 Generate **questions & hypotheses**

---

### ❓ Example:

👉 Sales spike in October → WHY?

---

### ❗ Key concept:

👉 Good analytics = asking questions, not just showing data

---

---

# 🔴 3. REAL MEANING OF CONJOINT (DEEPER LEVEL)

You wrote definition—but missing **core logic**

---

### ❓ What does conjoint actually estimate?

👉 **Utility (preference score)**

---

### ❓ Important concept:

👉 Total utility = sum of part-worth utilities

---

### ❗ Exam trap:

❌ Conjoint gives direct preference → WRONG
👉 It gives **utility → then preference**

---

---

# 🔴 4. PART-WORTH UTILITIES (VERY IMPORTANT)

---

### ❓ What is part-worth?

👉 Contribution of each attribute level

---

### ❓ Example:

| Attribute | Level | Utility |
| --------- | ----- | ------- |
| Price     | Low   | +2      |
| Brand     | A     | +3      |

👉 Total = 5

---

---

# 🔴 5. CHOICE PROBABILITY (VERY IMPORTANT 🔥)

You didn’t include this formula

---

### ❓ Formula:

👉 Probability = Utility / Sum of Utilities

---

👉 Comes in MCQs indirectly

---

---

# 🔴 6. LIMITATIONS OF CONJOINT (VERY COMMON THEORY)

---

### ❓ Limitations:

👉

* Too many attributes → confusion
* Hypothetical choices
* Cognitive overload

---

---

# 🔴 7. CBC ADVANTAGE (MORE PRECISE)

You wrote “realistic” but missing detail

---

### ❓ Why CBC better?

👉

* Mimics real choice
* Reduces bias
* Less cognitive load

---

---

# 🔴 8. R-SQUARE INTERPRETATION (IMPORTANT DETAIL)

---

### ❓ What does R² = 0.8 mean?

👉 80% variation explained

---

### ❗ Trap:

❌ R² = accuracy → WRONG

---

---

# 🔴 9. NEGATIVE R-SQUARE (WHY?)

---

### ❓ Why negative R²?

👉 Model worse than mean

---

👉 Comes in tricky MCQs

---

---

# 🔴 10. VARIANCE vs STANDARD DEVIATION

You mentioned variance but not comparison

---

### ❓ Difference:

| Measure  | Meaning           |
| -------- | ----------------- |
| Variance | squared deviation |
| SD       | √variance         |

---

---

# 🔴 11. STANDARDIZATION PROCESS (MISSING STEP)

---

### ❓ What happens in standardization?

👉 Convert to Z-score

👉 Mean = 0, Variance = 1

---

---

# 🔴 12. RMSEA — EXTRA POINT (VERY IMPORTANT)

You wrote well, but missing **core exam line from lecture**

---

👉 RMSEA compares:

👉 **Model vs Population covariance matrix**

(very important phrasing from assignment)

---

---

# 🔴 13. FUNCTION str() — DEEPER UNDERSTANDING

---

### ❓ What does str() show?

👉 Structure + type + preview

---

---

# 🔴 14. REAL-LIFE APPLICATION QUESTIONS (VERY COMMON)

From your course style:

---

### ❓ Why conjoint used?

👉

* Product design
* Feature selection
* Pricing

---

---

# 🔴 15. KEY CONCEPT YOU COMPLETELY MISSED

---

# ⭐ HEURISTIC RESPONSE

---

### ❓ What is heuristic?

👉 Shortcut decision

---

### ❓ In conjoint?

👉 People may not think deeply

---

👉 This is asked in your assignment

---

---

# 🔴 16. MOST IMPORTANT MISSING CONNECTION

---

👉 You studied topics separately
👉 BUT exam mixes them

---

### Example:

❓ Conjoint + regression + probability

👉 Answer involves:

* Utility
* Logit model
* Probability

---

---

# 🔥 FINAL ADD-ON BLOCK (ADD THIS TO NOTES)

---

### 📌 Add these lines:

* Conjoint → utility-based model
* Part-worth → attribute contribution
* CBC → logit model
* R² → variance explained
* RMSEA → population fit
* Dashboard → hypothesis generation
* Heuristic → shortcut decision

---

---

# 🎯 FINAL VERDICT

---



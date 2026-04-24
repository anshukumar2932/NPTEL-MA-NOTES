# 📘 Marketing Analytics – ALL IMPORTANT NUMERICALS (Exam Revision)

## 🔥 Topics Covered
- Z-score
- Variance
- Regression Basics
- RFM Calculations
- Market Basket (Support, Confidence)
- Forecast Error
- RMSE
- Elasticity
- Demand Function
- CLV Basics
- Probability (Naive Bayes)

---

# 🧠 1. Z-SCORE (VERY IMPORTANT)

---

### 📌 Formula:
Z = (X - μ) / σ

---

### ❓ What it means:
👉 Distance of value from mean in terms of standard deviation  

---

### 💡 Example:

Given:
- X = 80  
- Mean = 70  
- SD = 5  

Z = (80 - 70) / 5 = 2  

👉 Interpretation:
👉 Value is **2 standard deviations above mean**

---

# 🔴 2. VARIANCE

---

### 📌 Formula:
Variance = Σ (Xi - Mean)² / n

---

### 💡 Example:

Data: 2, 4, 6  

Mean = 4  

Variance = ((2-4)² + (4-4)² + (6-4)²)/3  
= (4 + 0 + 4)/3 = 8/3  

---

# 🔴 3. FORECAST ERROR (VERY IMPORTANT)

---

### 📌 Formula:
Error = Actual - Forecast  

---

### 💡 Example:

Actual = 125  
Forecast = 110  

Error = 125 - 110 = **+15**

---

### 📌 Interpretation:
- Positive → underestimation  
- Negative → overestimation  

---

# 🔴 4. RMSE (MODEL ACCURACY)

---

### 📌 Formula:
RMSE = √(Σ (Error²) / n)

---

### 💡 Example:

Errors: 2, -3, 4  

RMSE = √((4 + 9 + 16)/3)  
= √(29/3)  

---

### 📌 Use:
👉 Lower RMSE = better model  

---

# 🔴 5. PRICE ELASTICITY

---

### 📌 Formula:
Elasticity = (% change in demand) / (% change in price)

---

### 💡 Example:

Price ↑ 10%  
Demand ↓ 20%  

Elasticity = -20 / 10 = -2  

---

### 📌 Interpretation:
- |E| > 1 → elastic  
- |E| < 1 → inelastic  
- |E| = 1 → unit elastic  

---

# 🔴 6. DEMAND FUNCTION

---

### 📌 Formula:
D = a - bP  

---

### 💡 Example:

D = 100 - 2P  

If P = 10  
D = 100 - 20 = 80  

---

### 📌 Interpretation:
👉 Price ↑ → Demand ↓  

---

# 🔴 7. RFM CALCULATION (VERY IMPORTANT)

---

### 📌 Formula:
Score = R + F + M (or weighted)

---

### 💡 Example:

Customer:
- Recency = 5  
- Frequency = 4  
- Monetary = 3  

RFM = 5 + 4 + 3 = **12**

---

### 📌 Weighted Example:
R×100 + F×10 + M  

= 5×100 + 4×10 + 3  
= 543  

---

### 📌 Interpretation:
👉 Higher score → better customer  

---

# 🔴 8. MARKET BASKET ANALYSIS (VERY IMPORTANT)

---

## 📌 SUPPORT

Support(A) = Transactions with A / Total transactions  

---

### 💡 Example:

10 baskets, 4 contain bread  

Support = 4/10 = 0.4  

---

## 📌 CONFIDENCE

Confidence(A → B) = Support(A ∩ B) / Support(A)

---

### 💡 Example:

Bread in 4 baskets  
Bread + Butter in 2  

Confidence = 2/4 = 0.5  

---

### 📌 Interpretation:
👉 50% chance of buying butter with bread  

---

# 🔴 9. PROBABILITY (NAIVE BAYES)

---

### 📌 Formula:
P(A|B) = [P(B|A) × P(A)] / P(B)

---

### 💡 Example:

P(Spam) = 0.4  
P(Word|Spam) = 0.8  
P(Word) = 0.5  

P(Spam|Word) = (0.8 × 0.4)/0.5 = 0.64  

---

# 🔴 10. CLV (BASIC NUMERICAL IDEA)

---

### 📌 Simple Formula:
CLV = Revenue × Lifetime  

---

### 💡 Example:

Monthly revenue = 1000  
Lifetime = 12 months  

CLV = 1000 × 12 = 12000  

---

# 🔴 11. AVERAGE PURCHASE VALUE

---

### 📌 Formula:
Monetary / Frequency  

---

### 💡 Example:

Monetary = 1000  
Frequency = 5  

Avg = 1000/5 = 200  

---

# 🔴 12. COSINE SIMILARITY (CONCEPTUAL)

---

### 📌 Formula:
Cosine = (A·B) / (|A||B|)

---

### 📌 Use:
👉 Recommender systems  

---

# 🔴 13. DISTANCE (CLUSTERING)

---

### 📌 Formula:
Distance = √Σ (Xi - Yi)²  

---

### 💡 Example:

Points:
(1,2) and (4,6)  

Distance = √((1-4)² + (2-6)²)  
= √(9 + 16) = √25 = 5  

---

# 🔴 14. ADSTOCK (ADVANCED)

---

### 📌 Formula:
Adstockₜ = Adₜ + λ × Adstockₜ₋₁  

---

### 💡 Example:

Adₜ = 100  
λ = 0.5  
Previous = 50  

Adstock = 100 + 0.5×50 = 125  

---

# 🔴 15. TIME SERIES MODEL

---

### 📌 Formula:
Xₜ = Trend + Seasonality + Error  

---

### 📌 Use:
👉 Forecasting  

---

# 📘 Marketing Analytics – ADVANCED NUMERICALS (Exam Practice)

---

# 🔴 1. Z-SCORE (ADVANCED)

---

### ❓ Q1. Identify outlier using Z-score

Given:
Mean = 50  
SD = 5  
Value = 65  

👉 Z = (65 - 50)/5 = 3  

👉 Interpretation:
👉 Z > 3 → **Outlier**

---

### ❓ Q2. Which value is closer to mean?

A: Z = 0.5  
B: Z = 2  

👉 Answer: A (closer to mean)

---

# 🔴 2. VARIANCE (TRICKY)

---

### ❓ Q3. Data: 1, 1, 1, 1  

Mean = 1  

Variance = 0  

👉 Interpretation:
👉 No variation  

---

### ❓ Q4. If all values increase by +5, what happens?

👉 Variance stays SAME  

---

# 🔴 3. FORECAST ERROR (MULTI STEP)

---

### ❓ Q5.

Actual: 100, 120, 130  
Forecast: 90, 110, 140  

Errors:
= 10, 10, -10  

---

### ❓ Q6. Mean Error

= (10 + 10 - 10)/3 = 10/3  

---

### ❓ Q7. RMSE

= √((100 + 100 + 100)/3)  
= √100 = 10  

---

# 🔴 4. ELASTICITY (TRICKY)

---

### ❓ Q8.

Price ↑ 20%  
Demand ↓ 10%  

Elasticity = -10/20 = -0.5  

👉 Inelastic  

---

### ❓ Q9.

Price ↓ 10%  
Demand ↑ 30%  

Elasticity = 30/10 = 3  

👉 Highly elastic  

---

### ❓ Q10. Revenue impact

Elastic → revenue ↑  
Inelastic → revenue ↓  

---

# 🔴 5. DEMAND FUNCTION (MULTI STEP)

---

### ❓ Q11.

D = 200 - 5P  

Find demand when P = 20  

D = 200 - 100 = 100  

---

### ❓ Q12. Revenue

R = P × D  

R = 20 × 100 = 2000  

---

### ❓ Q13. Max revenue concept

Occurs where elasticity = 1  

---

# 🔴 6. RFM (ADVANCED)

---

### ❓ Q14.

Customer A: R=5, F=2, M=1  
Customer B: R=3, F=4, M=5  

👉 Best customer?

👉 A (Recency most important)

---

### ❓ Q15. Weighted RFM

Score = R×100 + F×10 + M  

A = 521  
B = 345  

👉 A is better  

---

# 🔴 7. MARKET BASKET (ADVANCED)

---

### ❓ Q16.

100 transactions  
Bread in 40  
Butter in 30  
Both in 20  

---

Support(Bread) = 40/100 = 0.4  

Confidence(Bread→Butter) = 20/40 = 0.5  

---

### ❓ Q17. Lift

Lift = 0.5 / 0.3 = 1.67  

👉 Strong association  

---

### ❓ Q18. Which rule is stronger?

Rule A: Confidence = 0.8  
Rule B: Confidence = 0.6  

👉 A  

---

# 🔴 8. NAIVE BAYES (ADVANCED)

---

### ❓ Q19.

P(A)=0.3  
P(B|A)=0.5  
P(B)=0.2  

P(A|B) = (0.5×0.3)/0.2 = 0.75  

---

### ❓ Q20. Interpretation

👉 75% probability  

---

# 🔴 9. CLUSTERING DISTANCE

---

### ❓ Q21.

Points:
A(2,3), B(6,7)  

Distance = √((2-6)² + (3-7)²)  
= √(16 + 16) = √32  

---

### ❓ Q22. Which points are closer?

Distance smaller → closer  

---

# 🔴 10. ADSTOCK (MULTI STEP)

---

### ❓ Q23.

Adₜ = 200  
λ = 0.4  
Previous = 100  

Adstock = 200 + 0.4×100 = 240  

---

### ❓ Q24. If λ increases?

👉 More carry-over effect  

---

# 🔴 11. TIME SERIES

---

### ❓ Q25.

Xₜ = 100  
Trend = 60  
Seasonality = 30  

Error = 100 - 90 = 10  

---

# 🔴 12. CLV (ADVANCED)

---

### ❓ Q26.

Monthly revenue = 500  
Retention = 10 months  

CLV = 500 × 10 = 5000  

---

### ❓ Q27. If retention increases?

👉 CLV increases  

---

# 🔴 13. MIXED CONCEPT QUESTIONS

---

### ❓ Q28.

High RFM + high CLV = ?

👉 Best customers  

---

### ❓ Q29.

High support but low confidence means?

👉 Frequent item but weak rule  

---

### ❓ Q30.

High confidence but low support?

👉 Strong but rare rule  

---

# 🚨 FINAL TRICK QUESTIONS

---

### ❓ Q31. Elasticity always positive?
👉 ❌ No (usually negative)

---

### ❓ Q32. RMSE negative?
👉 ❌ No  

---

### ❓ Q33. Support > 1 possible?
👉 ❌ No  

---

### ❓ Q34. Z-score negative possible?
👉 ✅ Yes  

---

# 🎯 FINAL PRACTICE MCQ

---

### ❓ Q35.

Support = 0.4  
Confidence = 0.5  

What does it mean?

👉 40% transactions contain item  
👉 50% chance of co-purchase  

---

# 🚀 FINAL REVISION

👉 Remember:

- Z > 3 → outlier  
- RMSE ↓ → better  
- Elasticity >1 → elastic  
- Lift >1 → strong  
- RFM → customer value  


# 🚨 FINAL QUICK REVISION

👉 Remember:

- Z-score = distance  
- Error = Actual – Forecast  
- RMSE = accuracy  
- Elasticity = sensitivity  
- Support = frequency  
- Confidence = probability  
- RFM = behavior  

---

# 🎯 FINAL TIP

👉 Numericals are:
- Easy marks  
- Formula-based  
- Repeated in exam  

Focus on:
✔ Support & Confidence  
✔ Forecast error  
✔ Elasticity  
✔ Z-score  

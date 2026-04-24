# 📘 Week 8 – Marketing Analytics (Detailed Exam Q&A)

## 🔥 Topics Covered
- Market Basket Analysis
- Association Rules (Support, Confidence)
- RFM Analysis
- Retail Analytics Basics
- R Functions

---

# 🧠 PART 1: MARKET BASKET ANALYSIS (VERY IMPORTANT 🔥)

---

### ❓ Q1. What is Market Basket Analysis?
👉 A data mining technique used to identify **products frequently bought together**.

---

### 💡 Example:
- Bread → Butter  
- Milk → Cornflakes  

👉 Used in:
- Amazon recommendations  
- Supermarket product placement  

---

### ❓ Q2. Why is Market Basket Analysis important?
👉 
- Cross-selling (buy X → suggest Y)  
- Store layout optimization  
- Promotions and bundling  

---

### ❓ Q3. What is an association rule?
👉 A rule of the form:

👉 **A → B**

Meaning:
👉 If customer buys A, they are likely to buy B  

---

# 🔴 PART 2: KEY METRICS (VERY IMPORTANT 🔥)

---

### ❓ Q4. What is Support?
👉 Frequency of itemset in dataset  

👉 Formula:
👉 Support(A) = (Transactions containing A) / (Total transactions)

---

### ❓ Q5. What is Confidence?
👉 Probability that B is bought when A is bought  

👉 Formula:
👉 Confidence(A → B) = Support(A ∩ B) / Support(A)

---

### ❓ Q6. What is Lift? (Conceptual)
👉 Measures strength of association beyond chance  

👉 Lift > 1 → strong association  
👉 Lift = 1 → independent  
👉 Lift < 1 → weak  

---

### ❓ Q7. Which metric measures accuracy of rule?
👉 Confidence  

---

### ❓ Q8. Which metric measures coverage?
👉 Support  

---

# 🔴 PART 3: ALGORITHMS

---

### ❓ Q9. Which algorithm is commonly used?
👉 Apriori Algorithm  

---

### ❓ Q10. What does Apriori do?
👉 
1. Finds frequent itemsets  
2. Generates rules  

---

### ❓ Q11. What is minimum support?
👉 Threshold to filter important itemsets  

---

### ❓ Q12. Why Apriori is useful?
👉 Reduces computation by eliminating rare combinations  

---

# 🔴 PART 4: RFM ANALYSIS (VERY IMPORTANT 🔥)

---

### ❓ Q13. What is RFM?
👉 A method to segment customers based on behavior  

---

### ❓ Q14. What does RFM stand for?

👉 
- R = Recency (last purchase time)  
- F = Frequency (how often purchase)  
- M = Monetary (how much spent)  

---

### ❓ Q15. Which is most important in RFM?
👉 Recency (VERY COMMON MCQ)

---

### ❓ Q16. What does Frequency measure?
👉 How often customer buys  

---

### ❓ Q17. What does Monetary measure?
👉 Total spending  

---

### ❓ Q18. Why is RFM useful?

👉 
- Identify loyal customers  
- Target promotions  
- Improve marketing ROI  

---

### ❓ Q19. What is RFM segmentation?
👉 Dividing customers into groups based on R, F, M scores  

---

### ❓ Q20. What does high RFM score mean?
👉 Highly valuable customer  

---

# 🔴 PART 5: PRACTICAL INSIGHT QUESTIONS

---

### ❓ Q21. If a customer has:
- High recency  
- High frequency  
- High monetary  

👉 What type of customer?
👉 VIP / loyal customer  

---

### ❓ Q22. If frequency is low?
👉 Customer is inactive  

---

### ❓ Q23. Monetary / Frequency gives?
👉 Average purchase value  

---

# 🔴 PART 6: R FUNCTIONS (IMPORTANT)

---

### ❓ Q24. What does read.table() do?
👉 Reads file into data frame  

---

### ❓ Q25. is.date() converts date?
👉 ❌ False  

👉 (Common trap question)

---

# 🔴 PART 7: EXAM TRAPS (VERY IMPORTANT)

---

### ❓ Q26. itemplot() is used for item frequency?
👉 ❌ False  

---

### ❓ Q27. RFM helps improve spending?
👉 ✅ True  

---

### ❓ Q28. Market basket analysis is used for?
👉 Co-purchasing patterns  

---

### ❓ Q29. Frequency represents?
👉 Number of transactions  

---

### ❓ Q30. RFM helps in?
👉 Customer targeting  

---

# 🔴 PART 8: HIGH-PROBABILITY MCQs

---

### ❓ Q31. Market basket analysis is:
👉 Data mining technique  

---

### ❓ Q32. Confidence measures:
👉 Probability  

---

### ❓ Q33. Support measures:
👉 Frequency  

---

### ❓ Q34. RFM stands for:
👉 Recency, Frequency, Monetary  

---

### ❓ Q35. Best customers have:
👉 High R, F, M  

---

# 🚨 FINAL QUICK REVISION

👉 Remember these:

- MBA = co-purchase  
- Support = frequency  
- Confidence = probability  
- RFM = behavior  
- Recency = most important  

---

# 🎯 FINAL TIP

👉 Week 8 is:
- Very scoring  
- Concept-based  
- Repeated in exams  

Focus on:
✔ Definitions  
✔ Formulas  
✔ Applications  

Your Week 8 notes are already **excellent (~92–94%)** 👍
Now let’s push them to **100% exam-ready** with:

👉 **1. What ELSE to add (missing high-yield concepts)**
👉 **2. More advanced + tricky questions (exam level)**

---

# 🚨 WHAT YOU’RE STILL MISSING (WEEK 8 ADDITIONS)

---

# 🔴 1. LIFT — FULL INTERPRETATION (VERY IMPORTANT 🔥)

You mentioned it, but not deeply enough.

---

### ❓ Lift meaning (full):

👉 Lift = Confidence / Support(B)

---

### ❓ Interpretation:

| Lift | Meaning              |
| ---- | -------------------- |
| > 1  | Positive association |
| = 1  | Independent          |
| < 1  | Negative association |

---

👉 Exam LOVES this

---

---

# 🔴 2. SUPPORT vs CONFIDENCE vs LIFT (CONFUSION TRAP)

---

### ❓ Difference:

| Metric     | Meaning                 |
| ---------- | ----------------------- |
| Support    | Frequency               |
| Confidence | Conditional probability |
| Lift       | Strength beyond chance  |

---

---

# 🔴 3. APRIORI PRINCIPLE (VERY IMPORTANT)

---

### ❓ Key idea:

👉 If itemset is frequent → all subsets must be frequent

---

👉 Used to reduce computation

---

---

# 🔴 4. RULE DIRECTION (IMPORTANT)

---

### ❓ A → B same as B → A?

👉 ❌ No

---

👉 Confidence changes

---

---

# 🔴 5. STRONG RULE CRITERIA

---

### ❓ Rule is strong if:

👉 High support + high confidence + high lift

---

---

# 🔴 6. RFM — DEEPER INSIGHT

---

### ❓ Recency most important because?

👉 Recent buyers more likely to buy again

---

---

### ❓ Low recency means?

👉 Long time since last purchase → risk of churn

---

---

# 🔴 7. RFM SCORING (VERY IMPORTANT)

---

### ❓ How scoring works?

👉 Each variable given score (1–5)

---

### ❓ Example:

👉 R=5, F=4, M=3

---

---

# 🔴 8. CUSTOMER SEGMENTS (VERY IMPORTANT)

---

### ❓ Types:

👉

* Champions (high RFM)
* At-risk (low R)
* New customers
* Lost customers

---

---

# 🔴 9. CROSS-SELL vs UPSELL (IMPORTANT)

---

### ❓ Cross-sell:

👉 Recommend related product

---

### ❓ Upsell:

👉 Recommend higher-value product

---

---

# 🔴 10. DATA STRUCTURE IN MBA

---

### ❓ Data format?

👉 Transaction dataset

---

---

# 🔴 11. LIMITATIONS OF MARKET BASKET

---

### ❓ Limitations:

👉

* Large computation
* Too many rules
* Not causal (only association)

---

---

# 🔴 12. SUPPORT THRESHOLD (IMPORTANT)

---

### ❓ Why minimum support?

👉 Remove rare/unimportant patterns

---

---

# 🔴 13. RFM vs CLV (IMPORTANT DIFFERENCE)

---

### ❓ Difference:

| Concept | Meaning         |
| ------- | --------------- |
| RFM     | Behavior        |
| CLV     | Value over time |

---

---

# 🔥 NOW — ADD MORE QUESTIONS (EXAM LEVEL)

---

# 🧠 ADVANCED MCQs

---

### ❓ Q1. Lift > 1 means?

a) Negative relation
b) Positive relation
c) No relation
d) Random

👉 ✅ Answer: b

---

---

### ❓ Q2. Confidence measures?

👉 Conditional probability

---

---

### ❓ Q3. Support measures?

👉 Frequency

---

---

### ❓ Q4. Apriori principle states?

👉 Subsets must be frequent

---

---

### ❓ Q5. Which metric shows strongest rule?

👉 Lift

---

---

### ❓ Q6. Recency measures?

👉 Time since last purchase

---

---

### ❓ Q7. Frequency measures?

👉 Number of purchases

---

---

### ❓ Q8. Monetary measures?

👉 Spending

---

---

### ❓ Q9. Cross-sell means?

👉 Related products

---

---

### ❓ Q10. Upsell means?

👉 Higher-value product

---

---

# 🔥 TRICK QUESTIONS

---

### ❓ Q11. A → B same as B → A

👉 ❌ False

---

---

### ❓ Q12. Lift = confidence

👉 ❌ False

---

---

### ❓ Q13. MBA shows causation

👉 ❌ False

---

---

### ❓ Q14. High support always strong rule

👉 ❌ False

---

---

# 🔥 CASE-BASED QUESTIONS

---

### ❓ Q15.

Customer buys bread → suggest butter

👉 Market basket

---

---

### ❓ Q16.

Customer buys premium version

👉 Upselling

---

---

### ❓ Q17.

Customer buys phone → suggest cover

👉 Cross-selling

---

---

### ❓ Q18.

Customer last purchase long ago

👉 Low recency

---

---

# 🔥 NUMERICAL QUESTIONS

---

### ❓ Q19.

Support = 0.4
Confidence = 0.5
Support(B) = 0.2

Lift = 0.5 / 0.2 = 2.5

👉 Strong rule

---

---

### ❓ Q20.

10 transactions
Item appears in 3

Support = 3/10 = 0.3

---

---

# 🔥 MATCH-TYPE QUESTIONS

---

| Term       | Meaning     |
| ---------- | ----------- |
| Support    | Frequency   |
| Confidence | Probability |
| Lift       | Strength    |
| RFM        | Behavior    |
| MBA        | Co-purchase |

---

---

# 🚨 FINAL ADD-ON BLOCK

Add these to your notes:

✔ Lift formula
✔ Apriori principle
✔ Strong rule criteria
✔ RFM scoring
✔ Customer segments
✔ Cross-sell vs upsell

---





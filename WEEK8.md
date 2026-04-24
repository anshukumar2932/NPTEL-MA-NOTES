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

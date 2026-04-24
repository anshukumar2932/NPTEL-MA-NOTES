# 📘 Week 7 – Marketing Analytics (Detailed Exam Q&A)

## 🔥 Topics Covered
- Machine Learning Basics
- Recommender Systems
- Collaborative Filtering
- Sparse Matrix
- Clustering Basics
- Evaluation Scheme in R

---

# 🧠 PART 1: MACHINE LEARNING BASICS

---

### ❓ Q1. What is Machine Learning?
👉 A technique where systems **learn patterns from data** and make predictions without explicit programming.

---

### ❓ Q2. Machine learning is helpful for?

👉 
1. Predicting user behavior  
2. Filtering irrelevant information  
3. Making recommendations  

✅ Answer: **All of the above**

---

### 💡 Real-world examples:
- Netflix recommendations  
- Amazon product suggestions  
- Spam filtering  

---

### ❓ Q3. Difference: Statistics vs Machine Learning?

👉 
- **Statistics** → inference about population  
- **Machine Learning** → predictive patterns  

---

### ❓ Q4. What type of problems ML solves?
👉 
- Classification  
- Prediction  
- Recommendation  

---

# 🔴 PART 2: RECOMMENDER SYSTEMS (VERY IMPORTANT 🔥)

---

### ❓ Q5. What is a recommender system?
👉 System that suggests products/items based on user preferences.

---

### ❓ Q6. Where are recommender systems used?
👉 
- Amazon  
- Netflix  
- YouTube  

---

### ❓ Q7. What is the goal of recommender systems?
👉 
- Personalization  
- Increase sales  
- Improve user experience  

---

### ❓ Q8. What is personalization?
👉 Adapting recommendations based on:
- user preferences  
- behavior  
- interests  

👉 Answer: **All of the above**

---

# 🔴 PART 3: COLLABORATIVE FILTERING (VERY IMPORTANT 🔥)

---

### ❓ Q9. What is collaborative filtering?
👉 Recommends items based on **similar users’ behavior**

---

### 💡 Example:
👉 If users A & B like similar products  
👉 Then recommend A’s liked items to B  

---

### ❓ Q10. Types of collaborative filtering?

👉 
- User-based  
- Item-based  

---

### ❓ Q11. Key idea of collaborative filtering?
👉 “People like you also liked…”

---

### ❓ Q12. What data is used?
👉 User-item interaction data  

---

### ❓ Q13. Limitation of collaborative filtering?

👉 
- Cold start problem  
- Sparse data  
- New users/products  

---

# 🔴 PART 4: SPARSE MATRIX (VERY IMPORTANT)

---

### ❓ Q14. What is a sparse matrix?
👉 Matrix with **very few non-zero values**

---

### 💡 Example:
👉 In recommender systems:
- Many users haven’t rated most products  

---

### ❓ Q15. Why sparse matrix is important?
👉 
- Efficient storage  
- Important in recommendation systems  

---

# 🔴 PART 5: SIMILARITY & MATRICES

---

### ❓ Q16. What is similarity matrix?
👉 Matrix showing similarity between items/users  

---

### ❓ Q17. What is used in sequence alignment?
👉 Similarity matrices  

---

### ❓ Q18. What does higher similarity score mean?
👉 More similar items/users  

---

# 🔴 PART 6: R FUNCTIONS (IMPORTANT)

---

### ❓ Q19. What does evaluationscheme() do?
👉 Creates training and testing dataset  

---

### ❓ Q20. correlate.test() is used for correlation?
👉 ❌ False  

---

# 🔴 PART 7: CLUSTERING BASICS

---

### ❓ Q21. What is clustering?
👉 Grouping similar data points together  

---

### ❓ Q22. Why clustering is used?
👉 
- Segment customers  
- Find patterns  

---

### ❓ Q23. Example scenario:
👉 Dataset of singers, guitarists, anchors  

👉 First step?
👉 ✅ Clustering  

---

### ❓ Q24. Clustering is:
👉 Unsupervised learning  

---

# 🔴 PART 8: PERSONALIZATION & FILTERING

---

### ❓ Q25. Personalization includes?
👉 
- Recommendation  
- Filtering  
- Prediction  

✅ Answer: All  

---

### ❓ Q26. What is filtering?
👉 Removing irrelevant items  

---

# 🔴 PART 9: EXAM TRAPS (VERY IMPORTANT)

---

### ❓ Q27. Machine learning only used for prediction?
👉 ❌ False  

---

### ❓ Q28. Collaborative filtering uses item features?
👉 ❌ False  

👉 Uses user behavior  

---

### ❓ Q29. Sparse matrix has many non-zero values?
👉 ❌ False  

---

### ❓ Q30. Clustering is supervised learning?
👉 ❌ False  

---

# 🔴 PART 10: HIGH-PROBABILITY MCQs

---

### ❓ Q31. ML helps in?
👉 Prediction + filtering + recommendation  

---

### ❓ Q32. Collaborative filtering is based on?
👉 Similar users  

---

### ❓ Q33. Sparse matrix means?
👉 Few non-zero values  

---

### ❓ Q34. evaluationscheme() is used for?
👉 Training/testing  

---

### ❓ Q35. Clustering is?
👉 Unsupervised learning  

---

# 🚨 FINAL QUICK REVISION

👉 Remember these:

- ML = prediction + recommendation  
- CF = similar users  
- Sparse matrix = mostly zeros  
- Clustering = grouping  
- Personalization = user-based  

---

# 🎯 FINAL TIP

👉 Week 7 is:
- Moderate difficulty  
- Concept-heavy  
- Frequently asked  

Focus on:
✔ Collaborative filtering  
✔ Sparse matrix  
✔ Clustering basics  

Your Week 7 notes are already **very good (~90–92%)** 👍
Now let’s push it to **full exam-ready (100%)** with:

👉 **1. What ELSE to add (missing high-yield concepts)**
👉 **2. More advanced + tricky questions (exam level)**

---

# 🚨 WHAT YOU’RE STILL MISSING (WEEK 7 ADDITIONS)

---

# 🔴 1. CONTENT-BASED FILTERING (VERY IMPORTANT — MISSING)

You only covered collaborative filtering.

---

### ❓ What is content-based filtering?

👉 Recommends items based on **item features + user history**

---

### ❓ Example:

👉 If you like action movies → recommend similar genre

---

### ❗ Difference:

| Method        | Based on      |
| ------------- | ------------- |
| Collaborative | Users         |
| Content-based | Item features |

---

---

# 🔴 2. HYBRID RECOMMENDER SYSTEM

---

### ❓ What is hybrid system?

👉 Combination of collaborative + content-based

---

👉 Used in real systems (Netflix, Amazon)

---

---

# 🔴 3. COSINE SIMILARITY (VERY IMPORTANT 🔥)

---

### ❓ What is it?

👉 Measures similarity between vectors

---

### ❓ Formula idea:

👉 (A · B) / (|A||B|)

---

👉 Common in recommender systems

---

---

# 🔴 4. DISTANCE vs SIMILARITY (CONFUSION TRAP)

---

### ❓ Difference:

| Concept    | Meaning       |
| ---------- | ------------- |
| Distance   | Dissimilarity |
| Similarity | Closeness     |

---

---

# 🔴 5. TRAIN-TEST SPLIT PURPOSE

---

### ❓ Why split data?

👉 Avoid overfitting

---

---

# 🔴 6. OVERFITTING (VERY IMPORTANT)

---

### ❓ What is overfitting?

👉 Model performs well on training but poorly on test

---

---

# 🔴 7. UNDERFITTING

---

### ❓ What is underfitting?

👉 Model too simple

---

---

# 🔴 8. EVALUATION METRICS (ADVANCED)

---

### ❓ What is accuracy?

👉 Correct predictions

---

### ❓ What is precision?

👉 Relevant predictions

---

---

# 🔴 9. SIMILARITY METHODS (IMPORTANT)

---

### ❓ Types:

👉

* Cosine
* Pearson correlation

---

---

# 🔴 10. CLUSTERING METHODS (YOU MISSED DETAIL)

---

### ❓ Types:

👉

* K-means
* Hierarchical

---

---

# 🔴 11. K-MEANS (VERY IMPORTANT)

---

### ❓ How it works?

👉

1. Choose K
2. Assign points
3. Update centroid

---

---

# 🔴 12. K-MEANS LIMITATIONS

---

👉

* Sensitive to initialization
* Needs K
* Affected by outliers

---

---

# 🔴 13. COLD START PROBLEM (DEEPER)

---

### ❓ Types:

👉

* New user
* New item

---

---

# 🔴 14. SPARSITY PROBLEM (IMPORTANT)

---

### ❓ What is it?

👉 Too many missing values

---

---

# 🔴 15. RECOMMENDATION SCORE (IMPORTANT)

---

### ❓ How recommendation works?

👉 Weighted average of similar users/items

---

---

# 🔥 NOW — ADD MORE QUESTIONS (EXAM LEVEL)

---

# 🧠 ADVANCED MCQs

---

### ❓ Q1. Content-based filtering uses?

a) Users
b) Item features
c) Random
d) Price

👉 ✅ Answer: b

---

---

### ❓ Q2. Hybrid recommender combines?

👉 Collaborative + content

---

---

### ❓ Q3. Cosine similarity measures?

👉 Angle between vectors

---

---

### ❓ Q4. Overfitting means?

👉 Good training, poor testing

---

---

### ❓ Q5. Underfitting means?

👉 Model too simple

---

---

### ❓ Q6. Train-test split prevents?

👉 Overfitting

---

---

### ❓ Q7. Which is similarity method?

👉 Cosine

---

---

### ❓ Q8. K-means requires?

👉 Number of clusters (K)

---

---

### ❓ Q9. Cold start problem means?

👉 No data

---

---

### ❓ Q10. Sparse matrix contains?

👉 Few non-zero values

---

---

# 🔥 TRICK QUESTIONS

---

### ❓ Q11. Collaborative uses item features

👉 ❌ False

---

---

### ❓ Q12. Clustering is supervised

👉 ❌ False

---

---

### ❓ Q13. Cosine similarity gives distance

👉 ❌ False

---

---

### ❓ Q14. Overfitting is good

👉 ❌ False

---

---

# 🔥 CASE-BASED QUESTIONS

---

### ❓ Q15.

Recommend based on similar items → ?

👉 Content-based

---

---

### ❓ Q16.

Recommend based on similar users → ?

👉 Collaborative

---

---

### ❓ Q17.

New user no data → ?

👉 Cold start

---

---

### ❓ Q18.

Too many empty ratings → ?

👉 Sparsity problem

---

---

# 🔥 NUMERICAL / CONCEPT

---

### ❓ Q19.

Similarity high → ?

👉 More similar

---

---

### ❓ Q20.

Distance high → ?

👉 Less similar

---

---

# 🔥 MATCH-TYPE QUESTIONS

---

| Term          | Meaning    |
| ------------- | ---------- |
| Collaborative | Users      |
| Content-based | Items      |
| Sparse        | Few values |
| Clustering    | Grouping   |
| ML            | Prediction |

---

---

# 🚨 FINAL ADD-ON BLOCK

Add these to your notes:

✔ Content-based filtering
✔ Hybrid recommender
✔ Cosine similarity
✔ Overfitting / underfitting
✔ K-means
✔ Train-test split

---


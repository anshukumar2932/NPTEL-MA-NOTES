# 📘 Week 1 – Marketing Analytics (DETAILED THEORY + Q&A)

## 🔥 Topics Covered
- Introduction to R
- Data Types in R
- Data Structures (Vector, Matrix, Data Frame)
- Functions in R
- Missing Values (NA)
- Packages & Libraries

---

# 🧠 PART 1: INTRODUCTION TO R

---

### ❓ Q1. What is R?
👉 A programming language used for:
- Statistics  
- Data analysis  
- Visualization  

---

### ❓ Q2. R is mainly used in?
👉 
- Statistics  
- Probability  
- Problem solving  

✅ Answer: **All of the above**

---

### ❓ Q3. What is RStudio?
👉 IDE (interface) to work with R  

---

# 🔴 PART 2: DATA TYPES IN R

---

### ❓ Q4. What are basic data types?

👉 
- Numeric  
- Character  
- Logical  

---

### ❓ Q5. What is a factor?
👉 Categorical variable  

---

### ❓ Q6. How are factors stored?
👉 As integers with labels  

---

### ❓ Q7. Example:
👉 Gender = Male/Female  

---

# 🔴 PART 3: DATA STRUCTURES (VERY IMPORTANT 🔥)

---

### ❓ Q8. What is a vector?
👉 Collection of elements of same type  





### ❓ Q10. What is a matrix?

👉 2D data structure with same data type

---

### ❓ Q11. Statement:

👉 Matrix is 3D data
👉 ❌ False

---

### ❓ Q12. What is a data frame?

👉 2D structure with different data types

---

### ❓ Q13. Difference: Matrix vs Data frame?

👉

* Matrix → same type
* Data frame → mixed types

---

# 🔴 PART 4: FUNCTIONS IN R (VERY IMPORTANT 🔥)

---

### ❓ Q14. What is a function?

👉 Predefined operation

---

### ❓ Q15. In R, every operation has a call for?

👉 Function

---

### ❓ Q16. Example:

```R
mean(x)
sum(x)
```

---

# 🔴 PART 5: MISSING VALUES (NA)

---

### ❓ Q17. What is NA?

👉 Missing value

---

### ❓ Q18. How to check NA?

👉 `is.na()`

---

### ❓ Q19. How to remove NA in max function?

👉

```R
max(x, na.rm=TRUE)
```

---

### ❓ Q20. What does na.rm=TRUE do?

👉 Removes missing values

---

# 🔴 PART 6: PACKAGES & LIBRARIES

---

### ❓ Q21. What is a package?

👉 Collection of functions

---

### ❓ Q22. Packages are grouped into?

👉 Single unit

---

### ❓ Q23. What does library() do?

👉 Loads package

---

### ❓ Q24. Statement:

👉 library() is used to access package location
👉 ✅ True

---

# 🔴 PART 7: MODES & OBJECTS

---

### ❓ Q25. What is mode of object?

👉 Type of data

---

### ❓ Q26. Example:

```R
a <- c("a","b")
mode(a)
```

👉 Output: Character

---

### ❓ Q27. Which is NOT object in R?

👉 Strings

---

# 🔴 PART 8: PRACTICAL QUESTIONS

---

### ❓ Q28. max(x) ignoring NA?

👉 max(x, na.rm=TRUE)

---

### ❓ Q29. is.na() is used for?

👉 Checking missing values

---

### ❓ Q30. Matrix is?

👉 2D structure

---

# 🔴 PART 9: EXAM TRAPS (VERY IMPORTANT)

---

### ❓ Q31. Matrix is 3D?

👉 ❌ False

---

### ❓ Q32. Strings are R objects?

👉 ❌ False

---

### ❓ Q33. library() is useless?

👉 ❌ False

---

### ❓ Q34. Functions are not needed?

👉 ❌ False

---

# 🔴 PART 10: HIGH-PROBABILITY MCQs

---

### ❓ Q35. Packages are?

👉 Single unit

---

### ❓ Q36. is.na() checks?

👉 Missing values

---

### ❓ Q37. Matrix is?

👉 2D

---

### ❓ Q38. Data frame allows?

👉 Mixed data types

---

### ❓ Q39. R is used for?

👉 Statistics

---

# 🚨 FINAL QUICK REVISION

👉 Remember:

* Vector = same type
* Matrix = 2D same type
* Data frame = mixed type
* Function = operation
* NA = missing

---

# 🎯 FINAL TIP

👉 Week 1 is:

* Easy
* Direct questions
* Scoring

Focus on:
✔ Data structures
✔ NA handling
✔ Functions
✔ Packages

Your Week 1 notes are already **very solid** 👍 — honestly better than what most students prepare.

But if you want **FULL marks**, here’s what you’re **missing / should add** 👇

---

# 🚨 WHAT YOU MISSED (IMPORTANT ADDITIONS)

---

# 🔴 1. VECTOR CREATION METHODS (VERY COMMON MCQ)

You defined vector, but not **how to create it**

### ❓ Q. How to create vector?

```r
c(1,2,3)
```

👉 `c()` = combine function

---

### ❓ Other ways:

```r
1:5        # sequence
seq(1,10,2)
rep(1,5)
```

---

# 🔴 2. LENGTH FUNCTION

### ❓ Q. How to find length of vector?

```r
length(x)
```

👉 VERY commonly asked

---

# 🔴 3. CLASS vs MODE (CONFUSION TRAP)

You only wrote **mode**

### ❓ Difference?

👉 `mode()` → internal storage
👉 `class()` → object type

---

### ❓ Example:

```r
class(dataframe)
```

---

# 🔴 4. DATA FRAME CREATION (IMPORTANT)

You defined it but didn’t show creation

### ❓ Q. How to create?

```r
df <- data.frame(name="A", age=20)
```

---

# 🔴 5. INDEXING (VERY IMPORTANT 🔥)

Almost always asked indirectly

---

### ❓ Vector indexing:

```r
x[1]
```

---

### ❓ Matrix indexing:

```r
x[1,2]
```

👉 row, column

---

# 🔴 6. ASSIGNMENT OPERATORS

### ❓ Q. Assignment in R?

```r
<- 
=
```

👉 `<-` preferred

---

# 🔴 7. LOGICAL OPERATORS (MISSING)

---

### ❓ Examples:

```r
x > 5
x == 2
x != 3
```

---

### ❓ AND / OR:

```r
&   # AND
|   # OR
```

---

# 🔴 8. IMPORTANT BUILT-IN FUNCTIONS (HIGH PROBABILITY)

You only gave mean & sum

👉 Add these:

```r
min(x)
max(x)
median(x)
sd(x)
var(x)
```

---

# 🔴 9. SEQUENCE vs REPEAT (COMMON CONFUSION)

---

### ❓ seq():

👉 generates sequence

---

### ❓ rep():

👉 repeats values

---

---

# 🔴 10. INSTALL vs LIBRARY (VERY IMPORTANT TRAP)

---

### ❓ install.packages()

👉 installs package

---

### ❓ library()

👉 loads package

---

👉 EXAM TRAP 🔥

---

# 🔴 11. WORKSPACE CONCEPT

---

### ❓ Workspace?

👉 Environment where variables are stored

---

---

# 🔴 12. PRINT vs OUTPUT

---

### ❓ print()

👉 explicitly display output

---

---

# 🔴 13. COMMON ERRORS (VERY USEFUL)

---

### ❓ NA vs NULL

👉 NA = missing value
👉 NULL = no value

---

---

# 🔴 14. EXTRA MCQs YOU MISSED

---

### ❓ R is case sensitive?

👉 ✅ True

---

### ❓ Everything in R is?

👉 Object

---

### ❓ Data frame is?

👉 List of equal length vectors

---

---

# 🔴 15. VERY IMPORTANT CONCEPT (OFTEN ASKED)

---

### ❓ What is vectorization?

👉 Operations applied on entire vector

Example:

```r
x + 2
```

---

---

# 🎯 FINAL ADD-ON SUMMARY

Add these to your notes:

✔ Vector creation methods
✔ length()
✔ class()
✔ indexing
✔ logical operators
✔ install vs library
✔ basic stats functions
✔ vectorization

---




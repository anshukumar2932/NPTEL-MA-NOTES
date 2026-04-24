# 🧠 1. BASIC R SYNTAX

### 👉 Creating variables

```r
x <- 10
y = 20
```

👉 Both `<-` and `=` work (but `<-` is standard in R)

---

# 🔴 2. VECTORS (MOST IMPORTANT)

### 👉 Create vector

```r
x <- c(1,2,3,4)
```

👉 `c()` = combine function

---

### 👉 Access elements

```r
x[1]     # first element
x[2:3]   # range
```

---

### 👉 Basic functions

```r
sum(x)
mean(x)
length(x)
```

---

### 👉 Example

```r
x <- c(10,20,30)
mean(x)   # 20
```

---

# 🔴 3. HANDLING MISSING VALUES (VERY IMPORTANT)

### 👉 Check NA

```r
is.na(x)
```

---

### 👉 Remove NA in calculation

```r
x <- c(10, NA, 30)

mean(x)                 # NA
mean(x, na.rm=TRUE)     # 20
```

👉 ⚠️ Exam favorite: `na.rm=TRUE`

---

# 🔴 4. MATRIX

### 👉 Create matrix

```r
m <- matrix(c(1,2,3,4), nrow=2)
```

---

### 👉 Access

```r
m[1,2]   # row 1, column 2
```

---

### 👉 Example

```r
m <- matrix(1:6, nrow=2)
m
```

---

# 🔴 5. DATA FRAME (VERY IMPORTANT)

### 👉 Create dataframe

```r
df <- data.frame(
  name = c("A","B"),
  age = c(20,25)
)
```

---

### 👉 Access column

```r
df$name
df[1,2]
```

---

### 👉 Structure

```r
str(df)
```

👉 Shows data types (EXAM QUESTION)

---

# 🔴 6. FACTORS

### 👉 Create factor

```r
gender <- factor(c("Male","Female","Male"))
```

---

### 👉 Check levels

```r
levels(gender)
```

👉 Stored as integers internally

---

# 🔴 7. BASIC FUNCTIONS (IMPORTANT)

---

### 👉 `seq()` – sequence

```r
seq(1,10)
seq(1,10, by=2)
```

👉 Output: 1 3 5 7 9

---

### 👉 `rep()` – repeat

```r
rep(1,5)
rep(c(1,2),3)
```

👉 Output: 1 2 1 2 1 2

---

---

# 🔴 8. CONDITIONAL STATEMENTS

### 👉 if-else

```r
x <- 10

if(x > 5){
  print("Greater")
} else {
  print("Smaller")
}
```

---

# 🔴 9. LOOPS

### 👉 for loop

```r
for(i in 1:5){
  print(i)
}
```

---

### 👉 while loop

```r
i <- 1
while(i <= 5){
  print(i)
  i <- i + 1
}
```

---

# 🔴 10. FUNCTIONS (VERY IMPORTANT)

---

### 👉 Create function

```r
add <- function(a,b){
  return(a+b)
}

add(2,3)   # 5
```

---

### 👉 Without return

```r
add <- function(a,b){
  a+b
}
```

---

# 🔴 11. LOGICAL OPERATIONS

```r
x > 5
x == 10
x != 3
```

---

### 👉 Example

```r
x <- 10
x > 5   # TRUE
```

---

# 🔴 12. %in% OPERATOR

```r
x <- c(1,2,3)

2 %in% x   # TRUE
5 %in% x   # FALSE
```

👉 Used in MCQs

---

# 🔴 13. MAX / MIN FUNCTIONS

```r
x <- c(10,20,NA)

max(x, na.rm=TRUE)
min(x, na.rm=TRUE)
```

---

# 🔴 14. READING DATA

```r
df <- read.table("file.txt")
```

👉 Creates dataframe

---

# 🔴 15. RANDOM FUNCTIONS

### 👉 sample()

```r
sample(1:10, 3)
```

👉 Random 3 numbers

---

# 🔴 16. MODEL FUNCTIONS (IMPORTANT)

---

### 👉 lm() – linear regression

```r
model <- lm(y ~ x, data=df)
```

---

### 👉 glm() – logistic regression

```r
model <- glm(y ~ x, family=binomial)
```

---

# 🔴 17. IMPORTANT EXAM FUNCTIONS

| Function       | Use           |
| -------------- | ------------- |
| `is.na()`      | check missing |
| `na.rm=TRUE`   | remove NA     |
| `str()`        | structure     |
| `seq()`        | sequence      |
| `rep()`        | repeat        |
| `sample()`     | random        |
| `read.table()` | read data     |

---

# ⚠️ COMMON EXAM TRAPS

---

### ❌ Wrong

```r
mean(x)   # with NA → NA
```

### ✅ Correct

```r
mean(x, na.rm=TRUE)
```

---

### ❌ Wrong

* Matrix = 3D

### ✅ Correct

* Matrix = 2D

---

### ❌ Wrong

* Data frame = same type

### ✅ Correct

* Mixed type

---

# 🎯 FINAL QUICK REVISION

👉 Remember:

* `c()` = vector
* `matrix()` = 2D
* `data.frame()` = mixed
* `is.na()` = missing
* `str()` = structure
* `sample()` = random

---

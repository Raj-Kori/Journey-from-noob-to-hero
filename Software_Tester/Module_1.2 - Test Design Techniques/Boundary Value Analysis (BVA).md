---
title: Module 1 - Test Design Techniques
start_date: 2026-03-30
end_date: 2026-04-19
tags:
  - BVA
  - EP
  - Decision_Table
  - State_Transition
---
---

# 🔷 Boundary Value Analysis (BVA)

> [!note] Definition  
> Boundary Value Analysis (BVA) is a **black-box testing technique** that focuses on testing values at the **boundaries of input ranges**, where defects are most likely to occur.

---

## 🧠 Key Concept

- Errors usually occur at **edge values (boundaries)**
    
- Tests are designed using:
    
    - Minimum value
        
    - Just above minimum
        
    - Nominal value
        
    - Just below maximum
        
    - Maximum value
        

---

# 📊 Example (Age Validation: 18–56)

|Type|Values|
|---|---|
|Invalid (min - 1)|17|
|Valid|18, 19, 37, 55, 56|
|Invalid (max + 1)|57|

---

## ✅ Valid Test Cases

- 18
    
- 19
    
- 37
    
- 55
    
- 56
    

---

## ❌ Invalid Test Cases

- 17
    
- 57
    

---

# 🎯 Key Rule

> [!tip] Always test:  
> **min, min+1, nominal, max-1, max**

---

# 🔢 Test Case Formula

For **n variables**:

👉 **Maximum Test Cases = 4n + 1**

---

## 📌 Example

For n = 3:

👉 4 × 3 + 1 = **13 test cases**

---

# 🧪 Single Fault Assumption

> [!note] Concept  
> Test one variable at boundary while keeping others at **normal values**

### Example:

- Test **Year** → keep Month & Day constant
    
- Test **Day** → keep Month & Year constant
    
- Test **Month** → keep Day & Year constant
    

---

# ⚙️ Where BVA is Used

- Input validation testing
    
- Range-based fields (age, salary, marks)
    
- Form validations
    
- APIs with numeric constraints
    

---

# ⚠️ Limitations

- Cannot handle **complex variable relationships**
    
- Not suitable for **dependent inputs**
    
- Works best with **range-based inputs only**
    

---

# 🔗 Equivalence Partitioning (EP)

> [!note] Definition  
> EP divides input data into **valid and invalid groups (partitions)** to reduce test cases.

---

## 📊 Example (6–10 Characters Allowed)

|Input Range|Result|
|---|---|
|0–5|Invalid|
|6–10|Valid|
|11–14|Invalid|

---

# 🤝 BVA + EP Together

## Why Combine?

- Reduces number of test cases
    
- Improves coverage
    
- Efficient for large inputs
    

---

# 🎯 Key Insight

> EP selects **range**, BVA tests **edges of that range**

---

# ⚡ Quick Revision

|Concept|Meaning|
|---|---|
|BVA|Test boundary values|
|Focus|Edge cases|
|Formula|4n + 1|
|EP|Divide into partitions|

---

# 🔗 Related Notes

- [[Boundary Value Analysis (BVA)]]
    
- [[State_Transition]]
    
- [[Decision_Table]]
    
- [[EP]]
---
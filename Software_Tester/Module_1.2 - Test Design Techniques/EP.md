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
# 🔷 Equivalence Partitioning (EP)

> [!note] Definition  
> Equivalence Partitioning is a **black-box testing technique** that divides input data into **valid and invalid groups (partitions)** to reduce the number of test cases.

---

## 💡 Simple Explanation (Very Important)

Instead of testing **every possible input**, we:

- Divide inputs into **groups (partitions)**
    
- Assume all values in a group behave the same
    
- Test **one value from each group**
    

---

### 🎯 Key Idea

> If one value from a partition works correctly,  
> then all values in that partition are assumed to work correctly.

---

# 🧠 Key Concept

- Reduces **number of test cases**
    
- Covers **valid + invalid inputs**
    
- Works best for **range-based inputs**
    

---

# 📊 Types of Partitions

## 🔹 Valid Partition

- Inputs that should be **accepted**
    

## 🔹 Invalid Partition

- Inputs that should be **rejected**
    

---

# 📌 Guidelines

- **Range input (e.g., 50–90)**  
    → 1 valid + 2 invalid partitions
    
- **Exact value input**  
    → 1 valid + 2 invalid
    
- **Set of values**  
    → 1 valid + 1 invalid
    
- **Boolean input**  
    → 1 valid + 1 invalid
    

---

# 🧪 Examples

## 📍 Example 1: Percentage (50–90)

|Partition|Type|Example|
|---|---|---|
|< 50|Invalid|40|
|50–90|Valid|70|
|> 90|Invalid|95|

---

## 📍 Example 2: Product ID

|Partition|Type|Example|
|---|---|---|
|Valid IDs|Valid|45|
|Invalid IDs|Invalid|999|

---

## 📍 Example 3: OTP (6 Digits)

|Partition|Type|Example|
|---|---|---|
|< 6 digits|Invalid|123|
|= 6 digits|Valid|123456|
|> 6 digits|Invalid|12345678|

---

# 🎯 When to Use

- Input fields with ranges
    
- Form validations
    
- Login / OTP / ID validation
    
- APIs with input constraints
    

---

# ✅ Advantages

- Reduces test cases significantly
    
- Easy to implement
    
- Improves test coverage
    
- Saves time and effort
    

---

# ❌ Limitations

- May miss edge cases (use with BVA)
    
- Not suitable for complex logic
    
- Assumes all values behave the same
    

---

# 🤝 EP vs BVA

|Technique|Focus|
|---|---|
|EP|Divide inputs into groups|
|BVA|Test boundary values|

> [!tip] Best practice: Use **EP + BVA together**

---

# 🎯 Key Insight

> EP reduces test cases, BVA improves accuracy

---

# ⚡ Quick Revision

|Concept|Meaning|
|---|---|
|EP|Divide inputs into partitions|
|Goal|Reduce test cases|
|Types|Valid / Invalid|
|Best Used With|BVA|

---

# 🔗 Related Notes

- [[Boundary Value Analysis (BVA)]]
    
- [[State_Transition]]
    
- [[Decision_Table]]
    
- [[EP]]
---
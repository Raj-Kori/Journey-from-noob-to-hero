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
# 🔷 Decision Table Testing

> [!note] Definition  
> Decision Table Testing is a **black-box testing technique** used to test systems where the output depends on **multiple input conditions and their combinations**.

---

## 🧠 Key Concept

- Used when **multiple conditions affect output**
    
- Represents logic in **tabular format**
    
- Conditions → True (T) / False (F)
    
- Helps cover **all possible combinations**
    

---

# 📊 Structure of Decision Table

Decision Table has **4 main parts**:

|Part|Description|
|---|---|
|Condition Stub|List of conditions (inputs)|
|Condition Entries|Values (T/F) for conditions|
|Action Stub|Possible actions (outputs)|
|Action Entries|Output for each condition combination|

---

# 📌 Simple Example (Login System)

| Conditions     | Rule 1        | Rule 2 | Rule 3 | Rule 4 |
| -------------- | ------------- | ------ | ------ | ------ |
| Username Valid | T             | T      | F      | F      |
| Password Valid | T             | F      | T      | F      |
| **Action**     | Login Success | Error  | Error  | Error  |

---

# 🧪 Types of Decision Tables

## 🔹 Limited Entry

- Only **True / False values**
    
- Simple conditions
    

## 🔹 Extended Entry

- Multiple values (not just T/F)
    
- More complex scenarios
    

---

# ⚙️ When to Use

- Business rule validation
    
- Complex logic systems
    
- Form validations
    
- Insurance, banking systems
    
- Pricing or discount logic
    

---

# 🎯 Key Rules

- Order of rules **does not matter**
    
- Each column = **one test case**
    
- Covers **all condition combinations**
    

---

# ✅ Advantages

- Handles complex logic easily
    
- Ensures **complete test coverage**
    
- Easy to understand (tabular format)
    
- Reduces missing test cases
    

---

# ❌ Disadvantages

- Large tables for many conditions
    
- Time-consuming to create
    
- Hard to manage for very complex systems
    

---

# 🎯 Key Insight

> Best used when **output depends on multiple input combinations**

---

# ⚡ Quick Revision

|Concept|Meaning|
|---|---|
|Decision Table|Condition vs Action table|
|Focus|Multiple input combinations|
|Output|Based on rules|
|Use Case|Business logic|

---

# 🔗 Related Notes

- [[Boundary Value Analysis (BVA)]]
    
- [[State_Transition]]
    
- [[Decision_Table]]
    
- [[EP]]
---
---
title: Module 1.3 - Test Design Techniques
start_date: 2025-03-20
end_date: 2026-04-19
tags:
  - Test_plan
  - Test_Case
  - Bug_report
---
|              |                |                          |                                                                                         |                           |                                                     |          |         |
| ------------ | -------------- | ------------------------ | --------------------------------------------------------------------------------------- | ------------------------- | --------------------------------------------------- | -------- | ------- |
| Test Case ID | Module         | Test Scenario            | Test Steps                                                                              | Test Data                 | Expected Result                                     | Priority | Status  |
| TC_001       | Authentication | Valid Login              | 1. Open site  <br>2. Click login  <br>3. Enter valid credentials  <br>4. Click submit   | Valid username/password   | User should login successfully                      | High     | Pending |
| TC_002       | Authentication | Invalid Login            | 1. Open site  <br>2. Click login  <br>3. Enter invalid credentials  <br>4. Click submit | Invalid username/password | Error message should be displayed                   | High     | Pending |
| TC_003       | Search         | Search Product           | 1. Enter product name in search bar  <br>2. Click search                                | Laptop                    | Relevant products should be displayed               | High     | Pending |
| TC_004       | Search         | Apply Filters            | 1. Search product  <br>2. Apply price/category filters                                  | Price < 50000             | Filtered results should be shown                    | Medium   | Pending |
| TC_005       | Product Page   | Validate Product Details | 1. Open product page                                                                    | Any product               | Correct price, description, and availability shown  | High     | Pending |
| TC_006       | Cart           | Add to Cart              | 1. Select product  <br>2. Click Add to Cart                                             | Any product               | Product should be added to cart                     | High     | Pending |
| TC_007       | Cart           | Remove from Cart         | 1. Open cart  <br>2. Click remove                                                       | Any product               | Product should be removed from cart                 | Medium   | Pending |
| TC_008       | Checkout       | Proceed to Checkout      | 1. Open cart  <br>2. Click checkout                                                     | Valid cart items          | User should navigate to checkout page               | High     | Pending |
| TC_009       | Payment        | Successful Payment       | 1. Enter payment details  <br>2. Submit                                                 | Valid test card           | Payment should be successful                        | High     | Pending |
| TC_010       | Order          | Order Confirmation       | 1. Complete payment                                                                     | Valid order               | Order confirmation page with order ID should appear | High     | Pending |
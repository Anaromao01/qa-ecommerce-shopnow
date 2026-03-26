# qa-ecommerce-shopnow

# 🧪 QA Project — Ecommerce ShopNow (Fictional)

This repository contains a **fictional software testing project**, created for **learning, practice, and QA portfolio purposes**.

The goal is to demonstrate skills in:
- Test case creation  
- Professional bug report writing  
- Severity and priority analysis  
- User and business impact assessment  
- Test organization and documentation  

> ⚠️ **Note:**  
> This project is fictional. The “ShopNow” application is not real and was created only to simulate common ecommerce scenarios.

---

## 📦 Project Scope

Mobile ecommerce application with the following simulated features:

- User login  
- Product listing  
- Price filtering  
- Shopping cart  
- Checkout  
- PIX payment  

---

## ✅ Tested Features

- Login  
- Cart  
- Product filtering  
- Checkout and payment  

---

## 🐞 Reported Bugs

### 🔴 BUG001 — Checkout  
**Title:** When clicking “Place Order”, the app returns to Home  
**Severity:** High  
**Priority:** High  

**Description:**  
After completing all checkout steps, the user is unable to place the order and is redirected to the home screen.

---

### 🟠 BUG002 — Price Filter  
**Title:** Price filter disappears when clicking “Next page”  
**Severity:** Medium  
**Priority:** High  

**Description:**  
When navigating between pages, the applied filter is lost, displaying products outside the selected criteria.

---

### 🔴 BUG003 — PIX Payment (CRITICAL)  
**Title:** Infinite loading when selecting PIX payment  
**Severity:** Critical  
**Priority:** P0  

**Description:**  
After selecting PIX as the payment method, the system remains stuck in an infinite loading state, blocking the purchase completion.

**Impact:**  
- Payment blockage  
- Financial risk to the business  
- Cart abandonment  

---

## 🧪 Test Cases

| ID   | Title                          |
|------|--------------------------------|
| TC001 | Login with valid credentials  |
| TC002 | Login with invalid password   |
| TC003 | Add product to cart           |
| TC004 | Filter products by price      |
| TC005 | Complete order via PIX        |

Test cases are written following QA best practices:
- Precondition  
- Steps  
- Expected result  

---

## 📊 QA Summary

- Critical features tested with focus on user experience  
- Critical bug identified in PIX checkout flow  
- System **not recommended for release** due to financial risk  

### Release Status  
❌ **Not recommended**

---

## 📌 Recommendations

- Prioritize fixing BUG003 (PIX) — P0 priority  
- Implement timeout and fallback in the payment flow  
- Ensure filter persistence between pages  
- Improve logs and error messages in checkout  

---

## 👩‍💻 Author

**Ana Claudia Romão**  
QA Career Transition | Manual Testing | Software Quality  

🔗 GitHub: https://github.com/Anaromao01
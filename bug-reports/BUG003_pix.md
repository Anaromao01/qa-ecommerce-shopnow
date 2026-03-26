# BUG-003 — Infinite loading when selecting PIX payment

## Environment
- App: ShopNow  
- Version: 2.3.1  
- Device: Android 14  
- User: Logged in  

---

## Precondition

- User is logged in  
- User has no saved credit card  
- Product added to the cart  

---

## Steps to Reproduce

1. Open the app with a logged-in user  
2. Add a product to the cart  
3. Enter a valid address  
4. Select **PIX** as the payment method  
5. Confirm the payment method  

---

## Expected Result

The app should display:

✅ PIX QR Code  
✅ Copy-and-paste payment code  

---

## Actual Result

The app remains stuck in an infinite loading state, preventing the payment from being completed.

---

## Severity / Priority

- Severity: Critical  
- Priority: P0  

**Justification:** Blocks PIX payment, causing revenue loss and cart abandonment.

---

## Evidence

Fictional project (simulation for portfolio purposes).
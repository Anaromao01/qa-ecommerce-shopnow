# BUG-001 — Checkout redirects to Home when placing an order

## Environment
- App: ShopNow  
- Version: 2.3.1  
- Device: Android 14  
- User: Logged in  

---

## Precondition
User must be logged in and have at least one product in the cart.

---

## Steps to Reproduce

1. Be logged into the application  
2. Add a product to the cart  
3. Enter a valid address  
4. Enter a valid payment method  
5. Click on **Place Order**

---

## Expected Result

The system should successfully complete the order and display the message:

✅ “Order placed successfully” + receipt.

---

## Actual Result

When clicking on **Place Order**, the app redirects to the Home screen without completing the order.

---

## Severity / Priority

- Severity: High  
- Priority: High  

**Justification:** This bug blocks the main purchase flow and may lead to cart abandonment.

---

## Evidence

Fictional project (simulation for portfolio purposes).
# Test Cases – E-commerce UI Testing (Demoblaze)

## TC001 – Verify homepage loads successfully
**Precondition:** Browser opened  
**Steps:**
1. Navigate to [https://www.demoblaze.com/](https://www.demoblaze.com/)  
**Expected Result:** Homepage displays with product listings.  
**Priority:** High  

---

## TC002 – Verify product details page opens
**Precondition:** Homepage loaded  
**Steps:**
1. Click on a product name  
**Expected Result:** Product details page opens with title, description, and price.  
**Priority:** High  

---

## TC003 – Add product to cart
**Precondition:** Product details page open  
**Steps:**
1. Click **"Add to cart"**  
2. Accept confirmation alert  
**Expected Result:** Product is added to cart, alert message is shown.  
**Priority:** High  

---

## TC004 – Remove product from cart
**Precondition:** Product in cart  
**Steps:**
1. Navigate to **"Cart"**  
2. Click **"Delete"** next to the product  
**Expected Result:** Product is removed from cart.  
**Priority:** Medium  

---

## TC005 – Verify checkout process
**Precondition:** Product in cart  
**Steps:**
1. Click **"Place Order"**  
2. Fill in form details  
3. Click **"Purchase"**  
**Expected Result:** Order confirmation message is displayed.  
**Priority:** High  
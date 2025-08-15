\# Bug Reports – E-commerce UI Testing (Demoblaze)



---



\## Bug 001 – Product image not loading on homepage

\*\*ID:\*\* BUG-001  

\*\*Title:\*\* Product image missing for "Samsung galaxy s6" on homepage  

\*\*Priority:\*\* High  

\*\*Severity:\*\* Major  

\*\*Environment:\*\*  

\- Browser: Google Chrome 126  

\- OS: Windows 10 Pro (64-bit)  



\*\*Preconditions:\*\*

\- Homepage is loaded.



\*\*Steps to Reproduce:\*\*

1\. Navigate to https://www.demoblaze.com/ 

2\. Scroll to "Samsung galaxy s6" in the product list  



\*\*Expected Result:\*\* Product image should be visible and match the product description.  

\*\*Actual Result:\*\* Image placeholder is shown instead of product image.  



\*\*Attachments:\*\*  

\- Screenshot: `/screenshots/defects/BUG-001.png`



---



\## Bug 002 – Cart count not updating after adding a product

\*\*ID:\*\* BUG-002  

\*\*Title:\*\* Cart item counter does not update after adding a product  

\*\*Priority:\*\* Medium  

\*\*Severity:\*\* Major  



\*\*Preconditions:\*\*

\- Homepage is loaded.



\*\*Steps to Reproduce:\*\*

1\. Open product details for any item.  

2\. Click \*\*"Add to cart"\*\*.  

3\. Accept alert message.  



\*\*Expected Result:\*\* Cart icon should display updated item count (e.g., 1).  

\*\*Actual Result:\*\* Cart counter remains unchanged until page refresh.  



---



\## Bug 003 – Checkout form allows empty required fields

\*\*ID:\*\* BUG-003  

\*\*Title:\*\* Place Order allows submission with empty required fields  

\*\*Priority:\*\* High  

\*\*Severity:\*\* Critical  



\*\*Preconditions:\*\*

\- Product is added to the cart.



\*\*Steps to Reproduce:\*\*

1\. Go to \*\*Cart\*\*.  

2\. Click \*\*"Place Order"\*\*.  

3\. Leave all fields empty.  

4\. Click \*\*"Purchase"\*\*.  



\*\*Expected Result:\*\* Validation messages should appear, preventing submission.  

\*\*Actual Result:\*\* Purchase completes without entering mandatory data.  


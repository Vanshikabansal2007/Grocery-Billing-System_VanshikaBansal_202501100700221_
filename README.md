# Grocery-Billing-System_VanshikaBansal_202501100700221_
🛒 Grocery Billing System (Python)
📌 Problem Statement

Develop a simple Grocery Billing System using Python that:

Accepts the prices of three grocery items from the user.

Calculates the total bill amount.

Applies a 10% discount if the total amount exceeds ₹50.

Displays the total amount, discount applied, and final payable amount in a formatted billing structure.

💡 Approach

Display Welcome Message

Print a heading for the Grocery Billing System.

Take User Input

Accept prices of three items using float(input()).

Calculate Total

Add all three item prices:

total = it1 + it2 + it3

Apply Discount

If total amount is greater than 50:

discount = total * 0.1

(10% discount is applied)

Generate Final Bill

Print:

Total Amount

Discount

Final Payable Amount (total - discount)

Format values to two decimal places using:

{value:.2f}
✅ Result

The program successfully:

Takes user input for three grocery items.

Calculates total amount.

Applies a 10% discount when total exceeds ₹50.

Displays a clean and formatted bill.

📌 Example Output
------------------------
--> WELCOME TO <--
GROCERY BILLING SYSTEM
------------------------

Enter Price of item 1: 20
Enter price of item 2: 25
Enter price of item 3: 15

-----------------------
---Billing Details---
-----------------------
Total : 60.00
Discount : 6.00
Final Price : 54.00

Thank You For Shopping
🧾 Conclusion

This project demonstrates:

Basic Python input/output

Arithmetic operations

Conditional statements (if)

Formatted printing

It is a beginner-friendly program that helps understand billing logic and discount calculations.

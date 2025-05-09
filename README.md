#  Automation Exercise - Automated GUI Testing
##  Automated tests using Selenium with Java for an E-commerce website
##  Website home page
![homepage](https://user-images.githubusercontent.com/124753072/235929032-4471bd18-9133-46ae-84da-931f0d94bb35.jpg)

##  About this project
The project was created to practice test automation skills using the Selenium (Java) framework, utilizing skills learned in a course on the Udemy platform. The website under test is a website specifically designed for automated testing. The project contains a total of 26 automated tests, created based on test cases defined by the site's developers. After running and executing the tests, using the proper command, a test report can be generated, which describes in detail the activities performed and the statuses of each test.

##  Tools:
+ IntelliJ IDEA
+ Maven
+ Selenium WebDriver
+ TestNG
+ Allure Report

##  Project Design:
+ Page Object Model
+ Fluent Interface
+ Data-Driven approach
+ Behavior-Driven approach
+ ###  Test Case 1: Register User
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Signup / Login' button </ol>
<ol> 5. Verify 'New User Signup!' is visible </ol>
<ol> 6. Enter name and email address </ol>
<ol> 7. Click 'Signup' button </ol>
<ol> 8. Verify that 'ENTER ACCOUNT INFORMATION' is visible </ol>
<ol> 9. Fill details: Title, Name, Email, Password, Date of birth </ol>
<ol> 10. Select checkbox 'Sign up for our newsletter!' </ol>
<ol> 11. Select checkbox 'Receive special offers from our partners!' </ol>
<ol> 12. Fill details: First name, Last name, Company, Address, Address2, Country, State, City, Zipcode, Mobile Number </ol>
<ol> 13. Click 'Create Account button' </ol>
<ol> 14. Verify that 'ACCOUNT CREATED!' is visible </ol>
<ol> 15. Click 'Continue' button </ol>
<ol> 16. Verify that 'Logged in as username' is visible </ol>
<ol> 17. Click 'Delete Account' button </ol>
<ol> 18. Verify that 'ACCOUNT DELETED!' is visible and click 'Continue' button </ol>

---

###  Test Case 2: Login User with correct email and password
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Signup / Login' button </ol>
<ol> 5. Verify 'Login to your account' is visible </ol>
<ol> 6. Enter correct email address and password </ol>
<ol> 7. Click 'login' button </ol>
<ol> 8. Verify that 'Logged in as username' is visible </ol>

---

###  Test Case 3: Login User with incorrect email and password
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Signup / Login' button </ol>
<ol> 5. Verify 'Login to your account' is visible </ol>
<ol> 6. Enter incorrect email address and password </ol>
<ol> 7. Click 'login' button </ol>
<ol> 8. Verify error 'Your email or password is incorrect!' is visible </ol>

---

###  Test Case 4: Logout User
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Signup / Login' button </ol>
<ol> 5. Verify 'Login to your account' is visible </ol>
<ol> 6. Enter correct email address and password </ol>
<ol> 7. Click 'login' button </ol>
<ol> 8. Verify that 'Logged in as username' is visible </ol>
<ol> 9. Click 'Logout' button </ol>
<ol> 10. Verify that user is navigated to login page </ol>

---

###  Test Case 5: Register User with existing email
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Signup / Login' button </ol>
<ol> 5. Verify 'New User Signup!' is visible </ol>
<ol> 6. Enter name and already registered email address </ol>
<ol> 7. Click 'Signup' button </ol>
<ol> 8. Verify error 'Email Address already exist!' is visible </ol>

---

###  Test Case 6: Contact Us Form
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Contact Us' button </ol>
<ol> 5. Verify 'GET IN TOUCH' is visible </ol>
<ol> 6. Enter name, email, subject and message </ol>
<ol> 7. Upload file </ol>
<ol> 8. Click 'Submit' button </ol>
<ol> 9. Click OK button </ol>
<ol> 10. Verify success message 'Success! Your details have been submitted successfully.' is visible </ol>
<ol> 11. Click 'Home' button and verify that landed to home page successfully </ol>

---

###  Test Case 7: Verify Test Cases Page
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Test Cases' button </ol>
<ol> 5. Verify user is navigated to test cases page successfully </ol>

---

###  Test Case 8: Verify All Products and product detail page
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Products' button </ol>
<ol> 5. Verify user is navigated to ALL PRODUCTS page successfully </ol>
<ol> 6. The products list is visible </ol>
<ol> 7. Click on 'View Product' of first product </ol>
<ol> 8. User is landed to product detail page </ol>
<ol> 9. Verify that detail detail is visible: product name, category, price, availability, condition, brand </ol>

---

###  Test Case 9: Search Product
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click on 'Products' button </ol>
<ol> 5. Verify user is navigated to ALL PRODUCTS page successfully </ol>
<ol> 6. Enter product name in search input and click search button </ol>
<ol> 7. Verify 'SEARCHED PRODUCTS' is visible </ol>
<ol> 8. Verify all the products related to search are visible </ol>

---

###  Test Case 10: Verify Subscription in home page
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Scroll down to footer </ol>
<ol> 5. Verify text 'SUBSCRIPTION' </ol>
<ol> 6. Enter email address in input and click arrow button </ol>
<ol> 7. Verify success message 'You have been successfully subscribed!' is visible </ol>

---

###  Test Case 11: Verify Subscription in Cart page
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'Cart' button and scroll down to footer </ol>
<ol> 5. Verify text 'SUBSCRIPTION' </ol>
<ol> 6. Enter email address in input and click arrow button </ol>
<ol> 7. Verify success message 'You have been successfully subscribed!' is visible </ol>

---

###  Test Case 12: Add Products in Cart
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'Products' button </ol>
<ol> 5. Hover over first product and click 'Add to cart' </ol>
<ol> 6. Click 'Continue Shopping' button </ol>
<ol> 7. Hover over second product and click 'Add to cart' </ol>
<ol> 8. Click 'View Cart' button </ol>
<ol> 9. Verify both products are added to Cart </ol>
<ol> 10. Verify their prices, quantity and total price </ol>

---

###  Test Case 13: Verify Product quantity in Cart
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'View Product' for any product on home page </ol>
<ol> 5. Verify product detail is opened </ol>
<ol> 6. Increase quantity to 4 </ol>
<ol> 7. Click 'Add to cart' button </ol>
<ol> 8. Click 'View Cart' button </ol>
<ol> 9. Verify that product is displayed in cart page with exact quantity </ol>

---

###  Test Case 14: Place Order: Register while Checkout
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Add products to cart </ol>
<ol> 5. Click 'Cart' button </ol>
<ol> 6. Verify that cart page is displayed </ol>
<ol> 7. Click Proceed To Checkout </ol>
<ol> 8. Click 'Register / Login' button </ol>
<ol> 9. Fill all details in Signup and create account </ol> 
<ol> 10. Verify 'ACCOUNT CREATED!' and click 'Continue' button </ol>
<ol> 11. Verify ' Logged in as username' at top </ol>
<ol> 12. Click 'Cart' button </ol>
<ol> 13. Click 'Proceed To Checkout' button </ol>
<ol> 14. Verify Address Details and Review Your Order </ol>
<ol> 15. Enter description in comment text area and click 'Place Order' </ol>
<ol> 16. Enter payment details: Name on Card, Card Number, CVC, Expiration date </ol>
<ol> 17. Click 'Pay and Confirm Order' button </ol>
<ol> 18. Verify success message 'Congratulations! Your order has been confirmed!' </ol>
<ol> 19. Click 'Delete Account' button </ol> 
<ol> 20. Verify 'ACCOUNT DELETED!' and click 'Continue' button </ol>

---

###  Test Case 15: Place Order: Register before Checkout
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'Signup / Login' button </ol>
<ol> 5. Fill all details in Signup and create account </ol>
<ol> 6. Verify 'ACCOUNT CREATED!' and click 'Continue' button </ol>
<ol> 7. Verify ' Logged in as username' at top </ol>
<ol> 8. Add products to cart </ol>
<ol> 9. Click 'Cart' button </ol>
<ol> 10. Verify that cart page is displayed </ol>
<ol> 11. Click Proceed To Checkout </ol>
<ol> 12. Verify Address Details and Review Your Order </ol>
<ol> 13. Enter description in comment text area and click 'Place Order' </ol>
<ol> 14. Enter payment details: Name on Card, Card Number, CVC, Expiration date </ol>
<ol> 15. Click 'Pay and Confirm Order' button </ol> 
<ol>16. Verify success message 'Congratulations! Your order has been confirmed!' </ol>
<ol> 17. Click 'Delete Account' button </ol>
<ol> 18. Verify that 'ACCOUNT DELETED!' and click 'Continue' button </ol>

---

###  Test Case 16: Place Order: Login before Checkout
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'Signup / Login' button </ol>
<ol> 5. Fill email, password and click 'Login' button </ol>
<ol> 6. Verify 'Logged in as username' at top </ol>
<ol> 7. Add products to cart </ol>
<ol> 8. Click 'Cart' button </ol>
<ol> 9. Verify that cart page is displayed </ol>
<ol> 10. Click Proceed To Checkout </ol>
<ol> 11. Verify Address Details and Review Your Order </ol>
<ol> 12. Enter description in comment text area and click 'Place Order' </ol>
<ol> 13. Enter payment details: Name on Card, Card Number, CVC, Expiration date </ol>
<ol> 14. Click 'Pay and Confirm Order' button </ol>
<ol> 15. Verify success message 'Congratulations! Your order has been confirmed!' </ol>

---

###  Test Case 17: Remove Products From Cart
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Add products to cart </ol>
<ol> 5. Click 'Cart' button </ol>
<ol> 6. Verify that cart page is displayed </ol>
<ol> 7. Click 'X' button corresponding to particular product </ol>
<ol> 8. Verify that product is removed from the cart </ol>

---

###  Test Case 18: View Category Products
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that categories are visible on left side bar </ol>
<ol> 4. Click on 'Women' category </ol>
<ol> 5. Click on any category link under 'Women' category, for example: Dress </ol>
<ol> 6. Verify that category page is displayed and confirm text 'WOMEN - DRESS PRODUCTS' </ol>
<ol> 7. On left side bar, click on any sub-category link of 'Men' category </ol>
<ol> 8. Verify that user is navigated to that category page </ol>

---

###  Test Case 19: View & Cart Brand Products
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Click on 'Products' button </ol>
<ol> 4. Verify that Brands are visible on left side bar </ol>
<ol> 5. Click on any brand name </ol> 
<ol> 6. Verify that user is navigated to brand page and brand products are displayed </ol>
<ol> 7. On left side bar, click on any other brand link </ol>
<ol> 8. Verify that user is navigated to that brand page and can see products </ol>

---

###  Test Case 20: Search Products and Verify Cart After Login
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Click on 'Products' button </ol> 
<ol> 4. Verify user is navigated to ALL PRODUCTS page successfully </ol>
<ol> 5. Enter product name in search input and click search button </ol>
<ol> 6. Verify 'SEARCHED PRODUCTS' is visible </ol>
<ol> 7. Verify all the products related to search are visible </ol>
<ol> 8. Add those products to cart </ol>
<ol> 9. Click 'Cart' button and verify that products are visible in cart </ol>
<ol> 10. Click 'Signup / Login' button and submit login details </ol>
<ol> 11. Again, go to Cart page </ol>
<ol> 12. Verify that those products are visible in cart after login as well </ol>
<ol> 13. Remove all products that have been added </ol>
<ol> 14. Verify 'Cart is empty! Click here to buy products.' is visible </ol>

---

###  Test Case 21: Add review on product
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Click on 'Products' button </ol>
<ol> 4. Verify user is navigated to ALL PRODUCTS page successfully </ol>
<ol> 5. Click on 'View Product' button </ol>
<ol> 6. Verify 'Write Your Review' is visible </ol>
<ol> 7. Enter name, email and review </ol>
<ol> 8. Click 'Submit' button </ol>
<ol> 9. Verify success message 'Thank you for your review.' </ol>

---

###  Test Case 22: Add to cart from Recommended items
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Scroll to bottom of page </ol>
<ol> 4. Verify 'RECOMMENDED ITEMS' are visible </ol>
<ol> 5. Click on 'Add To Cart' on Recommended product </ol>
<ol> 6. Click on 'View Cart' button </ol>
<ol> 7. Verify that product is displayed in cart page </ol>

---

###  Test Case 23: Verify address details in checkout page
<ol> 1. Launch browser </ol>
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfully </ol>
<ol> 4. Click 'Signup / Login' button </ol>
<ol> 5. Fill all details in Signup and create account </ol>
<ol> 6. Verify 'ACCOUNT CREATED!' and click 'Continue' button </ol>
<ol> 7. Verify ' Logged in as username' at top </ol>
<ol> 8. Add products to cart </ol>
<ol> 9. Click 'Cart' button </ol>
<ol> 10. Verify that cart page is displayed </ol>
<ol> 11. Click Proceed To Checkout </ol>
<ol> 12. Verify that the delivery address and the billing address is same address filled at the time registration of account </ol>
<ol> 13. Click 'Delete Account' button </ol>
<ol> 14. Verify 'ACCOUNT DELETED!' and click 'Continue' button </ol>

---

###  Test Case 24: Download Invoice after purchase order
<ol> 1. Launch browser </ol> 
<ol> 2. Navigate to url 'http://automationexercise.com' </ol>
<ol> 3. Verify that home page is visible successfull </ol>
<ol> 4. Add products to cart </ol>
<ol> 5. Click 'Cart' button </ol>
<ol> 6. Verify that cart page is displayed </ol>
<ol> 7. Click Proceed To Checkout </ol>
<ol> 8. Click 'Register / Login' button </ol>
<ol> 9. Fill all details in Signup and create account </ol>
<ol> 10. Verify 'ACCOUNT CREATED!' and click 'Continue' button </ol>
<ol> 11. Verify ' Logged in as username' at top </ol>
<ol> 12. Click 'Cart' button </ol>
<ol> 13. Click 'Proceed To Checkout' button </ol>
<ol> 14. Verify Address Details and Review Your Order </ol>
<ol> 15. Enter description in comment text area and click 'Place Order' </ol>
<ol> 16. Enter payment details: Name on Card, Card Number, CVC, Expiration date </ol>
<ol> 17. Click 'Pay and Confirm Order' button </ol>
<ol> 18. Verify success message 'Congratulations! Your order has been confirmed!' </ol>
<ol> 19. Click 'Download Invoice' button and verify invoice is downloaded successfully </ol>
<ol> 20. Click 'Continue' button </ol>
<ol> 21. Click 'Delete Account' button </ol>
<ol> 22. Verify 'ACCOUNT DELETED!' and click 'Continue' button </ol>

---

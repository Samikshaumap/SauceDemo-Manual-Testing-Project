# Requirements and Application Flow

Project: E-Commerce Web Application – Manual Testing  
Application: SauceDemo  
Website: https://www.saucedemo.com/  
Testing Type: Manual Testing

## 1. Introduction

SauceDemo is a demo e-commerce web application used to practise and understand the manual testing of shopping workflows.

The application allows users to log in, view products, sort products, add products to the shopping cart, and complete the checkout process.

## 2. Project Requirements

The following functional requirements were identified during application exploration.

### 2.1 Login Module

- The user should be able to log in using valid credentials.
- The application should display an error message for invalid credentials.
- The application should display appropriate validation messages when required fields are empty.

### 2.2 Products Module

- The application should display products after successful login.
- Product names and prices should be visible.
- The user should be able to open a product details page.

### 2.3 Sorting Module

- The user should be able to sort products by name (A to Z).
- The user should be able to sort products by name (Z to A).
- The user should be able to sort products by price (low to high).
- The user should be able to sort products by price (high to low).

### 2.4 Shopping Cart Module

- The user should be able to add products to the cart.
- The user should be able to remove products from the cart.
- The cart should display the selected product details.
- The cart badge should update according to cart changes.
- The user should be able to add multiple products.
- The user should be able to continue shopping from the cart.

### 2.5 Checkout Module

- The user should be able to navigate to the checkout information page.
- The user should be able to enter checkout information.
- The application should validate required information.
- The order overview should display the selected product details.
- The user should be able to finish the order.
- The application should display an order confirmation message.
- The user should be able to cancel the checkout process.
- The user should be able to navigate back to the products page after order completion.

### 2.6 Logout Module

- The user should be able to log out of the application.
- After logout, the user should return to the login page.

## 3. Application Flow

The main application workflow is:

1. Open the SauceDemo website.
2. Enter username and password.
3. Click the Login button.
4. Navigate to the Products page.
5. View the available products.
6. Sort products using the available sorting options.
7. Open product details if required.
8. Add one or more products to the shopping cart.
9. Open the shopping cart.
10. Verify product details and prices.
11. Remove products or continue shopping if required.
12. Click Checkout.
13. Enter checkout information.
14. Continue to the order overview.
15. Verify the order details.
16. Click Finish to complete the order.
17. Verify the order confirmation.
18. Click Back Home to return to the Products page.
19. Log out of the application.

## 4. Test Data

The following demo credentials are used for testing:

| Field       |  Test Data    | 
|-------------|---------------|
| Username    |  standard_user|
| Password    |  secret_sauce |
| First Name  |  Sam          |
| Last Name   |  Mas          |
| Postal Code |  444809       |

Note: These are demo test credentials and sample checkout details.

## 5. Testing Scope

The following modules are included in this project:

- Login
- Products
- Sorting
- Shopping Cart
- Checkout
- Logout

Testing is performed manually using the SauceDemo demo application.

## 6. Conclusion

Requirement identification and application flow analysis help understand the application's functionality before preparing test scenarios and detailed test cases.

These requirements are used as the basis for manual testing of the SauceDemo application.
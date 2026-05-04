#Project Overview

This project is a complete End-to-End Automation Testing Framework built for the demo e-commerce application Swag Labs (SauceDemo).

It automates real-world user journeys like login, product selection, cart management, and checkout flow—designed to reflect how QA engineers build scalable frameworks in real companies.

Objective:
To design a robust, scalable, and maintainable automation framework that validates critical business flows of an e-commerce platform.

Key Features:
🔹 End-to-End test scenarios (Login → Inventory → Cart → Checkout → Logout)
🔹 Page Object Model (POM) architecture
🔹 Reusable components & utility classes
🔹 Data-driven testing using TestNG
🔹 Screenshot capture on failure
🔹 Advanced reporting (Extent Reports)
🔹 Cross-browser testing support
🔹 CI/CD ready framework
Tech Stack:
Language: Java
Automation Tool: Selenium WebDriver
Test Framework: TestNG
Build Tool: Maven
Design Pattern: Page Object Model (POM)
Reporting: Extent Reports
Version Control: Git & GitHub
Project Structure:
swaglabs-automation/
│── src/
│   ├── main/java/
│   │   ├── base/              # WebDriver setup & BaseTest
│   │   ├── pages/             # LoginPage, InventoryPage, CartPage, CheckoutPage
│   │   ├── utils/             # ConfigReader, ScreenshotUtil, WaitUtils
│   │
│   ├── test/java/
│   │   ├── tests/             # Test classes
│   │   │   ├── LoginTest.java
│   │   │   ├── ProductTest.java
│   │   │   ├── CartTest.java
│   │   │   ├── CheckoutTest.java
│   │
│── resources/
│   ├── config.properties
│   ├── testng.xml
│
│── reports/                   # Extent Reports
│── screenshots/               # Failure screenshots
│── pom.xml
│── README.md
Test Scenarios Covered:
Authentication
Valid login
Invalid login
Locked-out user validation
Product Module
View product list
Sort products (Price/Name)
Add product to cart
Cart Module
Verify added items
Remove items from cart
Checkout Flow
Enter user details
Complete checkout
Validate order confirmation
Logout
Successful logout functionality


Chrome browser


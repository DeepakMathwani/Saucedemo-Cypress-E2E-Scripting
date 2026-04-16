# 🧪 Cypress E2E Testing – SauceDemo Project

## 📌 Project Overview

This project contains **End-to-End (E2E) test automation** for the website **SauceDemo** using **Cypress**.

The test suite validates:

* Login functionality (valid & invalid scenarios)
* Product selection & cart operations
* Sorting functionality
* UI elements validation
* Navigation & logout flow

---

## 🌐 Application Under Test

* URL: https://www.saucedemo.com/
* Application Name: Swag Labs

---

## 🚀 Tech Stack

* Cypress (JavaScript)
* Node.js
* Mocha (Test Framework - built into Cypress)
* Chai (Assertions)

---

## 📂 Project Structure

```
cypress/
│── e2e/
│   └── test.cy.js
│
│── fixtures/
│── support/
│
cypress.config.js
package.json
README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Open Cypress UI

```bash
npx cypress open
```

### 3️⃣ Run Tests in Headless Mode

```bash
npx cypress run
```

---

## 🧪 Test Scenarios Covered

### ✅ 1. URL & Title Validation

* Verify correct URL
* Verify page title

### ❌ 2. Invalid Login Test

* Enter wrong password
* Validate login failure scenario

### 🔒 3. Locked User Login

* Test login with locked user
* Verify system behavior

### 🛒 4. Complete E2E Flow

* Login with valid credentials
* Add multiple products to cart
* Remove item from cart
* Perform sorting (A-Z, Z-A, Price)
* Validate social media links
* Scroll behavior testing
* Logout functionality

---

## 🔍 Key Cypress Concepts Used

* `cy.visit()` – Navigate to URL
* `cy.get()` – Locate elements
* `cy.should()` – Assertions
* `cy.contains()` – Text validation
* `cy.scrollTo()` – Scroll testing
* `cy.wait()` – Static wait (used for demo)
* `beforeEach()` – Setup before each test
* Aliases using `.as()`

---

## ⚠️ Known Improvements (Future Enhancements)

* Replace `cy.wait()` with dynamic waits
* Use Page Object Model (POM)
* Add custom commands
* Parameterize test data
* Add API testing integration
* Add CI/CD pipeline (GitHub Actions / Jenkins)

---

## 👨‍💻 Author

* Deepak Mathwani

---

## 📌 Notes

This project is created for learning and practicing Cypress automation in a real-world E2E scenario.   

# qa-web-testing-saucedemo
# QA Web Testing Project – SauceDemo

## Project Overview

This project demonstrates manual testing of the SauceDemo web application.
It includes test case design, execution, defect reporting, and enhancement suggestions based on real test results.

The goal of this project is to simulate a real QA workflow, including functional testing, negative testing, and exploratory testing.

---

## Application Under Test

* Application: SauceDemo
* URL: https://www.saucedemo.com/
* Type: Web Application (E-commerce Demo)

---

## Scope of Testing

### Included

* Login functionality
* Product listing and sorting
* Product details page
* Shopping cart functionality
* Checkout process

### Excluded

* Performance testing
* Security testing
* Backend/API validation

---

## Tools Used

* Microsoft Excel Online (Test Cases & Reports)
* GitHub (Version Control & Documentation)
* Mozilla Firefox (Test Browser)
* Screenshot tool (Evidence capture)

---

## Test Design

A total of **30 test cases** were created covering:

* Positive scenarios
* Negative scenarios
* Validation checks
* Navigation flows
* Functional testing

---

## Test Execution Summary

| Metric           | Value |
| ---------------- | ----- |
| Total Test Cases | 30    |
| Passed           | 29    |
| Failed           | 1     |
| Blocked          | 0     |

---

##  Defect Report

### BUG-001 – Zip Code Field Validation Issue

* **Module:** Checkout
* **Severity:** Medium
* **Priority:** Medium

### Description

The Zip Code field accepts alphabetic characters instead of restricting input to numeric values.

### Steps to Reproduce

1. Add a product to the cart
2. Proceed to checkout
3. Enter valid First Name and Last Name
4. Enter alphabetic characters in the Zip Code field
5. Continue the checkout process

### Expected Result

The system should validate the Zip Code field and only allow numeric values.

### Actual Result

The system accepts alphabetic characters and allows the user to proceed.

---

##  Enhancement Requests

During testing, several improvement opportunities were identified:

* Restrict checkout process when cart is empty
* Add validation for First Name field (no numeric values)
* Add validation for Last Name field (no numeric values)
* Improve Zip Code field validation rules

These are considered **enhancements**, not critical defects.

---

##  Evidence

Screenshots were captured for key test scenarios such as:

* Successful login
* Failed login attempts
* Product added to cart
* Checkout process
* Order completion

---

##  Key Learnings

* Understanding of QA test lifecycle (Test Planning → Execution → Reporting)
* Difference between bugs and enhancements
* Importance of clear expected results
* How to document defects professionally
* How to structure a QA project in GitHub

---

##  Conclusion

This project demonstrates practical manual testing skills applied to a real-world-like web application, including test design, execution, defect reporting, and documentation.

It serves as part of a QA Junior portfolio focused on manual testing fundamentals.

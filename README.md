# QA Manual Testing Project – SauceDemo

##  Overview

This project demonstrates manual QA testing applied to the SauceDemo web application.
It simulates a real-world QA workflow including test design, execution, defect reporting, and enhancement identification.

The goal is to validate core e-commerce functionalities and document results in a structured and professional way.

---

##  Application Under Test

* **Application:** SauceDemo
* **URL:** https://www.saucedemo.com/
* **Type:** Web-based e-commerce demo application

---

##  Scope of Testing

### Covered Areas

* Login functionality
* Product listing and sorting
* Product details page
* Shopping cart operations
* Checkout process

### Testing Types

* Functional Testing
* Negative Testing
* Validation Testing
* Exploratory Testing
* End-to-End Testing

---

##  Test Summary

* **Total Test Cases:** 30
* **Passed:** 29
* **Failed (Defects):** 1
* **Blocked:** 0

---

##  Defect Summary

### BUG-001 – Zip Code Field Validation

**Issue:**
The Zip Code field accepts alphabetic characters instead of restricting input to numeric values.

**Severity:** Medium
**Priority:** Medium

**Status:** Confirmed defect during execution

---

##  Key Enhancements Identified

The following improvements were suggested based on testing results:

* Add validation for Zip Code field (numeric only)
* Add validation for First Name and Last Name fields
* Restrict checkout process when cart is empty

These are classified as **enhancement requests**, not functional defects.

---

##  Evidence

Screenshots were captured to support key test scenarios:

* Successful and failed login attempts
* Product interactions (add/remove cart)
* Checkout flow
* Order confirmation

---

##  QA Approach

Testing was performed using a manual black-box approach focusing on:

* User workflows
* Input validation
* Functional correctness
* Edge cases and negative scenarios

---

## 🚀 Conclusion

This project demonstrates practical QA skills including test case design, execution, defect reporting, and structured documentation aligned with real QA workflows.

It is part of a QA portfolio focused on manual testing fundamentals and software quality validation.

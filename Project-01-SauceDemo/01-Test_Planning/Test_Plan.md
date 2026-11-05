# Test Plan – SauceDemo Web Application

## 1. Project Overview

| Item | Details |
|---|---|
| Project Name | SauceDemo Web Application Testing |
| Application | SauceDemo |
| Application URL | [https://www.saucedemo.com/](https://www.saucedemo.com/) |
| Testing Type | Manual Testing |
| Testing Level | UI and Functional Testing |
| Testing Approach | Black-box Testing |
| Project Type | Personal QA Portfolio Project |
| Prepared By | Syaikhoh Numaa |
| Status | In Progress |

## 2. Test Objectives

The objective of this project is to evaluate the functionality and reliability of the SauceDemo web application through manual testing.

The testing aims to:

- Verify that the application's core functionalities work as expected.
- Validate user interactions and input handling.
- Identify defects and unexpected application behavior.
- Verify data consistency across different application modules.
- Document test results and report identified defects.

## 3. Scope of Testing

### 3.1 In Scope

The testing will cover the following application modules:

#### Module 1 – Login

- Login with valid credentials.
- Login with invalid credentials.
- Login with empty or incomplete fields.
- Locked-out user validation.
- Login error messages and behavior.
- Logout functionality.

#### Module 2 – Products

- Product listing and display.
- Product details.
- Product sorting.
- Product information validation.

#### Module 3 – Shopping Cart

- Add products to cart.
- Remove products from cart.
- Cart item display.
- Cart information consistency.
- Reset App State functionality, where applicable.

#### Module 4 – Checkout

- Checkout information form.
- Required field validation.
- Order overview.
- Price calculation.
- Order completion.

### 3.2 Out of Scope

The following activities are excluded from this project:

- Backend API testing.
- Database testing.
- Performance and load testing.
- Security penetration testing.
- Payment gateway integration testing.
- Cross-browser compatibility testing beyond the selected test environment.
- Mobile application testing.

## 4. Test Approach

Testing will be conducted manually using predefined test scenarios and test cases.

The following testing techniques will be applied:

- **Functional Testing:** Verify that application features perform their intended functions.
- **Positive Testing:** Verify application behavior with valid inputs and expected user actions.
- **Negative Testing:** Verify how the application handles invalid inputs and unexpected user actions.
- **Boundary Value Analysis:** Test relevant input field boundaries.
- **Equivalence Partitioning:** Group input data into valid and invalid categories.
- **UI Testing:** Verify interface elements, labels, buttons, and displayed information.
- **Integration-oriented Functional Testing:** Verify that data and behavior remain consistent when moving between related modules.

Test execution results will be recorded, and identified defects will be documented in separate bug reports.

## 5. Test Environment

| Component | Details |
|---|---|
| Application | SauceDemo |
| URL | https://www.saucedemo.com/ |
| Operating System | macOS Sonoma 14.4 |
| Browser | Google Chrome |
| Browser Version | 153.0.8010.53 |
| Testing Type | Manual Testing |
| Test Environment | Web Browser |

## 6. Test Data

SauceDemo provides predefined demo credentials for testing different user scenarios.

### 6.1 Accepted Usernames

| Username | Testing Purpose |
|---|---|
| `standard_user` | Standard user flow |
| `locked_out_user` | Locked-out account validation |
| `problem_user` | Application behavior testing |
| `performance_glitch_user` | Application behavior with potential performance delays |
| `error_user` | Application behavior testing |
| `visual_user` | UI and visual behavior testing |

### 6.2 Password

| Password | Applicable Users |
|---|---|
| `secret_sauce` | All accepted usernames listed above |

### 6.3 Additional Test Data

| Test Data | Testing Purpose |
|---|---|
| Invalid username | Negative login testing |
| Invalid password | Negative login testing |
| Empty username | Required field validation |
| Empty password | Required field validation |
| Valid checkout information | Checkout form testing |
| Invalid or incomplete checkout information | Checkout validation testing |

**Note:** The predefined credentials are provided by SauceDemo for demonstration and testing purposes. Additional invalid or incomplete test data will be created as needed for each test scenario.

## 7. Entry Criteria

Testing can begin when:

- The SauceDemo application is accessible.
- The test environment and browser are ready.
- Test scenarios have been identified.
- Test cases have been prepared and reviewed.
- Required test data is available.

## 8. Exit Criteria

Testing can be considered complete when:

- All planned test cases have been executed or their execution status has been documented.
- Actual results have been recorded.
- Identified defects have been documented.
- Critical or high-severity defects have been reviewed.
- Unexecuted and blocked test cases have been explained.
- The Test Summary Report has been prepared.

## 9. Test Deliverables

The following deliverables will be prepared:

1. Test Plan
2. Test Scenarios
3. Test Cases
4. Test Execution Report
5. Bug Reports
6. Test Summary Report
7. Screenshots and Test Evidence

## 10. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Application becomes unavailable | Resume testing when the application is accessible. |
| Test data produces unexpected results | Verify test credentials and input data before execution. |
| Application behavior differs between user types | Record the user type and observed behavior during execution. |
| Test coverage is incomplete | Review test scenarios against the defined scope. |
| Defects cannot be reproduced | Record detailed steps, test data, and screenshots. |

## 11. Test Schedule

| Activity | Planned Status |
|---|---|
| Test Planning | Completed |
| Test Scenario Preparation | Not Started |
| Test Case Preparation | Not Started |
| Test Execution | Not Started |
| Bug Reporting | Not Started |
| Test Summary | Not Started |

## 12. Approval and Review

| Role | Name | Status |
|---|---|---|
| Prepared By | Syaikhoh Numaa | Self-review |
| Reviewed By | N/A | Personal Portfolio Project |

---

**Project Note:** This is an independent Manual QA portfolio project using the publicly available SauceDemo demo application. Test scenarios and test cases are prepared for learning and demonstration purposes. Actual test results and defects will only be reported after execution.

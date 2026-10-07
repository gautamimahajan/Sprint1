ParaBank Manual Testing Project

Project Overview

This project demonstrates manual software testing of the ParaBank web application.
The objective is to verify that the major banking functionalities work correctly, meet the expected requirements, and provide a reliable user experience.

The project follows a structured manual testing process from test planning through test execution, defect reporting, and test summary.

Application Under Test

Application: ParaBank
Testing Type: Manual Testing
Domain: Online Banking
Testing Approach: Functional / Black-Box Testing

ParaBank is an online banking application that provides features such as user registration, login, account management, fund transfers, bill payment, and transaction-related operations.

Testing Process

The project follows this testing flow:

Test Plan → Test Scenarios → Test Cases → Test Data → Test Execution → Defect Report → Test Summary

1. Test Plan

Defines the testing objectives, scope, resources, assumptions, risks, and overall testing approach.

2. Test Scenarios

Identifies the major functionalities that need to be tested.

Examples:

User registration

User login

Account overview

Open new account

Transfer funds

Bill payment

Account activity

Logout

3. Test Cases

Detailed test cases are prepared with information such as:

Test Case ID

Test Scenario

Preconditions

Test Steps

Test Data

Expected Result

Actual Result

Status

Both positive and negative test cases are considered.

4. Test Data

Test data is prepared to validate different application conditions, including valid and invalid inputs.

5. Test Execution

The test cases are executed against the ParaBank application and the actual results are compared with the expected results.

Possible execution status:

Pass – Actual result matches expected result.

Fail – Actual result does not match expected result.

Blocked – Test cannot be executed because of a dependency or issue.

6. Defect Report

Any failed test case is analyzed and reported as a defect with relevant details such as:

Defect ID

Summary

Steps to Reproduce

Expected Result

Actual Result

Severity

Priority

Status

7. Test Summary

The final summary provides an overview of executed test cases, passed/failed cases, defects identified, and the overall testing result.

Scope of Testing

In Scope

Registration

Login and logout

Account overview

Account creation

Fund transfer

Bill payment

Account activity / transactions

Form validation

Error messages

Basic navigation

Positive and negative functional testing

Out of Scope

Performance testing

Security penetration testing

Load and stress testing

Compatibility testing across all browsers/devices

Automation testing

Production database validation

Testing Types

Functional Testing

Smoke Testing

Sanity Testing

Regression Testing

Retesting

Positive Testing

Negative Testing

UI Validation

Validation of error messages

Tools & Technologies

Application: ParaBank

Documentation: Microsoft Excel

Testing: Manual Testing

Defect Tracking: Excel-based defect report

Browser: Web browser such as Google Chrome

Deliverables

This project contains the following testing documents:

Test Plan

Test Scenarios

Test Cases

Test Data

Test Execution

Defect Report

Test Summary

Project Structure

ParaBank-Manual-Testing/
│
├── Parabank Manual Testing.xlsx
└── README.md

Objective

The main objective of this project is to gain practical experience in the Software Testing Life Cycle (STLC) by designing and executing manual test cases for an online banking application and documenting the results systematically.

Expected Outcome

The testing process helps identify functional issues, validate application requirements, ensure important banking workflows work as expected, and improve the overall quality and reliability of the application.

Conclusion

The ParaBank Manual Testing project demonstrates a complete manual testing workflow, starting from test planning and scenario identification and continuing through test case design, execution, defect reporting, and test closure.

This project can be used as a manual testing portfolio/academic project to demonstrate practical knowledge of software testing concepts and documentation.

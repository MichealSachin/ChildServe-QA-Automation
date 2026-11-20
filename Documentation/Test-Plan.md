
# ChildServe – Test Plan

## 1. Document Information

| Field | Details |
|---|---|
| Project Name | ChildServe QA Automation Portfolio |
| Application Under Test | OpenEMR Demo |
| Document Name | Test Plan |
| Version | 1.0 |
| Status | In Progress |
| Prepared By | QA Engineer |

## 2. Purpose

The purpose of this Test Plan is to define the testing activities, scope, approach, resources, schedule, risks and deliverables for the project.

## 3. Testing Scope

### 3.1 In Scope

- Login and Logout Testing
- Patient Search Testing
- Patient Registration Testing (if available)
- Form Field Validation
- Positive and Negative Testing
- UI Automation Testing
- API Testing (for confirmed endpoints)
- SQL Practice and Data Validation
- Regression Testing
- Cross-Browser Testing

### 3.2 Out of Scope

- Production environment testing
- Real patient data testing
- Destructive testing on shared demo records
- Actual payment or insurance transactions
- Unavailable application features

## 4. Test Approach

Testing will be performed using a combination of manual and automated testing.

### Manual Testing

- Requirement analysis
- Test scenario preparation
- Test case design
- Test execution
- Defect reporting
- Retesting and regression testing

### Automation Testing

- Playwright with TypeScript
- Page Object Model
- Reusable functions
- Fixtures and hooks
- Data-driven testing
- Cross-browser execution
- HTML reporting

## 5. Test Environment

| Component | Configuration |
|---|---|
| Operating System | Windows 11 |
| IDE | Visual Studio Code |
| Runtime | Node.js |
| Language | TypeScript |
| Automation | Playwright |
| Version Control | Git and GitHub |
| Browsers | Chromium, Firefox, WebKit |
| Application | OpenEMR Demo |

## 6. Test Types

- Functional Testing
- Smoke Testing
- Sanity Testing
- Regression Testing
- Retesting
- Positive Testing
- Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- API Testing
- Database Testing
- Cross-Browser Testing
- Basic Security Testing

## 7. Test Deliverables

- Test Scenarios
- Test Cases
- Requirement Traceability Matrix
- Test Execution Results
- Defect Reports
- Automation Scripts
- API Test Scripts
- SQL Validation Queries
- HTML Test Reports
- Final Test Summary Report

## 8. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Engineer | Requirement analysis and test design |
| QA Engineer | Manual test execution |
| QA Engineer | Automation development |
| QA Engineer | Defect reporting and retesting |
| QA Engineer | Test reporting and documentation |

Note: This is a single-person training portfolio project. The roles above represent project responsibilities, not a claim of an actual project team.

## 9. Test Schedule

| Phase | Planned Activity |
|---|---|
| Day 1 | Project scope, strategy and test plan |
| Day 2 | Test scenarios, test cases and RTM |
| Day 3 | JavaScript, TypeScript and Playwright |
| Day 4 | Locators, assertions and debugging |
| Day 5 | POM and framework development |
| Day 6 | UI automation and regression |
| Day 7 | API testing |
| Day 8 | SQL and database testing |
| Day 9 | GitHub and CI/CD |
| Day 10 | Final execution and reporting |

## 10. Entry Criteria

- Application is accessible.
- Testing scope is defined.
- Test environment is available.
- Test cases are prepared.
- Required tools are installed.

## 11. Exit Criteria

- Planned test cases are executed.
- Results are documented.
- Critical defects are reported.
- Automation tests are executed.
- Final test report is prepared.

## 12. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Demo application unavailable | Retry after checking connectivity |
| Shared test data changes | Use synthetic test data |
| Automation failures | Debug using traces and screenshots |
| Browser incompatibility | Verify browser support |
| Limited project time | Prioritize critical workflows |

## 13. Defect Management

Defects will be recorded with:

- Defect ID
- Summary
- Description
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Environment
- Evidence
- Status

## 14. Test Reporting

Test execution reports will include:

- Total Test Cases
- Passed Test Cases
- Failed Test Cases
- Blocked Test Cases
- Not Executed Test Cases
- Defect Summary
- Automation Execution Results

## 15. Approval and Status

Project: ChildServe QA Automation Portfolio

Document: Test Plan

Version: 1.0

Status: In Progress

This document is prepared for independent QA training and portfolio demonstration.


# ChildServe – Test Strategy

## 1. Introduction

This document defines the overall testing approach for the ChildServe QA Automation Portfolio Project.

The OpenEMR demo application is used as the Application Under Test (AUT).

## 2. Testing Objectives

- Verify application functionality against defined requirements.
- Identify defects early.
- Validate positive and negative scenarios.
- Improve test coverage through automation.
- Ensure application stability through regression testing.
- Validate API responses and data integrity where supported.

## 3. Testing Levels

### 3.1 Unit Testing
Validate individual components independently where source code or suitable test interfaces are available.

### 3.2 Integration Testing
Verify interactions between application components and services where test access is available.

### 3.3 System Testing
Validate complete application workflows.

### 3.4 User Acceptance Testing
Validate whether application workflows meet defined user expectations.

## 4. Testing Types

- Functional Testing
- Smoke Testing
- Sanity Testing
- Regression Testing
- Retesting
- Positive Testing
- Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Cross-Browser Testing
- API Testing
- Database Testing
- Basic Security and Role-Based Access Testing

## 5. Automation Strategy

Automation Tool: Playwright

Programming Language: TypeScript

Framework Design: Page Object Model (POM)

Planned Framework Components:
- Page Objects
- Test Specifications
- Fixtures
- Hooks
- Reusable Utilities
- Test Data
- Environment Configuration

Automation Coverage:
- Login workflows
- Patient search
- Supported patient management workflows
- Form validations
- Negative scenarios
- Regression scenarios

Only verified and repeatable application workflows will be automated.

## 6. API Testing Strategy

- Validate HTTP status codes.
- Validate response bodies.
- Verify response headers.
- Test positive and negative scenarios.
- Validate required fields and response data types.

API endpoints will be selected only after confirming their availability and authorization.

## 7. Database Testing Strategy

- Practice SQL SELECT queries.
- Validate data using WHERE conditions.
- Perform INNER JOIN and LEFT JOIN.
- Practice aggregate functions.
- Validate data consistency using synthetic datasets.

Direct access to the OpenEMR demo database is not assumed.

## 8. Cross-Browser Testing

Planned browsers:
- Chromium
- Firefox
- WebKit

Browser execution will depend on application and environment compatibility.

## 9. Defect Management

Each confirmed defect will include:
- Defect ID
- Summary
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Evidence
- Status

No issue will be reported as a confirmed defect without sufficient evidence and an applicable requirement or expected behavior.

## 10. Test Execution and Reporting

- Execute manual test cases.
- Execute automated test scripts.
- Record Pass, Fail and Blocked results.
- Capture screenshots and traces for failures.
- Generate Playwright HTML reports.
- Track defects and retest fixes.

## 11. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Demo data changes | Use controlled synthetic data |
| Network issues | Retry after confirming connectivity |
| Browser compatibility | Execute cross-browser tests |
| Unstable test scripts | Use reliable locators and assertions |
| Shared demo environment | Avoid destructive operations |

## 12. Tools and Technologies

- Playwright
- TypeScript
- Node.js
- Visual Studio Code
- Git
- GitHub
- Postman
- SQL
- GitHub Actions / Jenkins

## 13. Test Completion Criteria

- Planned test cases are executed.
- Results are documented.
- Critical issues are reported.
- Automation execution is reviewed.
- Test reports are prepared.

## 14. Document Information

Project: ChildServe QA Automation Portfolio

Document: Test Strategy

Version: 1.0

Status: In Progress

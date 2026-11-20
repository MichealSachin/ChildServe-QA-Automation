
# Defect Report

## Defect ID
BUG_PAT_001

## Defect Title
Application accepts age above the maximum allowed limit.

## Module
Patient Registration

## Test Case ID
TC_PAT_AGE_001

## Preconditions
Patient Registration page is accessible.

## Test Steps
1. Open Patient Registration page.
2. Enter patient name.
3. Enter age as 135.
4. Click Save.

## Test Data
Age: 135

## Expected Result
Application should reject the age and display an appropriate validation message.

## Actual Result
Sample observation: Application accepts the age and adds the patient.

## Severity
High

## Priority
High

## Status
New

## Environment
Training example – Not verified in OpenEMR demo.

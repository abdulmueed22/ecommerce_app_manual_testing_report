# E-Commerce App — Manual Testing Report

A structured manual software testing report for the Flutter-based e-commerce application in this repository. The report is designed to support test planning, test execution, and requirement coverage tracking.

## Project Overview

This workbook documents important application features and maps requirements to test scenarios and individual test cases. It covers customer-facing workflows as well as key admin and payment flows.

## Scope of Testing

The report focuses on four high-priority feature areas:

1. **Authentication and Profile Access** — registration, login validation, and logout/session behavior.
2. **Product Discovery** — product listings, product details, category browsing, and search.
3. **Admin Product Management** — admin access, product upload, image validation, and product visibility.
4. **Checkout, Payment, and Order Tracking** — Stripe test payments, order creation, admin order management, and order-status updates.

## Workbook Contents

The Excel workbook contains five sheets:

| Sheet | Description |
|---|---|
| **Read Me** | Report purpose, scope, assumptions, and execution guidance |
| **Feature Inventory** | Important application features and selected testing scope |
| **Test Scenarios** | Scenario IDs, descriptions, priorities, and test-case counts |
| **Test Cases** | Detailed test cases with prerequisites, steps, test data, expected results, and actual-result fields |
| **RTM** | Requirement Traceability Matrix mapping requirements to scenarios and test cases |

## Test Case Details

Each test case includes:

- Test Case ID
- Test Scenario ID
- Test Case Name and Title
- Prerequisites
- Test Steps / Actions
- Test Data
- Expected Result
- Actual Result / Execution Status

## Traceability

Requirement IDs (`REQ-*`), scenario IDs (`TS-*`), and test case IDs (`TC-*`) are used consistently across the workbook to make coverage easier to review and maintain.

## Execution Notes

- Test cases are initially marked **Not Executed**. Update the actual result only after running the test.
- Use a dedicated test/staging environment and **Stripe test mode** for payment scenarios.
- Do not use real customer information or live payment credentials.
- Confirm field requirements, role permissions, order statuses, and expected behavior against the current application build before execution.
- Record failures and link them to defect IDs or supporting screenshots as appropriate.

## Deliverable

The main deliverable is the Excel workbook:

`ecommerce_app_manual_testing_report.xlsx`

It can be used as a baseline for manual QA execution, test evidence collection, and requirement coverage reviews.

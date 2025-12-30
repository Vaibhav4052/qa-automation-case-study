Name: Vaibhav Bhaskar More
Role Applied: QA Automation Engineer

📌 Overview

This repository contains my submission for the QA Automation Engineering Case Study focused on testing a multi-tenant B2B SaaS platform (WorkFlow Pro).

The goal of this assignment was not only to write test cases, but to demonstrate real-world testing thinking, including:

Debugging flaky automation tests

Designing a scalable automation framework

Validating end-to-end flows across API, Web, and Mobile layers

🧪 Tools & Technologies

Python

Pytest

Playwright

REST API testing

BrowserStack (conceptual integration)

CI/CD-aware test design

📂 Submission Contents
Part 1: Debugging Flaky Tests

Identified root causes of flaky Playwright tests

Explained why issues occur more frequently in CI/CD

Refactored test code using proper waits and stable assertions

Focused on reliability rather than hard-coded assumptions

Part 2: Test Automation Framework Design

Proposed a maintainable and scalable framework structure

Covered:

Web and Mobile testing

Multi-tenant support

Role-based testing

API + UI separation

Highlighted missing requirements and clarifying questions that should be asked in real projects

Part 3: API + UI Integration Testing

Designed an end-to-end flow:

Project creation via API

Verification in Web UI

Mobile accessibility validation

Tenant isolation and security checks

Emphasized API-driven test data creation for speed and stability

🧠 Testing Philosophy

My approach focuses on:

Stability over speed

API-first testing where possible

Clear failures instead of flaky passes

CI/CD readiness

Realistic assumptions and constraints

Rather than assuming ideal conditions, the tests are designed to handle real production behavior such as dynamic loading, network delays, and tenant-specific variations.

⚠️ Assumptions

Authentication tokens are managed via environment variables

Test users exist for each tenant

BrowserStack credentials are configured externally

Test data cleanup is handled after execution

📄 Document

The complete case study response is provided in the PDF file included in this repository.

✅ Final Note

This submission reflects how I would approach automation testing in a real production SaaS environment, balancing technical correctness, maintainability, and business impact.

Thank you for reviewing my submission.

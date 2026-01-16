## Overview

This repository demonstrating my experience as a Quality Engineer / SDET working with Playwright and TypeScript.The focus of this project is to show how I design, write, and maintain realistic, reliable UI automation that fits into a modern development workflow not just isolated test scripts.

---

## Problem This Project Addresses

In real projects, UI automation often:

* Becomes flaky and unreliable
* Lacks structure and scalability
* Provides little value in CI/CD
* Is hard to debug when tests fail

### This project solves those issues by:

* Using Playwright’s auto-waiting and tracing
* Applying Page Object Model (POM) for maintainability
* Automating critical user workflows
* Making tests CI-ready and debuggable
* Producing clear execution reports

## Tech Stack

* Playwright – UI automation (fast, stable, cross-browser)
* TypeScript – Type safety and scalable test design
* Node.js / npm – Dependency management
* GitHub Actions – CI execution
* Playwright HTML Reports – Test visibility and debugging

##  What Is Automated

This project automates business-critical UI scenarios, such as:

* User login and authentication flows
* Form submission and validation
* Navigation and page state verification
* Positive and negative test cases
* Cross-browser testing (Chromium / Firefox / WebKit)

Tests are:

* Independent and repeatable
* Written with meaningful assertions
* Free of hard waits
* Designed to run reliably in CI

---

## 📁 Project Structure

```
QA-Profile/
├── README.md     # About the project and how it’s organized (this file)
├── docs/         # test strategy showing planning and QA approach
├── data/         # Reusable test data
├── pages/        # Page Object Models
├── tests/
│   ├── ui/             # UI test case scripts
│   ├── api/            # API automation test scripts
│   └── integration/    # Integration test scenarios
├── reports/          # HTML reports
├── utils/
│   ├── randomDataGenerator.ts     # generate random test data
│   ├── dataProvider.ts          # Login authentication helpers
├── playwright.config.ts
├── playwright.yml # CI pipeline
├── package.json
└── README.md
```
---

##  Running the Tests

### Run Locally

```bash
npm install
npx playwright install
npx playwright test
```

### View HTML Report

```bash
npx playwright show-report
```

### CI Execution

* Tests run automatically via **GitHub Actions**
* Triggered on push / pull requests
* Results available in the **Actions** tab

---

##  Example Output

After execution, Playwright provides:

* Pass / fail summary
* Screenshots and traces for failures
* Execution time per test
* Detailed HTML report


##  QA Practices Followed

* Page Object Model (POM)
* Stable locator strategies
* Clear assertions and test naming
* No hard-coded waits
* CI-friendly test design
* Focus on maintainability and reliability

##  About Me
**Ayesha – Quality Engineer / SDET**

* 5+ years Manual Testing experience
* 1+ year Automation experience
* Hands-on with Playwright + TypeScript
* Strong focus on test reliability and CI integration

---

##  Future Improvements

* Expand coverage for edge cases
* Add API automation alongside UI tests
* Improve reporting and metrics
* Optimize parallel execution



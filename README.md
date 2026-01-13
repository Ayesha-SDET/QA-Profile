# SDET / QA Portfolio Repository

## Overview

This repository is a practical QA Automation portfolio demonstrating my experience as Quality Engineer / SDET working with Playwright and TypeScript.
The focus of this project is to show how I design, write, and maintain realistic, reliable UI automation that fits into a modern development workflow not just isolated test scripts.

**Problem This Project Addresses**
In real projects, UI automation often:
Becomes flaky and unreliable
Lacks structure and scalability
Provides little value in CI/CD
Is hard to debug when tests fail

**This project solves those issues by:**
Using Playwright’s auto-waiting and tracing
Applying Page Object Model (POM) for maintainability
Automating critical user workflows
Making tests CI-ready and debuggable
Producing clear execution reports

**⚙️ Tech Stack**

Playwright – UI automation (fast, stable, cross-browser)
TypeScript – Type safety and scalable test design
Node.js / npm – Dependency management
GitHub Actions – CI execution
Playwright HTML Reports – Test visibility and debugging

**🧪 What Is Automated**

This project automates business-critical UI scenarios, such as:
User login and authentication flows
Form submission and validation
Navigation and page state verification
Positive and negative test cases
Cross-browser testing (Chromium / Firefox / WebKit)

**Tests are:**
Independent and repeatable
Written with meaningful assertions
Free of hard waits
Designed to run reliably in CI

---

## Repository Structure

```
├── README.md                   # Recruiter-optimized overview, executive summary, and instructions
├── Test_Strategy.pdf           # Full Test Strategy document
├── CI_CD_Workflow.md           # Sample CI/CD integration workflow
├── Automation_Pyramid.png      # Visual representation of automation focus
├── sample_test_cases/          # Example test cases
├── badges/                     # Optional: Status, coverage, or CI/CD badges
└── docs/                       # Optional: Additional diagrams, screenshots, or reference materials
```

---

## README.md Highlights

* **Executive Summary:** 1-page overview of QA approach, automation, and measurable outcomes
* **Automation Pyramid:** Visual of manual, API, and UI testing focus
* **How to Run Tests:** Sample commands for Playwright execution (PR validation, full regression, CI/CD headless)
* **Contact Info:** LinkedIn and email for recruiter follow-up

---

## CI/CD Workflow

* Integrates automated tests at **PR validation**, **nightly regression**, and **pre-production deployment**
* Supports **fast feedback**, **risk mitigation**, and **release confidence**
* Mermaid diagram included for visual clarity

---

## Automation Pyramid

* **Manual & Exploratory Testing:** Edge cases, usability, exploratory testing
* **API Tests:** Business logic, validation, contract tests
* **UI / E2E Tests:** Critical flows automated with Playwright

*Focus is primarily on API-level automation, with selective UI coverage.*

---

## How to Run Tests (Sample)

### Install Dependencies

```bash
npm install
```

### Run All Tests

```bash
npx playwright test
```

### Run Specific Test File

```bash
npx playwright test sample_test_cases/login.spec.ts
```

### Generate HTML Test Report

```bash
npx playwright show-report
```

### CI/CD Mode (Headless)

```bash
npx playwright test --headless --parallel --reporter=html
```

---

## Contact

* **LinkedIn:** [[LinkedIn](https://www.linkedin.com/in/ayesha78699/)]
* **Email:** [ayesha.uni.hudd@gmail.com]



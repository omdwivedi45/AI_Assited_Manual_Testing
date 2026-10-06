# AI-Assisted Manual Testing

## Key Testing Principle
* **"NEVER TRUST A STATUS CODE ALONE"** - Functional verification requires auditing the response body metadata for data integrity gaps.

## Project Overview
This project demonstrates an AI-assisted manual testing approach using a web application as the Application Under Test (AUT).

AI was used to assist with test scenario and test case generation. The generated test cases were then reviewed and validated manually against the actual application.

The purpose of this project is to demonstrate how AI can support a manual tester while keeping human validation, test execution, and defect identification as the responsibility of the tester.

---

## Application Under Test
* **Application:** SauceDemo (`https://saucedemo.com`)
* **Testing Approach:** AI-Assisted Manual Testing
* **Testing Type:** Manual Functional Testing

---

## Directory Structure Layout
- `requirements.md` - Clean baseline specifications.
- `TEST CASES.xlsx` - 30 executed positive, negative, and boundary test cases (20 PASS, 10 FAIL).
- `AI VS ME LOGS.xlsx` - 6 documented AI hallucinations filtered out by the human tester.
- `bug reports/` - Detailed breakdown records of manual system defects.
  - `evidence/` - Screenshot repository for validation failure logs.

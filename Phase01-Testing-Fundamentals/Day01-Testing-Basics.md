# Day 1: Introduction to Software Testing

## 1. What Is Software Testing?

Software Testing is the process of checking whether a software application works as expected and meets its requirements.

**Example:** In a banking application, a tester checks whether a user can log in, check their balance, and transfer money correctly.

## 2. Why Is Software Testing Important?

Software Testing helps to:

- Identify bugs and defects.
- Improve software quality.
- Verify that requirements are met.
- Reduce the risk of failures.
- Improve user experience.
- Build confidence in the software.

## 3. What Is a Bug?

A bug is a defect in software that causes it to behave differently from the expected result.

**Example:**

Expected result: A user logs in successfully with valid credentials.

Actual result: An error message appears even though the credentials are valid.

This may indicate a bug that needs investigation.

## 4. Expected Result vs. Actual Result

**Expected Result:** What should happen according to the requirements.

**Actual Result:** What actually happens when a test is executed.

## 5. What Is Manual Testing?

Manual Testing is the process of checking software manually without using automation scripts to execute the tests.

**Example:** A tester opens a login page, enters a username and password, clicks Login, and checks the result.

## 6. What Is Automation Testing?

Automation Testing uses tools and scripts to execute tests automatically.

**Example:** Using Java and Selenium to automate login tests and verify the result.

## 7. Verification vs. Validation

**Verification:** Are we building the product right? It includes reviewing requirements, designs, and code.

**Validation:** Are we building the right product? It checks whether the software meets user needs, often by executing tests.

## 8. Quality Assurance vs. Quality Control

**Quality Assurance (QA):** Focuses on improving the processes used to develop software.

**Quality Control (QC):** Focuses on checking whether the product meets quality requirements. Software testing is an important QC activity.

## 9. Basic Software Testing Process

1. Understand the requirements.
2. Identify test scenarios.
3. Write test cases.
4. Prepare test data.
5. Execute test cases.
6. Compare actual results with expected results.
7. Report defects.
8. Retest fixes and perform regression testing when appropriate.

## 10. Types of Testing — Introduction

- **Functional Testing:** Checks whether features work according to requirements.
- **Non-Functional Testing:** Checks qualities such as performance, usability, and reliability.
- **Smoke Testing:** Checks whether the main functions of a new build work well enough for further testing.
- **Sanity Testing:** Checks a focused area after a small change or fix.
- **Regression Testing:** Checks whether changes have affected existing functionality.
- **Retesting:** Checks whether a previously reported defect has been fixed.

These topics will be covered in detail on later days.

## 11. Sample Login Test Cases

| Test Case ID | Test Scenario | Expected Result |
|---|---|---|
| TC001 | Enter valid username and password | User logs in successfully |
| TC002 | Enter an incorrect password | Appropriate error message appears |
| TC003 | Leave username empty | Required-field validation appears |
| TC004 | Leave password empty | Required-field validation appears |
| TC005 | Enter an unknown username | Appropriate error message appears |

*Note: Expected results must follow the application's actual requirements.*

## 12. Interview Questions and Answers

### Q1. What is Software Testing?

Software Testing is the process of checking software to identify defects and verify that it meets specified requirements.

### Q2. Why is Software Testing important?

It helps identify defects, improve quality, and reduce the risk of failures after software is released.

### Q3. What is a bug?

A bug is a defect that causes software to behave differently from the expected result.

### Q4. What is Manual Testing?

Manual Testing involves executing tests manually without using automation scripts.

### Q5. What is Automation Testing?

Automation Testing uses tools and scripts to execute tests automatically and verify results.

### Q6. What is the difference between Verification and Validation?

Verification reviews work products such as requirements and designs. Validation checks whether the developed software meets user needs.

### Q7. Can testing prove that software has no bugs?

No. Testing can reveal defects, but it cannot prove that software is completely defect-free.

### Q8. Who performs software testing?

Software testers and QA engineers commonly perform testing. Developers also test their code, and testing responsibilities can be shared across the team.

## 13. Practical Exercise

Imagine you are testing a registration page.

Write five test cases for:

1. Registration with valid details.
2. An invalid email address.
3. Empty mandatory fields.
4. Password and confirm-password mismatch.
5. Registration using an email address that already exists.

For each test case, include:

- Test Case ID
- Test Scenario
- Preconditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status (Pass/Fail)

## 14. Day 1 Revision

- Software Testing: Checks software against requirements.
- Bug: A defect that causes unexpected behaviour.
- Expected Result: What should happen.
- Actual Result: What actually happens.
- Manual Testing: Tests executed manually.
- Automation Testing: Tests executed using scripts and tools.
- Verification: Are we building the product right?
- Validation: Are we building the right product?
- QA: Focuses on improving processes.
- QC: Focuses on checking product quality.

## Day 1 Completion Checklist

- [ ] Read and understand the concepts.
- [ ] Practise explaining the interview answers aloud.
- [ ] Write five registration test cases.
- [ ] Save the notes in the GitHub repository.
- [ ] Commit and push the changes.


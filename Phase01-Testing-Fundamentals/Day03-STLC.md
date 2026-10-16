# Day 3: Software Testing Life Cycle (STLC)

## 1. What Is STLC?

STLC stands for **Software Testing Life Cycle**.

It is a step-by-step process followed by a testing team to test software and ensure that it meets the specified quality requirements.

**Example:** Suppose we are testing a college management system. The tester analyzes the requirements, plans testing, writes test cases, prepares the environment, executes tests, reports defects, and completes the testing activities.

## 2. Why Is STLC Important?

STLC is important because it helps to:

- Organize testing activities.
- Understand testing requirements.
- Prepare test cases systematically.
- Identify defects early.
- Track testing progress.
- Improve software quality.
- Ensure important requirements are tested.

## 3. Phases of STLC

STLC commonly has six phases.

### Phase 1: Requirement Analysis

In this phase, testers study the requirements to understand what needs to be tested.

**Example:** For a login page, the tester checks the requirements for valid credentials, invalid passwords, and empty fields.

**Tester’s activities:**
- Understand the requirements.
- Identify testable requirements.
- Ask questions about unclear requirements.
- Identify possible test scenarios.
- Identify testing types and risks.

**Deliverables:**
- Requirement analysis notes.
- Requirement Traceability Matrix (RTM), when applicable.
- Initial test scenarios.

### Phase 2: Test Planning

In this phase, the testing team decides how testing will be performed.

**Example:** The team decides which login features to test, how much time testing will take, and which team members will perform it.

**Tester’s activities:**
- Define the scope of testing.
- Estimate time and effort.
- Identify resources and tools.
- Identify risks.
- Prepare the test plan.
- Define entry and exit criteria.

**Deliverable:** Test Plan.

### Phase 3: Test Case Design and Development

In this phase, testers create test cases and prepare test data.

**Example:** A tester writes test cases for logging in with valid credentials, an incorrect password, and an empty username.

**Tester’s activities:**
- Write test cases.
- Prepare test data.
- Review test cases.
- Map test cases to requirements.
- Identify reusable test cases.

**Deliverables:**
- Test cases.
- Test data.
- Updated RTM, when applicable.

### Phase 4: Test Environment Setup

In this phase, the team prepares the environment required for testing.

**Example:** The tester gets access to the test application, a test database, a supported browser, and the required test accounts.

**Tester’s activities:**
- Verify application availability.
- Check browser and device requirements.
- Arrange test data and accounts.
- Verify database access when needed.
- Perform a basic environment check.

**Deliverable:** Ready-to-use test environment and environment readiness confirmation.

### Phase 5: Test Execution

In this phase, testers execute test cases and compare actual results with expected results.

**Example:** The tester enters valid login details. If the application opens the dashboard as expected, the test passes.

**Tester’s activities:**
- Execute test cases.
- Record actual results.
- Mark tests as Pass, Fail, or Blocked as appropriate.
- Report defects.
- Retest fixed defects.
- Perform regression testing when required.

**Deliverables:**
- Test execution results.
- Defect reports.
- Test execution status.

### Phase 6: Test Cycle Closure

In this phase, the testing team reviews the testing work and documents the outcome.

**Example:** After testing the login feature, the team summarizes the tests executed, defects found, unresolved risks, and remaining issues.

**Tester’s activities:**
- Review test results.
- Check test coverage.
- Summarize defects.
- Document lessons learned.
- Prepare the test summary report.
- Record outstanding risks and limitations.

**Deliverable:** Test Summary Report and testing closure documentation.

## 4. STLC Flow

Requirement Analysis
↓
Test Planning
↓
Test Case Design and Development
↓
Test Environment Setup
↓
Test Execution
↓
Test Cycle Closure

**Note:** These phases are commonly presented in this order, but real projects may overlap or repeat phases when requirements change or defects are fixed.

## 5. Real-Life Example: Login Page Testing

| STLC Phase | Activity |
|---|---|
| Requirement Analysis | Understand login requirements. |
| Test Planning | Decide testing scope, resources, and schedule. |
| Test Case Design | Write test cases for valid and invalid credentials. |
| Environment Setup | Prepare the application, browser, and test accounts. |
| Test Execution | Execute tests and report defects. |
| Test Cycle Closure | Summarize results, coverage, and unresolved issues. |

## 6. What Is the Difference Between SDLC and STLC?

| SDLC | STLC |
|---|---|
| Software Development Life Cycle. | Software Testing Life Cycle. |
| Covers the overall software development process. | Focuses on testing activities. |
| Includes planning, requirements, design, development, testing, deployment, and maintenance. | Includes requirement analysis, test planning, test design, environment setup, test execution, and closure. |
| Involves the wider software development team. | Focuses on testing work performed by testers and QA teams. |
| Goal is to develop and maintain software. | Goal is to plan, perform, and evaluate testing effectively. |

## 7. What Are Entry and Exit Criteria?

### Entry Criteria

Entry criteria are the conditions that should be met before starting a particular testing activity.

**Example:** Before executing login test cases, the application should be available, the test environment should be ready, and the necessary test cases and test data should be prepared.

### Exit Criteria

Exit criteria are the conditions used to decide whether a testing activity can be considered complete.

**Example:** The planned test cases have been executed, critical defects have been reviewed, and the team has documented the remaining risks.

Exit criteria depend on the project's requirements and risk level. Testing does not always require every defect to be fixed before closure.

## 8. What Is a Requirement Traceability Matrix (RTM)?

An RTM is a document that maps requirements to their corresponding test cases.

It helps the team check whether requirements are covered by testing.

**Example:**

| Requirement ID | Requirement | Test Case ID |
|---|---|---|
| REQ001 | User can log in with valid credentials. | TC001 |
| REQ002 | Invalid password displays an error. | TC002 |
| REQ003 | Username is mandatory. | TC003 |

## 9. Advantages of STLC

- Provides a structured testing process.
- Helps improve test coverage.
- Makes testing progress easier to track.
- Helps identify defects systematically.
- Improves communication within the team.
- Supports clear testing documentation.

## 10. Interview Questions and Answers

### Q1. What is STLC?

STLC stands for Software Testing Life Cycle. It is a structured process used to plan, design, execute, and close software testing activities.

### Q2. What are the phases of STLC?

The common phases are requirement analysis, test planning, test case design and development, test environment setup, test execution, and test cycle closure.

### Q3. What happens during requirement analysis?

Testers study the requirements, identify testable features, clarify doubts, and prepare initial test scenarios.

### Q4. What is test planning?

Test planning defines the testing scope, approach, resources, schedule, risks, and completion criteria.

### Q5. What happens during test execution?

Testers execute test cases, compare actual results with expected results, record the outcome, and report defects.

### Q6. What is test cycle closure?

It is the phase in which the team reviews testing results, summarizes defects and coverage, documents outstanding risks, and records lessons learned.

### Q7. What is the difference between entry and exit criteria?

Entry criteria define the conditions needed to start an activity. Exit criteria define the conditions used to decide whether the activity is complete.

### Q8. What is an RTM?

An RTM, or Requirement Traceability Matrix, maps requirements to test cases and helps track test coverage.

### Q9. Does STLC begin only after development is complete?

No. Testing activities can begin during requirement analysis, before coding is finished.

### Q10. What is the main goal of STLC?

The main goal is to perform testing systematically, evaluate software quality, identify defects, and provide information that helps the team make release decisions.

## 11. Practical Exercise

Imagine you are testing a student registration feature in a college management system.

Write the activities you would perform in all six STLC phases:

1. Requirement Analysis:
2. Test Planning:
3. Test Case Design and Development:
4. Test Environment Setup:
5. Test Execution:
6. Test Cycle Closure:

Then write five test cases for student registration.

Include these fields:
- Test Case ID
- Test Scenario
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status

## 12. Day 3 Revision Notes

- STLC means Software Testing Life Cycle.
- STLC organizes testing activities into phases.
- Requirement Analysis identifies what needs to be tested.
- Test Planning decides how testing will be performed.
- Test Case Design prepares test cases and test data.
- Environment Setup prepares the testing environment.
- Test Execution runs test cases and records results.
- Test Cycle Closure summarizes testing outcomes.
- RTM maps requirements to test cases.
- Entry criteria help determine when an activity can start.
- Exit criteria help determine when an activity is complete.




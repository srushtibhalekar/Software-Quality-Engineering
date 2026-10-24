# Day 8: Waterfall Model in Detail

## 1. What Is the Waterfall Model?

The Waterfall Model is a software development model in which work is completed phase by phase in a sequential order.

A team generally completes one phase before moving to the next phase.

**Simple example:** Building a house. First, you plan the house, then create the design, build it, inspect it, and finally hand it over.

Similarly, software development follows planned stages.

## 2. Phases of the Waterfall Model

### Phase 1: Requirement Analysis
The team collects and understands the customer's requirements.

**Example:** A banking application must allow users to log in, check balances, and transfer money.

**Tester’s role:** Understand requirements and identify unclear or missing information.

### Phase 2: System Design
The team prepares the software architecture, database design, and user interface design.

**Example:** Designing the login page and database tables for customer accounts.

**Tester’s role:** Review designs and begin planning test scenarios.

### Phase 3: Implementation (Coding)
Developers write the code according to the approved design.

**Example:** Developers implement login and money-transfer functionality using Java.

**Tester’s role:** Prepare test cases and test data while development is in progress.

### Phase 4: Testing
The testing team checks whether the developed software works as expected.

**Example:** Test login with valid credentials, invalid credentials, and empty fields.

**Tester’s role:**
- Execute test cases.
- Compare actual results with expected results.
- Report defects to developers.
- Retest fixed defects.
- Perform regression testing when needed.

### Phase 5: Deployment
The software is released to the production environment for users.

**Example:** Releasing the banking application to customers.

**Tester’s role:** Support release validation or smoke testing when required.

### Phase 6: Maintenance
The team fixes defects, updates features, and maintains the software after release.

**Example:** Fixing an issue where a customer cannot view their transaction history.

**Tester’s role:** Test fixes and check that existing features still work correctly.

## 3. Waterfall Model Diagram

Requirements → Design → Implementation → Testing → Deployment → Maintenance

Each phase generally follows the previous phase in a planned sequence.

## 4. Advantages of the Waterfall Model

1. Easy to understand and manage.
2. Each phase has clearly defined activities.
3. Documentation is usually detailed.
4. Progress is easy to track against the plan.
5. Can work well when requirements are stable and clearly understood.

## 5. Disadvantages of the Waterfall Model

1. Changes can be difficult and costly after a phase is completed.
2. Working software is usually delivered later in the process.
3. Major defects may be discovered late if testing is delayed.
4. Customer feedback may arrive too late to influence earlier decisions easily.
5. It is less suitable when requirements change frequently.

## 6. When Is the Waterfall Model Suitable?

It may be suitable when:
- Requirements are clear and stable.
- The technology is well understood.
- The project has fixed scope and documentation requirements.
- Changes are expected to be limited.

It may be unsuitable when:
- Requirements change frequently.
- The customer needs regular working releases.
- The project involves considerable uncertainty.

## 7. Role of a Tester in the Waterfall Model

A tester does not need to wait until the testing phase to contribute.

The tester can:
- Review requirements for ambiguity.
- Identify test scenarios early.
- Prepare a test plan and test cases.
- Prepare test data and verify the test environment.
- Execute tests when a testable build is available.
- Report, retest, and track defects.
- Perform regression testing.
- Prepare test summary reports.

**Important:** Although formal testing is often shown as a separate phase, test planning and reviews can begin earlier.

## 8. Real-Life Example: Banking Application

Suppose a company develops a banking application using the Waterfall Model.

| Phase | Example activity |
|---|---|
| Requirements | Define login, balance checking, and money transfer |
| Design | Design screens and database structure |
| Implementation | Developers write the application code |
| Testing | Test login, balance, and transfers |
| Deployment | Release the application |
| Maintenance | Fix issues and deliver updates |

If the customer requests a major new feature after design is approved, the team may need to revisit requirements and design, increasing time and cost.

## 9. Waterfall Model vs Agile Model

| Waterfall | Agile |
|---|---|
| Sequential approach | Iterative and incremental approach |
| Requirements are generally defined early | Requirements can evolve |
| Testing is often a distinct planned phase | Testing happens throughout iterations |
| Feedback may arrive later | Feedback is gathered frequently |
| Best for stable requirements | Useful when requirements change frequently |

Neither model is always best. The right choice depends on the project.

## 10. Interview Questions and Answers

### Q1. What is the Waterfall Model?
The Waterfall Model is a sequential software development model in which the project progresses through planned phases such as requirements, design, coding, testing, deployment, and maintenance.

### Q2. Why is it called the Waterfall Model?
It is called the Waterfall Model because the phases are represented as flowing downward from one stage to the next.

### Q3. What are the main phases of the Waterfall Model?
The main phases are requirement analysis, system design, implementation, testing, deployment, and maintenance.

### Q4. What is the tester's role in the Waterfall Model?
The tester reviews requirements, prepares test cases, executes tests, reports defects, retests fixes, and performs regression testing when required.

### Q5. What is the biggest disadvantage of the Waterfall Model?
Its main disadvantage is that accommodating changes late in the process can be difficult and expensive.

### Q6. Can testing start before coding is completed?
Yes. Test planning, requirement reviews, and test-case design can begin before coding is completed. Test execution generally requires a testable build.

### Q7. When should the Waterfall Model be used?
It can be used when requirements are clear, stable, and well documented.

### Q8. What is the difference between Waterfall and Agile?
Waterfall follows a mostly sequential process, while Agile develops and tests software in repeated iterations with frequent feedback.

## 11. Practical Exercise

Imagine you are testing a college management application.

Write down:
1. Two requirements for the application.
2. One design activity.
3. Two test cases for student login.
4. One possible defect.
5. One maintenance activity after release.



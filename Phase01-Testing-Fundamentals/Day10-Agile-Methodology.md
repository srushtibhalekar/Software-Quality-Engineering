# Day 10: Agile Methodology in Software Testing

## 1. What Is Agile Methodology?

Agile is a software development approach in which a team develops, tests, and improves software in small steps.

Instead of building the entire application before showing it to the customer, the team delivers small working parts and collects feedback regularly.

**Simple example:**

Suppose a company is developing a college management application.

- First, the team develops the login feature.
- Next, it develops the attendance feature.
- Then, it develops the results feature.
- After each iteration, the team tests the software and collects feedback.

This helps the team identify problems and make improvements regularly.

## 2. What Is an Iteration?

An iteration is a short development cycle in which the team plans, develops, tests, and reviews a part of the software.

In Scrum, iterations are commonly called **Sprints**.

A Sprint often lasts 1–4 weeks, depending on the team's working agreement.

**Example:** During a two-week Sprint, a team develops and tests the login and password-reset features.

## 3. What Is the Agile Process?

A simplified Agile process looks like this:

1. **Requirement discussion:** Understand what the customer needs.
2. **Sprint planning:** Select the work to complete in the Sprint.
3. **Development:** Developers build the selected features.
4. **Testing:** Testers check the features and report defects.
5. **Sprint review:** The team demonstrates completed work and gathers feedback.
6. **Retrospective:** The team discusses what went well and what can improve.
7. **Next Sprint:** The team starts the next cycle.

This process repeats as the product evolves.

## 4. What Is a Sprint?

A Sprint is a fixed-length period in Scrum during which the team works toward a defined goal.

**Example:**

Sprint 1: Student login  
Sprint 2: Attendance management  
Sprint 3: Examination results  
Sprint 4: Report generation

The exact features and order depend on the project's priorities.

## 5. What Is the Role of a Tester in Agile?

A tester works closely with developers, the Product Owner, and other team members.

The tester's responsibilities include:

- Understanding user stories and acceptance criteria.
- Identifying test scenarios.
- Preparing test cases and test data.
- Testing features during development.
- Reporting defects with clear steps to reproduce them.
- Retesting fixed defects.
- Performing regression testing.
- Participating in team meetings.
- Sharing testing status and risks.
- Helping improve quality throughout the Sprint.

**Important:** In Agile, testing is not limited to the end of development. Testing happens continuously as features become available.

## 6. What Is a User Story?

A user story describes a feature from the user's point of view.

A common format is:

**As a [type of user], I want [a feature], so that [a benefit].**

Example:

"As a student, I want to log in to the college portal so that I can view my attendance."

A tester uses the user story and its acceptance criteria to understand what should be tested.

## 7. What Are Acceptance Criteria?

Acceptance criteria are the conditions that a feature must satisfy to be accepted.

Example: Student login acceptance criteria:

- A student can log in with valid credentials.
- An error message appears for invalid credentials.
- Required-field messages appear when the username or password is empty.
- The password is not displayed as plain text.

These conditions help developers and testers understand the expected behavior.

## 8. What Is a Daily Stand-up Meeting?

A daily stand-up is a short team meeting used to share progress and identify blockers.

Team members commonly discuss:

1. What did I complete?
2. What will I work on next?
3. Is anything blocking my work?

**Example:** A tester says, "Yesterday I tested the login feature. Today I will test password reset. I am blocked because the test environment is unavailable."

## 9. Advantages of Agile

1. Frequent feedback from customers and stakeholders.
2. Problems can be identified earlier.
3. Changing requirements can be accommodated.
4. Working software is delivered incrementally.
5. Developers and testers collaborate regularly.
6. Teams can improve their process after each iteration.

## 10. Disadvantages of Agile

1. Requirements and priorities may change frequently.
2. The team needs regular communication and collaboration.
3. Estimating the final cost and timeline can be difficult when scope changes.
4. Poor documentation or communication can cause confusion.
5. Frequent releases require effective regression testing and automation where appropriate.

Agile does not mean that documentation or planning is unnecessary.

## 11. Agile vs Waterfall

| Agile | Waterfall |
|---|---|
| Development happens in iterations | Development generally follows sequential phases |
| Feedback is collected regularly | Feedback may arrive later |
| Requirements can evolve | Requirements are generally defined early |
| Testing happens throughout development | Formal testing is often shown as a separate later phase |
| Working software is delivered incrementally | The complete planned product is often delivered later |

Neither approach is right for every project. The choice depends on requirements, risks, constraints, and team needs.

## 12. What Is Scrum?

Scrum is a framework commonly used to apply Agile principles.

### Main Scrum Roles

**1. Product Owner**
- Helps maximize product value.
- Manages and prioritizes the Product Backlog.
- Clarifies product requirements.

**2. Scrum Master**
- Helps the team understand and apply Scrum.
- Helps address impediments.
- Supports effective Scrum events.

**3. Developers**
- Build a usable product increment.
- Plan and perform the work needed to achieve the Sprint Goal.

In Scrum, the Developers group can include people with testing skills and responsibilities.

## 13. Example: Testing a Login Feature in Agile

Suppose a team is building a shopping website.

User story: "As a customer, I want to log in so that I can view my orders."

A tester might perform these checks:

| Test scenario | Expected result |
|---|---|
| Enter valid credentials | Login succeeds |
| Enter an incorrect password | An appropriate error message appears |
| Leave fields empty | Required-field validation appears |
| Enter an unregistered email | Login is rejected appropriately |
| Log in and open order history | The correct user's orders are displayed |

The tester reports defects, verifies fixes, and checks that important existing functionality still works.

## 14. Interview Questions and Answers

### Q1. What is Agile methodology?

Agile is a software development approach in which teams build and improve software in small steps, test frequently, and collect feedback regularly.

### Q2. What is a Sprint?

A Sprint is a fixed-length period in Scrum during which a team works toward a specific goal.

### Q3. What is the role of a tester in Agile?

A tester understands requirements, prepares and executes tests, reports defects, retests fixes, performs regression testing, and collaborates with the team throughout development.

### Q4. What is a user story?

A user story describes a feature from the user's perspective and explains what the user wants and why.

### Q5. What are acceptance criteria?

Acceptance criteria are conditions that a feature must satisfy to be considered acceptable.

### Q6. What is a daily stand-up meeting?

It is a short daily meeting where team members share progress, planned work, and blockers.

### Q7. What is the difference between Agile and Waterfall?

Agile develops software in iterations with frequent feedback, while Waterfall generally follows a sequential process with phases planned in advance.

### Q8. Does Agile mean there is no documentation?

No. Agile supports useful documentation while emphasizing working software, collaboration, and adapting to change.

### Q9. What is regression testing in Agile?

Regression testing checks whether changes or new features have affected existing functionality.

### Q10. What is Scrum?

Scrum is an Agile framework that organizes work into Sprints and defines accountabilities, events, and artifacts to help teams deliver value.

## 15. Practical Exercise

Imagine you are a tester working on a college management application.

Write answers to these questions:

1. Write one user story for student attendance.
2. Write three acceptance criteria for that story.
3. Write three test cases for the attendance feature.
4. Explain what you would say during a daily stand-up meeting.
5. Give two advantages and two disadvantages of Agile.


# Day 11: Scrum Framework in Software Testing

## 1. What Is Scrum?

Scrum is an Agile framework that helps teams develop, deliver, and improve products through short, fixed-length periods called Sprints.

The team works together, checks progress regularly, and adapts based on feedback.

**Example:** A team developing a college management application may work on student login in one Sprint and attendance management in another.

## 2. What Is a Sprint?

A Sprint is a fixed-length period during which the team works toward a specific goal.

A Sprint is one month or less in Scrum. Many teams use two-week Sprints.

Example:
- Sprint 1: Student login
- Sprint 2: Attendance management
- Sprint 3: Examination results

The team aims to produce a usable product increment during each Sprint.

## 3. Scrum Accountabilities (Roles)

Scrum defines three accountabilities within the Scrum Team.

### 1. Product Owner
- Communicates the product goal.
- Manages and orders the Product Backlog.
- Helps the team understand what provides value to users.

**Example:** Decides that student login is more important than a profile-theme feature.

### 2. Scrum Master
- Helps everyone understand Scrum.
- Coaches the team in Scrum practices.
- Helps address impediments.
- Supports effective Scrum events.

**Example:** Helps the team resolve a recurring problem that prevents testing from starting on time.

### 3. Developers
- Create a usable product increment.
- Plan the work needed to achieve the Sprint Goal.
- Maintain quality throughout development.

Developers can include people with programming, testing, design, and other skills. Testing is not necessarily the responsibility of a separate role.

## 4. Scrum Events

Scrum has five key events when including the Sprint itself.

### 1. The Sprint
The overall timebox for the work and other Scrum events.

**Purpose:** Achieve the Sprint Goal and create a usable increment.

### 2. Sprint Planning
The Scrum Team plans the work for the upcoming Sprint.

**Example:** The team decides to develop and test student login during the next two weeks.

### 3. Daily Scrum
A 15-minute event for Developers to inspect progress toward the Sprint Goal and adapt their plan.

**Example:** The team discusses progress on login testing and a blocked test environment.

### 4. Sprint Review
The Scrum Team and stakeholders inspect the Sprint outcome and discuss what to do next.

**Example:** The team demonstrates the completed login feature to college representatives and gathers feedback.

### 5. Sprint Retrospective
The Scrum Team discusses how to improve quality and effectiveness.

**Example:** The team agrees to prepare test data earlier because test execution was delayed.

## 5. Scrum Artifacts

Scrum has three main artifacts.

### 1. Product Backlog
An ordered list of work needed to improve the product.

Example:
- Student login
- Attendance management
- Result viewing
- Fee payment

The Product Owner is accountable for effective Product Backlog management.

### 2. Sprint Backlog
The Sprint Goal, selected Product Backlog items, and the plan for delivering them.

Example:
- Sprint Goal: Enable secure student login.
- Selected work: Login page, credential validation, error messages, and related testing.

The Sprint Backlog is a plan by and for the Developers.

### 3. Increment
The usable, completed product work that meets the Definition of Done.

Example: A working and tested login feature that meets the team's Definition of Done and integrates with the existing application.

## 6. Definition of Done (DoD)

The Definition of Done is a shared description of the quality requirements that must be met for an increment to be considered complete.

A team's Definition of Done might include:
- Code is reviewed.
- Required tests pass.
- Important defects are resolved or handled according to agreed criteria.
- Documentation is updated when needed.
- The feature meets applicable quality standards.

The exact criteria depend on the product and organization.

**Remember:** A feature is not automatically Done just because coding is complete.

## 7. What Does a Tester Do in Scrum?

Scrum does not prescribe a separate Tester accountability. Testing is part of the team's work to build a quality product.

A person with testing responsibilities may:
- Review Product Backlog items.
- Clarify acceptance criteria with the team.
- Identify test scenarios and risks.
- Prepare test data.
- Test new features during the Sprint.
- Report and help investigate defects.
- Retest fixes and perform regression testing.
- Collaborate with developers on automation and quality checks.
- Help ensure the Definition of Done is met.

**Example:** During a login Sprint, the tester checks valid credentials, invalid credentials, empty fields, and relevant security requirements.

## 8. Scrum vs Agile

| Agile | Scrum |
|---|---|
| A set of values and principles for software development | A framework that helps teams work according to Agile principles |
| Includes different approaches and frameworks | One commonly used Agile framework |
| Does not require one specific set of events | Defines specific events, artifacts, and accountabilities |

**Simple way to remember:** Agile is the broader approach; Scrum is one way to put Agile principles into practice.

## 9. Advantages of Scrum

1. Work is organized into manageable Sprints.
2. Teams receive feedback regularly.
3. Progress and problems are inspected frequently.
4. The team can adapt its plans.
5. Quality improvement is part of ongoing work.
6. Stakeholders can see usable results incrementally.

## 10. Challenges of Scrum

1. Unclear goals can make Sprints ineffective.
2. Frequent interruptions can affect focus.
3. Poor communication can cause misunderstandings.
4. Technical debt can grow if quality is neglected.
5. Teams need discipline, collaboration, and regular inspection.

## 11. Practical Example: College Management Application

Suppose a team is building student attendance functionality.

**Product Backlog:** Student login, attendance entry, attendance reports.

**Sprint Goal:** Allow students to view their attendance.

**Sprint Planning:** The team selects the required work and makes a plan.

**During the Sprint:** Developers implement the feature; testing responsibilities include checking attendance values, permissions, and error handling.

**Daily Scrum:** Developers inspect progress toward the Sprint Goal and adjust their plan.

**Sprint Review:** The team demonstrates the attendance feature and gathers feedback.

**Sprint Retrospective:** The team identifies improvements for the next Sprint.

**Increment:** A usable attendance feature that meets the Definition of Done.

## 12. Interview Questions and Answers

### Q1. What is Scrum?
Scrum is an Agile framework in which a team works toward product goals through short, fixed-length Sprints and regular inspection and adaptation.

### Q2. What are the three Scrum accountabilities?
Product Owner, Scrum Master, and Developers.

### Q3. What is a Sprint?
A Sprint is a fixed-length period of one month or less during which the team works toward a Sprint Goal.

### Q4. What is the purpose of Sprint Planning?
The team establishes why the Sprint is valuable, what can be done, and how the work will be accomplished.

### Q5. What is the Daily Scrum?
It is a 15-minute event for Developers to inspect progress toward the Sprint Goal and adapt their plan.

### Q6. What happens during a Sprint Review?
The Scrum Team and stakeholders inspect the Sprint outcome and discuss future adaptations.

### Q7. What is a Sprint Retrospective?
It is an event where the Scrum Team identifies ways to improve quality and effectiveness.

### Q8. What are the three Scrum artifacts?
Product Backlog, Sprint Backlog, and Increment.

### Q9. What is the Definition of Done?
It is a shared description of the quality state required for a product increment to be considered complete.

### Q10. Is testing only the tester's responsibility in Scrum?
No. The whole Scrum Team is accountable for creating a valuable, usable increment that meets the Definition of Done. Team members collaborate on quality.

## 13. Practical Exercise

Imagine you are part of a Scrum Team developing a college application.

Answer these questions:

1. Who prioritizes the Product Backlog?
2. What is the purpose of the Daily Scrum?
3. Write one example of a Sprint Goal.
4. Write three possible Definition of Done criteria.
5. Give two testing activities you would perform during a Sprint.
6. Explain the difference between Sprint Review and Sprint Retrospective.

## 14. Day 11 Revision Checklist

- [ ] I can explain Scrum in simple words.
- [ ] I know the three Scrum accountabilities.
- [ ] I can explain all five Scrum events.
- [ ] I understand the three Scrum artifacts.
- [ ] I can explain the Definition of Done.
- [ ] I understand how testing fits into Scrum.
- [ ] I can answer the interview questions aloud.



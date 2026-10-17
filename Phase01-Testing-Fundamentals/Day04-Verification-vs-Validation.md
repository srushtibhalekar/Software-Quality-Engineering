# Day 4: Verification vs. Validation

## 1. Introduction

Verification and Validation are two important concepts in software testing. Both help improve software quality, but they focus on different things.

- **Verification:** Are we building the product right?
- **Validation:** Are we building the right product?

## 2. What Is Verification?

Verification is the process of checking requirements, documents, designs, and other work products to determine whether they meet specified requirements.

It commonly involves reviews, inspections, and walkthroughs without executing the software.

**Example:**

A customer asks for a login page with username and password fields.

Before the application is developed, the team reviews the requirements and design to check whether both fields are included.

This is Verification.

### Verification Activities

- Requirement reviews
- Design reviews
- Code reviews
- Document inspections
- Walkthroughs

### Advantages of Verification

- Helps identify mistakes early.
- Reduces the cost of fixing defects.
- Improves requirements and design quality.
- Can be performed before the software is ready to run.

## 3. What Is Validation?

Validation is the process of checking whether the developed software meets user needs and intended use.

It commonly involves executing the software and checking its actual behaviour against expected results.

**Example:**

After the login page is developed, the tester enters a valid username and password and checks whether the user can log in successfully.

This is Validation.

### Validation Activities

- Functional testing
- System testing
- User acceptance testing
- Usability testing
- Other forms of software execution-based testing

### Advantages of Validation

- Checks whether the software meets user needs.
- Identifies defects in actual software behaviour.
- Helps confirm that features work as intended.
- Provides confidence before release.

## 4. Verification vs. Validation

| Verification | Validation |
|---|---|
| Checks whether work products meet specified requirements. | Checks whether the software meets user needs and intended use. |
| Commonly uses reviews and inspections. | Commonly uses execution-based testing. |
| Often does not require running the software. | Usually involves running the software. |
| Can begin during requirements and design. | Can begin when testable software is available; validation planning can start earlier. |
| Example: Reviewing a login page design. | Example: Testing the developed login page. |

## 5. Real-Life Example: Online Banking Application

Suppose a team is developing an online banking application.

### Verification

The tester reviews the requirements and design to check whether the money transfer feature specifies the required fields, validation rules, and confirmation message.

The tester may also review test cases before execution.

### Validation

The tester uses the application to transfer money between test accounts and checks whether the transaction follows the requirements, the balance is updated correctly, and the appropriate confirmation is displayed.

## 6. Can Verification and Validation Find Defects?

Yes. Both can help identify problems.

**Verification example:** A review discovers that the password requirement is missing from the design.

**Validation example:** Testing reveals that the login page accepts an incorrect password.

Finding problems early through reviews can help reduce rework later.

## 7. Interview Questions and Answers

### Q1. What is Verification?

Verification checks whether requirements, designs, code, and other work products meet specified requirements. It often uses reviews and inspections.

### Q2. What is Validation?

Validation checks whether the developed software meets user needs and intended use. It commonly involves executing the application and testing its behaviour.

### Q3. What is the main difference between Verification and Validation?

Verification commonly checks work products against specifications, while validation checks whether the software meets user needs.

### Q4. Give an example of Verification.

Reviewing a login page design to confirm that the required username and password fields are included is an example of verification.

### Q5. Give an example of Validation.

Entering valid login credentials into the developed application and checking whether login succeeds is an example of validation.

### Q6. Which happens first, Verification or Validation?

Verification often begins during requirements and design, before the software is ready to execute. Validation activities commonly follow when testable software becomes available. Their activities may overlap throughout development.

### Q7. Can Verification be performed without executing the software?

Yes. Reviews, inspections, and walkthroughs can examine documents, designs, or code without running the application.

### Q8. Is testing part of Validation?

Execution-based software testing is a major part of validation. However, software quality also benefits from verification activities such as reviews and inspections.

### Q9. Why are both Verification and Validation important?

Verification helps identify problems in requirements and other work products, while validation checks whether the software meets user needs. Together, they improve quality and reduce risk.

### Q10. What is a simple way to remember the difference?

Verification: Are we building the product right?

Validation: Are we building the right product?

## 8. Practical Exercise

Imagine you are testing a college management system.

Classify each activity as Verification or Validation:

1. Reviewing the student registration requirements.
2. Checking the registration page design.
3. Entering student details into the application.
4. Checking whether an invalid email displays an error.
5. Reviewing test cases before execution.
6. Checking whether attendance is calculated correctly in the application.

Write your answers and explain why each activity belongs to that category.

## 9. Day 4 Revision Notes

- Verification checks work products against specified requirements.
- Validation checks whether the software meets user needs.
- Verification commonly involves reviews, inspections, and walkthroughs.
- Validation commonly involves executing software and checking its behaviour.
- Verification can identify problems before code execution.
- Validation checks the developed software in use.
- Both contribute to software quality.


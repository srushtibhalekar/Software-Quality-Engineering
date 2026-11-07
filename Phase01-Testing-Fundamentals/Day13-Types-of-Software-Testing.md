# Day 13: Types of Software Testing

## 1. What Are Types of Software Testing?

Software testing is divided into different types based on what we want to check.

The two major categories are:

1. Functional Testing
2. Non-Functional Testing

**Easy way to remember:**

- Functional Testing = What does the software do?
- Non-Functional Testing = How well does the software work?

Example: In a banking application:
- Functional: Can the user transfer money?
- Non-Functional: Does the money transfer page load quickly?

---

## 2. Functional Testing

### What is Functional Testing?

Functional Testing checks whether the software features work according to the specified requirements.

It focuses on what the application does.

**Example: Login Page**

We check:
- Can the user log in with valid credentials?
- Does an error message appear for an incorrect password?
- Does the application validate empty fields?
- Can the user log out successfully?

### Common Types of Functional Testing

#### 1. Unit Testing
Checks individual components or small pieces of code.

Example: Checking a Java method that calculates a total price.

#### 2. Integration Testing
Checks whether different modules work correctly together.

Example: Checking whether the login module communicates with the database.

#### 3. System Testing
Checks the complete application against its requirements.

Example: Testing login, payments, and transaction history in a banking application.

#### 4. Smoke Testing
Checks the basic and critical functions of a new software build to decide whether it is stable enough for further testing.

Example:
- Application opens.
- Login works.
- Dashboard loads.

#### 5. Sanity Testing
A focused check to verify that a particular change or bug fix works as expected.

Example: After fixing a password-reset issue, we check the password-reset functionality.

#### 6. Regression Testing
Checks whether new changes have affected existing functionality.

Example: After updating the login feature, we check whether registration and password reset still work.

#### 7. Retesting
Checks a previously failed test case again after the reported defect has been fixed.

Example: Login was failing with valid credentials. After the developer fixes the defect, the tester executes the same test again.

#### 8. User Acceptance Testing (UAT)
Checks whether the software meets business requirements and user expectations.

Example: Bank representatives verify whether the banking application meets their business needs.

---

## 3. Non-Functional Testing

### What is Non-Functional Testing?

Non-Functional Testing checks how well the software performs.

It focuses on quality characteristics such as performance, security, usability, and reliability.

**Example: Login Page**

We check:
- Does the login page load quickly?
- Can the application handle many users?
- Is user information protected?
- Is the page easy to understand?

### Common Types of Non-Functional Testing

#### 1. Performance Testing
Checks the speed, responsiveness, stability, and resource behavior of an application under different workloads.

Example: Checking how quickly a banking application responds when many users log in.

#### 2. Load Testing
Checks application behavior under an expected number of users or workload.

Example: Testing a website with 1,000 concurrent users if that is its expected workload.

#### 3. Stress Testing
Checks how the application behaves when the workload goes beyond its expected limits.

Example: Increasing the number of users until the application reaches its breaking point or starts failing.

#### 4. Security Testing
Checks whether the application protects data and prevents unauthorized access.

Example:
- Checking whether users can access another person's account.
- Checking whether passwords are protected.
- Checking whether unauthorized users can open restricted pages.

#### 5. Usability Testing
Checks whether the application is easy to understand and use.

Example: Checking whether a new user can easily find the login and registration options.

#### 6. Compatibility Testing
Checks whether the application works correctly across different browsers, devices, and operating systems.

Example: Testing a website on Chrome, Firefox, Edge, and mobile devices.

#### 7. Reliability Testing
Checks whether the application works consistently without frequent failures over a period of time.

Example: Checking whether a banking application continues working reliably during long operating periods.

#### 8. Scalability Testing
Checks whether an application can handle an increase in workload by adding resources or capacity.

Example: Checking whether an e-commerce website can support increasing traffic during a major sale.

---

## 4. Functional vs Non-Functional Testing

| Functional Testing | Non-Functional Testing |
|---|---|
| Checks what the software does | Checks how well the software works |
| Focuses on features | Focuses on quality characteristics |
| Checks business functionality | Checks performance, security, usability, etc. |
| Example: Login works correctly | Example: Login responds quickly |

---

## 5. Smoke Testing vs Sanity Testing

| Smoke Testing | Sanity Testing |
|---|---|
| Checks basic critical functionality | Checks a specific change or fix |
| Usually broad but shallow | Narrow and focused |
| Helps decide whether further testing can begin | Helps decide whether the specific change works correctly |
| Example: Check login, dashboard, and basic navigation | Example: Check a recently fixed password-reset feature |

---

## 6. Retesting vs Regression Testing

| Retesting | Regression Testing |
|---|---|
| Checks whether a particular defect is fixed | Checks whether existing functionality is affected by changes |
| Uses previously failed test cases | Uses relevant test cases for existing functionality |
| Focuses on the reported defect | Focuses on possible side effects |

**Remember:**
- Retesting = Check the same bug again.
- Regression = Check whether something else broke.

---

## 7. Real-Life Example: Online Shopping Application

Imagine you are testing an online shopping website.

### Functional Testing
1. User can register.
2. User can log in.
3. User can search for products.
4. User can add products to the cart.
5. User can complete payment.

### Non-Functional Testing
1. Website loads quickly.
2. Website supports many users.
3. User payment details are protected.
4. Website works on different browsers.
5. Website is easy to use.

---

## 8. Interview Questions and Answers

### Q1. What is Functional Testing?

Functional Testing checks whether software features work according to the specified requirements.

### Q2. What is Non-Functional Testing?

Non-Functional Testing checks quality characteristics such as performance, security, usability, and reliability.

### Q3. What is the difference between Functional and Non-Functional Testing?

Functional Testing checks what the application does, while Non-Functional Testing checks how well the application works.

### Q4. What is Smoke Testing?

Smoke Testing checks the basic and critical functionality of a new build to decide whether it is stable enough for further testing.

### Q5. What is Sanity Testing?

Sanity Testing is a focused check of a particular change or bug fix to verify that it works as expected.

### Q6. What is Regression Testing?

Regression Testing checks whether changes in the application have affected existing functionality.

### Q7. What is Retesting?

Retesting means executing a previously failed test case again after the developer fixes the defect.

### Q8. What is Performance Testing?

Performance Testing checks the speed, responsiveness, stability, and resource behavior of an application.

### Q9. What is Load Testing?

Load Testing checks how an application behaves under an expected workload.

### Q10. What is Stress Testing?

Stress Testing checks how an application behaves when the workload exceeds its expected limits.

### Q11. What is Security Testing?

Security Testing checks whether the application protects data and prevents unauthorized access.

### Q12. What is Compatibility Testing?

Compatibility Testing checks whether an application works correctly across different browsers, devices, and operating systems.

---

## 9. Practical Exercise

Imagine you are testing an online banking application.

Identify whether each situation is Functional or Non-Functional Testing.

1. Checking whether the user can log in.
2. Checking whether the application loads within three seconds.
3. Checking whether a user can transfer money.
4. Checking whether unauthorized users can access account details.
5. Checking whether the website works on Chrome and Firefox.
6. Checking whether the application supports 5,000 concurrent users.

Also identify the specific testing type wherever possible.

---

## 10. Day 13 Revision Checklist

- [ ] I understand Functional Testing.
- [ ] I understand Non-Functional Testing.
- [ ] I can explain common Functional Testing types.
- [ ] I can explain common Non-Functional Testing types.
- [ ] I know Smoke Testing vs Sanity Testing.
- [ ] I know Retesting vs Regression Testing.
- [ ] I can give real-life examples.
- [ ] I can answer the interview questions aloud.



# Day 12: Levels of Software Testing

## 1. What Are Levels of Testing?

Testing levels are different stages at which software is tested to check its quality and functionality.

There are four main levels of software testing:

1. Unit Testing
2. Integration Testing
3. System Testing
4. Acceptance Testing

**Easy way to remember:**

- Unit = One small part
- Integration = Connected parts
- System = Complete application
- Acceptance = Customer satisfaction

## 2. Unit Testing

### What is Unit Testing?

Unit Testing is the process of testing individual components or small pieces of code separately.

The main purpose is to check whether each small unit works correctly.

**Example:**

Suppose we have a banking application with a method that calculates the account balance.

We test that method separately to check whether it gives the correct result.

**Who performs it?**

Usually developers.

### Example Test Cases

| Test scenario | Expected result |
|---|---|
| Add 100 + 200 | Result should be 300 |
| Add 0 + 100 | Result should be 100 |
| Add -10 + 20 | Result should be 10 |

### Advantages
- Finds defects early.
- Makes debugging easier.
- Checks individual components.
- Supports safer code changes.

## 3. Integration Testing

### What is Integration Testing?

Integration Testing checks whether two or more modules work correctly together.

The main purpose is to identify problems in communication and data exchange between modules.

**Example:**

In a banking application:

- Login module
- Account module
- Database module

Integration testing checks whether these modules communicate correctly.

For example, after successful login, the application should retrieve the correct account details from the database.

**Who performs it?**

Developers and/or testers, depending on the project.

### Example Test Cases

| Test scenario | Expected result |
|---|---|
| Login module connects to database | Connection should work correctly |
| Account module requests balance | Correct balance should be displayed |
| Payment module sends transaction details | Correct details should reach the transaction module |

### Advantages
- Finds communication problems between modules.
- Checks data flow.
- Helps identify interface defects.

## 4. System Testing

### What is System Testing?

System Testing checks the complete application to verify that it works according to the specified requirements.

It tests the integrated system as a whole.

**Example:**

In a banking application, we test:

- User login.
- Balance checking.
- Money transfer.
- Transaction history.
- Logout.

We check whether all these features work correctly together.

**Who performs it?**

Usually the testing or QA team.

### Example Test Cases

| Test scenario | Expected result |
|---|---|
| Login with valid credentials | User should log in |
| Check account balance | Correct balance should appear |
| Transfer money | Transaction should complete according to requirements |
| View transaction history | Correct transaction details should appear |

### Advantages
- Checks the complete application.
- Finds defects in end-to-end functionality.
- Helps verify system requirements.

## 5. Acceptance Testing

### What is Acceptance Testing?

Acceptance Testing checks whether the software meets business requirements and user expectations.

The main purpose is to decide whether the software is acceptable for its intended use.

**Example:**

A bank develops a new banking application.

Before release, bank representatives or selected users check whether customers can log in, view balances, and transfer money as expected.

**Who performs it?**

Customers, business users, or designated acceptance testers.

### Types of Acceptance Testing

**1. User Acceptance Testing (UAT)**

Actual users or business representatives verify whether the software meets their needs.

Example: Bank employees check whether the banking application supports their daily work.

**2. Alpha Testing**

Testing performed at the developer's site or in a controlled internal environment before the product is released to external users.

**3. Beta Testing**

A version of the software is made available to selected external users in a real-world environment to collect feedback.

### Advantages
- Confirms business requirements.
- Collects user feedback.
- Helps assess readiness for release.

## 6. Comparison of Four Testing Levels

| Testing Level | What Is Tested? | Main Purpose |
|---|---|---|
| Unit Testing | Individual component | Check small units |
| Integration Testing | Connected modules | Check communication |
| System Testing | Complete application | Check overall behavior |
| Acceptance Testing | Software against user/business needs | Check acceptability |

## 7. Real-Life Example: Online Shopping Application

Imagine you are testing an online shopping application.

**Unit Testing:**
- Check the price calculation method.
- Check the discount calculation method.

**Integration Testing:**
- Check whether the cart module sends correct details to the payment module.
- Check whether the payment module communicates with the order module.

**System Testing:**
- Search for a product.
- Add it to the cart.
- Make a payment.
- Check the order history.

**Acceptance Testing:**
- Customers or business representatives verify whether the shopping application meets their requirements.

## 8. Important Difference: Integration Testing vs System Testing

| Integration Testing | System Testing |
|---|---|
| Checks connected modules | Checks the complete application |
| Focuses on communication between modules | Focuses on overall system behavior |
| Can be performed before the entire system is complete | Requires an integrated system |
| Finds interface and data exchange problems | Finds system-level defects |

## 9. Important Difference: System Testing vs Acceptance Testing

| System Testing | Acceptance Testing |
|---|---|
| Checks the complete system against specified requirements | Checks whether the software meets business needs |
| Usually performed by the testing team | Usually performed by customers or business representatives |
| Focuses on system behavior | Focuses on acceptability for intended use |

## 10. Interview Questions and Answers

### Q1. What are the four levels of software testing?

The four levels are Unit Testing, Integration Testing, System Testing, and Acceptance Testing.

### Q2. What is Unit Testing?

Unit Testing checks individual components or small pieces of code separately to make sure they work correctly.

### Q3. What is Integration Testing?

Integration Testing checks whether different modules work correctly when connected.

### Q4. What is System Testing?

System Testing checks the complete integrated application against its specified requirements.

### Q5. What is Acceptance Testing?

Acceptance Testing checks whether the software meets business requirements and user expectations.

### Q6. Who performs Unit Testing?

Unit Testing is usually performed by developers.

### Q7. What is UAT?

UAT stands for User Acceptance Testing. It checks whether the application meets the needs of its intended users or business representatives.

### Q8. What is the difference between Alpha and Beta Testing?

Alpha testing is performed internally in a controlled environment, while Beta testing involves selected external users who try the software in real-world conditions.

### Q9. Which testing level checks communication between modules?

Integration Testing.

### Q10. Which testing level checks the complete application?

System Testing.

## 11. Practical Exercise

Imagine you are testing a college management application.

Identify which testing level is suitable for each situation:

1. Checking a Java method that calculates student marks.
2. Checking whether the login module communicates with the student database.
3. Testing login, attendance, fees, and results in the complete application.
4. Asking college staff to verify whether the application meets their requirements.

Write your answers and explain why you selected each level.

## 12. Day 12 Revision Checklist

- [ ] I can explain the four testing levels.
- [ ] I understand Unit Testing.
- [ ] I understand Integration Testing.
- [ ] I understand System Testing.
- [ ] I understand Acceptance Testing.
- [ ] I can explain UAT, Alpha, and Beta testing.
- [ ] I can compare Integration and System Testing.
- [ ] I can answer the interview questions aloud.


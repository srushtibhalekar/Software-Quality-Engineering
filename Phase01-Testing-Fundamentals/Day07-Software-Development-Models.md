# Day 7: Software Development Models

## 1. What Is a Software Development Model?

A Software Development Model is a structured approach that explains how software development activities are organized and performed.

It helps the team plan, design, develop, test, and deliver software.

Different projects use different models depending on their requirements, budget, timeline, risks, and customer needs.

**Example:** A project with fixed requirements may use the Waterfall Model, while a project with frequently changing requirements may use an Agile approach.

## 2. Why Are Software Development Models Important?

Software development models help to:

- Organize project activities.
- Define the order of development tasks.
- Improve communication among team members.
- Manage project time and resources.
- Plan testing activities.
- Identify risks and problems.
- Deliver software according to project needs.

## 3. Common Software Development Models

Some commonly discussed models and approaches are:

1. Waterfall Model
2. V-Model
3. Prototype Model
4. Iterative Model
5. Spiral Model
6. Agile Model

Each approach has its own advantages, disadvantages, and suitable use cases.

## 4. Waterfall Model

The Waterfall Model follows a sequential approach. One phase is generally completed before the next phase begins.

**Typical phases:**

1. Requirements
2. Design
3. Development
4. Testing
5. Deployment
6. Maintenance

**Example:** A project with clearly defined requirements and few expected changes may use a Waterfall approach.

**Advantages:**
- Easy to understand and manage.
- Phases and deliverables are clearly defined.
- Works well when requirements are stable.

**Disadvantages:**
- Changes can be expensive later in the project.
- Working software may become available relatively late.
- Testing often happens after development.

## 5. V-Model

The V-Model is a development approach that connects development phases with corresponding testing activities.

Testing is planned early, alongside requirements and design.

**Common relationships:**

| Development Activity | Corresponding Testing Activity |
|---|---|
| Business requirements | Acceptance Testing |
| System requirements | System Testing |
| High-level design | Integration Testing |
| Detailed design | Unit Testing |
| Coding | Implementation point at the bottom of the V |

**Example:** While system requirements are being defined, the team plans how system testing will verify them.

**Advantages:**
- Encourages early test planning.
- Makes development and testing relationships clear.
- Helps trace tests to requirements.

**Disadvantages:**
- Can be difficult to adapt to frequent changes.
- Less flexible when requirements are unclear.
- A working product is usually not delivered incrementally in the classic model.

## 6. Prototype Model

The Prototype Model creates an early sample or working model of the software so stakeholders can review it and provide feedback.

**Example:** Before building a college management system, the team creates a sample student registration screen to understand user expectations.

**Advantages:**
- Helps clarify unclear requirements.
- Encourages early user feedback.
- Can reveal usability problems early.

**Disadvantages:**
- Frequent changes may increase cost and time.
- Users may mistake the prototype for the final product.
- Poorly managed prototypes can lead to weak design decisions.

## 7. Iterative Model

The Iterative Model develops and improves software through repeated cycles.

Each iteration uses feedback and evaluation to refine the product.

**Example:**

- Iteration 1: Develop student registration.
- Iteration 2: Improve registration and add attendance.
- Iteration 3: Add result management and improve existing features.

**Advantages:**
- Allows gradual improvement.
- Supports feedback between iterations.
- Problems can be identified during development.

**Disadvantages:**
- Requires effective planning and feedback.
- Repeated changes can affect cost and schedule.
- Poorly managed iterations can create rework.

## 8. Spiral Model

The Spiral Model develops software through repeated cycles with a strong focus on risk analysis.

Each cycle commonly includes planning, risk analysis, development and testing, and evaluation.

**Example:** A large banking system with significant security and financial risks may benefit from a risk-focused development approach.

**Advantages:**
- Focuses on identifying and managing risks.
- Supports evaluation at each cycle.
- Can accommodate changing requirements.

**Disadvantages:**
- Can be expensive.
- Requires expertise in risk analysis.
- May be unsuitable for small, low-risk projects.

## 9. Agile Model

Agile is an approach in which teams develop and deliver software in small increments, collaborate frequently, and adapt to changing requirements.

Work is often organized into short iterations or sprints.

**Example:** A team releases a basic shopping application first, then adds payment improvements and order tracking in later iterations.

**Advantages:**
- Supports changing requirements.
- Encourages regular feedback.
- Delivers usable features incrementally.
- Promotes collaboration.

**Disadvantages:**
- Requires regular communication.
- Frequent changes can affect scope.
- Delivery timelines can be difficult to predict without effective planning.

## 10. Comparison of Software Development Models

| Model | Main Characteristic | Suitable Situation |
|---|---|---|
| Waterfall | Sequential phases | Stable, well-understood requirements |
| V-Model | Development linked to testing | Projects needing structured verification and validation |
| Prototype | Early sample for feedback | Unclear requirements or user interface needs |
| Iterative | Repeated improvement cycles | Products that benefit from gradual refinement |
| Spiral | Risk-focused cycles | Large, complex, high-risk projects |
| Agile | Incremental delivery and adaptation | Projects with frequent feedback or changing requirements |

No single model is best for every project. The team should choose an approach based on the project's needs and constraints.

## 11. Role of a Software Tester in Different Models

### Waterfall Model
The tester reviews requirements and prepares test plans early. Detailed test execution often occurs after development.

### V-Model
The tester plans corresponding testing activities while requirements and designs are being prepared.

### Prototype Model
The tester can evaluate the prototype, check usability, and help identify unclear requirements.

### Iterative Model
The tester tests each iteration and checks whether changes have affected existing functionality.

### Spiral Model
The tester helps evaluate risks and tests software produced during each cycle.

### Agile Model
The tester collaborates with developers and product stakeholders, tests features during sprints, and performs regression testing as needed.

## 12. Interview Questions and Answers

### Q1. What is a Software Development Model?

A Software Development Model is an approach that organizes the activities involved in developing, testing, and delivering software.

### Q2. Name some common software development models.

Common examples are Waterfall, V-Model, Prototype, Iterative, Spiral, and Agile.

### Q3. What is the Waterfall Model?

The Waterfall Model is a sequential approach in which phases are generally completed in order before moving to the next phase.

### Q4. What is the V-Model?

The V-Model connects development activities with corresponding testing activities and encourages test planning early in development.

### Q5. What is the Prototype Model?

The Prototype Model creates an early version of a system to gather feedback and clarify requirements.

### Q6. What is the Iterative Model?

The Iterative Model develops and improves software through repeated cycles, using feedback to refine the product.

### Q7. What is the Spiral Model?

The Spiral Model is a risk-focused approach that develops software through repeated cycles of planning, risk analysis, development, and evaluation.

### Q8. What is Agile?

Agile is an approach that emphasizes collaboration, incremental delivery, feedback, and adaptation to changing requirements.

### Q9. Which model is suitable when requirements frequently change?

Agile or an iterative approach can be suitable because they support feedback and changes during development.

### Q10. Which model focuses strongly on risk analysis?

The Spiral Model focuses strongly on identifying and managing project risks.

## 13. Practical Exercise

Imagine you are developing a college management system.

Answer these questions:

1. Which model might suit a project with stable requirements? Why?
2. Which approach could help when student and teacher feedback frequently changes requirements?
3. Which model emphasizes risk analysis?
4. How can the V-Model help testers plan testing early?
5. Give one advantage and one disadvantage of the Waterfall Model.

Write your answers in your own words.

## 14. Day 7 Revision Notes

- Software Development Models organize software development activities.
- Waterfall follows a sequential approach.
- V-Model connects development activities with testing activities.
- Prototype uses an early sample to gather feedback.
- Iterative development improves software through repeated cycles.
- Spiral emphasizes risk analysis.
- Agile supports incremental delivery, collaboration, and changing requirements.
- The best approach depends on project needs and constraints.


# Quality Assurance, Testing, and Test-Driven Development (TDD)

### Week 7 Lecture

**Tony Clear**

## Taking Stock

- **Course Schedule:**
  - Review of where we are in the course.
  - Overview of upcoming content and assessments.
- **Assessment Schedule:**
  - Assignments drive learning.
  - Progress feedback and addressing any issues.

## Assignments Drive Your Learning

### Assignment 1A: Preparing for Software Development (20%)

- **Individual Tasks:**
  - Set up tools for coding, version control, and unit testing.
  - Collaborate with the team for code sharing and integration.
  - Learn and use the selected tech stack (front-end/backend).
  - Set up tools for quality assurance and cloud deployment.
  - Monitor and address issues post-deployment.
- **Goals:**
  - Understand product goals and create a Product Backlog.
  - Define Sprint 1 goals and create a Sprint Backlog.

### Assignment 1B: Full SDLC Full Stack Product Development (50%)

- **Team Project (4 members including QA):**
  - Develop a product collaboratively.
  - Apply a new tech stack and toolset.
  - Practice DevOps and Scrum methodologies.
  - Collaborate with a Product Owner and the team.
- **Sprints:**
  - Sprint 1: Weeks 6 and 7
  - Sprint 2: Weeks 8 and 9
  - Sprint 3: Weeks 10 and 11
- **Deliverables:**
  - Product increments submitted during tutorials in weeks 8, 10, and 12.
  - Capability and learning portfolio with evidence.

### Assignment 2: Knowledge Check (30%)

- **Individual Assessment:**
  - Submission in tutorials during weeks 1-5 (sign-off by TA).
  - Evidence portfolio and demonstration.
  - Online questions to confirm understanding of key concepts.
  - Scheduled during revision weeks.

## Team Contract and Commitments

- **Revision History:**
  - Date, Version, Description, Author.
- **Team Issue Report:**
  - Explanation of adverse situations.
  - Strategy for addressing deficiencies (skills lack, lack of contribution).
  - Strategy for demonstrating team commitment.
  - Author and signature.

## What is Quality Assurance?

- **Definition:**
  - A planned and systematic approach to evaluating software quality.
  - Ensures adherence to software product standards, processes, documentation, and procedures.
- **Focus Areas:**
  - Code design.
  - Product/Application.

## Key Aspects of Quality

### Perspectives on Software Quality

- **Transcendental View:** Quality is something that can be recognized but not defined.
- **User View:** Quality as fitness for purpose.
- **Manufacturing View:** Quality as conformance to specification.
- **Product View:** Quality tied to inherent characteristics of the product.
- **Value-Based View:** Quality depends on the amount a customer is willing to pay.

### Quality Assurance Process

- **Quality in Learning:**
  - Learning as a transformative process.
  - Need for a quality process to ensure predictable and high-quality outcomes.
- **Roles and Responsibilities:**
  - Allocate roles to appropriately skilled team members.
- **Measurement and Standards:**
  - Use of metrics to demonstrate conformance to standards.
  - Example standards: ISO 9126 (functionality, reliability, efficiency, usability, maintainability, portability).

## Key Aspects of Quality – Metrics and Testing

- **Metrics:**
  - Provide a yardstick to demonstrate conformance or highlight lack of it.
  - Examples include standards for coding, document formatting, recording meeting minutes.
- **Testing:**
  - Considered a quality control (QC) activity, part of the production function.
  - A multi-layered testing strategy is key (unit tests, integration tests, usability tests, performance tests, etc.).

## Key Aspects of Quality – Reviews and Continuous Processes

- **Quality Reviews:**
  - Inspections, walkthroughs, formal technical reviews.
  - Code and design inspections.
- **Continuous Processes:**
  - Pair programming.
  - Joint Application Development (JAD) workshops.
  - Test-Driven Development (TDD).
  - Continuous integration, regular code builds, refactoring.
- **Continuous Improvement:**
  - Software Process and Practice Improvement (SPPI).
  - Reflect and adapt processes for future improvements.

## Quality Assurance Accountability

- **Team Agreement Document:**
  - Commitments to one another.
  - Communication strategies.
  - Team roles and accountabilities (including QA for each iteration).
- **QA Accountability Reflection:**
  - Explanation of the team's emphasis on QA for the iteration.
  - Reflection on success and areas for improvement.
  - Plans for the next iteration.

## Evolving Views of Software Quality

- **Debate on Software Quality:**
  - Different views and measurements over time.
  - Need for contemporary guidelines and templates.
- **Software Quality Models:**
  - Various models to guide developers.
  - Examples include the ISO standards.

## Top 20 Software Quality Characteristics

- **Examples:**
  - Reliability
  - Usability
  - Maintainability
  - Efficiency
  - Portability
  - Functionality
  - Etc.

## Questions About Quality and Testing

- **Key Questions:**
  - What are the quality criteria to test the code against?
  - What are the quality testing practices?
  - How to prevent low-quality issues?
  - How to recognize pass or fail?
  - Actions to take if the quality test fails.
- **Considerations:**
  - You can never be 100% sure there are no defects.
  - Testing can only prove the presence of defects, not their absence.

## What is Testing?

- **Definition:**
  - Verifying that the behavior of the application matches what is specified or expected.
- **Purpose:**
  - Ensure code behaves as expected.
  - Provide confidence in releasing and experimenting.

## Testing Criteria and Recognizing Pass/Fail

- **Criteria:**
  - Expected output for given inputs.
  - Expected behavior of the application/system.
  - Coding standards and conventions.
- **Example of Bad Test Criteria:**
  - "The product should be user-friendly."

## Why Write Tests?

- **Documentation:**
  - Tests specify how code should work.
- **Consistency:**
  - Verify developers follow good practices and team conventions.
- **Comfort and Confidence:**
  - Strong test suite provides assurance for releases.
- **Productivity:**
  - Allows for faster shipping of code.

## Types of Software Testing

- **Functional Testing**
- **Usability Testing**
- **System Testing**
- **Unit Testing**
- **Integration Testing**
- **Exploratory Testing**
- **Black Box Testing**
- **White Box Testing**
- **Regression Testing**
- **Performance Testing**
- **Stress Testing**
- **Load/Stability Testing**
- **Security Testing**
- **Regulatory and Compliance Testing**

## Static Tests

- **Code Analysis Tools:**
  - Linters (e.g., ESLint).
  - Visual Studio Code squiggly lines.
  - SonarQube.

## The Risk of No Integration Testing

- **Issues:**
  - "It works on my machine" syndrome.
  - Lack of coordination and dependencies.
  - High risk when integrating code developed in isolation.

## Non-Functional Requirements (Quality Requirements)

- **Examples:**
  - Performance
  - Scalability
  - Security
  - Usability
  - Reliability

## Test Pyramid – Prioritizing Test Efforts

- **Concept:**
  - Focus on spending more effort on lower-level tests (unit tests) and less on higher-level tests (UI tests).
- **Mike Cohn’s Agile Testing Pyramid:**
  - Base: Unit Tests
  - Middle: Service/Integration Tests
  - Top: UI/End-to-End Tests

## Crispin’s Agile Testing Quadrants

- **Quadrants:**
  - Different types of tests categorized based on purpose and scope.
- **Purpose:**
  - Guide teams on what tests to focus on at different stages.

## Unit Tests with React

- **Tools:**
  - Jest (Test Runner)
  - React Testing Library
- **Components:**
  - Test assertion library.
  - Mocking features.
- **Testing Focus:**
  - Ensure components render correctly.
  - Simulate user interactions.

## Simulating User Interaction

- **Purpose:**
  - Test how users interact with the application.
- **Methods:**
  - Simulate events like clicks, inputs, and form submissions.

## Testing Resources

- **Tutorials and Videos:**
  - Unit Testing with Jest and React Testing Library.
  - Complete Guide to Component Testing with Jest.
  - Jest Crash Course.

## Test Automation

- **Regression Testing:**
  - Running all tests (or prioritized ones) to ensure new changes don't break existing functionality.
- **Continuous Delivery and DevOps:**
  - Rely on test automation for rapid deployment.
- **Benefits:**
  - Ensures tests are run at the right time.
  - Frees developers and testers for more analytical testing.

## Automating Integration Testing Continuously

- **Continuous Integration (CI):**
  - Integrate code changes frequently.
  - Run automated tests to catch issues early.
- **Continuous Deployment (CD):**
  - Automatically deploy code that passes tests to production or staging environments.

## What is Automated Testing?

- **Definition:**
  - Using software tools to run tests automatically.
- **Purpose:**
  - Increase efficiency.
  - Reduce human error.
  - Support continuous integration and deployment.

## Test Cases for Unit Test Design

- **Components of a Test Case:**
  - Test Case ID
  - Description
  - Test Steps
  - Test Data (Inputs)
  - Expected Results (Outputs)
- **Example Requirement:**
  - "If a user is a VIP customer and they order more than 10 items, they should not pay freight."
- **Acceptance Criteria Example:**
  - **Given** a logged-in VIP customer orders 11 items, **When** the order is confirmed, **Then** delivery is free.

## Backend API Testing with Postman or Insomnia

- **Tools:**
  - Postman
  - Insomnia
- **Features:**
  - Send HTTP requests to APIs.
  - Write and run tests on API responses.
- **Resources:**
  - Postman's documentation and learning center.

## Test-Driven Development (TDD)

- **Definition:**
  - Writing tests before writing the code to fulfill those tests.
- **Cycle:**
  - **Red:** Write a failing test.
  - **Green:** Write code to make the test pass.
  - **Refactor:** Improve the code while keeping tests passing.
- **Benefits:**
  - Improves code quality.
  - Encourages better design.
  - Provides documentation.

## 9 Excuses Why Developers Don't Test Their Code

1. "My code works fine—why should I even bother testing it?"
2. "This piece of code is untestable."
3. "I don't know what to test."
4. "Testing increases development time, and we're running out of time."
5. "The requirements are no good."
6. "This piece of code doesn't change."
7. "I can test this way faster if I do it manually."
8. "The client only wants to pay for deliverables."
9. "This piece of code is so small... it won't break anything."

## When Test-Driven Development Goes Wrong

- **Common Issues:**
  - Not following the TDD process properly.
  - Misunderstanding the purpose of tests.
  - Writing fragile tests tightly coupled to implementation.
- **Insights:**
  - TDD is valuable even when it goes wrong.
  - It's a cornerstone of Continuous Delivery, BDD, and DevOps.

## TDD = TFD + Refactoring

- **Test-First Development (TFD):**
  - Writing tests before code.
- **Refactoring:**
  - Improving code without changing its external behavior.
- **Clarification:**
  - Functional changes are not refactoring.
  - Refactoring changes the code structure, not its functionality.

## Examples of TDD – Further Study

- **Resources:**
  - Videos and tutorials on TDD.
  - Step-by-step examples in various programming languages.
- **Recommendations:**
  - Lynda.com courses on TDD.
  - Exploring TDD with practical examples.

## Testing Setup

- **Considerations:**
  - Use test databases or staging environments.
  - Create mock objects for dependencies.
- **Importance of Test Data:**
  - Vital for demonstrations and testing.
  - Poor test data can lead to failed demos.

## Adoption of TDD in Practice

- **Reality:**
  - Few organizations strictly follow TDD.
  - The key is ensuring new code is accompanied by tests.
- **Insight from Meyer (2014):**
  - The main idea is that code must be accompanied by tests.
  - Writing code and tests simultaneously is acceptable.

## TDD Empirical Study at SERL in AUT

- **Study Overview:**
  - Examined the experiences of adopting TDD in a project.
  - Compared TDD project with non-TDD projects.
- **Findings:**
  - Use of TDD was generally positive.
  - Identified benefits and challenges.

## Sharing Findings with Practitioners

- **Challenges:**
  - Communicating software engineering research effectively.
- **Design Science Lens:**
  - Helps summarize and assess research contributions.
- **Visual Abstracts:**
  - Tools like VASE (Visual Abstracts for Software Engineering).
- **Resources:**
  - DSSE.org
  - GitHub repository for VASE.

---

**Note:** This summary captures the main points from the lecture content provided, organized under appropriate headings for clarity. It includes definitions, key concepts, practices, considerations, and resources related to quality assurance, testing, and test-driven development in software engineering.

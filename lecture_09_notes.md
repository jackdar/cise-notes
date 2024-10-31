# Code Craft and Code Quality

### Week 9 Lecture

**Tony Clear**

## Overview

- **Quality of Code:**
  - Easy to change.
  - Behaves as expected (no bugs).
- **Quality of Product:**
  - Solves user problems.
  - Easy to understand and modify.
  - Predictable changes with limited impact.
  - Clear code intention.

## Techniques to Improve Code Quality

- **Test-Driven Development (TDD)**
- **Continuous Integration/Continuous Deployment (CI/CD)**
- **Pair/Mob Programming**
- **Code Reviews**
- **Coding Standards and Static Code Analysis**
  - Linters, SonarQube, etc.
- **Proper Naming and Structure**
- **Small Code Structures**

## Coding as a Craft

- **Iterative Development:**
  - Start with a sketch.
  - Add detail iteratively.
  - Revise, extend, and refine.
- **Continuous Improvement:**

  - Software is never truly finished.

- **Team Collaboration:**
  - Others need to read, understand, and modify your code.
- **Maintainability:**
  - Easier to debug and extend.
- **Future Self:**
  - You may revisit your code months later.
- **Professionalism:**
  - "Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live." — Martin Golding
- **Readability:**
  - Code is read more often than it is written.

## Writing Small and Focused Code

### Functions

- **Keep Functions Small:**
  - Rarely more than 20 lines; ideally less than 10.
- **Limit Arguments:**
  - Preferably no arguments.
- **Single Responsibility:**
  - Do one thing and do it well.
- **Example:**
  - A function that fetches, manipulates, and stores data should be split into three smaller functions.

### Classes

- **Single Responsibility Principle (SRP):**
  - Classes should have one responsibility.
- **Warning:**
  - Avoid too many tiny classes that complicate understanding and changes.

## Making Code Self-Documenting

- **Clear Intention:**
  - Code should be readable and its purpose immediately clear.
- **Avoid Excessive Comments:**
  - "Clear and expressive code with few comments is far superior to cluttered and complex code with lots of comments." — Robert C. Martin
- **Eliminate Magic Numbers:**
  - Use named constants instead of hard-coded values.
- **Use Descriptive Names:**
  - Methods and variables should reflect their purpose.

### Example Refactoring

**Before:**

```javascript
// Check to see if the employee is eligible for full benefits
if ((employee.flags & HOURLY_FLAG) && (employee.age > 65))
```

```javascript
if (employee.isEligibleForFullBenefits())
```

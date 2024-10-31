# Preparing to Iterate/Sprint

### Week 4

**Tony Clear**

## Taking Stock

- **Course Schedule:**
  - Review where we are in the course.
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
  - Build capability by developing a product collaboratively.
  - Apply a new tech stack and toolset.
  - Practice DevOps and Scrum ways of working.
  - Collaborate with a Product Owner and the team.
- **Sprints:**
  - Sprint 1: Weeks 5 and 6
  - Sprint 2: Weeks 7 and 8
  - Sprint 3: Weeks 9 and 10
- **Deliverables:**
  - Product increments submitted during tutorials in weeks 7, 9, and 11.
  - Capability and learning portfolio with evidence.

### Assignment 2: Knowledge Check (30%)

- **Individual Assessment:**
  - Submission in tutorials during weeks 1-5 (sign-off by TA).
  - Evidence portfolio and demonstration.
  - Online questions to confirm understanding of key concepts.
  - Scheduled during revision weeks.

## Agile Planning Levels

- **Reference:** Lal, R., & Clear, T. (2021). Three Levels of Agile Planning in a Software Vendor Environment.
- **Agile Planning:**
  - Emphasizes planning at multiple levels.
  - Adaptation based on team characteristics and project specifics.
  - Regular reflection and adjustment of working conventions.

## The Agile Manifesto – Many Ways of Working (WoW)

- **Key Points:**
  - Agile is a mindset with various methodologies.
  - Teams should personalize their methodology.
  - Iterative cycles of behavior and continuous improvement.

## Iterative Development Process

- **Pre-Iteration Activities:**
  - Create initial Product Backlog and Story Map (acknowledging uncertainty).
  - Develop user stories with acceptance criteria.
  - Detail understanding and design features for the next iteration only.
  - Set up architecture, tech stack, deployment, and development environment.
  - Plan for Iteration 1: Define goals and iteration backlog.
- **During Iterations:**
  - Coordinate work and maintain team alignment.
  - Regular team meetings and feedback sessions.
  - Review product increments and team processes.
  - Manage changes to requirements and risks.
  - Decide on iteration content through planning meetings.
  - Assure quality using CI/CD, pair programming, and TDD.

## User Stories as Documentation

- **Purpose of User Stories:**
  - Document user requirements.
  - Serve as units of work for:
    - Understanding user needs.
    - Splitting up work.
    - Designing product features.
    - Testing product features.
    - Organizing work order.
    - Planning iterations.
    - Monitoring progress.

## Lifecycle of User Stories

1. **Discover User Needs:**
   - Use various techniques (interviews, observations, workshops).
2. **Write High-Level User Stories (Epics):**
   - Keep them in the Product Backlog and User Story Map.
   - Define the Product Goal.
3. **Break Down into Smaller User Stories:**
   - Include acceptance criteria, success criteria, and Definition of Done.
4. **Decide on Work Order:**
   - Prioritize stories in the Product Backlog.
5. **Plan Iterations:**
   - Estimate team capacity and story sizes.
   - Select user stories for the next iteration.
6. **Develop and Monitor:**
   - Translate stories into design and code.
   - Monitor progress and adjust as needed.

## INVEST Checklist for User Stories

- **Independent:** Can the story stand alone?
- **Negotiable:** Open to change and discussion.
- **Valuable:** Provides value to the end user.
- **Estimable:** Can estimate the size and effort.
- **Small:** Sized appropriately for completion in a sprint.
- **Testable:** Can be tested and verified.

## Definition of Done

- **Criteria to Consider a User Story Complete:**
  - All tests passed (unit, integration, acceptance).
  - Code reviewed and submitted to the repository.
  - Feature deployed to the appropriate environment.
  - Documentation completed and available.
  - User Acceptance Testing (UAT) completed.
  - Any required approvals obtained.

## Using Story Maps for Planning

- **Purpose:**
  - Structure product features to model the entire product.
  - Provide context and relationships between features, user types, and their purposes.
- **Anatomy of a Story Map:**
  - **Columns:** User activities.
  - **Horizontal Slices:** Priority, importance, or frequency of use.
  - Features aligned under user activities.
  - Slices can represent scopes like MVP or sprint cycles.
- **Tools:**
  - Miro and other digital platforms for creating story maps.

## Technology Stacks and Roadmapping Strategy

- **Resources:**
  - [Aha! Roadmapping Guide](https://www.aha.io/roadmapping/guide/it-strategy/technology-stack)
  - Plan technology stack choices aligned with product goals.

## User Story Success Criteria

- **Acceptance Criteria:**
  - Define rules, tests, or behaviors for story success.
  - Common template: **Given** [context], **When** [event], **Then** [outcome].
- **Techniques:**
  - Behavior-Driven Development (BDD).
  - Acceptance Test-Driven Development (ATDD).

## Pre-Sprint Planning

### Big Picture Planning

- **Roadmap:**
  - Define sprint durations and goals.
  - In this case: 3 x 9-day sprints with specific sprint goals.
- **Release Plan:**
  - Deploy increments at the end of each sprint.
- **Focus:**
  - Delivering value to users.
  - Refining product and sprint goals.

### Selecting Work for the First Sprint

- **Estimation:**
  - Estimate story sizes using relative methods (e.g., story points, T-shirt sizes).
  - Determine team capacity (velocity) for the sprint.
- **Planning:**
  - Select user stories from the top of the Product Backlog until capacity is reached.
  - Aim for small, similarly sized stories for consistency.

## Software Project Estimation Issues

- **Challenges:**
  - Inconsistencies in estimation methods and findings.
  - Difficulty in providing reliable advice to practitioners.
- **Examples of Inconsistent Findings:**
  - Model-based vs. expert-based estimation studies showing conflicting results.
  - Regression vs. analogy methods yielding varied outcomes.
  - Cross-company data vs. local data in predictions.

## Estimation in Agile Software Development

- **Findings:**
  - Story Points are commonly used for sizing in Agile teams.
  - Collective estimation helps in reaching team consensus and reducing biases.
- **Mobile App Development:**
  - Factors like the number of screens and supported platforms affect estimation.
  - Expert judgment and function size measurement are frequently used techniques.

## Working with the Client: Useful Questions to Ask

1. What business problem are you trying to solve?
2. What's the motivation for solving this problem?
3. What would a highly successful solution do for you?
4. How can we judge the success of the solution?
5. Which business activities and events should be included or excluded?
6. Can you foresee any unexpected or adverse consequences?
7. What's a successful solution worth?
8. Who are the stakeholders that could influence or be influenced by this project?
9. Are there related projects or systems that could have an impact?

## Monitoring Progress During a Sprint

- **User Story Board:**
  - Visual tool to track the status of user stories.
  - Columns represent different stages (e.g., To Do, In Progress, Testing, Done).
- **States of User Stories:**
  - Developing
  - Testing
  - Deployment
  - Done
- **Tools:**
  - Physical boards or electronic tools like Trello, Asana, Jira, Azure DevOps.

## Pre-Sprint Design and Architecture

- **Non-Functional (Quality) Requirements:**
  - Consider performance, scalability, security, etc.
- **Tech Stack Example:**
  - Front-end: NEXT.js
  - Back-end: Nest.js on Node.js
  - Database: MongoDB

## Working as an Individual in a Team

- **Workflow:**
  - Continuous Integration (CI) practices.
  - Adherence to coding standards and code quality.
- **Non-Functional Requirements:**
  - Focus on aspects like usability and performance.

## Team Collaboration

- **Building a High-Performing Team:**
  - Build trust and share expectations.
  - Coordinate work and goals frequently.
  - Reflect on team processes and improve.
  - Foster a safe environment.
- **Practices:**
  - Break work into manageable pieces.
  - Use mob programming and collective problem-solving.
  - Regularly check progress with users or the Product Owner.

## Risk Planning

- **Identifying Risks:**
  - Not meeting quality or goals.
  - Misalignment with Product Owner expectations.
  - Unused or irrelevant product features.
  - Learning new technologies taking longer than expected.
- **Mitigation Strategies:**
  - Define quality and goals clearly.
  - Ensure code is maintainable and robust.
  - Share critical knowledge within the team.

## Expectations for Sprint 1

- **Setup:**
  - Development environment and tool pipeline for each team member.
  - Single repository in GitHub.
- **Planning:**
  - Create Product Backlog and User Story Map.
  - Develop Sprint Backlog based on estimates and team velocity.
- **Practices:**
  - Use planning poker for estimation.
  - Try mob programming.
  - Implement automated testing.
  - Practice continuous integration with frequent builds.
- **Deliverables:**
  - Releasable Product Increment deployed to the cloud.
  - Epic stories with detailed priority stories.

## Comparative Agility Assessment

- **Reference:** Williams, L., Rubin, K., & Cohn, M. (2010). Driving Process Improvement via Comparative Agility Assessment.
- **Agility Dimensions:**
  - Teamwork
  - Requirements
  - Planning
  - Technical Practices
  - Quality
  - Culture
  - Knowledge Creation
- **Purpose:**
  - Assess and improve agility across key areas.
  - Consists of 32 characteristics within the seven dimensions.

---

## Questions and Comments

Feel free to ask any questions or share your thoughts!

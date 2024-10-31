# Software Risks and Scale

### Week 10 Lecture

**Tony Clear**

## Taking Stock

- **Course Progress:**
  - Review of the course schedule.
  - Overview of assignments and iterations.
  - Reflecting on where we are now and what's coming next.

## Software and Risk - Definitions

### Traditional Focus on Project Risks

- **Primary Focus in Literature:**
  - Risk analysis and mitigation often center on project development aspects like budget and schedule overruns.
  - Less emphasis on satisfying the customer by meeting technical requirements.

### Definitions of Project Risk

- **Henry (2004):**

  - _"An event, development, or state in a software project that causes damage, loss, or delay."_

- **Schwalbe (2004):**
  - _"Problems that might occur on the project and how they might impede project success."_

### Limitations of Traditional Risk Analysis

- **Narrow Focus:**

  - Emphasis on quantifiable risks related to project development (time, budget).
  - Often excludes qualitative risks and broader stakeholder considerations.

- **Result:**
  - Risks to extra-project stakeholders may be underestimated or ignored.
  - Tunnel vision can lead to overlooking key stakeholders, affecting requirements and implementation.

## Software and Risk – Traffic Control Scenario

### Overview of the Project

- **Objective:**
  - Develop traffic control software to direct approaching traffic into the least congested lanes on a multi-lane bridge.
  - Aim to facilitate maximum and continuous traffic flow, especially during rush hours.

### Identified Stakeholders

- **Vehicle Drivers:**

  - Those traversing the bridge.

- **Bridge Maintenance Personnel:**

  - Responsible for the upkeep and safety of the bridge.

- **City Traffic Authority:**
  - Manages traffic flow and infrastructure.

### Success Criteria Defined

- **System Performance:**

  - Works well in its context.
  - Does not promote vehicle accidents.

- **Project Management:**
  - Delivered on time.
  - Within budget.
  - Accurate cost/benefit analysis showing reasonable return on investment.

### Unexpected Outcome

- **Despite meeting all the above conditions, the system was judged a failure.**

- **Question:**
  - Why was the system considered a failure despite meeting its success criteria?

## Software and Risk - Traffic Control Gone Wrong

### System Failure During Emergency

- **Scenario:**

  - An emergency nuclear disaster evacuation exercise required the system to manage heavy traffic loads continuously for 8 hours.

- **System Behavior:**

  - In the eighth hour, the software changed lane directions for lanes already filled with cars.

- **Consequences:**
  - Misdirection and accidents occurred.
  - The bridge was clogged for almost 20 hours.
  - Significant delays and safety hazards were introduced.

### Technical Cause of Failure

- **Crystal Clock Issue:**

  - The clock used for timing decisions would gradually go out of synchronization after 7 or more hours of continuous use.
  - This led to incorrect timing decisions by the software.

- **Developer Awareness:**
  - The developer was fully aware of this problem.
  - It was a known issue that required attention.

## Software and Risk – Cold Reboot Needed?

### Developer's Mitigation Strategy

- **User Manual Warning:**

  - To reset the clock and avoid synchronization issues, the developer specified in the user manual that the software should be briefly stopped and restarted after 6 hours of continuous heavy traffic loads.

- **Assumption:**
  - The users (traffic authority personnel) would read the manual and follow the instructions to reboot the system as needed.

### Decision Rationale

- **Meeting Constraints:**

  - To meet schedule and budget constraints, the developers opted for a documentation fix rather than implementing a software solution to address the clock issue.

- **Focus on Project Goals:**
  - Emphasized delivering the system on time, within budget, and satisfying the immediate customer requirements.
  - Prioritized project development risks over operational risks.

## Software and Risk – Documentation Fix?

### Narrowing of Risk Focus

- **Project Risk Analysis:**

  - Focused primarily on risks impacting development goals (time, budget, customer satisfaction).

- **Exclusion of Broader Risks:**

  - Did not adequately consider operational risks and the potential impact on end-users and other stakeholders during extended use.

- **Emphasis in Literature:**
  - Many software development textbooks and risk management articles reinforce this narrow focus on development risks.

### Implications

- **Underestimation of Risks:**

  - Ignoring qualitative risks and the needs of extra-project stakeholders can lead to significant failures, as seen in the traffic control scenario.

- **Ethical Considerations:**
  - Responsibility to consider the safety and well-being of all stakeholders, not just project delivery metrics.

## Software and Risk – All Stakeholders?

### Need for Broader Risk Analysis

- **Stakeholder Identification:**

  - Essential to identify all stakeholders, including those indirectly affected by the software.

- **Quotation from Schmidt et al. (2001):**

  - _"Failure to identify all stakeholders: Tunnel vision leads project management to ignore some of the key stakeholders in the project, affecting requirements, and implementation, etc."_

- **Recommendation:**

  - Project risk analysis must expand beyond traditional methods to include a broader scope of risks and stakeholders.
  - Consider both quantitative and qualitative risks.

- **Ethical Responsibility:**
  - Developers have a duty to foresee potential negative impacts on all stakeholders and address them appropriately.

## Software and Risk – SoDIS (Software Development Impact Statement)

### Introduction to SoDIS

- **Purpose:**

  - A practical mechanism for ethical risk assessment in software development.
  - Helps identify and mitigate risks that traditional risk analysis might overlook.

- **Components:**
  - Systematically identifies stakeholders and potential impacts.
  - Evaluates risks associated with software decisions.
  - Encourages ethical considerations in risk management.

### Stakeholder Analysis

- **Identifying All Stakeholders:**

  - Direct Stakeholders:
    - Users, customers, developers.
  - Indirect Stakeholders:
    - Those affected by the software's operation, such as the general public, regulatory bodies, etc.

- **Understanding Stakeholder Concerns:**
  - Elicit concerns related to safety, privacy, security, usability, and other factors.

### SoDIS Inspection Process

1. **Define the Project:**

   - Clearly understand the project's goals, scope, and context.

2. **Identify Stakeholders:**

   - Create a comprehensive list of all stakeholders.

3. **Elicit Stakeholder Concerns:**

   - Engage with stakeholders to understand their needs and potential impacts.

4. **Identify Ethical Issues:**

   - Analyze the project for potential ethical dilemmas or conflicts.

5. **Assess Risks:**

   - Evaluate the likelihood and impact of identified risks on each stakeholder.

6. **Develop Mitigation Strategies:**

   - Propose solutions to minimize or eliminate risks.
   - Consider alternative designs or additional features.

7. **Document Findings:**

   - Create a Software Development Impact Statement outlining the analysis and decisions.

8. **Review and Iterate:**
   - Revisit the SoDIS throughout the project as new risks or stakeholders emerge.

### Benefits of SoDIS

- **Comprehensive Risk Management:**

  - Ensures all potential risks are considered.

- **Ethical Decision-Making:**

  - Incorporates ethical considerations into project planning.

- **Stakeholder Engagement:**

  - Promotes open communication with stakeholders.

- **Improved Project Outcomes:**
  - Reduces the likelihood of project failures due to unforeseen risks.

## Software and Risk – Security Risk Lifecycle

### Lifecycle Phases

1. **Risk Identification:**

   - Recognize potential security risks early in the development process.

2. **Risk Assessment:**

   - Evaluate risks in terms of likelihood and potential impact.
   - Prioritize risks based on severity.

3. **Risk Mitigation:**

   - Implement strategies to reduce or eliminate risks.
   - Includes designing secure code, implementing security controls, etc.

4. **Risk Monitoring:**

   - Continuously observe risks throughout the project lifecycle.
   - Update risk assessments as new threats emerge.

5. **Risk Communication:**

   - Keep all stakeholders informed about risks and mitigation efforts.

6. **Risk Review:**
   - Regularly review the effectiveness of risk management strategies.
   - Learn from incidents to improve future practices.

### Importance in Software Development

- **Proactive Approach:**

  - Anticipate and address risks before they become issues.

- **Regulatory Compliance:**

  - Meet legal and industry standards for security and risk management.

- **Trust and Reputation:**
  - Protect the organization's reputation by preventing security breaches.

## Concluding: Software Projects – Student Projects & Risks

### Recent Research on Student Projects and Risk Management

- **Studies by New Zealand Researchers (Kirk et al., 2022; 2024):**

  - Focused on incorporating risk management into student group projects.

- **Purpose:**
  - To understand how risk management affects project outcomes in educational settings.
  - To develop low-overhead risk management frameworks suitable for student projects.

### Findings

- **Impact of Poor Risk Management:**

  - Teams with inadequate risk management strategies tend to perform worse.
  - Higher likelihood of encountering significant issues within the team.

- **Instructor Intervention:**

  - Teams with poor risk practices more frequently required instructor assistance to address problems.

- **Benefits of Risk Frameworks:**
  - Improved team performance.
  - Better project outcomes.
  - Enhanced learning experiences for students.

### Identified Risk Categories

1. **Communication Risks:**

   - Miscommunication or lack of communication among team members.
   - Language barriers or differing communication styles.

2. **Technical Risks:**

   - Insufficient technical skills or experience.
   - Challenges with new technologies or tools.

3. **Scheduling Risks:**

   - Poor time management.
   - Conflicting commitments (e.g., other courses, work).

4. **Scope Risks:**

   - Unclear project requirements.
   - Scope creep or changes in project objectives.

5. **Stakeholder Risks:**

   - Not adequately considering client needs or expectations.
   - Lack of feedback from supervisors or clients.

6. **Team Dynamics Risks:**

   - Conflicts within the team.
   - Uneven workload distribution.

7. **Resource Risks:**
   - Limited access to necessary resources (software, hardware).

### Conclusions and Recommendations

- **Importance of Risk Management Education:**

  - Teaching students about risk identification, assessment, and mitigation prepares them for real-world projects.

- **Implementing Risk Frameworks:**

  - Even low-overhead risk management processes can significantly improve project outcomes.

- **Active Monitoring:**

  - Regular check-ins and updates on risk status help prevent issues from escalating.

- **Instructor Support:**
  - Educators should guide students in risk management practices and intervene when necessary.

## References

- **Gotterbarn, D., & Rogerson, S. (2005).** Responsible Risk Analysis for Software Development: Creating the Software Development Impact Statement. _Communications of the AIS_, 15, 730-750.

- **Gotterbarn, D., Clear, T., & Kwan, C. (2008).** A Practical Mechanism for Ethical Risk Assessment - A SoDIS Inspection. In K. Himma & H. Tavani (Eds.), _The Handbook of Information and Computer Ethics_ (pp. 429-472). John Wiley & Sons.

- **Kirk, D., Luxton-Reilly, A., & Tempero, E. (2022).** Refining a Risk Framework for Student Group Projects. _Proceedings of the 22nd Koli Calling International Conference on Computing Education Research_, Koli, Finland. https://doi.org/10.1145/3564721.3564730

- **Kirk, D., Luxton-Reilly, A., Tempero, E., Crow, T., Denny, P., Fowler, A., Hooper, S., Meads, A., Shakil, A., & Singh, P. (2024).** Educator Experiences of Low Overhead Student Project Risk Management. _Proceedings of the 26th Australasian Computing Education Conference_.

**Key Takeaways:**

- **Holistic Risk Management:**

  - Software projects must consider risks beyond project development, including operational, ethical, and stakeholder-related risks.

- **Importance of Ethical Considerations:**

  - Developers have a responsibility to anticipate and mitigate risks that could harm stakeholders.

- **Stakeholder Engagement:**

  - Identifying and involving all stakeholders can prevent failures and improve project success.

- **Educational Implications:**

  - Incorporating risk management into education prepares students for professional practice.

- **Continuous Improvement:**
  - Regularly reviewing and updating risk management strategies is essential for adapting to new challenges.

**Note:** Effective software risk management requires a comprehensive approach that goes beyond traditional project constraints. By considering the impacts on all stakeholders and incorporating ethical risk assessment tools like SoDIS, developers can create software that not only meets technical requirements but also serves the broader needs of society. Educators play a crucial role in instilling these practices in future software engineers.

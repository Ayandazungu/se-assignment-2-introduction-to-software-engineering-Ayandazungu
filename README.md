[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15230690&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?

"Software engineering is a systematic collection, analysis of and study of the systematic way of developing software".

It is a detailed approach consisting of a Philosophy, Techniques, Methodologies and Tools to handle the Software Systems.

Software engineering, on the other hand, covers the process of software development in full, from requirements gathering to design, implementation, testing, and maintenance, while traditional programming focuses only on the coding aspect of programming.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

1. Planning: This phase consists of project planning, feasibility study, resource allocation, and risk assessment. This legwork establishes the basic building blocks of the project by setting down the scope and aims of what you want to achieve.

2. Collecting & analyzing beta: to prepare detail requirement list which goes to the next phase.

3. Design: This is the part where the requirements are transformed into architectural and detailed design and includes system design, database design, and user interface design.

4. Implementation: This consists of the actual coding of the software components as stately designed. This phase transforms design documents into runnable code.

5. Testing: It is the process of evaluating a system or its components with the intent to find whether it satisfies the specified requirements or not and identifies any defects to ensure that the product is defect free. This encompasses unit integration, system and acceptance testing fix.

6. Deployment: Deploying the software into the production environment to be used by the end-users, This part includes a lot of things like installation and setup, initial support etc.

7. Maintenance: Post deployment activities to address bugs and performance, add new requirements. Corrective, Adaptive, Preventive and Perfective Maintenance.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Key Differences

1. Process Structure:

Agile: Iterative and incremental, allowing continuous integration and delivery.
Waterfall: Linear and sequential, with distinct, non-overlapping phases.

2. Flexibility:

Agile: Highly flexible, accommodating changes at any stage of the project.
Waterfall: Rigid, with limited ability to incorporate changes once a phase is completed.

3. Documentation:

Agile: Emphasizes working software over comprehensive documentation but maintains necessary records.
Waterfall: Heavy reliance on detailed documentation throughout the project lifecycle.

4. Customer Involvement:

Agile: Continuous involvement of the customer throughout the development process.
Waterfall: Limited customer involvement after the initial requirements phase.

5. Project Delivery:

Agile: Delivers functional software increments at the end of each sprint, providing early and continuous delivery.
Waterfall: Delivers the final product only at the end of the development cycle.

Preferred Scenarios:

Agile:

Dynamic Requirements: Projects where requirements are expected to change frequently or are not well-defined from the beginning.

Customer Involvement: Projects that benefit from continuous user feedback and iterative improvement.

Quick Market Release: When a quick release to market with subsequent iterations is advantageous.

Complex and Innovative Projects: Suitable for projects involving innovation or where the final outcome is not clearly defined.

Waterfall:

Well-Defined Requirements: Projects where requirements are well understood, stable, and unlikely to change.

Predictable Outcomes: Suitable for projects with predictable outcomes where each phase can be planned in detail.

Regulated Industries: Projects in industries with strict regulatory requirements that necessitate extensive documentation and predefined processes.

Smaller, Low-Risk Projects: Projects that are relatively small in scope and have low risk associated with changing requirements.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements Engineering is the process of systematically identifying, documenting, and managing the requirements of a software system. It aims to ensure that the final product meets the needs and expectations of its users and stakeholders.

Process:

1. Elicitation:

Gathering requirements from stakeholders through interviews, surveys, workshops, observations, and other techniques.
Identifying functional and non-functional requirements.

2. Analysis:

Analyzing and prioritizing requirements to resolve conflicts, ensure feasibility, and determine their impact on the system.
Creating models to represent requirements (e.g., use case diagrams, user stories).

3.Specification:

Documenting the requirements in a clear, detailed, and unambiguous manner.
Producing artifacts such as Software Requirements Specification (SRS) documents.

4.Validation:

Ensuring the documented requirements accurately reflect the stakeholders' needs.
Conducting reviews, inspections, and validation sessions with stakeholders.

5. Management:

Continuously managing and tracking changes to the requirements throughout the project lifecycle.
Ensuring that any changes are assessed for impact and are agreed upon by stakeholders.

Importance:

1. Alignment with Stakeholder Needs: Ensures that the final product aligns with the needs and expectations of stakeholders.

2. Risk Mitigation: Identifies potential issues early in the development process, reducing the risk of project failure.

3. Clear Communication: Provides a clear and detailed understanding of the project requirements to all team members and stakeholders, facilitating better planning and execution.

4. Scope Management: Helps in managing project scope by clearly defining what is to be included in the project, preventing scope creep.

5. Quality Assurance: Ensures that the developed software meets the required quality standards and performs as expected.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity is a fundamental design principle in software engineering that involves dividing a software system into distinct, self-contained units called modules. Each module encapsulates a specific piece of functionality and interacts with other modules through well-defined interfaces. The aim of modularity is to manage complexity by breaking down a large system into smaller, manageable parts.

How Modularity Improves Maintainability:

1. Easier Debugging and Testing:

Because each module is self-contained, it can be developed, tested, and debugged independently. This isolation simplifies identifying and fixing issues within a specific module.
Unit testing can be more effectively applied to individual modules, ensuring that each module functions correctly before integration.

2. Simplified Updates and Modifications:

Changes or updates can be made to a single module without affecting the entire system. This localized impact reduces the risk of introducing new bugs and simplifies regression testing.
Developers can focus on one module at a time, making the maintenance process more manageable and less error-prone.

3. Improved Code Readability and Understanding:

Smaller, well-defined modules are easier to understand and navigate than a large monolithic codebase. This improved readability helps new developers quickly grasp the system’s structure and functionality.
Clear separation of concerns allows developers to focus on specific functionalities without being overwhelmed by unrelated parts of the system.

4. Reusability:

Modules can often be reused across different projects or within different parts of the same project. This reuse can save development time and ensure consistency.
Reusable modules can form the basis of a library or framework, providing standardized solutions to common problems.

How Modularity Improves Scalability:

1. Parallel Development:

Different teams or developers can work on separate modules simultaneously without interfering with each other’s work. This parallelism can speed up the development process and allow for better resource allocation.
Teams can specialize in particular modules, enhancing productivity and expertise.

2. Incremental Integration:

New features can be added incrementally by developing new modules or extending existing ones. This incremental approach allows for continuous integration and delivery, accommodating growing system requirements.
Systems can evolve gradually, scaling up in functionality without the need for large-scale overhauls.

3. Flexible Architecture:

A modular system can be more easily adapted to changing requirements. If a new technology or design pattern becomes relevant, only the affected modules need to be updated.
The ability to replace or upgrade individual modules without overhauling the entire system supports long-term scalability.

4. Load Distribution:

In distributed systems, different modules can be deployed across multiple servers or nodes. This distribution can balance the load more effectively, improving performance and scalability.
Microservices architecture is an example of modularity that enhances scalability by allowing each service (module) to be scaled independently.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Software testing is a crucial process in software development that ensures the quality, functionality, and reliability of the software. Different levels of software testing are performed at various stages of the development lifecycle to identify and fix issues early and ensure that the software meets its requirements.

1. Unit Testing
Definition: Unit testing involves testing individual components or units of code, such as functions or methods, to ensure they work correctly in isolation.

Purpose:

Verify that each unit performs as expected.
Detect and fix bugs early in the development process.
Facilitate code refactoring and maintenance.
Tools: JUnit (Java), NUnit (.NET), PyTest (Python), Jasmine (JavaScript).

Example: Testing a function that calculates the sum of two numbers to ensure it returns the correct result for various input values.

2. Integration Testing
Definition: Integration testing focuses on verifying the interactions between different units or modules of the software. It ensures that integrated components work together as intended.

Purpose:

Detect issues that arise when modules interact.
Ensure data flows correctly between integrated units.
Validate the interactions of external systems and interfaces.
Tools: JUnit (Java), NUnit (.NET), PyTest (Python), Postman (API testing).

Example: Testing the interaction between a user authentication module and a database module to ensure that user login works correctly.

3. System Testing
Definition: System testing involves testing the complete and integrated software system to verify that it meets the specified requirements.

Purpose:

Validate the end-to-end functionality of the system.
Ensure the system performs well in various environments and scenarios.
Test the system’s compliance with the functional and non-functional requirements.
Tools: Selenium (web applications), JMeter (performance testing), TestComplete (automated testing).

Example: Testing an e-commerce application’s entire workflow, from user registration and product search to checkout and payment processing.

4. Acceptance Testing
Definition: Acceptance testing, also known as User Acceptance Testing (UAT), involves verifying that the software meets the business requirements and is ready for deployment. It is typically performed by end-users or stakeholders.

Purpose:

Ensure the software meets the users' needs and expectations.
Validate that the system is ready for production.
Identify any issues that were not caught during previous testing phases.
Tools: TestRail (test management), QAComplete (test management), Zephyr (test management).

Example: End-users testing a new accounting software to ensure it meets all their business needs and is ready for use in their daily operations.

Importance of Testing in Software Development

Quality Assurance:

Testing ensures that the software meets the required quality standards and performs as expected.
Identifies defects and issues early in the development process, reducing the cost and effort required to fix them.

Risk Mitigation:

Helps identify potential risks and vulnerabilities in the software, allowing developers to address them before they become critical issues.
Reduces the likelihood of system failures and crashes in the production environment.

Improved User Experience:

Ensures that the software is user-friendly and meets the needs and expectations of its users.
Helps identify and fix usability issues, enhancing the overall user experience.

Compliance and Reliability:

Verifies that the software complies with relevant standards, regulations, and requirements.
Ensures the reliability and stability of the software in various environments and use cases.

Cost Efficiency:

Detecting and fixing defects early in the development process is less expensive than addressing them after the software has been deployed.
Reduces the costs associated with post-release maintenance and support.

Continuous Improvement:

Provides feedback to developers, allowing them to improve their code quality and development practices.
Facilitates continuous integration and delivery by ensuring that new changes do not introduce new defects.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version Control Systems (VCS) are tools that help manage changes to source code and other documents over time. They keep track of every modification made to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

Importance of Version Control Systems in Software Development

1. Collaboration:

Facilitates teamwork: Multiple developers can work on the same project simultaneously without overwriting each other’s changes.
Branching and merging: Allows developers to work on different features or bug fixes in separate branches and then merge them into the main codebase.

2. History and Documentation:

Track changes: Every change made to the code is recorded with details about who made the change, when it was made, and why it was made (through commit messages).
Audit trail: Provides a detailed history of the project’s development, which is useful for auditing and compliance purposes.

3. Backup and Restore:

Data recovery: In case of accidental data loss, changes can be rolled back to previous versions, ensuring no work is permanently lost.
Snapshots: Each version of the project is saved, so the state of the project at any point in time can be restored.

4. Conflict Resolution:

Identify conflicts: Helps identify and resolve conflicts when multiple developers change the same part of the code simultaneously.
Merge tools: Provides tools to help merge conflicting changes and ensure a smooth integration.

5. Release Management:

Tagging and releases: Specific points in the project history can be tagged as releases, making it easy to manage and track different versions of the software.
Stable versions: Ensures that stable versions can be released while ongoing development continues in parallel branches.

6. Branching Strategies:

Feature branches: Developers can create branches for new features, which can be developed and tested independently before merging into the main branch.
Hotfix branches: Critical fixes can be developed in isolation and merged back into the main branch and relevant release branches.

Popular Version Control Systems and Their Features
1. Git:

Distributed VCS: Each developer has a complete copy of the repository, including its full history.

Speed and Performance: Git is known for its speed and efficiency in handling large projects.

Branching and Merging: Advanced branching and merging capabilities allow for flexible workflows.

Tools and Integration: Integrates with many tools and services, including GitHub, GitLab, and Bitbucket.

Community and Support: Extensive community support and documentation.

2. Subversion (SVN):

Centralized VCS: All code changes are tracked in a central repository.

Atomic Commits: Ensures that commits are atomic, meaning they are all-or-nothing.

Directory Versioning: Tracks changes to directory structures, not just file contents.

Access Control: Fine-grained access control to different parts of the repository.

Integration: Integrates well with various development environments and CI/CD tools.

3. Mercurial:

Distributed VCS: Similar to Git, each developer has a complete copy of the repository.

Ease of Use: Designed to be easy to learn and use.

Performance: Efficient handling of large projects and repositories.

Branching: Supports lightweight branching and merging.

Cross-platform: Works well across different operating systems.

4. Perforce (Helix Core):

Centralized VCS: Focuses on performance and scalability for large projects.

File Locking: Provides file locking mechanisms to prevent conflicts on large binary files.

Scalability: Handles very large repositories and high transaction volumes efficiently.

Integration: Integrates with various development tools and pipelines.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

A Software Project Manager (SPM) is responsible for overseeing the planning, execution, and completion of software development projects. They ensure that projects are delivered on time, within budget, and to the specified quality standards. The role involves coordinating teams, managing resources, and mitigating risks to achieve project goals.

Key Responsibilities of a Software Project Manager

1. Project Planning:

Defining Scope: Determine the project's scope, goals, and deliverables in collaboration with stakeholders.
Creating a Project Plan: Develop a detailed project plan outlining tasks, timelines, resources, and milestones.

2. Resource Management:

Allocating Resources: Assign appropriate resources, including team members, tools, and budget, to different tasks.
Monitoring Resource Utilization: Ensure efficient use of resources throughout the project lifecycle.

3. Team Coordination:

Leading the Team: Provide leadership and guidance to the project team, fostering a collaborative and productive environment.
Communication: Facilitate clear and consistent communication within the team and with stakeholders.

4. Risk Management:

Identifying Risks: Identify potential risks that could impact the project’s success.
Mitigating Risks: Develop and implement strategies to mitigate identified risks.

5. Scheduling and Time Management:

Setting Timelines: Establish realistic project schedules with clear deadlines.
Tracking Progress: Monitor the progress of tasks against the schedule and adjust as necessary.

6. Budget Management:

Budget Planning: Develop and manage the project budget, ensuring costs are kept within agreed limits.
Cost Control: Track expenditures and control costs throughout the project.

7. Quality Assurance:

Defining Quality Standards: Establish quality standards and ensure they are met throughout the project.
Quality Control: Implement processes for regular quality checks and testing.

8. Stakeholder Management:

Engaging Stakeholders: Maintain regular communication with stakeholders to keep them informed and involved.
Managing Expectations: Ensure stakeholders’ expectations are realistic and aligned with project goals.

9. Documentation and Reporting:

Maintaining Documentation: Keep detailed records of project activities, decisions, and changes.
Reporting Progress: Provide regular status reports to stakeholders on project progress, risks, and issues.

10. Change Management:

Handling Changes: Manage changes to the project scope, schedule, and budget in a controlled manner.
Impact Analysis: Assess the impact of changes and ensure they are documented and communicated.

Challenges Faced in Managing Software Projects

1. Scope Creep:

Definition: Uncontrolled changes or continuous growth in project scope.
Mitigation: Clearly define and document the scope at the project’s outset and manage changes through a formal change control process.

2. Resource Constraints:

Issue: Limited availability of skilled team members, tools, and budget.
Solution: Efficient resource planning and prioritization, and securing additional resources if necessary.

3. Time Management:

Issue: Meeting project deadlines and managing time effectively.
Solution: Develop a realistic project schedule, monitor progress regularly, and make adjustments as needed.

4. Communication Breakdown:

Issue: Ineffective communication among team members and stakeholders.
Solution: Establish clear communication channels and regular update meetings.

5. Risk Management:

Issue: Identifying and managing potential risks that could impact the project.
Solution: Implement a robust risk management plan and continually assess and address risks.

6. Quality Assurance:

Issue: Ensuring the final product meets quality standards and stakeholder expectations.
Solution: Implement thorough testing and quality control processes throughout the development cycle.

7. Stakeholder Engagement:

Issue: Keeping stakeholders engaged and managing their expectations.
Solution: Maintain regular communication, involve stakeholders in key decisions, and manage expectations realistically.

8. Technology Challenges:

Issue: Dealing with rapidly changing technology and integrating new tools.
Solution: Stay informed about technological trends and provide training for the team.

9. Team Dynamics:

Issue: Managing diverse team members and resolving conflicts.
Solution: Foster a collaborative team environment and address conflicts promptly and effectively.

10. Adaptability to Change:

Issue: Adapting to changes in project requirements, technology, and market conditions.
Solution: Maintain flexibility in project planning and encourage a culture of adaptability within the team.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance refers to the process of modifying and updating software applications after their initial deployment. These modifications may include fixing bugs, improving performance, adding new features, and adapting the software to new environments or technologies. The goal is to ensure the software continues to function correctly and efficiently over time.

Types of Maintenance Activities

1. Corrective Maintenance:

Definition: Involves identifying and fixing defects or bugs discovered in the software after it has been released.
Examples: Fixing a bug that causes the application to crash, resolving a security vulnerability, or correcting an incorrect calculation.

2. Adaptive Maintenance:

Definition: Modifications made to the software to keep it usable in a changing environment. This includes adapting the software to new operating systems, hardware, or regulatory requirements.
Examples: Updating software to be compatible with a new version of the operating system, adapting to changes in tax laws, or ensuring compatibility with new hardware.

3. Perfective Maintenance:

Definition: Enhancements made to improve the performance, maintainability, or other attributes of the software, as well as adding new features to meet user requirements.
Examples: Optimizing code to improve application performance, refactoring code for better maintainability, adding new functionalities based on user feedback.

4. Preventive Maintenance:

Definition: Involves making changes to the software to prevent potential issues in the future. This includes activities to increase software reliability and reduce the risk of future problems.
Examples: Regularly updating libraries and dependencies to avoid future compatibility issues, implementing security patches to protect against potential vulnerabilities, and conducting regular code reviews to identify potential issues.

Importance of Maintenance in the Software Lifecycle

1. Ensures Continued Functionality:

As environments change (e.g., operating systems, hardware), software must be updated to ensure it continues to function correctly. Adaptive maintenance is crucial to maintaining software usability in new environments.

2. Enhances Performance and Efficiency:

Through perfective maintenance, software can be optimized to improve performance, making it faster and more efficient. This helps to meet evolving user expectations and demands.

3. Increases Software Longevity:

Regular maintenance extends the life of software by ensuring it remains functional and relevant over time. This can delay the need for costly replacements or complete rewrites.

4. Maintains Security:

Corrective and preventive maintenance activities are essential to identifying and fixing security vulnerabilities. Regular updates help protect software from new threats and ensure compliance with security standards.

5. Improves User Satisfaction:

By fixing bugs, adding new features, and improving performance, maintenance enhances the overall user experience, leading to higher user satisfaction and retention.

6. Reduces Long-Term Costs:

Regular maintenance can prevent major issues that would be more costly to fix if left unattended. It is often more cost-effective to address small issues continuously than to deal with significant problems later.

7. Adapts to Changing Requirements:

Software needs to evolve to meet new user requirements and business needs. Perfective and adaptive maintenance activities ensure the software stays aligned with these changing demands.

8. Supports Compliance and Standards:

As regulations and standards evolve, software must be updated to ensure compliance. Adaptive maintenance ensures that the software meets the latest regulatory requirements, avoiding legal issues and fines.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Software engineers often encounter various ethical challenges due to the profound impact their work can have on society. Here are some common ethical issues they might face:

1. Privacy and Data Protection:

Issue: Ensuring the privacy and security of user data. Misuse or mishandling of personal information can lead to breaches, identity theft, and loss of trust.
Example: Collecting more data than necessary or failing to secure user data properly.

2. Intellectual Property and Plagiarism:

Issue: Respecting intellectual property rights and avoiding plagiarism. Using code or software without proper licensing or acknowledgment can lead to legal issues and damage reputations.
Example: Copying code from open-source projects without adhering to licensing terms.

3. Algorithmic Bias and Fairness:

Issue: Developing algorithms that are unbiased and fair. Unintended biases in algorithms can result in unfair treatment of certain groups or individuals.
Example: An AI recruiting tool that unfairly discriminates against candidates based on gender or race due to biased training data.

4. Security and Vulnerability Disclosure:

Issue: Balancing the need to disclose software vulnerabilities with the potential risks of exploitation. Responsible disclosure involves notifying affected parties and allowing time to fix issues before publicizing them.
Example: Discovering a major security flaw and deciding whether to inform the public immediately or give the company time to address the issue first.

5. User Consent and Transparency:

Issue: Ensuring users are fully informed about how their data will be used and obtaining their consent. Lack of transparency can lead to mistrust and legal consequences.
Example: Implementing hidden data collection features without informing users or getting their consent.

6. Impact on Society:

Issue: Considering the broader societal impact of software. Software engineers must evaluate how their work affects various aspects of society, including employment, mental health, and social interactions.
Example: Developing addictive features in social media applications that contribute to mental health issues.

7. Workplace Ethics:

Issue: Navigating ethical dilemmas within the workplace, such as conflicts of interest, whistleblowing, and adherence to ethical codes of conduct.
Example: Being pressured to cut corners on quality to meet deadlines or budget constraints.
Ensuring Adherence to Ethical Standards

Software engineers can adopt several practices to ensure they adhere to ethical standards:

1. Education and Training:

Continuous Learning: Stay informed about ethical standards, data privacy laws, and best practices through ongoing education and professional development.
Ethics Courses: Participate in ethics courses and training programs to understand the ethical implications of their work.

2. Adherence to Professional Codes of Conduct:

Follow Guidelines: Abide by established codes of conduct and ethical guidelines provided by professional organizations such as the ACM (Association for Computing Machinery) and IEEE (Institute of Electrical and Electronics Engineers).
Promote Integrity: Encourage colleagues and team members to adhere to these standards.

3. Privacy by Design:

Integrate Privacy: Incorporate privacy and data protection measures into the design and development process from the beginning.
Minimize Data Collection: Collect only the data necessary for the application’s functionality and ensure it is securely stored and processed.

4. Bias and Fairness Audits:

Regular Audits: Conduct regular audits to detect and mitigate biases in algorithms and data sets.
Diverse Teams: Involve diverse teams in the development process to identify potential biases and ensure broader perspectives.

5. Transparent Communication:

User Communication: Clearly communicate to users how their data will be used and obtain their informed consent.
Disclosure: Be transparent about the limitations and potential risks of software systems.

6. Responsible Vulnerability Disclosure:

Follow Protocols: Adhere to responsible disclosure protocols by informing affected parties and providing time for fixes before publicizing vulnerabilities.
Collaborate with Security Experts: Work with security professionals to address vulnerabilities promptly.

7. Ethical Decision-Making Frameworks:

Adopt Frameworks: Use ethical decision-making frameworks to systematically evaluate the potential impacts of decisions.
Stakeholder Analysis: Consider the perspectives and interests of all stakeholders, including users, clients, and society at large.

8. Whistleblowing Policies:

Encourage Reporting: Promote a culture where ethical concerns can be reported without fear of retaliation.
Protect Whistleblowers: Ensure there are protections in place for those who report unethical practices.

References:

PLP Academy 


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].

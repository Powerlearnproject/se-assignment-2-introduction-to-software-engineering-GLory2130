[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15224108&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Is the systematic application of engineering principles,methods and tools to the development and maintenance of high quality software system
What is software engineering, and how does it differ from 
traditional programming?
software engineering implies the principles or rules to software creation, ensuring that the software created is reliable and perform it's works efficiently on machines.
Whereas, Traditional Programming focusses primarily on writing code to implemet functionalities without considering on project management,user requirements and long term maintenance.
These two differ interm of methodologies since So ftware engineering fllows the structure of software development life cycle(SDLC) unlike Traditional programming doesn't follow at all.

Software Development Life Cycle (SDLC):
Is a structured process that provides a well-structured flow of phases that help an organization to quickly produce high-quality software which is well-tested and ready for production use

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
1.Requirement gathering:gathering and analysing all the user and the system requirements needed for the software development.Documenting how the system should do and behave
2.Design:here is the part of designing the software that has to be developed by regarding the user interface design,system design,data design,developing different models and prototypes
3.Implentation:This part involve programming,debugging,intergrating models since it implies implying the specified design into lines of codes
4.Testing:The software has to be verified that it perform it works efficiently as intended.Include unit testing,system testing,intergration system and acceptance system
5.Deployment:Allow the users to access the software through installation,configuration and setting up environments
6.Maintenance:This is implied updating new features ,fixing bugs and improving performance

Agile vs. Waterfall Models:
Agile Model:Agile breaks the project into small iterations or sprints, allowing for continuous feedback and improvement.
WHILE:
Waterfall Model:Waterfall follows a strict sequence of phases, where each phase must be completed before the next begins.

Agile Model has Preferred Scenarios that are suitable for projects where requirements are expected to change frequently, such as startups or innovative projects.
WHILE:
WaterFall Model:Best for projects with well-defined requirements and low risk of changes, such as government contracts or large enterprise systems.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Requirements Engineering:
Is the process of defining, documenting, and maintaining the requirements for a software system.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirement Engineering
Is the process of defining, documenting, and maintaining the requirements for a software sys
Software Design Principles:

Process of requirement engineering
1.Feasibility Study
2.Requirements elicitation
It is related to the various ways used to gain knowledge about the project domain and requirements. The various sources of domain knowledge include customers, business manuals, the existing software of the same type, standards, and other stakeholders of the project. The techniques used for requirements elicitation include interviews, brainstorming, task analysis.

Advantages of Requirements Engineering
1.Helps ensure that the software being developed meets the needs and expectations of the stakeholders
2.Can help identify potential issues or problems early in the development process, allowing for adjustments to be made before significant 
3.Helps ensure that the software is developed in a cost-effective and efficient manner
4.Can improve communication and collaboration between the development team and stakeholders
5.Helps to ensure that the software system meets the needs of all stakeholders.
6.Provides an unambiguous description of the requirements, which helps to reduce misunderstandings and errors.

3.Requirements specification
This activity is used to produce formal software requirement models. All the requirements including the functional as well as the non-functional requirements and the constraints are specified by these models in totality. During specification, more knowledge about the problem may be required which can again trigger the elicitation process. The models used at this stage include ER diagrams, data flow diagrams(DFDs), function decomposition diagrams(FDDs), data dictionaries, etc.

4.Requirements for verification and validation
Verification: It refers to the set of tasks that ensures that the software correctly implements a specific function. 

Validation: It refers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements. If requirements are not validated, errors in the requirement definitions would propagate to the successive stages resulting in a lot of modification and rework. The main steps for this process include:

1.The requirements should be consistent with all the other requirements i.e. no two requirements should conflict with each other.
2.The requirements should be complete in every sense.
3.The requirements should be practically achievable.


5.Requirements management
Requirement management is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. This stage takes care of the changing nature of requirements. It should be ensured that the SRS is as modifiable as possible to incorporate changes in requirements specified by the end users at later stages too. Modifying the software as per requirements in a systematic and controlled manner is an extremely important part of the requirements engineering process.


Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
 Modularity:
 is the design principle of breaking down a software system into smaller, manageable, and self-contained units (modules).
 Modularity improves maintainability in fixing issues in a small part of the system without affectibg the entire system. Also, in scalability modularity facilitates adding new features by introducing new modules without altering ones
Testing in Software Engineering:
is the process of checking the quality, functionality, and performance of a software product before launching.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
1.Unit testing is a method of testing individual units or components of a software application. It is typically done by developers and is used to ensure that the individual units of the software are working as intended. Unit tests are usually automated and are designed to test specific parts of the code.

2.Integration testing is a method of testing how different units or components of a software application interact with each other. It is used to identify and resolve any issues that may arise when different units of the software are combined. Integration testing is typically done after unit testing and before functional testing and is used to verify that the different units of the software work together as intended.

3.System testing is a type of software testing that evaluates the overall functionality and performance of a complete and fully integrated software solution. It tests if the system meets the specified requirements and if it is suitable for delivery to the end-users. This type of testing is performed after the integration testing and before the acceptance testing.

Advantages of Software Testing
1.Improved software quality and reliability.
2.Early identification and fixing of defects.
3.Improved customer satisfaction.
4.Increased stakeholder confidence.
5.Reduced maintenance costs.
6.Customer Satisfaction
7.Cost Effective
8.Quality Product
9.Low Failure


Version Control Systems:
Is a system that tracks the progress of code across the software development lifecycle and its multiple iterations – which maintains a record of every change complete with authorship, timestamp, and other details – and also aids in managing change.

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version control system:
Is a system that tracks the progress of code across the software development lifecycle and its multiple iterations – which maintains a record of every change complete with authorship, timestamp, and other details – and also aids in managing change.

Example of version control system
Local Version Control Systems: It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools. It keeps patch sets (differences between files) in a special format on disk.


Importance of version control:
  It helps the developer team to efficiently communicate and manage(track) all the changes that have been made to the source code along with the information like who made and what changes have been made. A separate branch is created for every contributor who made the changes and the changes aren’t merged into the original source code unless all are analyzed as soon as the changes are green signaled they merged to the main source code. 

Software Project Management:
is a proper way of planning and leading software projects. It is a part of project management in which software projects are planned, implemented, monitored, and controlled

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Role of project manager
1.Project planning
2.Project monitoring and control
Software Maintenance:

key responsibilities are planning, organizing, directing and controlling.

challenges  faing in project management
1.Poor communication
Strong communication is one of the keys to completing a project successfully. With well-developed written and verbal communication skills, a project manager can effectively give instructions, gather information and update stakeholders. Otherwise, their team can become confused, leading to delays

2.Unclear goals
Projects can be successful only if the team has well-defined and measurable goals to work toward. Ideally, every member of the team is aware of each project objective and the stakeholders' exact expectations concerning each. Otherwise, they may spend undue time and resources trying to accomplish something that doesn't provide the desired value.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance:
is a continuous process that occurs throughout the entire life cycle of the software system.

Several Types of Software Maintenance
1.Corrective Maintenance: This involves fixing errors and bugs in the software system.
2.Patching: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.
3.Adaptive Maintenance: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.
4.Perfective Maintenance: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.
5.Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups.

Advantages of Software Maintenance
1.Improved Software Quality: Regular software maintenance helps to ensure that the software is functioning correctly and efficiently and that it continues to meet the needs of the users.
2.Enhanced Security: Maintenance can include security updates and patches, helping to ensure that the software is protected against potential threats and attacks.
3.Increased User Satisfaction: Regular software maintenance helps to keep the software up-to-date and relevant, leading to increased user satisfaction and adoption.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Ethical Issues
1.Unethical data collection
With the shift to digital marketing, companies are exponentially valuing user data. It’s an important source to use in development. However, it’s easy to get carried away in the act of acquiring it. Customers have to be fully aware of what information they’re sharing and how it’s going to be used.

Software developers face a difficult choice regarding personal data. They have two options: develop systems that possibly abuse user data or voice concerns despite going against the project’s objectives.

2.Algorithmic bias
Computers cannot understand morality as a concept. When it is not thoroughly checked, its systems can unintentionally show bias. For instance, when it was discovered that Google’s image processing engine couldn’t adequately reflect black and brown skin tones in images, the company came under fire for allegedly fostering systematic racism.

Software developers must deliberate potential biases in developing their products. By studying social norms and analyzing their current data, they can prevent wrong assumptions in the collection and use of information.

How to avoid ethical issues:
1.Be proactive
While you work honestly when writing code, there’s no telling where it can lead to. The client and your team can easily veer away from the original purpose of your project. Throughout the process of development, think of the potential threats and misconduct that can happen. As a software engineer, you must assess the current technology you’re developing and take proactive measures to address any potential abuse and other ethical issues in software development.

2.Be accountable
You should strive to improve the integrity and reputation of the profession as a software engineer. For instance, you should avoid making false claims regarding your application that could be deceptive or misleading. Make sure you keep your employer, clients, customers, and other stakeholders in the loop by reporting software issues and other potential ethical issues in software development.

References:
1.https://www.geeksforgeeks.org/types-software-testing/
2.https://www.spiceworks.com/tech/devops/articles/what-is-version-control/
3.https://www.geeksforgeeks.org/version-control-systems/
4.https://fullscale.io/blog/ethical-issues-in-software-development/
5.https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].

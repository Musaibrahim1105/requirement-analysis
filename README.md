# requirement-analysis
## Requirement Analysis in Software Development
Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.

### What is Requirement Analysis
Requirement analysis in the SDLC is the compass that guides software through the complex terrain of the development, ensuring every steps align with your destination: a successful user-centric application. Requirement analysis is important because it helps us get rid of the costly mistake of misalignment of project and overspending.

### Why is Requirement Analysis Important?
- Cost and time estimation:facilitate accurate esimation of project cost, resources and time 
- Scope definition: clearly define the scope of the project, which helps in preventing scope creep
- Clarity and understanding: it helps in understanding what the stakeholder expect from the software reducing ambinguity

### Key Activities in Requirement Analysis
1. Requirement Gathering
- Interviews: Conducting interviews with stakeholder to gather detailed information about their needs and expectation
- Surveys/Quentionnaires: Distributing surveys to gather requirement from a larger audience
- Document Analysis: Reviewing existing documentation and system to understand current functionalities and requirements.

2. Requirement Elicitation
- Brainstorming: conducting brainstorming sessions to generate ideas and gather requirement
- Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirement

3. Requirement Documentation
- Requirement specification document: Creating detailed documents that list both functional and non-functional requirements
- User Stories: Writing users stories to describe functionalities from users perspectives
- Use Cases: creating use case diagrams to show interaction between users and the system


4. Requirement Analysis and Modeling
- Requirement Priotization: Priotizing requirement base on their importance and impact on the project
- Feasibility Analysis: Assessing the feasibility of requirement in terms of technical, financial and time constraint
- Modeling: Creating models (e.g data flow diagrams, entity relational diagrams) to visualise and analyze requirement

5. Requirement Validation
- Review and approval: Reviewing th documented requirement with the stakeholders to ensure accuracy and completeness
- Acceptance criteria: defining clear acceptance criteria for each requirement to ensure they meet the expected standards
- Traceability: Establishing traceability matrices to ensure all requirement are addressed during development and testing

### Types of Requirements
- Functional Requirement: Describe what the system should do in other words, they define the basic system behaviour under specific conditions e.g user authentication, property search, booking system and user registration.
- Non-Functional requirements: Describe how the system should perform. e.g performance, security, maintenance, scalability and usability.

## Use Case Diagrams
It is the visual represention f interactions between users and the system.
- what are use case diagrams?
they show how different users (actors) interact with the system to achieve specific goals (use case).
- creating use case diagrams:
identify actors (e.g guest, registered users, admin); define use case (e.g search properties, book properties, book property, manage listing); draw interaction between use cases.
- Benefits of Use Case Diagrams:
provide a clear visual represention of system functionalities, help in identifying and organising system requirements, facilitate communication amongs stakeholders and development team 
![image alt](https://github.com/Musaibrahim1105/requirement-analysis/blob/d64ba3103f9970882fee07b1ff946b305152cb78/alx-booking-uc.png.png)

## Acceptance Criteria
acceptance criteria are conditions that a feature must meet to be accepted by the stakeholder, acceptance criteria ensure all parties have a clear understanding of feature requirements, provide a basis of validation, help in maintaining quality and meeting user expectation.

1. Successful Checkout After Booking
Given the user has an active booking
When the user clicks the "Check Out" button
Then the system should mark the booking as "Checked Out"
And display a confirmation message
2. Final Charges Are Calculated
Given the user is checking out
When the checkout is processed
Then the system should calculate total charges including taxes and any extra services used
And display a final summary of the charges
3. Payment is Completed Before Final Checkout
Given the user has unpaid charges
When the user initiates checkout
Then the system should prompt the user to complete payment
And only allow checkout after payment is confirmed
4. Prevent Checkout Without Active Booking
Given the user has no current booking
When the user tries to access the checkout page
Then the system should display an error message: "No active booking to check out from"
5. Booking Slot Becomes Available After Checkout
Given the checkout is successful
Then the associated booking slot should become available for new users

# requirement-analysis

## Requirement Analysis in Software Development

This repository is dedicated to exploring the process of requirement analysis in the software development lifecycle (SDLC). This process is crucial for ensuring all stakeholders have a clear, shared understanding of how the system will operate and what its projected performance will be.

## What is Requirement Analysis?
Requirement Analysis (or Requirements Engineering) is the process of defining, documenting, and maintaining the requirements for a software system. It acts as the  bridge between the business needs of stakeholders and the detailed technical "blueprint" that developers will use to build the software.
It answers the fundamental questions:
* **What** should the system do? (Functional requirements)
* **How well** should the system do it? (Non-functional requirements)
* **What constraints** must it operate under? (Business rules, technical constraints, etc.)

## Why is Requirement Analysis Important?
1.  Helps define the scope of the project to prevent **scope creep**.
2.  Provides a solid foundation on which the design and development of the system can begin.
3.  Ensures the team can accurately estimate the project cost, resources, and development time.
4.  It helps to make sure that the specified requirements match the customer's and stakeholders' expectations.
5.  **Reduces overall project cost** by catching errors and misunderstandings early. A mistake fixed in the requirements phase is 100x cheaper than fixing it after the product is built.

   ### Key Activities in Requirement Analysis
**1. Requirement Gathering:**
This is where the requirements are gathered via various methods like interviews, questionnaires, workshops, and even document analysis.
**2. Requirement Elicitation:**
Here, ideas are generated and requirements are gathered. Finally, prototypes are created to visualize the system, and requirements are refined.
**3. Requirement Documentation:**
All functional and non-functional requirements are written down. It is in this step that user stories are written and use case diagrams are drawn.
**4. Requirement Analysis and Modelling:**
Requirements are prioritized based on importance and impact on the project. Feasibility analysis is done on the requirements based on different factors, and models are created to visualize the requirements.
**5. Requirement Validation:**
Requirements are reviewed to ensure they meet the required accuracy. Acceptance criteria are drawn up, and traceability matrices are created to ensure all requirements are addressed during development and testing.

## Types of Requirements

### Functional Requirements

Describes *what* the system does.

* **Search Properties**: The user should be able to look for a property based on price, availability, cost, and location.
* **Booking System**: Users should be able to book properties and view their booking details.
* **Payment System**: Users should be able to pay for the properties they have booked.
* **User Authentication**: The system should be able to onboard new users and provide secure registration and login for existing users.
* **Property Onboarding**: Landlords and property owners should be able to add their properties to the platform upon providing proof of ownership.

### Non-Functional Requirements

Describes the *performance* and *quality* of the system.

* **Page Load Time:** All primary pages (homepage, search results, listing details) must load fully in under 3 seconds.
* **Search Latency:** A search query with multiple filters (date, location, price) must return results in under 2 seconds.
* **Booking Transaction:** The "Confirm and Pay" action must be processed (including payment authorization) and return a confirmation to the user in under 5 seconds.
* **Fault Tolerance:** The failure of one component (e.g., a single web server or a microservice) must not cause the entire system to fail.
* **Database Scalability:** The database must support read replicas to handle the high load of search queries without slowing down booking transactions.

  ## Use Case Diagrams
Use case diagrams are a visual representation that shows how different users, called actors, interact with a system to achieve specific goals, known as use cases.
To create one, you:
1.  Identify the actors.
2.  Define the use cases.
3.  Draw the interactions between the actors and the use cases.
   ![Use case diagram](https://github.com/SirrPascal/requirement-analysis/blob/main/alx-booking-uc.png?raw=true)

## Benefits of Use Case Diagrams
* They provide a clear visual representation of the system's functionalities.
* They help identify and organize the system's requirements.
* They facilitate communication among all stakeholders and the development team.

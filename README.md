1. Introduction
This document plans the strategy, objectives, resources, and schedule for functional, security, and performance testing for the Contact List App Website from Contacts and Users to check that the system works as expected.
1.1. Objective
To validate the CRUD functionality and authentication mechanisms of the Contact List App APIs (Contacts and Users) through structured API testing aligned with Scrum methodology. The goal is to ensure each endpoint behaves correctly with valid and invalid inputs, handles errors gracefully, maintains data integrity, and adheres to basic security standards.
1.2. Background
The Contact List App provides RESTful APIs for managing user contact records. This project is conducted over a 5-day sprint simulation with two teams:
•	Team 1: Responsible for testing Contacts APIs
•	Team 2: Responsible for testing Users APIs
Testing will be performed using Postman, documented in Excel and Word, and tracked via Trello.

2. Scope
2.1. In-Scope:
2.1.1. Contacts: (Contact List Documentation ‘Contacts’ 1)
2.1.1.1. POST / Add Contact (CLD – 1.1)
2.1.1.2. GET / Get Contact List (CLD – 1.2)
2.1.1.3. GET / Get Contact (CLD – 1.3)
2.1.1.4. PUT / Update Contact (CLD – 1.4)
2.1.1.5. PATCH / Update Contact (CLD – 1.5)
2.1.1.6. DELETE / Delete Contact (CLD – 1.6)
2.1.2. Users: (Contact List Documentation ‘Users’ 2)
2.1.2.1. POST / Add User (CLD – 2.1)
2.1.2.2. GET / Get User Profile (CLD – 2.2)
2.1.2.3. PATCH / Update User (CLD – 2.3)
2.1.2.4. POST / Log Out User (CLD – 2.4)
2.1.2.5. POST / Log In User (CLD – 2.5)
2.1.2.6. DELETE / Delete User (CLD – 2.6)

3. Deliverables
3.1. Test Plan
3.2. API–UI Mapping Document
3.3. Excel Test Case Document
3.4. Postman Collection and Environment Variables and Assertions and Bug Logs	
3.5. Bug Report
3.6. RTM (Requirements Traceability Matrix)
3.7. Test Summary Report
3.8. Presentation Slides

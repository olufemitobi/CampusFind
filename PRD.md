BU-COS 209 - GROUP 10
Project Name: CampusFind – Campus Lost and Found System
Project Type: Web-Based Application


1. Product Overview
Product Name: CampusFind
Description: CampusFind is a web-based platform designed to help students and staff report, locate and recover lost belongings within a university environment. A platorm will be made where users can report items they have lost or items they have found. Other users can browse these reports, search for specific belongings and contact the person who submitted a report.
Purpose: As the name implies, CampusFind makes recovering lost belongings on campus easier. 

2. Problem Statement
Losing personal belongings on campus is a common experience among students and staff. Items such as phones, wallets, identity cards, textbooks, keys and other personal belongings can easily be misplaced every single day without assurance of finding them.
When this happens, people often turn to WhatsApp groups, friends, notice boards or security offices to ask whether anyone has seen their belongings. Unfortunately, these methods do not always produce results because the information is scattered across different platforms and may not reach the right people.
There is also no convenient way to connect someone who has found an item with the person who lost it.
CampusFind intends to solve this problem by creating a central platform where lost and found items can be reported, searched for and recovered more easily.

3. Product Goals and Objectives
The major goal of CampusFind is to improve how lost and found belongings are reported and recovered within the university.
The specific objectives are to:
- Provide a central platform for reporting lost and found items.
- Make it easier for students and staff to search for missing belongings.
- Connect individuals who have lost items with those who have found them.
- Reduce the time spent searching for misplaced belongings.
- Keep lost and found information organised and accessible.
- Allow administrators to monitor reports and deal with suspicious submissions.
Success Metrics:
The success of CampusFind can be measured by:
- Number of registered users.
- Number of lost and found reports submitted.
- Number of items successfully recovered.
- Time taken to locate reported items.
- Number of unresolved reports.
- Number of suspicious reports identified and handled.

4. Target Users
CampusFind is primarily designed for members of a university community.
The target users include:
A. Students: Students who have misplaced personal belongings or found items belonging to other people.
B. Lecturers and University Staff: Members of staff who may also lose or find belongings within the school environment.
C. System Administrators: Individuals responsible for monitoring the platform, managing reports and handling inappropriate or suspicious submissions.

5. Stakeholders
Stakeholders are individuals or groups who have an interest in the development, operation or success of CampusFind.
Students => Reporting lost items and finding missing belongings.
Lecturers and Staff => Reporting and recovering personal or work-related items.
University Management => Improving organisation and accountability on campus.
System Administrators => Managing users and monitoring reports.
Development Team => Designing, developing and maintaining the platform.
Stakeholder Questions to Be Confirmed:
Before development, the team should seek clarification on the following:
- Should registration be restricted to students with valid university email addresses?
- Should all item reports be visible to every registered user?
- Should the university security office have access to reported items?
- How should ownership be confirmed before an item is handed over?
- Should users be allowed to report items anonymously?
These questions are important because their answers may affect how the system is designed.

6. User Needs
Users of CampusFind should be able to:
- Create an account and access the platform.
- Report belongings they have lost.
- Upload details and photographs of items they have found.
- Search for items using names, categories and locations.
- View information about reported items.
- Contact the person who submitted a report.
- Update the status of an item when it has been recovered.
Administrators should also be able to manage reports and remove inappropriate content.

7. Functional Requirements
Functional requirements describe the specific actions CampusFind must support.
Requirement
Users must be able to register and log in.
Users must be able to submit lost-item reports.
Users must be able to submit found-item reports.
Users must be able to provide item descriptions, categories, dates and locations.
Users must be able to upload photographs of reported items.
Users must be able to browse available lost and found reports.
Users must be able to search for items using keywords and categories.
Users must be able to view the details of reported items.
Users must be able to contact the person who submitted a report through an agreed contact method.
Users must be able to update their reports when an item is recovered or returned.
Administrators must be able to review and manage reports.
Administrators must be able to remove suspicious or inappropriate reports.

8. Non-Functional Requirements
These requirements describe how well the system should operate.
Performance: Under normal operating conditions, 95% of search requests should return results within two seconds.
Security: User passwords must be securely hashed and must never be stored as plain text. Access to administrative functions must be restricted to authorised users.
Usability: The platform should have a simple interface that students and staff can understand without special technical knowledge.
Reliability: The system should store submitted reports correctly and retrieve them when needed. Failed submissions should not create duplicate reports.
Availability: The platform should be accessible whenever users need to report or search for missing belongings, subject to agreed hosting availability.
Privacy: Users' personal information and contact details should only be accessible according to the platform's agreed privacy and access rules.
Scalability: The system should be designed to accommodate an increasing number of users and item reports.

9. User Stories
User stories describe the features from the perspective of the people who will use CampusFind.
User Story 1 – Account Registration
As a student, I want to create an account so that I can access the lost and found platform.
User Story 2 – Reporting Lost Items
As a student, I want to report an item I have lost so that someone who finds it can identify and contact me.
User Story 3 – Reporting Found Items
As a student, I want to upload details of an item I have found so that its owner has a chance of recovering it.
User Story 4 – Searching for Items
As a user, I want to search for reported items using keywords and categories so that I can find relevant information without going through every report.
User Story 5 – Contacting Users
As a user, I want to contact the person who reported an item so that we can arrange how it will be recovered.
User Story 6 – Managing Reports
As an administrator, I want to review suspicious reports so that the platform remains useful and trustworthy.
User Story 7 – Updating Item Status
As a user, I want to mark an item as recovered so that other users know it is no longer missing.

10. Acceptance Criteria
Acceptance criteria determine when a feature can be considered complete.
Feature: User Registration
- Users must provide the required registration information.
- Invalid or incomplete information must be rejected.
- Users must be able to log in with their registered credentials.
- Passwords must be stored securely.
Feature: Reporting a Lost Item
- A user must be logged in before submitting a report.
- The item name, description and location must be provided.
- The report must be saved successfully.
- Invalid submissions must display an appropriate error message.
Feature: Reporting a Found Item
- Users must be able to provide details of found belongings.
- Users should be able to attach an item photograph.
- Successful reports must appear in the found-items section.
Feature: Searching for Items
- Users must be able to search using keywords.
- Users must be able to filter results by category.
- Relevant results should be displayed.
- The system should provide a clear message when no matching items are found.
Feature: Recovering an Item
- Users must be able to update the status of their reports.
- Recovered items must be clearly identified.
- Updated information must remain available after the user logs out.

11. System Scope and Feature Prioritisation
To make the first version manageable, the project will use the MoSCoW prioritisation method.
Must Have (Essential for the first release)
- User registration and login.
- Lost-item reporting.
- Found-item reporting.
- Viewing reported items.
- Basic search functionality.
- Updating item recovery status.
Should Have (Important but not essential for the first release)
- Search filters by category and location.
- Photograph uploads.
- User-to-user contact functionality.
- Administrative report management.
Could Have (Additional features if time permits)
- Email notifications.
- Advanced search filters.
- Report statistics and activity summaries.
Won't Have (Excluded from the first release)
- GPS tracking of lost belongings.
- Artificial intelligence-based image recognition.
- Online reward payments.
- Integration with external police or security databases.
Minimum Viable Product (MVP):
The first version of CampusFind will focus on account registration, lost and found reports, browsing, basic searching and updating the recovery status of items.
These features are sufficient to provide a useful service without making the initial development unnecessarily complicated.

12. Technical Requirements
The proposed technologies for developing CampusFind are:
Frontend:
- HTML for page structure.
- CSS for styling and layout.
- JavaScript for interactive features.
Backend:
- Node.js for server-side development.
- Express.js for routing and API development.
Database:
- MongoDB for storing user accounts and lost and found reports.
Development Tools:
- Visual Studio Code for writing and managing code.
- Git and GitHub for version control and team collaboration.
Platform:
CampusFind will be developed as a responsive web application that can be accessed through mobile phones, tablets and computers.
These are proposed technical choices and may be adjusted by the development team during the architecture and technology decision stage.

13. Constraints and Assumptions
Constraints
- Development time and available resources may be limited.
- Users need internet access to use the platform.
- The accuracy of reports depends on the information provided by users.
- The system requires adequate storage for uploaded photographs.
- The team may have limited access to university-approved identity verification services.
Assumptions
- Students and staff have access to internet-enabled devices.
- Users are willing to report lost and found belongings.
- Users will provide accurate information when submitting reports.
- The university community will be the primary audience.
- Administrators will be available to monitor reports and handle inappropriate submissions.

14. Open Questions
The following decisions must be clarified before or during development:
1. Will registration require a valid university email address?
2. Will users communicate through an in-app messaging system or shared contact details?
3. Who will be responsible for verifying that an item belongs to the person claiming it?
4. Will the university security department participate in managing found items?
5. How long should unresolved item reports remain on the platform?
The development team should not treat these unanswered questions as confirmed requirements.

15. Conclusion
CampusFind is intended to address a problem that students and university staff can easily relate to. Misplaced belongings can cause unnecessary stress and inconvenience, especially when there is no organised way to report or search for them.
By providing a central platform for reporting, searching and recovering lost belongings, CampusFind aims to make the process more organised and accessible.
The first release will concentrate on the features that directly address the problem. Additional features can be introduced later based on user feedback and the needs of the university community.
The overall objective is to build a simple, reliable and useful platform that makes finding lost belongings on campus less difficult.
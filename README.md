# findjob

Task 1: ER Diagram Planning
Entities and Attributes:
Job Seeker:

Attributes:
JobSeekerID (Primary Key)
Name
Email
Phone
Resume
Education
Experience
Job Posting:

Attributes:
JobPostingID (Primary Key)
Title
Description
Requirements
Company
Location
Salary
DatePosted
Application:

Attributes:
ApplicationID (Primary Key)
JobSeekerID (Foreign Key)
JobPostingID (Foreign Key)
DateApplied
Status (e.g., Pending, Accepted, Rejected)
Skill Set:

Attributes:
SkillID (Primary Key)
SkillName
Relationships and Cardinalities:
Job Seeker-to-Application: One-to-Many (A Job Seeker can submit multiple applications, but each application is submitted by one Job Seeker.)
Job Posting-to-Application: One-to-Many (A Job Posting can have multiple applications, but each application is for one Job Posting.)
Job Seeker-to-Skill Set: Many-to-Many (A Job Seeker can have multiple skills, and a skill can be associated with multiple Job Seekers.)
Task 2: Project Planning Document
Project Goals and Scope:
Objectives:

Develop a user-friendly job searching application.
Facilitate efficient job applications and postings.
Match Job Seekers with suitable Job Postings based on skills.
Scope:

User registration and authentication.
Job Seeker can create/edit their profile and upload a resume.
Employers can post/edit job listings.
Job Seekers can search for jobs based on various criteria.
Job Seekers can apply to jobs, and Employers can view applications.

Project Structure Overview:
/src: Contains the source code of the application.
/models: Database models.
/views: Front-end views.
/controllers: Back-end logic.
/routes: Application routes.
/docs: Project documentation.
/database: Database setup scripts and schema.

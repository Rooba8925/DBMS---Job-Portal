Job Portal System

Overview:
The Job Portal System is a web-based application developed to simplify the job search and recruitment process. It connects job seekers and employers through an online platform where employers can post job openings and job seekers can search and apply for jobs.
The system is built using HTML, CSS, PHP, and MySQL, with the database managed through DBMS. It provides features such as job searching, application submission, application tracking, and recruitment management.


Objectives:
- To design and develop a job portal using a Database Management System (DBMS).
- To allow job seekers to search and apply for jobs easily.
- To allow employers to post job openings and manage applications.
- To store and manage job listings, candidate profiles, and application status efficiently.
- To provide a simple and user-friendly interface for both employers and job seekers.

Features:

Job Seeker
- Register and login
- View available job listings
- Filter jobs based on:
  - Company
  - Location
  - Category
  - Salary
- Apply for jobs by submitting:
  - Resume
  - Skills
  - Experience
- Track application status (Accepted / Rejected / Pending)

Employer
- Register and login with company details
- Post job openings
- View applicants for posted jobs
- Review candidate profiles
- Accept or reject job applications
- Manage recruitment workflow

Application Status
- Displays real-time status of job applications
- Job seekers can track their applications
- Employers can update application status

Technologies Used:

Frontend
- HTML
- CSS

Backend
- PHP

Database
- MySQL

Tools
- XAMPP
- phpMyAdmin

Database Tables:

The system uses the following main tables:

- users – stores user login details
- employerprofile – stores employer company information
- job_listings – stores job posting details
- jobseeker_profile – stores candidate profile information
- job_application – stores application status and applied jobs

System Workflow:

Job Seeker Workflow
1. Register or login
2. Search and filter available jobs
3. Apply for jobs by submitting resume and skills
4. Track application status

Employer Workflow
1. Register or login
2. Post job vacancies
3. View applications from job seekers
4. Accept, reject, or keep applications pending

Project Structure:

job-portal-system/
│
├── login.php
├── register.php
├── employer_dashboard.php
├── jobseeker_dashboard.php
├── post_job.php
├── apply.php
├── application.php
├── db.php
├── config.php
└── assets/

Security Features:
- Password hashing for secure login
- Role-based access (Employer / Job Seeker)
- Secure database queries using prepared statements

Conclusion:
The Job Portal System provides a centralized platform for managing job recruitment activities. It allows job seekers to explore job opportunities and apply for positions while enabling employers to efficiently manage job postings and candidate applications. The integration of HTML, CSS, PHP, and MySQL ensures a dynamic, secure, and user-friendly application.

References:
1. Silberschatz, A., Korth, H.F., & Sudarshan, S. Database System Concepts (7th Edition) – McGraw Hill.
2. https://nevonprojects.com/job-portal-project
TeachTeam Web Application
TeachTeam is a cloud-powered, full-stack tutor recruitment platform designed for efficient, data-driven selection across university courses. Built using Next.js (TypeScript), Express.js, TypeORM, and MySQL, the system delivers secure end-to-end workflow management for tutors, lecturers, and administrators.
Features
User Authentication & Registration
•	Role-based registration as Tutor or Lecturer with validation for strong passwords
•	Google reCAPTCHA v2 to prevent bot registrations
•	All credentials securely encrypted and stored in a Cloud MySQL database
•	Custom avatar upload for personalized profiles
Tutor Dashboard
•	Submit applications for one or multiple courses, specifying credentials, experience, and skill sets
•	View dashboard with user info and profile avatar
•	Persistent storage of all tutor actions and applications through REST API integration
Lecturer Dashboard
•	Personalized dashboard with tabs: Applications, Selected Tutors, Visual Analysis
•	Filter applications by course, tutor, role, and other criteria
•	Rank and comment on tutors; dynamic updates to ranking and comment records
Visual Analysis
•	Comprehensive dashboard showing tutor selection stats, rankings, and feedback for all lecturers
•	Interactive table with live tutor data, selection status, average ranks, and comments
Admin Dashboard (Standalone)
•	Built with React and GraphQL (Apollo Client); fully decoupled from TeachTeam main app
•	Admin authentication and privileges for course and lecturer assignment
•	CRUD for course listings and tutor accounts, including access control
•	Generate reports: selected tutors, high-engagement tutors, and non-selected tutors
Backend Integration
•	Express server with TypeORM and MySQL for robust, scalable data handling
•	All actions (registration, login, tutor/lecturer/admin operations) managed via REST APIs
•	File uploads managed through Multer for secure avatar storage
Technology Stack
Component	Technology
Frontend	Next.js / TypeScript
Backend	Express.js / Node.js
ORM	TypeORM
Database	MySQL (Cloud-hosted)
Admin Panel	React / Apollo Client
File Upload	Multer
Security	Google reCAPTCHA v2
Quick Start
1.	Clone the Repository:
git clone https://github.com/jaikanthsellappan/TeachTeam
2.	Install Dependencies:
Run npm install in both frontend and backend folders.
3.	Configure Database:
Set up Cloud MySQL credentials.
Add courses via admin panel or execute the database initialization query found in dependencies.txt under the backend folder.
4.	Start Servers:
Run frontend (npm run dev or yarn dev) and backend (npm start) servers.
5.	Login & Roles:
•	Admin: admin / admin
•	Tutors & Lecturers: Register via the main application


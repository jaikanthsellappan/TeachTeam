TeachTeam Web Application

TeachTeam is a full-stack, cloud-powered web platform for tutor recruitment and selection, built with Next.js (TypeScript), Express.js, TypeORM, and MySQL. The app streamlines the process for tutors applying for courses, and lecturers reviewing, selecting, and ranking candidates via dynamic dashboards. All data is securely stored in a cloud MySQL database to ensure reliability and persistence across sessions.

Features
    •	Role-based User Authentication:
    Tutors and lecturers register using a robust authentication system (with password strength validation and Google reCAPTCHA v2). Avatars can be uploaded for custom profiles.
    •	Tutor Dashboard:
    Tutors can apply for multiple courses, specify credentials and experience, upload profile images, and view or manage their applications. All interactions are handled via REST APIs.
    •	Lecturer Dashboard:
    Lecturers access a personalized dashboard showing applications only for their assigned courses. Features include powerful filtering, selection/deselection of tutors, ranking, and commenting.
    •	Visual Analysis Dashboard:
    Live overview of tutor selection stats, including most/least selected tutors and unselected candidates, with average rankings and comments visualized in interactive tables.
    •	Admin Dashboard (Standalone Module):
    Built with React and Apollo Client (GraphQL). Admins assign courses to lecturers, manage tutor and course records, block/unblock accounts, and generate custom selection reports.

| Component    | Technology               |
|--------------|--------------------------|
| Frontend     | Next.js (TypeScript)     |
| Backend      | Express.js (Node.js)     |
| ORM          | TypeORM                  |
| Database     | MySQL (Cloud-hosted)     |
| Admin Panel  | React, Apollo Client     |
| File Uploads | Multer                   |
| Security     | Google reCAPTCHA v2      |


Quick Start
1.	Clone the repository
2.	Install dependencies (npm install) in both frontend and backend directories
3.	Configure database
    •	Use the admin panel to add courses and map lecturers
    •	Or run the SQL script in dependencies.txt inside the backend folder for initial setup
4.	Start the application
    •	Frontend: npm run dev
    •	Backend: npm start
5.	Access with your role credentials
    •	Admin login: admin / admin
    •	Tutors and Lecturers: Register via main app
Please refer to the "README before starting the application" file for initial setup details, database configuration, and troubleshooting steps.

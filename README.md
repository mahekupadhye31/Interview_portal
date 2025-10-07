Interview Preparation Platform

This platform is a comprehensive tool for interview preparation, allowing candidates to register, apply for interviews, access resources, track their progress, and receive feedback—all in one place. It is designed to help interviewees and recruiters streamline the application and interview process efficiently.

🚀 Features

Login and Signup Functionality

Convenient registration page with minimal fields: full name, email, SAP ID, graduation year, and password.

Users authenticate using Token Authentication, logging in with SAP ID and password.

Resources

A dedicated resources page acting as a hub for tutorials, tools, and materials.

Organized by categories such as frontend, backend, app, and design for easy access.

Application Form

Allows candidates to submit interview applications.

Fields include resume link, GitHub repository link, and other relevant information.

Dashboard for Interviewees

Personalized dashboard to view and manage upcoming interviews and tasks.

Includes a progress tracker to monitor interview preparation and task completion.

FAQs Section

Provides clear answers to common questions to help candidates feel prepared and confident.

Interview Scheduling Feature

Allows interviewers to efficiently schedule interviews with candidates.

Simplifies the process, reducing manual coordination and communication.

Marking System

Enables recruiters to record scores or evaluations for candidates after interviews.

Can be integrated into recruitment management or HR systems.

Additional Feedback

Allows interviewers to provide personalized feedback to candidates.

Helps candidates improve and prepares them for future interviews.

🛠️ Tech Stack

Frontend: React.js

Backend: Django

📸 Demonstrations / Screenshots
<p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/login-page.png" alt="Login Page" /> </p> <p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/resources-page.png" alt="Resources Page" /> </p> <p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/application-form.png" alt="Application Form" /> </p> <p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/dashboard.png" alt="Dashboard" /> </p> <p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/interview-scheduling.png" alt="Interview Scheduling" /> </p> <p align="center"> <img width="785" src="https://raw.githubusercontent.com/username/repo-name/main/assets/marking-feedback.png" alt="Marking & Feedback" /> </p>
🔗 Feature Usage / API Endpoints
Feature / Action	Method	Endpoint / URL (if applicable)	Description
Login	POST	/api/login/	Authenticate users with SAP ID and password. Returns a token for session.
Signup / Registration	POST	/api/register/	Create a new user account with full name, email, SAP ID, graduation year, and password.
View Resources	GET	/api/resources/	Fetch categorized resources (frontend, backend, app, design) for interview prep.
Submit Application Form	POST	/api/application/	Submit candidate’s resume, GitHub link, and other info for interview.
View Dashboard	GET	/api/dashboard/	View upcoming interviews, tasks, and preparation progress.
Schedule Interview	POST	/api/schedule-interview/	Interviewers can schedule interviews with candidates.
Mark Interview	POST	/api/mark-interview/	Recruiters can record evaluation scores for candidates.
Provide Feedback	POST	/api/feedback/	Interviewers can give additional feedback to candidates.
View FAQs	GET	/api/faqs/	Retrieve frequently asked questions for interview preparation.

⚡ Tip: Replace endpoints with your actual Django routes if different.

⚙️ Installation & Setup (Local)

Clone the repository:

git clone https://github.com/username/repo-name.git
cd repo-name


Install dependencies:

# Frontend
cd frontend
npm install

# Backend
cd ../backend
pip install -r requirements.txt


Set environment variables in .env:

SECRET_KEY=your_django_secret_key
DEBUG=True
DATABASE_URL=your_database_url


Run the application:

# Backend
python manage.py runserver

# Frontend
npm start


Access the platform at:

http://localhost:3000

👨‍💻 Contributors

Mahek Upadhye

Rishab Pendam

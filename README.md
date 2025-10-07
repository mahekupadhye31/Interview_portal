# Interview Preparation Platform

Interview Preparation Platform is a comprehensive tool for interview preparation, allowing candidates to register, apply for interviews, access resources, track their progress, and receive feedback — all in one place. It helps interviewees and recruiters streamline the application and interview process efficiently.

<p align="center">
  <img width="785" height="426" alt="Dashboard Snapshot" src="src/assets/dashboard.png" />
</p>

## 🚀 Features

### Login and Signup Functionality
- Minimal fields for convenient registration: full name, email, SAP ID, graduation year, and password.  
- Authentication is handled via Token Authentication; users log in using SAP ID and password.

### Resources
- A hub for tutorials, tools, and materials to help interviewees improve their skills.  
- Organized by categories: frontend, backend, app, and design for easy navigation.

### Application Form
- Allows candidates to submit applications with resume and GitHub links.  
- Collects all relevant information for interview scheduling.

### Dashboard for Interviewees
- View and manage upcoming interviews, tasks, and preparation progress.  
- Includes progress tracker (percentage or circle) to monitor tasks and motivate users.

### FAQs Section
- Provides clear answers to common questions to prepare candidates and reduce individual inquiries.

### Interview Scheduling Feature
- Enables interviewers to schedule interviews efficiently.  
- Simplifies scheduling, reduces back-and-forth communication, and ensures smooth interviews.

### Marking System
- Allows recruiters to record evaluations and scores after interviews.  
- Can integrate with recruitment or HR systems.

### Additional Feedback
- Lets interviewers provide personalized feedback to candidates.  
- Helps candidates improve and prepare better for future interviews.

## 🛠️ Tech Stack

- Frontend: React.js  
- Backend: Django  

## 📸 Demonstrations

### Interviewee Side
<p align="center">
  <img width="785" height="426" alt="Login Page" src="src/assets/signup-page.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Login Page" src="src/assets/login-page.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Dashboard" src="src/assets/dashbboard.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Application Form" src="src/assets/application-form.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Profile" src="src/assets/profile-page.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Resources" src="src/assets/resources.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="FAQs" src="src/assets/faqs.png" />
</p>

### Interviewer Side

<p align="center">
  <img width="785" height="426" alt="Marking & Feedback" src="src/assets/admin-dashboard.png" />
</p>

<p align="center">
  <img width="785" height="426" alt="Marking & Feedback" src="src/assets/admin-student-data.png" />
</p>

## ⚙️ Installation & Setup (Local)

### Clone the Repository

```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```
### Frontend

```bash
cd frontend
npm install
```
### Backend

```bash
cd ../backend
pip install -r requirements.txt
```
### Create a .env file in the backend root

``` bash
SECRET_KEY=your_django_secret_key
DEBUG=True
DATABASE_URL=your_database_url
```
### Run the backend
``` bash
python manage.py runserver
```
### Run the frontend
```bash
npm start
```
## 🔗 Feature / API Endpoints

| Method   | Endpoint                   | Description                                     |
| -------- | -------------------------- | ----------------------------------------------- |
| **POST** | `/api/register/`           | Register a new user account                     |
| **POST** | `/api/login/`              | Login with SAP ID and password                  |
| **GET**  | `/api/resources/`          | Retrieve all categorized resources              |
| **POST** | `/api/application/`        | Submit interview application                    |
| **GET**  | `/api/dashboard/`          | View dashboard with progress and upcoming tasks |
| **POST** | `/api/schedule-interview/` | Schedule an interview for a candidate           |
| **POST** | `/api/mark-interview/`     | Record interview evaluation / scores            |
| **POST** | `/api/feedback/`           | Provide additional feedback to interviewee      |
| **GET**  | `/api/faqs/`               | Retrieve frequently asked questions             |


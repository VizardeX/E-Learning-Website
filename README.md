# E-Learning Platform – Adaptive Web-Based Learning System

## Overview
This project is a feature-rich E-Learning platform built with NestJS, MongoDB, and Next.js. It supports three user roles—students, instructors, and administrators—and provides adaptive learning experiences, performance tracking, and secure communication. The backend is modular and scalable, and the frontend is optimized for dynamic, role-based content delivery.

## Features

### User Management and Security
- Secure user registration and login using JWT
- Password hashing with bcrypt
- Role-based access control (student, instructor, admin)
- Admin-level search, monitoring, and moderation tools

### User Roles and Permissions

#### Student
- Register, log in, and manage personal profile
- View enrolled courses and modules
- Attempt adaptive quizzes and view results
- Track learning progress and performance analytics
- Send messages to instructors or peers
- Participate in course discussions
- Write and manage personal study notes

#### Instructor
- Create and manage courses and modules
- Add multimedia content to lessons
- Create quizzes for the students
- Monitor student activity and download reports
- Reply to student messages and forum posts
- Announce course updates via notifications

#### Administrator
- Full access to all system data
- View, search, and manage users (students and instructors)
- Moderate discussion forums
- Manage system logs and data backups
- Oversee platform-wide activity and enforce rules


### Course and Module Management
- Instructors can create, update, and organize courses into modules
- Upload and manage multimedia content (PDFs, videos, links)
- RESTful APIs support scalable course and module structures

### Adaptive Quizzes and Assessment
- Centralized question bank
- Quiz creation and response tracking
- Adaptive difficulty based on student performance
- Storage and retrieval of student responses

### Performance Analytics
- Student dashboards with progress, scores, and performance trends
- Instructor dashboards with engagement reports and analytics
- Data visualization tools for insights into learning behavior

### Communication Tools
- Real-time chat between students and instructors
- Threaded discussion forums per course/module
- Message history and notifications for replies and updates

### Notes and Personal Tools
- Quick Notes: personal note-taking area for students
- Notifications for announcements, new content, and activity

## Technologies Used

### Backend
- NestJS (Node.js + TypeScript)
- MongoDB with Mongoose
- JWT for authentication
- bcrypt for password encryption

### Frontend
- Next.js (React-based)
- Tailwind CSS (or similar styling library)
- Axios for API interaction

### Additional Tools
- REST APIs
- WebSockets for real-time chat
- Cron jobs or scheduled tasks for automated backups
- Modular service-based backend structure

### How to run
- Go to backend folder using `cd backend` command in the terminal and then write the command `npm i`. After it finishes running, write the command `npm run start`
- Go to frontend folder using `cd frontend` command in the terminal and then write the command `npm i`. After it finishes running, write the command `npm run dev`




CRM Lead Management System

 Project Overview

The CRM (Customer Relationship Management) Lead Management System is a web application designed to manage client leads generated through website contact forms. It helps businesses track, organize, and update leads efficiently through a centralized dashboard.

This project demonstrates full-stack web development skills including frontend development, backend API creation, database management, and CRUD operations.

---

 Objective

To build a CRM application that allows administrators to:

- Store client lead information
- Track lead status
- Manage follow-up notes
- Monitor lead conversion progress
- Securely access lead management features

---

 Features

Lead Management

✔ Add new leads

✔ View all leads

✔ Edit lead details

✔ Delete leads

Lead Information

- Name
- Email
- Phone Number
- Lead Source
- Status
- Notes

Lead Status Tracking

- New
- Contacted
- Converted

Notes & Follow-Ups

- Add notes for each lead
- Track follow-up activities
- Maintain communication history

Admin Features

- Secure Admin Login
- Protected Dashboard
- Lead Management Panel

Dashboard

- Total Leads
- New Leads Count
- Contacted Leads Count
- Converted Leads Count

---

 Technologies Used

Frontend

- HTML5
- CSS3
- JavaScript
- React.js

Backend

- Node.js
- Express.js

Database

- MongoDB

Tools

- Git
- GitHub
- Postman
- VS Code
 Installation & Setup

Clone Repository

git clone https://github.com/your-username/crm-lead-management.git

Navigate to Project Folder

cd crm-lead-management

Install Frontend Dependencies

cd client
npm install

Install Backend Dependencies

cd ../server
npm install

Configure Environment Variables

Create a ".env" file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run Backend Server

npm start

Run Frontend Application

npm start

---

 API Endpoints

Leads

Method| Endpoint| Description
GET| /api/leads| Get all leads
GET| /api/leads/:id| Get single lead
POST| /api/leads| Create new lead
PUT| /api/leads/:id| Update lead
DELETE| /api/leads/:id| Delete lead

Authentication

Method| Endpoint| Description
POST| /api/auth/login| Admin Login
POST| /api/auth/register| Register Admin

---

Skills Gained

This project demonstrates:

- CRUD Operations
- REST API Development
- React Frontend Development
- Backend Integration
- MongoDB Database Management
- Authentication & Authorization
- Business Workflow Automation
- Full Stack Development

---

Deployment

Frontend

- Netlify
- Vercel

Backend

- Render
- Railway

Database

- MongoDB Atlas

---

Live Demo

Add your deployed application link here:

https://your-crm-app-link.com

---

Screenshots

Add screenshots of:

- Login Page
- Dashboard
- Lead Listing Page
- Lead Details Page
- Status Management

---

Future Enhancements

- Email Notifications
- SMS Alerts
- Lead Assignment System
- Analytics Dashboard
- Export Leads to Excel/PDF
- Customer Interaction History
- Multi-User Roles

---

 Author

Amrutha Valli

GitHub: https://github.com/your-username

LinkedIn: https://linkedin.com/in/your-profile

Email:amruthavallinelliparthi@gmail.com

---

 License

This project is developed for educational and internship purpose.

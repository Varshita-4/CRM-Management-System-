# CRM Management System

A full-stack Customer Relationship Management (CRM) application built using the **MERN Stack** (MongoDB, Express.js, React.js, and Node.js). The application provides secure role-based authentication and dedicated dashboards for administrators and users to efficiently manage tickets, tasks, and user accounts.

---

## Features

### Admin Dashboard
- Manage users (Create, Update, Delete)
- Assign and manage tasks
- Manage customer support tickets
- Update ticket status (Pending, Approved, Resolved)
- Activate/Deactivate user accounts
- Dashboard analytics and visualizations

### User Dashboard
- Raise support tickets
- View assigned tasks
- Submit completed tasks
- Track ticket status
- Dashboard overview with statistics

### Authentication
- JWT-based Authentication
- Role-based Authorization
- Login / Logout
- Forgot Password
- Reset Password

---

## Tech Stack

### Frontend
- React.js
- Vite
- React Router
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

## Project Structure

```
CRM-Management-System
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── src
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Varshita-4/CRM-Management-System-.git
```

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## Default Credentials

### Admin

Email

```
admin@gmail.com
```

Password

```
@Password123
```

### User

Email

```
user@gmail.com
```

Password

```
@Password123
```

---


## License

This project is intended for educational and portfolio purposes.
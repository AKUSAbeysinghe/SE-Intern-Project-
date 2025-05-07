# 🧠 Cloud-Based Task Manager (MERN Stack)

A modern, cloud-powered task management platform designed for efficient collaboration between teams. Built with the MERN stack, this system allows admins to manage users and tasks while giving users an intuitive interface for tracking their work.



## 🚀 Features

### 👑 Admin Features
- **User Management**: Create admin accounts, manage team members, activate/disable accounts
- **Task Assignment**: Assign tasks to one or many users, edit task details and statuses
- **Task Properties**:
  - Label tasks (Todo, In Progress, Completed)
  - Set priority (High, Medium, Normal, Low)
  - Manage sub-tasks
- **Asset Management**: Upload task-related files (e.g., images)
- **User Account Control**: Trash or permanently delete tasks

### 🙋‍♀️ User Features
- **Task Interaction**: Change task status, view detailed task info


### ⚙️ General Features
- **Authentication**: Secure login with role-based access control (Admin/User)
- **Profile Management**: Update user details and passwords
- **Dashboard**:
  - Summary of activities
  - Filter by task stage (Todo, In Progress, Completed)

---

## 🧰 Technologies Used

### Frontend
- [React (Vite)](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

### Backend
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)

### Database
- [MongoDB],  [MongoDB (via Atlas)](https://www.mongodb.com/cloud/atlas)

---

## ⚙️ Setup Instructions

### 📦 Server Setup
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8800
NODE_ENV=development

pgsql
Copy
Edit

#### 2. Set Up MongoDB (Atlas)
- Visit: https://www.mongodb.com/cloud/atlas
- Create a free account
- Create a cluster and database
- Whitelist your IP address
- Create a database user
- Copy the connection URI and add it to your `.env`

#### 3. Run the Server

```bash
cd server
npm install
npm start
#### 1. Environment Variables (`.env`)
Create a `.env` file inside the `server/` directory:

🧪 Example Admin Credentials
json
Copy
Edit
{
  "email": "admin@example.com",
  "password": "yourPassword123",
  "isAdmin": true
}



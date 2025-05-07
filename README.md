#  Cloud-Based Task Manager (MERN Stack)

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

###  Client Setup

npm install
npm start

###  Server Setup

npm install
npm start
#### 1. Environment Variables (`.env`)
Create a `.env` file inside the `server/` directory:



MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8800
NODE_ENV=development



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

```

## 🖼 Screenshots

### 🔐 Login Page

![task2](https://github.com/user-attachments/assets/6c6f5aed-43a9-42a3-8582-662316edfd4a)


### 🏠 Dashboard

![task1](https://github.com/user-attachments/assets/0f468d22-ee3d-4028-90aa-8fda64326251)



### 🧩 Task Details

![task3](https://github.com/user-attachments/assets/81346297-27b8-44f2-ad2c-96f6f1e1ec1a)

![task4](https://github.com/user-attachments/assets/11c50501-c6be-4d05-8ecf-0865a7de1ed8)






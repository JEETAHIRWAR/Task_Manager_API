# 🚀 Task Manager API

A scalable **RESTful Task Management API** built using **Node.js, Express.js, and MongoDB** with JWT-based authentication. This API allows users to manage their tasks securely with full CRUD operations.

---

## 🌐 Live Demo
👉 https://task-manager-api-4x6e.onrender.com

---

## 📌 Features
- 🔐 User Authentication (JWT)
- 👤 User Registration & Login
- 📋 Task Management (CRUD)
- 🗂️ User-specific tasks
- ⏱️ Deadlines & task status
- 🛡️ Secure password hashing (bcrypt)
- ⚡ REST API architecture

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** JWT (JSON Web Token)  
- **Testing:** Postman  
- **Deployment:** Render  

---

## 📁 Project Structure

```bash
task-manager-api/
│── config/
│── controllers/
│── middleware/
│── models/
│── routes/
│── .env
│── server.js


---

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/task-manager-api.git
cd task-manager-api


### 2. Install dependencies
```bash
npm install

### 3. Create .env file
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### 4. Run the server
```bash 
npm run dev

## 📬 API Endpoints

### 👤 Auth Routes
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/users/register | Register user |
| POST | /api/users/login | Login user |

---

### 📋 Task Routes (Protected)
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | /api/tasks | Get all tasks |
| POST | /api/tasks | Create task |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

---

## 🔐 Authentication
Use **Bearer Token** in headers:

```bash
Authorization: Bearer YOUR_TOKEN

### 🧪 Sample Payloads
### Register
```bash 
{
  "name": "Jeet",
  "email": "jeet@gmail.com",
  "password": "123456"
}

### Create Task
```bash 
{
  "title": "Learn Backend",
  "description": "Build API",
  "status": "pending",
  "deadline": "2026-06-01"
}

### 🚀 Deployment
- This project is deployed on Render with MongoDB Atlas as the database.

## 💡 Future Improvements
Pagination & filtering
Role-based access control
API documentation (Swagger)
Frontend integration (React)

# 👨‍💻 Author

Jeet Ahirwar
📍 Bhopal, India
📧 jeetahirwar664@gmail.com

⭐ Support

If you like this project, give it a ⭐ on GitHub!


# Employee Management System

## 🔧 Task-02 | ProDigy InfoTech Internship

An **Employee Management System** web application that allows administrators to efficiently manage employee records using full CRUD operations (Create, Read, Update, Delete). The system features robust **authentication**, **authorization**, and **form validation** to ensure data security and integrity.

---

## ✨ Features

- ✅ Add, view, edit, and delete employee records
- 🔐 Secure login system with role-based access control
- 🛡️ Password hashing and session protection
- 📄 Server-side and client-side input validation
- 🌐 Responsive user interface with clean UX/UI
- ⚠️ Error handling and form feedback
- 🗂️ Organized codebase for scalability and maintenance

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (or React if applicable)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Validation**: Joi / express-validator (or custom logic)
- **Styling**: Bootstrap / TailwindCSS / Material UI (based on your project)

---

## 🔒 Security Features

- Token-based user authentication
- Secure password hashing with bcrypt
- Route protection middleware for sensitive APIs
- Input validation to prevent XSS/SQL injection

---

## 🚀 How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/employee-management-system.git
Install dependencies:

bash
Copy
Edit
cd employee-management-system
npm install
Setup environment variables:

Create a .env file and add the following:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run the application:

bash
Copy
Edit
npm run dev
Access the app:

Open your browser and go to: http://localhost:5000

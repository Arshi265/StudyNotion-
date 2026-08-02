<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=30&duration=3000&pause=1000&color=4F46E5&center=true&vCenter=true&width=700&lines=StudyNotion;Full+Stack+MERN+Ed-Tech+Platform;Learn+%7C+Teach+%7C+Grow" />

<h3>A Modern Learning Management System (LMS) built using the MERN Stack</h3>

<p>
A feature-rich online education platform where instructors can create and manage courses, while students can explore, purchase, and track their learning journey.
</p>

<p>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js"/>
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb"/>
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwind-css"/>
<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux"/>

</p>

<p>

<a href="https://study-notion-arshi266.vercel.app">🌐 Live Demo</a>
•
<a href="https://github.com/Arshi265">GitHub</a>

</p>

</div>

---

# 📚 About

StudyNotion is a Full Stack Learning Management System (LMS) developed using the **MERN Stack**. The platform enables instructors to publish educational content while allowing students to browse, purchase, and learn through an intuitive interface.

The application implements secure authentication, online payments, cloud media storage, role-based dashboards, and progress tracking to provide a complete online learning experience.

---

# ✨ Features

## 👨‍🎓 Student

- User Registration & Login
- OTP Email Verification
- Browse Available Courses
- Shopping Cart
- Razorpay Payment Integration
- Course Enrollment
- Watch Video Lectures
- Track Course Progress
- Update Profile
- Change Password

---

## 👨‍🏫 Instructor

- Instructor Dashboard
- Create New Courses
- Upload Course Thumbnail
- Upload Video Lectures
- Edit/Delete Courses
- Manage Course Content
- View Enrolled Students
- Revenue Analytics

---

## 🔐 Authentication

- JWT Authentication
- Role-Based Authorization
- Protected Routes
- Forgot Password
- Reset Password
- OTP Verification
- Password Hashing using bcrypt

---

# 🛠 Tech Stack

| Frontend | Backend | Database | Services |
|----------|----------|----------|----------|
| React.js | Node.js | MongoDB | Cloudinary |
| Redux Toolkit | Express.js | Mongoose | Razorpay |
| Tailwind CSS | REST APIs | MongoDB Atlas | Nodemailer |

---

# 🏗 System Architecture

```
                     React Frontend
                           │
                     REST API Calls
                           │
                    Express.js Server
                           │
                     Business Logic
                           │
                        MongoDB Atlas
                           │
         Cloudinary | Razorpay | Nodemailer
```

---

# 📂 Folder Structure

```
StudyNotion

├── public
├── src
│   ├── components
│   ├── pages
│   ├── redux
│   ├── services
│   └── utils
│
├── server
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   └── mail
│
├── images
├── package.json
└── README.md
```

---

# 🚀 Core Modules

- Authentication
- User Profile
- Instructor Dashboard
- Student Dashboard
- Course Management
- Categories
- Sections & Subsections
- Ratings & Reviews
- Payment Gateway
- Email Notifications

---

# 📸 Screenshots

## 🏠 Home Page

![](images/home.png)

---

## 📚 Course Details

![](images/course.png)

---

## 🎓 Student Dashboard

![](images/student-dashboard.png)

---

## 👨‍🏫 Instructor Dashboard

![](images/instructor-dashboard.png)

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/Arshi265/StudyNotion-.git
```

Install Dependencies

```bash
npm install
```

Run Frontend

```bash
npm start
```

Run Backend

```bash
cd server
npm install
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=

MONGODB_URL=

JWT_SECRET=

MAIL_HOST=

MAIL_USER=

MAIL_PASS=

CLOUD_NAME=

API_KEY=

API_SECRET=

FOLDER_NAME=

RAZORPAY_KEY=

RAZORPAY_SECRET=
```

---

# 📡 API Modules

### Authentication

- Signup
- Login
- Send OTP
- Forgot Password
- Reset Password

### Courses

- Create Course
- Update Course
- Delete Course
- Get Course Details
- Get All Courses

### Profile

- Get Profile
- Update Profile

### Payment

- Capture Payment
- Verify Payment

---

# 🚀 Future Enhancements

- AI Course Recommendations
- Live Classes
- Certificates
- Discussion Forum
- Mobile Application
- Dark Mode
- Push Notifications
- Admin Dashboard

---

# 👩‍💻 Author

### Arshi Bano

B.Tech Electrical Engineering  
MANIT Bhopal

📧 Email: arshi.bano265@gmail.com

💼 LinkedIn: YOUR_LINKEDIN_URL

🐙 GitHub: https://github.com/Arshi265

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

Made with ❤️ by **Arshi Bano**

</div>
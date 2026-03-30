# 📚 School Management System

## 🚀 Project Overview
Build a web-based **School Management System** using Python that helps schools, coaching centers, and tuition institutes manage students, teachers, attendance, fees, and exams.

The system should be designed with a clean architecture and modular structure so it can be extended into a production-ready application in the future.

---

## 🎯 Objective
Develop a scalable and maintainable MVP that:
- Solves real administrative problems for institutions
- Demonstrates strong backend fundamentals
- Follows good coding and testing practices

---

## 👥 User Roles

### 1. Admin
- Full system access
- Manages students, teachers, classes, fees, and reports

### 2. Teacher
- Manage attendance
- Enter exam marks
- View assigned classes

### 3. Parent
- View student details
- Check attendance, fees, and results
- View notices

---

## 🧩 Core Features

### 🔐 1. Authentication (Google OAuth)
- Login using Google account
- Role-based access control (Admin / Teacher / Parent)
- Secure session handling
- Restrict access based on role

---

### 👨‍🎓 2. Student Management
- Add / Edit / Delete students
- Store:
  - Full Name
  - Date of Birth
  - Class & Section
  - Admission Number
  - Parent Details
  - Contact Information
- Search and filter students

---

### 👩‍🏫 3. Teacher Management
- Add / Edit / Delete teachers
- Store:
  - Name
  - Subject
  - Contact details
  - Assigned classes

---

### 🏫 4. Class & Section Management
- Create classes (e.g., Grade 1, Grade 2)
- Create sections (A, B, etc.)
- Assign class teachers
- Assign students to classes

---

### 📅 5. Attendance Management
- Mark daily attendance (Present / Absent / Leave)
- Class-wise attendance entry
- View attendance history
- Student-wise attendance summary

---

### 💰 6. Fee Management
- Create fee records
- Track:
  - Paid / Unpaid / Partial payments
- View pending dues per student
- Fee summary dashboard

---

### 📝 7. Exams & Results
- Create exams (Midterm, Final, etc.)
- Enter subject-wise marks
- Calculate:
  - Total marks
  - Percentage
- Generate report card (basic view)

---

### 📢 8. Notices / Announcements
- Admin can post notices
- Teachers and parents can view notices
- Timestamped announcements

---

### 📊 9. Dashboard
- Total students
- Total teachers
- Attendance summary
- Pending fees
- Recent notices

---

## 🛠️ Tech Stack

### Backend
- Python (FastAPI preferred)

### Database
- MySQL

### ORM
- SQLAlchemy

### Frontend
- React (preferred)  
  or any modern frontend framework (Vue / Angular)

### Authentication
- Google OAuth 2.0

---

## 🏗️ System Requirements

- RESTful API design
- Modular project structure
- Environment-based configuration (.env)
- Proper error handling
- Input validation
- Basic logging

---

## 🧪 Testing Requirements

- Unit tests are mandatory
- Use `pytest`
- Cover:
  - Core business logic
  - API endpoints
- Mock external dependencies (e.g., database where required)
- Ensure tests are easy to run via a single command

---

## 📦 Deliverables

- ✅ Complete source code (GitHub repository)
- ✅ Database schema (ER diagram or SQL file)
- ✅ API documentation (Swagger / Postman)
- ✅ Unit tests with clear instructions to run
- ✅ README with setup instructions
- ✅ Sample test data (seed script)
- ✅ Screenshots or demo video

---

## ⚙️ Bonus Features (Optional)

- Email/SMS notifications
- Online fee payments (Stripe/Razorpay)
- Multi-school support (SaaS mode)
- Export reports (PDF/CSV)
- Improved UI/UX

---

## 📌 Evaluation Criteria

- Code quality & structure
- Feature completeness
- Test coverage and quality
- API design
- UI usability
- Documentation clarity

---

## 🎯 Expected Outcome

A fully functional MVP application that:
- Demonstrates strong backend engineering skills
- Includes proper testing
- Is structured for future scalability and enhancements

---

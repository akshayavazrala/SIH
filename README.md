# STEM Learn Odisha

An interactive STEM (Science, Technology, Engineering, and Mathematics) learning platform designed to make education engaging through educational games, quizzes, assignments, and doubt-solving features.

## 📚 Project Overview

STEM Learn Odisha is a web-based educational platform that helps students learn Science and Mathematics through interactive activities and gamified learning experiences.

The platform provides separate dashboards for students and teachers, allowing teachers to manage educational content while students can learn, play games, submit assignments, and track their progress.

---

## ✨ Features

### Student Features
- Student Registration & Login
- Interactive Learning Games
- Subject-wise Learning Modules
- Assignment Submission
- Quiz Participation
- Doubt Submission System
- Progress Tracking
- Profile Management

### Teacher Features
- Teacher Registration & Login
- Assignment Management
- Quiz Creation
- Student Performance Monitoring
- Doubt Resolution System
- Educational Content Management

### Educational Content
- Mathematics Modules
- Science Modules
- English Learning Activities
- Interactive STEM Games
- Grade-wise Learning Resources

---

## 🏗️ Project Structure

```
SIH-main/
│
├── home.html
├── about.html
├── contact.html
│
├── student-login.html
├── student-dashboard.html
│
├── teacher-login.html
├── teacher-dashboard.html
│
├── class-6/
│   ├── maths/
│   ├── science/
│   └── english/
│
├── uploads/
│
├── server.js
├── package.json
├── stem_learn_odisha.db
└── sessions.db
```

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- SQLite3

### Additional Packages
- bcryptjs
- multer
- cors
- express-session

---

## 📦 Dependencies

```json
{
  "express": "^4.21.2",
  "sqlite3": "^5.1.7",
  "bcryptjs": "^2.4.3",
  "multer": "^1.4.5-lts.1",
  "cors": "^2.8.5",
  "express-session": "^1.18.2"
}
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd SIH-main
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file if required:

```env
PORT=5000
```

### 4. Run the Server

```bash
node server.js
```

or

```bash
npm start
```

### Development Mode

```bash
npm run dev
```

---

## 🌐 Access the Application

After starting the server, open:

```text
http://localhost:5000
```

---

## 🗄️ Database

The application uses SQLite databases:

- `stem_learn_odisha.db`
- `sessions.db`

The backend automatically creates required tables for:

- Students
- Teachers
- Games
- Assignments
- Quizzes
- Doubts
- User Sessions

---

## 🎮 Learning Modules

### Mathematics
- Knowing Numbers
- Fractions
- Decimal Numbers
- Geometry
- Geometrical Shapes
- Data Management
- Natural Numbers
- Measurements

### Science
- Living Things
- Objects Around Us
- Scientific Activities
- Interactive Learning Games

### English
- Vocabulary Games
- Grammar Activities
- Language Learning Exercises

---

## 📸 File Upload Support

The platform supports:

- Assignment Uploads
- Profile Pictures
- Educational Resources

Uploads are stored in:

```text
/uploads
```

---

## 🔒 Security Features

- Password Hashing using bcrypt
- Session Management
- Input Validation
- Secure Authentication System

---

## 🎯 Target Audience

- School Students
- Teachers
- Educational Institutions
- STEM Learning Programs

---

## 👥 Contributors

Developed as part of the **Smart India Hackathon (SIH)** project to promote engaging STEM education through technology.

---

## 📄 License

This project is developed for educational purposes under the Smart India Hackathon initiative.

---

## Future Enhancements

- AI-powered Doubt Solving
- Leaderboards
- Progress Analytics
- Mobile Application
- Multi-language Support
- Gamification Rewards System

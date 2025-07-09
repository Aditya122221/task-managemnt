## 🎓 TubeAcademy


* Developed a full-stack web application for a coaching institute, supporting three user roles: Admin, Teacher,
and Student.
* Implemented Admin functionalities to register students/teachers, manage salaries, and assign subjects.
* Enabled Teachers to upload, edit, and delete educational videos for students.
* Designed the Student experience to access and watch course videos seamlessly.
* Created individual profile pages for all users, allowing them to update their information.
* Built a secure authentication and authorization system for role-based access control.
* Ensured a responsive and user-friendly UI using React and CSS.</li>

## 🌐 Deployed Link

<a href="https://tube-academy.vercel.app/" target="_blank">https://tube-academy.vercel.app/</a>

## 📁 Directory Structure

```
.
├── README.md
├── backend/
│   ├── .env
│   ├── .env.example
│   ├── .gitignore
│   ├── index.js
│   ├── package-lock.json
│   ├── package.json
│   ├── controllers/
│   │   ├── AddSubTasks.js
│   │   ├── GetAllTasks.js
│   │   ├── Login.js
│   │   ├── Register.js
│   │   ├── TaskAdd.js
│   │   ├── TaskDelete.js
│   │   └── TaskWithId.js
│   ├── models/
│   │   ├── TaskModel.js
│   │   └── UserModel.js
│   └── routes/
│       └── route.js
├── Frontend/
│   ├── .env
│   ├── .env.example
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── vercel.json
│   ├── vite.config.js
│   ├── public/
│   │   └── favicon.ico
│   └── src/
│       ├── App.css
│       ├── App.jsx
│       ├── main.jsx
│       ├── Components/
│       │   ├── Register.jsx
│       │   └── TaskDashboard.jsx
│       ├── CSS/
│       │   ├── Register.module.css
│       │   └── TaskDashboard.module.css
```

## 🛠️ Installation Steps:

<p>1. Clone Repository</p>

```
git clone https://github.com/Aditya122221/TubeAcademy.git
```

<p>2. Frontend Installation</p>

```
cd frontend
```
```
npm install
```

<p>3. Backend Installation</p>

```
cd backend
```
```
npm install
```

<p>4. .env Set up</p>
Create .env file in both Frontend and Backend directory and follow the .env.example file to setup the .env file

## 🛠️ Technologies Used

*   Frontend: React JS, CSS
*   Backend: Express, Node JS
*   Database: Mongo DB
*   Deployment: Vercel, Render
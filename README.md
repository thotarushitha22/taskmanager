# taskmanager
TEAM TASK MANAGER – FULL STACK APPLICATION
===========================================


GitHub Repo: https://github.com/thotarushitha22/taskmanager/edit/main/README.md

PROJECT OVERVIEW
----------------
A web application for teams to create projects, assign tasks, and track progress with role‑based access (Admin / Member).

FEATURES
--------
- Authentication (Signup/Login) with JWT & HTTP‑only cookies.
- Role‑Based Access Control:
  - Admin: full CRUD on projects and tasks, assign members.
  - Member: view and update status only of tasks assigned to them.
- Project management: create, edit, delete, add members.
- Task management: create, assign, set due date, track status (todo/in‑progress/done).
- Dashboard: task statistics (total, by status, overdue) and recent tasks.
- Responsive UI with React + Tailwind CSS.

TECH STACK
----------
Backend: Node.js, Express, MongoDB (Mongoose), JWT, bcryptjs
Frontend: React, React Router, Axios, Tailwind CSS, React Hot Toast
Database: MongoDB (local or Atlas)
Deployment: Railway

LOCAL SETUP
-----------
1. Clone repo: git clone <repo-url>
2. Backend:
   cd backend
   npm install
   Create .env with:
     PORT=5000
     MONGO_URI=mongodb://localhost:27017/taskmanager
     JWT_SECRET=your_secret
     CLIENT_URL=http://localhost:3000
   npm start
3. Frontend:
   cd frontend
   npm install
   Create .env with:
     REACT_APP_API_URL=http://localhost:5000/api
   npm start
4. Open http://localhost:3000

USAGE GUIDE
-----------
1. Sign up as Admin (select "Admin" role).
2. Login → Dashboard.
3. Projects → Create project → add member emails (members must sign up first).
4. Tasks → Create task → assign to member, set due date.
5. Member login (incognito) → only sees assigned tasks → can change status.
6. Dashboard shows counts, including overdue tasks.

DEPLOYMENT ON RAILWAY
---------------------
1. Push code to GitHub.
2. On Railway: New Project → Deploy from GitHub.
3. Create two services:
   Backend:
     Root directory: backend
     Environment: PORT, MONGO_URI (Atlas string), JWT_SECRET, CLIENT_URL (frontend URL)
   Frontend:
     Root directory: frontend
     Environment: REACT_APP_API_URL (backend URL + /api)
4. Deploy. Copy frontend URL → this is your live URL.

API ENDPOINTS (main)
---------------------
POST   /api/auth/signup
POST   /api/auth/login
POST   /api/auth/logout
GET    /api/auth/me
GET    /api/projects
POST   /api/projects       (admin only)
DELETE /api/projects/:id   (admin only)
GET    /api/tasks
POST   /api/tasks          (admin only)
PUT    /api/tasks/:id/status
DELETE /api/tasks/:id      (admin only)
GET    /api/dashboard

KNOWN ISSUES
------------
- If MongoDB Atlas gives "querySrv ECONNREFUSED", use standard connection string (mongodb://) or switch to local MongoDB.
- If port 5000 is in use, kill process: netstat -ano | findstr :5000 → taskkill /PID <PID> /F

SUBMISSION
----------
- Live URL: [TEAM TASK MANAGER – FULL STACK APPLICATION
===========================================

Live URL: [Your Railway frontend URL – add after deployment]
GitHub Repo: [Your GitHub repository URL]

PROJECT OVERVIEW
----------------
A web application for teams to create projects, assign tasks, and track progress with role‑based access (Admin / Member).

FEATURES
--------
- Authentication (Signup/Login) with JWT & HTTP‑only cookies.
- Role‑Based Access Control:
  - Admin: full CRUD on projects and tasks, assign members.
  - Member: view and update status only of tasks assigned to them.
- Project management: create, edit, delete, add members.
- Task management: create, assign, set due date, track status (todo/in‑progress/done).
- Dashboard: task statistics (total, by status, overdue) and recent tasks.
- Responsive UI with React + Tailwind CSS.

TECH STACK
----------
Backend: Node.js, Express, MongoDB (Mongoose), JWT, bcryptjs
Frontend: React, React Router, Axios, Tailwind CSS, React Hot Toast
Database: MongoDB (local or Atlas)
Deployment: Railway

LOCAL SETUP
-----------
1. Clone repo: git clone <repo-url>
2. Backend:
   cd backend
   npm install
   Create .env with:
     PORT=5000
     MONGO_URI=mongodb://localhost:27017/taskmanager
     JWT_SECRET=your_secret
     CLIENT_URL=http://localhost:3000
   npm start
3. Frontend:
   cd frontend
   npm install
   Create .env with:
     REACT_APP_API_URL=http://localhost:5000/api
   npm start
4. Open http://localhost:3000

USAGE GUIDE
-----------
1. Sign up as Admin (select "Admin" role).
2. Login → Dashboard.
3. Projects → Create project → add member emails (members must sign up first).
4. Tasks → Create task → assign to member, set due date.
5. Member login (incognito) → only sees assigned tasks → can change status.
6. Dashboard shows counts, including overdue tasks.

DEPLOYMENT ON RAILWAY
---------------------
1. Push code to GitHub.
2. On Railway: New Project → Deploy from GitHub.
3. Create two services:
   Backend:
     Root directory: backend
     Environment: PORT, MONGO_URI (Atlas string), JWT_SECRET, CLIENT_URL (frontend URL)
   Frontend:
     Root directory: frontend
     Environment: REACT_APP_API_URL (backend URL + /api)
4. Deploy. Copy frontend URL → this is your live URL.

API ENDPOINTS (main)
---------------------
POST   /api/auth/signup
POST   /api/auth/login
POST   /api/auth/logout
GET    /api/auth/me
GET    /api/projects
POST   /api/projects       (admin only)
DELETE /api/projects/:id   (admin only)
GET    /api/tasks
POST   /api/tasks          (admin only)
PUT    /api/tasks/:id/status
DELETE /api/tasks/:id      (admin only)
GET    /api/dashboard

KNOWN ISSUES
------------
- If MongoDB Atlas gives "querySrv ECONNREFUSED", use standard connection string (mongodb://) or switch to local MongoDB.
- If port 5000 is in use, kill process: netstat -ano | findstr :5000 → taskkill /PID <PID> /F

SUBMISSION
----------
- Live URL: [<img width="1881" height="839" alt="image" src="https://github.com/user-attachments/assets/ac865805-432d-4b56-8c4c-420def16f951" />]
- <img width="1896" height="818" alt="image" src="https://github.com/user-attachments/assets/ee4fe4bf-ad97-4114-9fad-f21679630afe" />

- GitHub repo: https://github.com/thotarushitha22/taskmanager/edit/main/README.md
- This README.txt

© 2026

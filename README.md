A full-stack Job Portal web application built with the MERN Stack (MongoDB, Express, React, Node.js).
It allows job seekers to browse & apply for jobs and employers to post and manage job listings.

🚀 Features
For Job Seekers

Create profile & upload resume

Browse & search jobs

Filter jobs by category, location, salary

Apply for jobs

Track job applications

For Employers

Create employer account

Post new job listings

Manage (edit/delete) job posts

View applications received

Authentication & Security

JWT-based authentication

Password hashing with bcrypt

Role-based access (Admin / Employer / Job Seeker)

🛠 Tech Stack

Frontend: React.js, React Router, Axios, TailwindCSS / Bootstrap
Backend: Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt.js
Database: MongoDB Atlas or Local MongoDB

📁 Project Structure
JobPortal/
 ├── backend/
 │   ├── config/
 │   ├── controllers/
 │   ├── models/
 │   ├── routes/
 │   ├── middleware/
 │   └── server.js
 │
 └── frontend/
     ├── public/
     ├── src/
     │   ├── components/
     │   ├── pages/
     │   ├── context/ or store/
     │   └── App.js
     └── package.json

⚙️ Installation
1. Clone the repository
git clone https://github.com/AnkitaKumari-14/JobPortal.git

2. Install backend dependencies
cd backend
npm install

3. Install frontend dependencies
cd ../frontend
npm install

4. Setup environment variables

Create a .env file in backend/:

MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000

▶️ Run Application

Backend:

cd backend
npm start


Frontend:

cd frontend
npm start


Frontend: http://localhost:3000

Backend: http://localhost:5000

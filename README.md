🏥 Prescripto – Hospital Management System

A full-stack MERN application designed to streamline hospital operations with dedicated dashboards for Admins, Doctors, and Patients. It simplifies appointment booking, prescription management, and record keeping with a clean and responsive UI.

🚀 Features

👩‍⚕️ Doctor Dashboard – manage appointments, view patient history, add prescriptions

👨‍🦰 Patient Dashboard – book appointments, track prescriptions, view history

🛠️ Admin Dashboard – manage doctors, patients, and overall records

🔐 Authentication & Authorization – secure login with JWT & role-based access

📅 Appointment Management – schedule, approve, cancel, and track bookings

📊 Database Integration – MongoDB for structured storage of users, doctors, patients, and appointments

📱 Responsive UI – built with React & Tailwind CSS for mobile and desktop

🛠️ Tech Stack

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT

⚡ Installation & Setup

Clone this repository

git clone https://github.com/your-username/prescripto.git
cd prescripto


Install dependencies for both frontend and backend

cd client && npm install
cd ../server && npm install


Configure environment variables (.env):

MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
PORT=5000


Start the project

# Run backend
cd server && npm start

# Run frontend
cd client && npm run dev

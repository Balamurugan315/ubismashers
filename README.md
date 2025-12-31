🏸 UBISmashers

UBISmashers is a full-stack web application designed to manage group expenses, payments, attendance, and reports for sports clubs or shared groups.
It provides role-based access for Admins and Members, real-time financial visibility, and smooth cloud deployment.

🔗 Live App: https://ubismashers.vercel.app/

🚀 Features
👤 Authentication & Roles

Secure JWT-based authentication

Role-based access control:

Admin

Member

Inactive members cannot log in

📊 Dashboard

Outstanding & completed payments summary

Quick access to expenses, payments, and attendance

Role-specific views (Admin vs Member)

💰 Expense Management

Admin can create expenses

Expenses are split among members

Members can:

View their expenses

Track payment status & history

Admin can:

View member-wise expense status

See pending and completed payments

💳 Payments

Members submit payments

Admin approves payments

Automatic balance updates

Payment approval notifications

🔔 Notifications

Admin notifications:

New payment requests

Member notifications:

New expenses

Payment approval confirmations

📈 Reports

Admin:

View total expenses

Member-wise expense reports

Member:

View only their own expenses

Export reports as Excel files

Reports include UBISmashers copyright

📅 Attendance

Daily attendance tracking

Simplified (no per-member expense sharing)

⚙️ Settings

Profile settings

Notification preferences

Group-level settings (Admin only)

🛠 Tech Stack
Frontend

React + TypeScript

Vite

Tailwind CSS

shadcn/ui

Hosted on Vercel

Backend

Node.js

Express

TypeScript

JWT Authentication

Hosted on Render

Database

MongoDB Atlas (Cloud)

🤖 AI-Assisted Development

This project was built with the help of:

Lovable

Cursor

AI tools accelerated development, but real-world debugging, deployment issues, authentication logic, and database consistency were handled manually — making this a strong production-grade learning experience.

🌍 Deployment Architecture
Frontend → Vercel
Backend  → Render
Database → MongoDB Atlas


Environment variables securely managed

CORS configured for production domains

Health check endpoint for backend monitoring

🧪 API Health Check
GET /health


Response:

{
  "status": "ok",
  "message": "Court Cost Connect API is running"
}

📦 Environment Variables
Backend (Render)
PORT=5000
MONGODB_URI=your_mongodb_atlas_url
JWT_ACCESS_SECRET=your_secret
JWT_REFRESH_SECRET=your_secret
FRONTEND_URL=https://ubismashers.vercel.app

Frontend (Vercel)
VITE_API_URL=https://your-backend.onrender.com

🧑‍💻 Getting Started (Local Setup)
1️⃣ Clone the repository
git clone https://github.com/Balamurugan315/UBIsmashers.git
cd UBIsmashers

2️⃣ Backend Setup
cd server
npm install
npm run dev

3️⃣ Frontend Setup
cd client
npm install
npm run dev

📌 Future Improvements

Push notifications

Role-based analytics

Mobile-friendly UI enhancements

Admin audit logs

🙌 Author

Bala Murugan
Full-Stack Developer
Built with passion, debugging, and persistence 🚀


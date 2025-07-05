💸 SplitManage – Expense Sharing & Bill Split App (MERN Stack)
SplitManage is a full-featured expense splitting application built with the MERN stack, designed to help users manage shared expenses with friends, roommates, or groups. It's ideal for group trips, household bills, or collaborative event planning.

📌 Features
👤 User Authentication – Secure login with sessions/token

👥 Create & Manage Groups – Add people to shared groups

💸 Split Bills Easily – Automatically divide expenses among members

📊 Dashboard Summary – See who owes whom in real time

🧾 Expense History – View itemized breakdown of all past expenses

📷 Responsive UI – Modern design compatible with all devices

⚙️ Tech Stack
Layer	Tech
Frontend	React.js, Axios, Tailwind CSS (or Bootstrap)
Backend	Node.js, Express.js
Database	MongoDB (Mongoose ORM)
API Tests	Postman (API_collection.json)
Deployment	Render / Heroku-ready (Procfile included)

📁 Project Structure
bash
Copy
Edit
SplitManage/
├── client/                     # Frontend files (React)
├── components/                 # Reusable React components
├── helper/                     # Utility functions
├── model/                      # MongoDB models (User, Group, Expense)
├── routes/                     # Express API routes
├── Screenshots/               # UI screenshots
├── API_collection.json         # Postman collection for backend API
├── app.js                      # Entry point for Express server
├── package.json                # Backend dependencies
├── Procfile                    # Deployment config (Render/Heroku)
└── dashboard-main-transparent.png  # Main dashboard preview image
🚀 Getting Started
🔧 Prerequisites
Node.js & npm

MongoDB Atlas or local MongoDB

Git

📦 Install Dependencies
bash
Copy
Edit
npm install
🛠️ Configure .env (if needed)
If you're using MongoDB Atlas or JWT tokens, create a .env:

env
Copy
Edit
PORT=5000
MONGO_URI=mongodb+srv://your-uri
JWT_SECRET=your_jwt_secret
▶️ Run the App
bash
Copy
Edit
npm start
Then visit:
http://localhost:5000 for backend (or frontend if integrated)

🧪 API Testing
This project includes a Postman collection to test all API endpoints.

📂 File: API_collection.json

Import this into Postman and test:

/register

/login

/group/create

/expense/add

/expense/settle

etc.


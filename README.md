💸 Polari X – Finance Manager

A modern personal finance dashboard that helps users track income, expenses, assets, and liabilities through interactive visualizations and an intuitive fintech-style interface.

🔗 Live Demo: https://polari-x-finance-manager.vercel.app/

🚀 Project Overview

Polari X is a smart financial management platform built to simplify how individuals understand their money. Instead of boring spreadsheets, users get visual insights, dynamic charts, and a clean UI that makes financial tracking easy and engaging.

It combines data visualization, user authentication, and profile management into one seamless experience.

🧩 Features

📊 Comprehensive Finance Dashboard

-  Income & Spending trend analysis
-  Income vs Expense comparison graph
-  Assets & Liabilities growth visualization
-  Category-based pie charts
-  Horizontal bar graphs for financial breakdown

🔄 Interactive Data Experience

- Flip cards reveal detailed data tables
- Dynamic charts powered by Chart.js

🎨 Modern UI/UX

- Inspired by Cred.club aesthetics
- Clean, minimal, responsive layout
- Vibrant chart colors on dark theme

🔀 User Controls

- Monthly / Yearly data toggle
- Light / Dark mode switch

🧾 User Profile Management

- Name, occupation, contact, city, DOB
- Persistent storage using MongoDB

🔐 Authentication System

- Secure Signup & Login
- Backend validation via Node.js + Express

🏗️ Tech Stack

- Frontend	HTML, CSS, JavaScript, Chart.js
- Backend	Node.js, Express.js
-  Database	MongoDB (Mongoose)
-  Authentication	Express + MongoDB
-  Deployment	Vercel (Frontend), Render/Railway/Cyclic (Backend)
  
🔁 Application Workflow

- User signs up or logs in securely
- User enters financial details (income, expenses, assets, liabilities)
- Data is stored in MongoDB
- Dashboard fetches data and renders:
- Line graphs
- Pie charts
- Bar charts
- User can toggle:
- Monthly/Yearly view
- Light/Dark mode

Profile details are editable and persist in database

📦 Project Structure
│
├── /frontend
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── charts.js
│
├── /backend
│   ├── server.js
│   ├── routes/
│   ├── models/
│   └── controllers/
│
└── README.md

⚙️ Backend Details

Runtime: Node.js

Framework: Express.js

Database: MongoDB (Mongoose)

Handles:

User authentication

Profile storage

Financial data storage

🛠️ Setup Instructions
📌 Prerequisites

Node.js & npm

MongoDB Atlas / Local MongoDB

📥 Installation
# Clone repo
git clone https://github.com/your-username/polari-x-finance-manager.git
cd polari-x-finance-manager

# Install backend dependencies
npm install

# Start server
npm start

👩‍💻 Team & Credits

👩‍💻 Sakshi Saini – Frontend Developer & UI/UX Designer

👨‍💻 Pulkit Sachdeva – Backend Developer

🎯 Project Vision

 💸 Polarix aims to transform financial tracking from complex and overwhelming to visual, intuitive, and empowering, helping users make smarter financial decisions with clarity.

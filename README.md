# 💰 Expense Tracker — Web Technologies Project  

A **full-stack Expense Tracker** built using the **MERN Stack (MongoDB, Express, React, Node.js)**.  
This project allows users to **record, categorize, and analyze** their daily expenses with **secure authentication**, **interactive dashboards**, and **clean visual insights**.  

---

## 🌐 Live Demo  
🔗 [View Demo](https://www.flexclip.com/share/14506219CWswFCsuEDrmEFfLIVLSC9zUQUi034Mc.html)  

---

## 👤 Author  
**Mokshi Jain**  
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/mokshi-jain-5b920930b/)  
- 💻 [GitHub Repository](https://github.com/mokshijain22/expense-tracker-webtech-project.git)  

---

## 🚀 Features  
- 🔐 **User Authentication** (JWT-based Login & Signup)  
- 💸 **Add, Edit, and Delete** Income & Expenses  
- 🏷️ **Categorize Transactions** (e.g., Food, Travel, Bills, Shopping, etc.)  
- 📊 **Expense Analysis Dashboard** with interactive charts  
- ☁️ **MongoDB Atlas Integration** for cloud database storage  
- ⚡ **RESTful APIs** with Express.js  
- 🌙 **Modern Responsive UI** built with React.js and Material-UI  
- 📈 **Visual Insights** using Chart.js  
- 🔄 **Real-Time Updates**

---

## 🧠 Tech Stack  

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | React.js, Material-UI, Chart.js |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas |
| **Authentication** | JSON Web Token (JWT) |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation & Setup  

### 🗂 1️⃣ Clone the Repository  
```bash
git clone https://github.com/mokshijain22/expense-tracker-webtech-project.git
cd expense-tracker-webtech-project

2️⃣ Setup Backend
cd backend
npm install


Create a .env file inside the backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Run the backend server:

npm start


Your backend should now be running at 👉 http://localhost:5000

🎨 3️⃣ Setup Frontend
cd frontend
npm install


Start the React app:

npm run dev


The frontend should now be running at:
👉 http://localhost:5173
 (if using Vite)
or
👉 http://localhost:3000
 (if using Create React App)

📂 Folder Structure
Expense-Tracker-WebTech-Project/
│
├── backend/               # Node.js + Express.js server
│   ├── models/            # MongoDB models
│   ├── routes/            # API routes
│   ├── controllers/       # Logic for handling routes
│   ├── config/            # DB configuration
│   └── server.js          # Entry point
│
├── frontend/              # React frontend
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── pages/         # Pages (Dashboard, Login, Signup)
│   │   └── App.js         # Main React component
│
└── README.md

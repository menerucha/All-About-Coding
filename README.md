# 📘 All About Coding

A scalable full-stack MERN platform that unifies structured programming education with real-time LeetCode progress tracking, eliminating context switching between learning and problem-solving.

---

## 🚀 Problem Statement

Most learners consume theory on one platform and practice coding on another, resulting in fragmented progress tracking and reduced consistency.

**All About Coding** bridges this gap by integrating public LeetCode profiles directly into a centralized learning dashboard.

---

## ✨ Core Features

- 📚 Structured learning paths for core programming concepts  
- 📊 Real-time LeetCode profile integration  
- 🔄 Normalized user progress tracking  
- 🧩 Reusable component-based frontend architecture  
- ⚡ RESTful API communication  
- 📦 Modular backend design  

---

## 🏗 Architecture Overview


Client (React + Vite)
        │
│ REST API Calls
        ▼
Backend (Node.js + Express)
       │
│ Data Fetch & Normalization
▼
LeetCode Public Profile
         │
▼
MongoDB (User Progress Storage)


### Design Principles

- Separation of concerns (client/server architecture)
- Layered backend structure (routes → controllers → services → models)
- Stateless REST APIs
- Scalable MongoDB schema design

---

## 🛠 Tech Stack

### Frontend
- React.js  
- Tailwind CSS  
- Vite
- HTML
- CSS
- Javascript

### Backend
- Node.js  
- Express.js  
- REST APIs  

### Database
- MongoDB  

### Deployment
- Render  

---

## 📂 Repository Structure


All-About-Coding/
│
├── client/ # React frontend
│ ├── components/
│ ├── pages/
│ └── services/
│
├── server/ # Express backend
│ ├── routes/
│ ├── controllers/
│ ├── services/
│ ├── models/
│ └── config/
│
└── README.md


---

## ⚙️ Running Locally

### 1️⃣ Clone the Repository

git clone https://github.com/menerucha/All-About-Coding
cd All-About-Coding
2️⃣ Backend Setup
cd server
npm install

Create a .env file inside /server:

PORT=5000
MONGO_URI=your_mongodb_connection_string

Start backend:

npm run dev
3️⃣ Frontend Setup

Open a new terminal:

cd client
npm install
npm run dev

Application runs at:

http://localhost:5173
🔐 Environment Requirements

Node.js v18+

MongoDB (local or cloud instance)

📈 Performance Considerations

Optimized API payloads

Asynchronous data fetching

Modular service layer

Reusable React components

🤝 Contributing

Fork the repository

Create a new branch (git checkout -b feature-name)

Commit changes (git commit -m "Add feature")

Push (git push origin feature-name)

Open a Pull Request

🔮 Roadmap

Authentication & role-based access control

Admin content management dashboard

Caching layer

CI/CD integration

Dockerized deployment

👩‍💻 Author

Rucha Mene
Computer Science Undergraduate | Full-Stack Developer

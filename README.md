# 📘 All About Coding

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/Node.js-v18%2B-green)](https://nodejs.org/)
[![Framework: React](https://img.shields.io/badge/Framework-React-blue)](https://reactjs.org/)

A scalable full-stack MERN platform that unifies structured programming education with real-time LeetCode progress tracking, eliminating context switching between learning and problem-solving.

---

## 🚀 Problem Statement

Most learners consume theory on one platform and practice coding on another, resulting in fragmented progress tracking and reduced consistency. 

**All About Coding** bridges this gap by integrating public LeetCode profiles directly into a centralized learning dashboard, providing a "single pane of glass" for a developer's growth.

---

## ✨ Core Features

* **📚 Structured Learning Paths:** Organized modules for core programming concepts and DSA.
* **📊 LeetCode Integration:** Real-time fetching and normalization of public LeetCode profile data.
* **🔄 Unified Progress:** Centralized tracking for both course completion and coding milestones.
* **🧩 Reusable Architecture:** Component-based frontend built with React and Vite.
* **⚡ RESTful API:** Modular backend design with a clear separation of concerns.

---

## 🏗 Architecture Overview

The application follows a **Decoupled Client-Server Architecture**:



[Image of MERN stack architecture diagram]


1.  **Client (React + Vite):** Handles UI/UX and state management.
2.  **Backend (Node.js + Express):** Processes business logic and fetches 3rd-party data.
3.  **External API:** Fetches live data from LeetCode public profiles.
4.  **Database (MongoDB):** Stores user progress, metadata, and learning paths.

### Design Principles
* **Layered Structure:** Routes → Controllers → Services → Models.
* **Statelessness:** Clean REST API implementation.
* **Scalability:** Normalized MongoDB schema for efficient data retrieval.

---

## 🛠 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | React.js, Tailwind CSS, Vite |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose) |
| **Deployment** | Render |

---

## 📂 Repository Structure

<img width="345" height="221" alt="image" src="https://github.com/user-attachments/assets/ec006561-c3a3-4753-90e7-5f8331eec648" />

## ⚙️ Running Locally

### 1. Clone the Repository
* **Command:**
    * git clone
      [https://github.com/menerucha/All-About-Coding](https://github.com/menerucha/All-About-Coding)
    * cd All-About-Coding


### 2. Backend Setup
* **Navigate to server:** `cd server`
* **Install dependencies:** `npm install`
* **Configure Environment:** Create a `.env` file in the `/server` directory:
    ```env
    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    ```
* **Start Server:** `npm run dev`

### 3. Frontend Setup
* **Open a new terminal**
* **Navigate to client:** `cd client`
* **Install dependencies:** `npm install`
* **Start Client:** `npm run dev`
* **Access App:** The application will be available at `http://localhost:5173`

---

## 📈 Performance Considerations

* **Optimized API Payloads:** Returns only necessary data to reduce latency and bandwidth usage.
* **Asynchronous Processing:** Efficient, non-blocking data fetching from external LeetCode APIs.
* **Modular Services:** Logic is decoupled into services to ensure easy maintenance and unit testing.

---

## 🔮 Roadmap

* [ ] **Authentication:** Implementation of JWT & Role-Based Access Control (RBAC).
* [ ] **Admin Dashboard:** Content management interface for curriculum updates.
* [ ] **Caching:** Integration of Redis for high-frequency LeetCode API requests.
* [ ] **DevOps:** Dockerized deployment and CI/CD pipeline integration.
* [ ] **UI/UX:** Native Dark Mode support and progress visualization charts.

---

## 🤝 Contributing

1.  **Fork** the repository.
2.  **Create** a new branch (`git checkout -b feature-name`).
3.  **Commit** your changes (`git commit -m "Add feature"`).
4.  **Push** to the branch (`git push origin feature-name`).
5.  **Open** a Pull Request.

---

## 👩‍💻 Author

**Rucha Mene**
*Computer Science Undergraduate | Full-Stack Developer*

# 📘 All About Coding  
**An Interactive Learning Platform with Integrated LeetCode Progress Tracking**

---

## 🚀 Overview

**All About Coding** is a full-stack MERN application designed to unify **learning and real coding practice** into a single platform.

The platform addresses a common problem faced by learners:
> Learning happens on one platform, practice on another, and progress is never tracked consistently.

To solve this, the application integrates **public LeetCode profiles** directly into the learning dashboard, allowing users to align theory with actual problem-solving progress.

---

## 🎯 Key Objectives

- Provide **structured learning paths** for programming concepts  
- Reduce learner drop-off caused by poor navigation and content overload  
- Maintain **cross-platform consistency** by integrating LeetCode progress  
- Build a scalable, maintainable full-stack architecture  

---

## 🛠 Tech Stack

### Frontend
- React.js  
- JavaScript (ES6+)  
- HTML5, CSS3  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  
- REST APIs  

### Database
- MongoDB  

### Tools & Platforms
- Git & GitHub  
- Axios  
- Render (Deployment)

---

## 🧠 System Architecture

```text
Client (React)
   |
   | REST API calls
   v
Backend (Node.js + Express)
   |
   | External data fetch & normalization
   v
LeetCode Public Profile
   |
   v
MongoDB (Normalized User Progress)

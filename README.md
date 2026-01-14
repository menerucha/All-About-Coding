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

✨ Core Features
📚 Structured Learning Paths

50+ programming topics organized into progressive learning modules

Reduced cognitive overload through clean navigation

Improved course completion rate by ~40%

🔗 LeetCode Profile Integration (Key Feature)

Users can link their public LeetCode profile to the platform.

Why this matters

Avoids duplicate progress tracking

Leverages trusted, real problem-solving metrics

Aligns learning content with actual practice

How it works

User submits LeetCode username

Backend fetches public profile data

Data is parsed and normalized

Progress is stored in MongoDB

Frontend displays unified learning + practice insights

⚙️ Backend API Design

Example endpoint:

POST /api/leetcode/connect


Responsibilities

Validate LeetCode username

Fetch public profile data

Normalize inconsistent external data

Cache results for performance

Ensure frontend stability even if external source fails

🗃 Database Design (Simplified)
UserProgress {
  userId,
  leetcode: {
    username,
    totalSolved,
    easySolved,
    mediumSolved,
    hardSolved,
    lastSyncedAt
  }
}


External data is never sent directly to the frontend

Frontend consumes only normalized, internal schemas

🛡 Reliability & Failure Handling

Graceful handling of:

Invalid usernames

External service downtime

Rate limiting

Cached data served when live sync fails

Platform functionality never blocked by external dependencies

📈 Performance & Scalability

Cached LeetCode stats reduce repeated external calls

Backend isolates integration logic for easy maintenance

Designed for future upgrades:

Background sync jobs

Queue-based processing

Official API integration (if available)

🧪 What This Project Demonstrates

Real-world API integration

Backend data normalization & caching

Clean separation of concerns

Product-driven engineering decisions

Full-stack ownership from UI to deployment

🔮 Future Improvements

Authentication & personalized dashboards

Topic-based recommendations using LeetCode performance

Scheduled background syncing

Analytics for learning progress trends

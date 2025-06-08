# mern-job-portal-tutorial
# 💼 Job Portal Tutorial

This project is a **job portal** that connects **job seekers** and **recruiters**.

- 👤 Job seekers can browse & apply for jobs and manage profiles.  
- 🏢 Recruiters can register companies, post jobs, and handle applications.  
- 🛠️ Built using a backend API (Node.js, MongoDB) and frontend with React & Redux.

---

## 🔍 Visual Overview

```mermaid
flowchart TD
    A0["User Authentication & Profile Management"]
    A1["Company Management"]
    A2["Job Management"]
    A3["Job Applications"]
    A4["Database Models (Mongoose Schemas)"]
    A5["Backend API Core (Entry, Routes, Controllers)"]
    A6["Authentication & Authorization Middleware"]
    A7["Frontend State Management (Redux Toolkit)"]

    A7 -->|Triggers API Calls| A5
    A5 -->|Applies Security| A6
    A6 -->|Verifies User| A0
    A5 -->|Interacts with Data| A4
    A5 -->|Updates Frontend| A7
    A1 -->|Companies Post Jobs| A2
    A0 -->|Users Apply| A3
    A2 -->|Jobs Receive Applications| A3

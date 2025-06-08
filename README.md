# 💼 MERN Job Portal App

A full-featured **Job Portal** built using the **MERN Stack**.

- 👩‍💻 Job Seekers can register, log in, create profiles & apply for jobs.
- 🧑‍💼 Recruiters can manage companies, post jobs & handle applications.
- 🌐 Built with: **MongoDB**, **Express**, **React**, **Node.js**, and **Redux Toolkit**.

---


```markdown
# Tutorial: Job Portal

This project is a **job portal** that connects *job seekers* and *recruiters*...

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

    A7 -- "Triggers API Calls" --> A5
    A5 -- "Applies Security" --> A6
    A6 -- "Verifies User" --> A0
    A5 -- "Interacts with Data" --> A4
    A5 -- "Updates Frontend" --> A7
    A1 -- "Companies Post Jobs" --> A2
    A0 -- "Users Apply" --> A3
    A2 -- "Jobs Receive Applications" --> A3


## 📘 Full Tutorial (All Chapters Included)

> 🔗 **Explore the entire step-by-step tutorial here:**  
> 👉 [**View on Code2Tutorial.com**](https://code2tutorial.com/tutorial/907f3622-01a3-4e27-83a3-767dd6bd7a21/index.md)

---

## 🧠 Topics Covered

- 🔐 **Authentication with JWT**
- 🧾 **User & Company Management**
- 🗂️ **CRUD for Jobs and Applications**
- 🔄 **Redux Toolkit for State Management**
- 🛡️ **Protected Routes & Middleware**
- 📦 **Mongoose Schema Design**

# 🧠 Personal Work Organizer (MVP)

A lightweight, local-first task management and decision-support system built with **Streamlit** and **JSON**.

This project focuses on a simple goal:

> **Help me decide what to do next — quickly and clearly.**

---

## 🚀 Overview

This tool is a personal productivity system that:

- Organizes tasks (one-time, periodic, progressive)
- Tracks deadlines and priorities
- Highlights urgent and overdue work
- Recommends what to do next

Everything runs **locally** — no cloud, no paid services.

---

## 🎯 MVP Scope

This is a **Minimum Viable Product (MVP)**.

### ✅ Included

- Add / edit / delete tasks
- Task categorization:
  - one-time
  - periodic
  - progressive
- Set:
  - due date
  - priority
  - status (not started / in progress / done)
- View:
  - all tasks
  - overdue tasks
  - tasks due soon
- Recommendation:
  - “What should I do next?”

---

### ❌ Not included (future work)

- Calendar view
- Advanced recurring logic
- Full project/milestone tracking
- Autonomous AI agent behavior
- Cloud sync / multi-device support

---

## 🧱 Architecture (Simple & Local)
```
[ Streamlit App ]
│
├── task_manager.py
├── recommender.py
└── tasks.json (local storage)
```

- No backend server
- No external database
- No paid API required

---

## 🗂️ Project Structure
```
personal-work-organizer/
│
├── app.py # Streamlit UI
├── task_manager.py # Task CRUD + JSON handling
├── recommender.py # Task prioritization logic
├── utils.py # Helper functions
├── tasks.json # Local task storage
├── requirements.txt
└── README.md
```
---

## ⚙️ Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/personal-work-organizer.git
cd personal-work-organizer


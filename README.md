# Task Scheduler with Notifications — Project Documentation

## 🗓️ Project Overview

A desktop reminder application built using Python and Tkinter that helps users create and manage scheduled tasks. The app supports due dates, recurring tasks (daily or weekly), and sends real-time desktop notifications using the Plyer library. Task data is saved in SQLite, and unique task IDs are generated using base62 encoding.

---

## ✨ Key Features

- Add tasks with title, description, due date and time.  
- Specify task repetition: once, daily, or weekly.  
- Background thread monitors and triggers alerts on time.  
- Tasks stored persistently in SQLite.  
- Notification popup using cross-platform Plyer library.  
- Task IDs are uniquely generated with custom base62 logic.

---

## 💻 Technologies Used

- Python 3.12  
- Tkinter (GUI)  
- SQLite3 (Local Database)  
- Plyer (Desktop notifications)  
- Base62 encoding (for ID logic)

---

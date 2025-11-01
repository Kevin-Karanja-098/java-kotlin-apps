<p align="center">
  <img src="screenshots/logo.png" alt="KevTech Logo" width="120" />
</p>

<h1 align="center">💬 KevTech — Social Connect App</h1>

<p align="center">
  A modern social Android app that brings users together through <b>chats</b>, <b>blogs</b>, <b>statuses</b>, and <b>community posts</b>.<br>
  Built with ❤️ using <b>Java (Android)</b> and powered by <b>Django REST API + PostgreSQL</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Java-blue?style=for-the-badge&logo=java" />
  <img src="https://img.shields.io/badge/Backend-Django-green?style=for-the-badge&logo=django" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/UI-Material%20Design-orange?style=for-the-badge&logo=android" />
  <img src="https://img.shields.io/badge/API-REST%20JSON-lightgrey?style=for-the-badge" />
</p>

---

## 🌟 Overview

**KevTech** is a social networking Android app designed for seamless communication and content sharing.  
Users can **chat**, **post blogs**, **share statuses**, **react**, **comment**, and **view insights** — all in one clean, responsive interface.

KevTech focuses on:
- Smooth, real-time user experience  
- Clean UI with Material Design  
- Reliable REST API with Django  
- Secure authentication and scalable data storage  

---

## 🧠 Key Features

✅ **Instant Messaging** — 1-on-1 chats with typing indicators and delivery status  
📝 **Blog Posts** — create and publish rich text posts with images  
📸 **Stories & Statuses** — share temporary posts that auto-expire  
👀 **Post Analytics** — see who viewed, liked, or commented  
💬 **Interactive Feed** — scroll through trending content  
🔔 **Notifications** — real-time updates for chats and posts  
👤 **User Profiles** — editable bio, profile photo, followers/following  
⚙️ **Settings Page** — manage account and app preferences  
🛡️ **Secure Authentication** — token-based login using Django REST  

---

## 🏗️ System Architecture


---

## 🖼️ Screenshots

### 🧭 First Row
| Home Feed | Chat Screen | Status | Profile |
|------------|-------------|---------|----------|
| ![Home](screenshots/home.png) | ![Chat](screenshots/chat.png) | ![Status](screenshots/status.png) | ![Profile](screenshots/profile.png) |

### 🚀 Second Row
| Create Post | Blog View | Notifications | Settings |
|--------------|------------|----------------|-----------|
| ![Create](screenshots/create_post.png) | ![Blog](screenshots/blog.png) | ![Notifications](screenshots/notifications.png) | ![Settings](screenshots/settings.png) |

> 🖼️ *All images are located in the `/screenshots` folder.*

---

## ⚙️ Installation & Setup

### 🔧 Backend Setup (Django)
```bash
# Clone the backend
git clone https://github.com/yourusername/kevtech-backend.git
cd kevtech-backend

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Start development server
python manage.py runserver

# 📝 Blog API

A simple and secure RESTful API for managing blog posts, built using **Django** and **Django REST Framework (DRF)**. It supports user authentication, permissions, throttling, and RESTful endpoints for listing and creating posts.

---

## 📌 Features

- ✅ List and create blog posts
- 🔒 Basic Authentication
- 🛡️ Permissions (`IsAuthenticated`)
- ⚡ Request Throttling (Scoped)
- 🗃️ Admin panel for managing posts
- 🚀 DRF ViewSets and Routers

---

## 📁 Project Structure

blog_project/
│
├── blog/ # Main app
│ ├── migrations/ # Database migration files
│ ├── admin.py # Admin panel registration
│ ├── models.py # Post model definition
│ ├── serializers.py # DRF serializers for the Post model
│ ├── views.py # ViewSets for Post API
│ ├── urls.py # App-level API routing
│
├── blog_project/ # Project configuration
│ ├── settings.py # Django settings
│ ├── urls.py # Root URL routing
│
├── manage.py # Django CLI management script



---

## ⚙️ Installation

### 1. Clone the repository


git clone https://github.com/HooriaMujtaba1/Blog-Api-Posts.git
cd blog_project

## 📬 Contact

For questions or suggestions, reach out to hooriamughal275@gmail.com


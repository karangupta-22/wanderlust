# 🌍 Wanderlust

**Wanderlust** is a full-stack web application for exploring and managing beautiful travel destinations. Built using the **MERN stack** (MongoDB, Express.js, Node.js) with **EJS** for templating and **MVC architecture**, this app allows admins to manage places while users can view, review, and comment.

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Templating Engine:** EJS  
- **Database:** MongoDB (via Mongoose)  
- **Authentication:** Passport.js, Express-session  
- **Architecture:** MVC Pattern  
- **Styling:** Bootstrap 5, Custom CSS  

---

## ✨ Features

### 🔒 Admin
- Full **CRUD** operations on visiting places
- Can add/edit/delete new travel destinations

### 👥 User
- View all listed places
- **Post comments and reviews**
- **Authentication & Authorization** system
- Friendly UI for seamless navigation

---

## 📁 Project Structure (MVC)

wanderlust/
├── models/ # Mongoose models (User, Place, Review)
├── routes/ # Route files for different parts of the app
├── controllers/ # Controller logic for each route
├── views/ # EJS templates
│ ├── partials/ # Reusable components like header/footer
├── public/ # Static assets (CSS, JS, images)
├── middleware/ # Custom middleware functions
├── app.js # Entry point

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust

## Install Dependency
- npm install

## Set up environment variables
- DATABASE_URL=your_mongodb_connection_string
- SECRET=your_session_secret

## Run the app
- node app.js

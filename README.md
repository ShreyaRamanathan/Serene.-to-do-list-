# Serene.-to-do-list-
Firebase-powered To-Do List with authentication and cloud persistence.
# 📝 Firebase To-Do List

A modern and responsive **To-Do List web application** built with Firebase Authentication and Firestore. Users can securely manage their tasks, while Guest Mode provides device-specific todo persistence.

## ✨ Features

* 🔐 Firebase Authentication
* ☁️ Firestore cloud data persistence
* 👤 User-specific todo lists
* 👻 Guest Mode
* 💾 Device-specific Guest Mode persistence
* ➕ Add, edit and delete todos
* ✅ Mark tasks as completed
* 🔄 Persistent data across refresh and re-login
* 📱 Responsive user interface
* ⚡ Fast and lightweight frontend

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript
* Firebase Authentication
* Firebase Firestore
* Vite
* Git & GitHub

## 🔥 Firebase Integration

Authenticated users have their todos associated with their Firebase user ID, while Guest Mode maintains a persistent guest identity for the same browser/device.

This keeps user data separated and allows previously created todos to be restored when returning to the application.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the project

```bash
cd YOUR-REPOSITORY
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the localhost URL shown in the terminal.

## 🔐 Firebase Setup

To run the project with your own Firebase project:

1. Create a Firebase project.
2. Enable Firebase Authentication.
3. Enable the required sign-in provider.
4. Create a Firestore Database.
5. Add your web app in Firebase.
6. Configure the Firebase web configuration in the project.
7. Configure appropriate Firestore Security Rules.

> Never upload Firebase service-account private keys or other sensitive credentials to GitHub.

## 📂 Project Structure

```text
├── src/
│   ├── main.js
│   └── ...
├── public/
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## 🎯 Project Goal

The goal of this project is to provide a simple and reliable task-management application with cloud synchronization for authenticated users and persistent device-based storage for Guest Mode.

## 👩‍💻 Author

**Shreya Ramanathan**

BE Computer Science and Engineering
Saranathan College of Engineering

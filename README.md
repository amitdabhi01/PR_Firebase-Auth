# 🔐 PR-Auth-Firebase

A modern **React + Firebase Authentication** project with Email/Password login, Google Sign-In, and User Registration. Built using **React, Vite, Firebase, and React-Bootstrap** for clean UI and fast performance.

---

## 🚀 Features

* ✅ Email & Password Authentication
* 🔐 Firebase Authentication Integration
* 🌐 Google Sign-In (OAuth)
* 📝 New User Registration
* 🔄 Login / Signup Toggle
* ⏳ Loading State Handling
* 🎨 Responsive UI with React-Bootstrap
* ⚡ Fast build with Vite

---

## 🧰 Tech Stack

* **Frontend:** React + Vite
* **UI Library:** React-Bootstrap
* **Authentication:** Firebase Auth
* **Language:** JavaScript (JSX)
* **Bundler:** Vite

---

## 📁 Project Structure

```
PR-Auth-Firebase/
│
├── public/
├── src/
│   ├── assets/
│   ├── auth/
│   │   └── Auth.jsx
│   ├── App.jsx
│   ├── main.jsx
│   ├── config.js   # Firebase config
│
├── .env
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🔑 Firebase Setup

1. Go to **Firebase Console**
2. Create a new project
3. Enable Authentication:

   * Email/Password
   * Google Provider
4. Get Firebase config and add to `config.js`

### Example `config.js`

```js
import { initializeApp } from "firebase/app";
import { getAuth, GoogleAuthProvider } from "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
};

const app = initializeApp(firebaseConfig);
export const auth = getAuth(app);
export const googleProvider = new GoogleAuthProvider();
```

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/your-username/PR-Auth-Firebase.git

# Go to project folder
cd PR-Auth-Firebase

# Install dependencies
npm install

# Start project
npm run dev
```

---

## 🔐 Authentication Methods

| Method                | Status |
| --------------------- | ------ |
| Email/Password Login  | ✅      |
| Email/Password Signup | ✅      |
| Google Sign-In        | ✅      |
| Firebase Auth         | ✅      |

---

## 🖥️ UI Preview

* Clean centered login card
* Google login button
* Toggle between Login & Signup
* Responsive layout

---

## 📌 Environment Variables (.env)

```
VITE_FIREBASE_API_KEY=xxxx
VITE_FIREBASE_AUTH_DOMAIN=xxxx
VITE_FIREBASE_PROJECT_ID=xxxx
VITE_FIREBASE_STORAGE_BUCKET=xxxx
VITE_FIREBASE_MESSAGING_SENDER_ID=xxxx
VITE_FIREBASE_APP_ID=xxxx
```

---

## 🧠 Learning Outcomes

* Firebase Authentication
* Google OAuth integration
* React state management
* Form handling
* Auth flow handling
* Secure login systems

---

## 📜 License

This project is open-source and free to use for learning and educational purposes.

---

## 🤝 Author

**Amit Dabhi**

* GitHub: `amitdabhi01`
* Project Name: **PR-Auth-Firebase**

---

⭐ If you like this project, don't forget to star the repo!

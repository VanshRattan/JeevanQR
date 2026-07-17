# 🚑 JeevanQR

> **Your Digital Lifesaver in Emergencies**
>
> A QR-based emergency healthcare platform that provides instant access to critical medical information, enabling faster and more informed medical assistance when every second matters.

---

## ✨ Features

- 🔐 **Secure Authentication** – User registration and login with protected routes.
- 👤 **Medical Profile Management** – Store personal and medical information securely.
- 💊 **Health Information Storage** – Save allergies, medications, blood group, and existing medical conditions.
- 📞 **Emergency Contacts** – Add emergency contact details that can be accessed instantly.
- 📱 **QR Code Generation** – Generate a unique QR code linked to your medical profile.
- 🚑 **Instant Emergency Access** – First responders can scan the QR code to view critical information without requiring login.
- ✏️ **Profile Updates** – Easily update medical records and emergency details.
- 🔒 **Secure Data Management** – Sensitive information stored securely using authentication and database protection.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **QR Generation:** QR Code Library

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/VanshRattan/JeevanQR.git
cd JeevanQR
```

### 2. Install Dependencies

#### Frontend

```bash
cd client
npm install
npm run dev
```

#### Backend

```bash
cd server
npm install
npm start
```

### 3. Configure Environment Variables

Create a `.env` file inside the `server` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

---

## 📸 Screenshots

### 🏠 Landing Page
![Landing Page](screenshots/landing-page.png)

### 🔐 Login Page
![Login Page](screenshots/login-page.png)

### 👤 User Dashboard
![Dashboard](screenshots/dashboard.png)

### 📱 QR Code Generation
![QR Code](screenshots/qr-code.png)

### 🚑 Emergency Information Page
![Emergency Page](screenshots/emergency-page.png)

---

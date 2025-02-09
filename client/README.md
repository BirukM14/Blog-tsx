# Blog Platform
# Github username : BirukM14
# - TypeScript + React + Node.js + microservice

## 📌 Project Overview
A modern, full-stack blog application built with **React**, **TypeScript**, and **Node.js**. It allows users to create, edit, delete, and view blog posts with authentication and real-time updates.

## 🚀 Tech Stack
- **Frontend**: React + TypeScript + Vite + Tailwind CSS
- **Backend**: Node.js + Express + TypeScript
- **Database**: MongoDB with Mongoose
-

---

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/blog-platform.git
cd blog-platform
```

### 2️⃣ Install Dependencies
#### Frontend
```sh
cd client
npm install
```

#### Backend
```sh
cd server
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file inside the `server/` directory:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Start the Application
#### Run Backend
```sh
cd server
npm run dev
```
#### Run Frontend
```sh
cd client
npm run dev
```

The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:5000`.

---

## 📂 Folder Structure
```plaintext
blog-platform/
│-- client/  # Frontend (React + TypeScript)
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/  # Page components
│   │   ├── hooks/  # Custom hooks
│   │   ├── context/  # Global state management
│   │   ├── services/  # API calls
│   │   └── App.tsx  # Main component
│   ├── public/  # Static assets
│   ├── index.html  # Main HTML file
│   ├── vite.config.ts  # Vite configuration
│   └── package.json
│
│-- server/  # Backend (Node.js + Express + TypeScript)
│   ├── src/
│   │   ├── models/  # Mongoose schemas
│   │   ├── routes/  # Express routes
│   │   ├── controllers/  # Request handlers
│   │   ├── middleware/  # Authentication & error handling
│   │   ├── config/  # Database & server configuration
│   │   ├── index.ts  # Main server file
│   ├── package.json
│   ├── tsconfig.json  # TypeScript config
│   ├── .env  # Environment variables
│   └── .gitignore
```

---

## 🔥 Features
✅ User Authentication (Signup/Login with JWT)
✅ CRUD Operations (Create, Read, Update, Delete Blog Posts)
✅ Rich Text Editing with Markdown Support
✅ Image Upload & Storage (Cloudinary or Local Storage)
✅ Responsive & Mobile-Friendly UI
✅ Dark Mode Support
✅ API Documentation (Swagger / Postman)

---

## 🤝 Contributing
1. Fork the project.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---

## 📜 License
This project is licensed under the MIT License.

---

## 📧 Contact
For any questions, feel free to reach out!
📩 Email: your-email@example.com
🐙 GitHub: [your-username](https://github.com/BirukM14)


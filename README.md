<h1 align="center">FinSight AI Backend</h1>
<p align="center">
  <b>Node.js + Express + TypeScript API for FinSight AI</b><br>
  Secure, scalable, and feature-rich backend powering the personal finance platform.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-18+-green?logo=node.js" />
  <img src="https://img.shields.io/badge/Express-4+-gray?logo=express" />
  <img src="https://img.shields.io/badge/TypeScript-5+-blue?logo=typescript" />
  <img src="https://img.shields.io/badge/MongoDB-6+-green?logo=mongodb" />
  <img src="https://img.shields.io/badge/JWT-Auth-orange?logo=jsonwebtokens" />
  <img src="https://img.shields.io/badge/Cloudinary-Images-lightgrey?logo=cloudinary" />
</p>

---

# 📚 FinSight AI Backend Documentation

This document explains the structure, setup, features, and customization of the FinSight AI backend application.

---

## 🗂️ Folder Structure

```
backend/
├── src/
│   ├── controllers/   # Route handlers and business logic
│   ├── models/        # Mongoose schemas and models
│   ├── routes/        # Express route definitions
│   ├── middleware/    # Auth, error handling, validation
│   ├── utils/         # Helper functions and services
│   ├── config/        # Configuration files (db, cloudinary, etc.)
│   ├── jobs/          # Scheduled tasks (cron jobs)
│   └── app.ts         # Express app entry point
├── .env.example       # Environment variable template
├── package.json       # Project metadata and scripts
└── README.md          # Project overview
```

---

## 🚀 Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Configure environment variables:**  
   Copy `.env.example` to `.env` and fill in your MongoDB URI, JWT secret, Cloudinary keys, and other required variables.

3. **Run the development server:**
   ```sh
   npm run dev
   ```

4. **Build for production:**
   ```sh
   npm run build
   npm start
   ```

---

## ✨ Features Explained

- **Authentication:** Secure login, registration, and JWT-based session management.
- **User Management:** Profile, settings, and preferences.
- **Transactions:** CRUD for income, expenses, and savings.
- **Recurring Transactions:** Manage subscriptions and regular payments.
- **Analytics & Reports:** Generate summaries, trends, and AI-powered insights.
- **CSV Import & Receipt Scanning:** Upload and parse financial data, scan receipts using AI.
- **Cloudinary Integration:** Store and manage images securely.
- **Scheduled Jobs:** Automated monthly reports and notifications.
- **Validation:** Zod for request and data validation.
- **Error Handling:** Centralized error middleware.

---

## 🛠️ Tech Stack

- **Node.js** + **Express** + **TypeScript**
- **MongoDB** (Mongoose ODM)
- **Passport** & **JWT** for authentication
- **Cloudinary** for image uploads
- **Zod** for validation
- **Google Gemini API** for AI insights

---

## ⚙️ Customization

- **Config:** Edit files in `src/config/` for database, cloud, and service settings.
- **Routes:** Add or modify endpoints in `src/routes/`.
- **Models:** Update schemas in `src/models/` for new data types.
- **Jobs:** Schedule tasks in `src/jobs/` for automation.
- **Validation:** Use Zod schemas for robust request validation.

---

## 🧑‍💻 Development Notes

- **TypeScript:** All code is type-safe for reliability.
- **Linting:** ESLint and Prettier recommended for code quality.
- **Testing:** Add unit and integration tests in a `tests/` folder.

---

## 📚 Further Reading

- [Express Documentation](https://expressjs.com/)
- [TypeScript Documentation](https://www.typescriptlang.org/)
- [MongoDB Docs](https://www.mongodb.com/docs/)
- [Passport.js](http://www.passportjs.org/)
- [Cloudinary Docs](https://cloudinary.com/documentation)
- [Zod Docs](https://zod.dev/)
- [Google Gemini API](https://ai.google.dev/)

---

## 📄 License

See [../LICENSE.md](../LICENSE.md) for license details.

---

> For frontend setup and more details, see the
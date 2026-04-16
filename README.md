# ⚡ FinPulse – AI-Powered Finance Management Dashboard

## 🚀 Overview

**FinPulse** is a full-stack finance management web application built using the MERN stack (MongoDB, Express, React, Node.js), designed to help users track income, expenses, and savings efficiently.

The application is enhanced with **AI-powered automation**, enabling intelligent categorization of transactions and generation of personalized financial insights.

---

## ✨ Features

### 🧾 Core Features

* Secure user authentication (Login/Signup)
* Add, delete, and manage transactions
* Track income, expenses, and savings
* Real-time balance calculation
* Category-based expense tracking
* Filter transactions by date and category

---

### 📊 Dashboard & Analytics

* Income vs Expense overview
* Monthly financial trends
* Category-wise expense distribution
* Visual charts for better insights

---

### 🤖 AI-Powered Features

#### 🔹 Auto Categorization

Automatically classifies transactions based on their description using AI.

**Example:**

* “Zomato order” → Food
* “Uber ride” → Travel

---

#### 🔹 Smart Financial Insights

Analyzes user spending patterns and generates insights such as:

* “You spent 30% more on food this month”
* “Your highest expense category is Shopping”

---

#### 🔹 (Optional) AI Chat Assistant

Users can ask natural language queries:

* “Where did I spend the most money?”
* “How much did I spend on travel?”

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

### AI Integration

* SambaNova API 

---

## 🧠 Architecture

```
Frontend (React)
      ↓
Backend (Node/Express)
      ↓
AI Layer (OpenAI API)
      ↓
MongoDB
```

> AI is integrated directly into backend APIs for intelligent processing.

---

## 📁 Project Structure

```bash
finpulse/
│
├── backend/
│   ├── server.js
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── utils/
│       └── ai.js   # AI logic
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── pages/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/MS12code/FinPulse.git
cd FinPulse
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
MONGO_URI=your_mongodb_connection
OPENAI_API_KEY=your_openai_api_key
PORT=5000
```

Run backend:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔌 API Endpoints

| Method | Endpoint    | Description                         |
| ------ | ----------- | ----------------------------------- |
| POST   | /add        | Add transaction (AI categorization) |
| GET    | /all        | Fetch all transactions              |
| DELETE | /delete/:id | Delete transaction                  |
| GET    | /insights   | AI-generated financial insights     |
| POST   | /chat       | AI chatbot queries                  |

---

## 🧠 How AI Works

* **Auto Categorization**
  Transaction descriptions are sent to an AI model, which assigns appropriate categories.

* **Insight Generation**
  User transaction data is summarized and analyzed to generate human-readable insights.

* **Backend Integration**
  AI is integrated directly into existing backend APIs, without requiring a separate AI server.

---

## 📸 Screenshots

(Add your UI screenshots here)

---

## 🚀 Future Enhancements

* 🔐 JWT Authentication improvements
* 📊 Advanced analytics dashboard
* ⏰ Recurring transactions automation
* 🔔 Budget alerts & notifications
* 🌙 Dark mode
* 📱 Mobile responsiveness
* 🤖 Advanced AI predictions

---

## 🧑‍💻 Author

**Medha Sharma**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.
